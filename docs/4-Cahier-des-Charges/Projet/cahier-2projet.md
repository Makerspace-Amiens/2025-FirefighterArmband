---
layout: default
title: Cahier des Charges Projet
nav_order: 2
parent: Cahier des Charges
has_children: true
---

# Cahier des Charges Réel (Prototype)

<br>
<div style="border-bottom: 3px solidrgb(148, 38, 38); width: 100%; margin-top: -1em; margin-bottom: 1em;"></div>

Dans le cadre de notre projet pédagogique, nous avons dû adapter la conception à des contraintes concrètes :

<div class="objectifs-carre">

  <div class="bulle">
    <p>Temps limité à<br><strong>75h de travail effectif</strong></p>
  </div>

  <div class="bulle">
    <p>Budget maximal de<br><strong>250 €</strong></p>
  </div>

  <div class="bulle">
    <p><strong>Matériel accessible</strong><br>et documenté</p>
  </div>

  <div class="bulle">
    <p><strong>Conception faisable</strong><br>à notre niveau d’étude</p>
  </div>

</div>

<style>
.objectifs-carre {
  display: grid;
  grid-template-columns: repeat(2, minmax(220px, 1fr));
  gap: 20px;
  justify-content: center;
  margin: 2rem auto;
  max-width: 700px;
}
.bulle {
  background-color: #f7f7f7;
  padding: 1.2rem;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  font-size: 0.95em;
  font-weight: 500;
}
</style>

Cette version conserve les **principes clés du projet**, tout en étant réalisable avec nos ressources.

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

<a class="bouton-suivant" href="../Projet/cahier-2-3contraintes">Next→</a>

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
