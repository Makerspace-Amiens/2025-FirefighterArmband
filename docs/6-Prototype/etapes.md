---
layout: default
title: Prototype
nav_order: 6
has_children: true
---

# Prototype et Étapes de Fabrication

<br>
<div style="border-bottom: 3px solid #d62828; width: 100%; margin-top: -1em; margin-bottom: 1em;"></div>

Cette section présente les différentes étapes de conception du prototype, divisées en trois volets principaux :

<style>
.triangle-container {
  position: relative;
  width: 400px;
  height: 360px;
  margin: 2rem auto;
}

.bubble {
  position: absolute;
  width: 150px;
  padding: 1rem;
  background-color: #fefefe;
  border: 2px solid #d62828;
  border-radius: 1rem;
  text-align: center;
  font-weight: bold;
  box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}

#bubble1 {
  top: 0;
  left: 50%;
  transform: translateX(-50%);
}
#bubble2 {
  bottom: 0;
  left: 0;
}
#bubble3 {
  bottom: 0;
  right: 0;
}

.arrow {
  position: absolute;
  width: 120px;
  height: 120px;
  border: 2px solid transparent;
  border-top-color: #6a040f;
  border-left-color: #6a040f;
  border-radius: 50%;
  transform: rotate(45deg);
}

#arrow1 {
  top: 60px;
  left: 145px;
  transform: rotate(225deg);
}
#arrow2 {
  bottom: 95px;
  left: 30px;
  transform: rotate(315deg);
}
#arrow3 {
  bottom: 95px;
  right: 30px;
  transform: rotate(135deg);
}
</style>

<div class="triangle-container">
  <div class="bubble" id="bubble1">
    Électronique<br>
    <small>Choix des composants, schémas, alimentation…</small>
  </div>
  <div class="bubble" id="bubble2">
    Modélisation d’un boîtier<br>
    <small>Conception, impression 3D, ergonomie…</small>
  </div>
  <div class="bubble" id="bubble3">
    Programmation du brassard<br>
    <small>Architecture logicielle, affichage, contraintes…</small>
  </div>

  <div class="arrow" id="arrow1"></div>
  <div class="arrow" id="arrow2"></div>
  <div class="arrow" id="arrow3"></div>
</div>


Chaque volet est documenté dans une sous-page dédiée. La programmation est elle-même subdivisée pour clarifier les aspects logiques, graphiques et les contraintes liées à l’utilisation embarquée.


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

<a class="bouton-suivant" href="../6-Prototype/etape-1elec">Next→</a>

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
