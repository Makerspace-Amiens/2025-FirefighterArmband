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
.triangle-wrapper {
  position: relative;
  width: 550px;
  height: 470px;
  margin: 3rem auto;
}

.bubble {
  position: absolute;
  width: 220px;
  height: 140px;
  background-color: #fff7f7;
  border: 2px solid #d62828;
  border-radius: 12px;
  padding: 1.2rem;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-size: 15px;
  z-index: 1;
}

.bubble-title {
  font-weight: bold;
  margin-bottom: 0.4rem;
}

.separator {
  width: 20px;
  height: 1.2rem;
  border-left: 2px solid #d62828;
  margin: 0.3rem 0;
}

.bubble-desc {
  font-size: 13px;
  color: #333;
  max-width: 90%;
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

.svg-lines {
  position: absolute;
  top: 0;
  left: 0;
  pointer-events: none;
  z-index: 0;
}
</style>

<div class="triangle-wrapper">

  <!-- Bulles -->
  <div class="bubble" id="bubble1">
    <div class="bubble-title">Électronique</div>
    <div class="separator"></div>
    <div class="bubble-desc">Choix des composants, schémas, alimentation…</div>
  </div>

  <div class="bubble" id="bubble2">
    <div class="bubble-title">Modélisation d’un boîtier</div>
    <div class="separator"></div>
    <div class="bubble-desc">Conception, impression 3D, ergonomie…</div>
  </div>

  <div class="bubble" id="bubble3">
    <div class="bubble-title">Programmation du brassard</div>
    <div class="separator"></div>
    <div class="bubble-desc">Architecture, contraintes, affichage…</div>
  </div>

  <!-- Lignes courbes SVG -->
  <svg class="svg-lines" width="550" height="470">
    <path d="M 275 140 Q 275 250 275 250" stroke="#6a040f" stroke-width="2" fill="none" />
    <path d="M 110 330 Q 275 270 275 250" stroke="#6a040f" stroke-width="2" fill="none" />
    <path d="M 440 330 Q 275 270 275 250" stroke="#6a040f" stroke-width="2" fill="none" />
  </svg>

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
