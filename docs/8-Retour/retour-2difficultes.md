---
layout: default
title: Difficultés rencontrées
parent: Retour
nav_order: 2
---

# ⚠️ Difficultés rencontrées

📡 Problème d’intégration du module GPS
L’un des principaux obstacles a été l’intégration du module GPS. Malgré plusieurs tentatives, nous n’avons pas réussi à faire communiquer le GPS de manière fiable avec l’ESP32. En conséquence, les coordonnées utilisées dans le prototype étaient simulées pour la démonstration.

📏 Erreur de format d’écran
Nous avions initialement prévu un écran de 6 × 10 cm, compatible avec un format de brassard. Cependant, nous avons reçu un écran de 16 × 10 cm, soit beaucoup plus large que prévu. Ce changement a impacté :

Le design du boîtier,

L’équilibre du brassard porté au bras,

Et l’ergonomie globale de l’appareil.

⏱️ Contraintes de temps
Enfin, le temps imparti au développement a été relativement court. Entre le choix du matériel, l’attente des livraisons, la conception mécanique, le codage et les tests, nous avons dû faire des compromis. Certains modules (comme le GPS) n’ont pas pu être pleinement intégrés, et la finition matérielle est restée partielle.

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

<a class="bouton-suivant" href="../8-Retour/retour-3amelio">Next→</a>

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
