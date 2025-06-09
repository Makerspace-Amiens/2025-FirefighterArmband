---
layout: default
title: Objectifs techniques
nav_order: 2
parent: Cahier des Charges Idéal
---

# Objectif du Projet Idéal

L’objectif est de proposer un **équipement de localisation embarqué**, utilisable en toute autonomie par un pompier sur le terrain, sans dépendre de son véhicule ou de la visibilité.

Ce brassard doit permettre de :

<div class="objectifs-croix">

  <div class="objectif haut gauche">
    <p><strong>Réduire les délais d’identification</strong><br>de points d’eau</p>
  </div>

  <div class="objectif haut droite">
    <p><strong>Adapter parfaitement</strong><br>le logiciel des pompiers</p>
  </div>

  <div class="objectif centre">
    <p><strong>Améliorer la réactivité</strong><br>en situation d’urgence</p>
  </div>

  <div class="objectif bas gauche">
    <p><strong>Assurer un guidage</strong><br>sûr, rapide et robuste</p>
  </div>

  <div class="objectif bas droite">
    <p><strong>Limiter les erreurs</strong><br>de localisation</p>
  </div>

</div>

<style>
.objectifs-croix {
  display: grid;
  grid-template-areas:
    "haut-gauche . haut-droite"
    ". centre ."
    "bas-gauche . bas-droite";
  grid-template-columns: 1fr auto 1fr;
  grid-template-rows: auto auto auto;
  justify-items: center;
  align-items: center;
  gap: 20px;
  margin: 2rem 0;
}

.objectif {
  background-color: #f7f7f7;
  padding: 1rem 1.2rem;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  max-width: 220px;
  text-align: center;
  font-size: 0.95em;
  font-weight: 500;
}

.haut.gauche   { grid-area: haut-gauche; }
.haut.droite   { grid-area: haut-droite; }
.centre        { grid-area: centre; background-color: #f0eaea; }
.bas.gauche    { grid-area: bas-gauche; }
.bas.droite    { grid-area: bas-droite; }
</style>

Ce système pourrait, à terme, être **connecté à un réseau local** pour synchronisation en caserne ou dans les véhicules de commandement.


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

<a class="bouton-suivant" href="../Projet/cahier-2projet">Next→</a>

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
  <img src="../../images/logoULS.png" alt="Logo ULS" />
  <a href="../../12-Contacts/contacts">Contacts</a>
</div>
