---
layout: default
title: Programmation
parent: Programmation du brassard
nav_order: 2
---

# Programmation du brassard

## <span style="color:#d62828;">Environnement et programmation</span>

Dans cette section, nous détaillons l’environnement logiciel utilisé pour développer notre projet, l’adaptation aux bibliothèques spécifiques à notre matériel, ainsi qu’un aperçu des grandes lignes du code.

---

## <span style="color:#d62828;">1. Environnement : IDE Arduino</span>

Pour la programmation du brassard, nous avons utilisé l’**IDE Arduino**, un environnement de développement très répandu dans le domaine de l’électronique embarquée.

- L’IDE Arduino permet de programmer en **C/C++**, avec une interface simple adaptée aux microcontrôleurs comme l’ESP32.
- Il offre un système de **gestion de bibliothèques** facilitant l’intégration de composants externes (affichage, GPS, capteurs…).
- Nous avons configuré l’IDE pour qu’il soit compatible avec la **carte ESP32 intégrée dans le CrowPanel**.

Ce choix nous a permis de profiter d’une large communauté, de nombreux exemples de code, et d’un déploiement rapide vers notre carte via USB.

---

## <span style="color:#d62828;">2. Utilisation des bibliothèques spécifiques au CrowPanel</span>

La carte que nous avons utilisée, le **CrowPanel d’Elecrow**, n’est pas officiellement supportée par l’IDE Arduino.  
Nous avons donc dû **chercher, tester et adapter plusieurs bibliothèques** pour réussir à exploiter son écran et ses fonctionnalités.

- Nous avons utilisé des **bibliothèques graphiques compatibles avec les écrans TFT** comme `TFT_eSPI`, que nous avons adaptées pour les dimensions et la configuration du CrowPanel.
- La configuration des broches de l’écran et la gestion tactile ont nécessité des ajustements manuels dans les fichiers de configuration.

Grâce à ces adaptations, nous avons pu afficher notre interface (flèche, distance, texte) de manière fluide et responsive.

---

## <span style="color:#d62828;">3. Grandes lignes du code et gestion des bibliothèques</span>

Le code principal s’articule autour de plusieurs modules :

- **Initialisation matérielle** : configuration de l’écran, de la boussole (I²C) et du GPS (UART).
- **Lecture des capteurs** : récupération des coordonnées GPS et de l’orientation magnétique.
- **Calculs** :
  - Calcul de la **distance** entre la position du pompier et un point d’eau (formule de Haversine).
  - Calcul de la **direction à suivre** (angle entre le cap actuel et la cible).
- **Affichage** :
  - Affichage de la **flèche directionnelle** orientée dynamiquement.
  - Affichage de la **distance** en mètres.
  - Affichage d’un message si le point d’eau est atteint ou hors de portée.



---

> Cette architecture simple mais robuste permet de maintenir le code facilement, tout en assurant une bonne réactivité lors de l’utilisation sur le terrain.

(-mettre un lien pour télécharger le code)


<!----------------------------------------------------------------------------->

<style>
.bouton-suivant {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #d62828;
  color: white;
  padding: 12px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  box-shadow: 0px 4px 12px rgba(0,0,0,0.2);
  transition: background-color 0.3s ease;
  z-index: 1000;
}

.bouton-suivant:hover {
  background-color: #a61c1c;
}
</style>

<a class="bouton-suivant" href="../6-Prototype/etape-3-3interface">Next→</a>

<!----------------------------------------------------------------------------->

<style>
.footer-bandeau {
  background-color: #f8d7da; /* rouge pastel */
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 3rem;
  border-top: 2px solid #d62828;
  font-weight: bold;
}

.footer-bandeau img {
  height: 40px;
}

.footer-bandeau a {
  color: #d62828;
  text-decoration: none;
  font-weight: bold;
  margin-right: 40px; /* ← ajoute une marge à droite */
}

.footer-bandeau a:hover {
  text-decoration: underline;
}
</style>

<div class="footer-bandeau">
  <img src="../images/logoULS.png" alt="Logo ULS" />
  <a href="../12-Contacts/contacts">Contacts</a>
</div>
