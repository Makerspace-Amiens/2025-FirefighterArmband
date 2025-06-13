---
layout: default
title: Interface Graphique
parent: Programmation du brassard
nav_order: 3
---

# Interface et Interface graphique
## Contraintes et choix liés à la programmation

Dans cette section, nous revenons sur plusieurs choix techniques importants qui ont influencé la structure finale de notre code.  
Certains problèmes nous ont forcés à revoir nos objectifs initiaux pour garantir un fonctionnement fiable et adapté au terrain.

---

### 1. Problèmes liés aux bibliothèques

L’un des principaux obstacles rencontrés a été la **gestion des bibliothèques**, notamment celles liées à l’affichage sur le **CrowPanel**.

- Les bibliothèques disponibles étaient parfois **mal documentées**, incomplètes ou incompatibles entre elles.
- Certaines dépendances entraient en **conflit avec d’autres bibliothèques nécessaires** au GPS ou à la boussole.
- L’intégration d’une interface graphique avec des animations (comme la flèche directionnelle) posait des **problèmes de stabilité ou de lenteur**.

Ces difficultés nous ont poussés à **réduire notre dépendance aux bibliothèques tierces** et à revoir la conception de notre interface.

---

### 2. Abandon de la flèche directionnelle

Initialement, nous avions prévu une **flèche orientée dynamiquement** pour indiquer la direction du point d’eau.  
Cependant, plusieurs contraintes nous ont amenés à **abandonner cette fonctionnalité** dans la version finale :

- Problèmes techniques liés au calcul d’angle et à l’actualisation graphique.
- Instabilité de l’affichage lorsque plusieurs capteurs fonctionnaient simultanément.
- Complexité de rendu sur un écran tactile peu optimisé.

Nous avons donc fait le choix de privilégier **la fiabilité du système** plutôt que des éléments visuellement complexes mais sources de bugs.

---

### 3. Interface simple, sans bibliothèque graphique

En réponse à ces limitations, nous avons conçu une **interface simple, claire, et sans dépendance à des bibliothèques graphiques complexes**.

- Affichage **uniquement textuel**, avec des valeurs lisibles (distance restante, message de confirmation, etc.).
- Codée directement en utilisant les fonctions de base de l’ESP32 et de l’écran.
- Réduction du nombre d’éléments affichés pour **faciliter la lecture rapide** en intervention.

Ce choix garantit une meilleure stabilité et une consommation minimale de ressources, tout en maintenant l’utilité du brassard.

---

### 4. Adaptabilité du système

Malgré ces simplifications, le système reste **entièrement adaptable** :

- Le code est **modulaire** : il peut être modifié facilement pour ajouter d’autres capteurs ou modifier les points d’eau.
- Les points d’eau sont stockés sous forme de **coordonnées GPS**, donc aisément modifiables dans le code ou via un fichier externe.
- Le système peut être porté sur **d’autres écrans ou microcontrôleurs**, tant que ceux-ci sont compatibles avec Arduino.

Nous avons donc préféré un système **fiable, adaptable et fonctionnel**, plutôt qu’un prototype visuellement complexe mais instable.

---

Ce retour d’expérience montre l’importance de faire des compromis techniques intelligents pour garantir **un usage concret sur le terrain**, là où l’efficacité prime sur l’apparence.


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

<a class="bouton-suivant" href="../7-Supports/supports">Next→</a>

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
