---
layout: default
title: Électronique
parent: Prototype
nav_order: 1
---

# Electronique

La partie électronique de notre projet a été relativement simple à mettre en place grâce à l'utilisation d'une carte électronique déjà très complète. En effet, nous avons opté pour un écran **Elecrow** équipé d’un **ESP32**, qui répondait parfaitement à l’ensemble de nos besoins pour le développement logiciel. Ce choix stratégique nous a permis de gagner un temps précieux et de nous concentrer davantage sur l’intégration des composants complémentaires nécessaires au bon fonctionnement de notre système.

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; align-items: flex-start; margin-bottom: 2rem;">

  <div style="flex: 1 1 45%; text-align: center;">
    <img src="../images/SchémaélectroniqueElecrow.png" alt="Vu de la carte électronique" style="width:100%; max-width:320px; border-radius:8px; box-shadow:0 4px 10px rgba(0,0,0,0.15);" />
    <p style="font-size: 0.9em; margin-top: 0.5rem;">Modèle sur OnShape – Vue globale</p>
  </div>
  </div>
 
## <span style="color:#d62828;">Choix des Modules Complémentaires</span>

Après avoir validé notre support principal, nous avons recherché les modules nécessaires à notre application. Deux capteurs se sont révélés indispensables :

- **Un module GPS NEO6M**, pour la géolocalisation.
- **Une boussole Grove 3 axes**, pour la détection de l’orientation.

Le module GPS a été choisi après plusieurs recherches en ligne, tandis que la boussole Grove a été sélectionnée en raison de notre expérience préalable avec cette marque lors de travaux pratiques antérieurs.


## <span style="color:#d62828;">Intégration des Composants</span>

- **La boussole** a été connectée via le **bus I²C**, une interface simple et fiable pour ce type de capteur.
- **Le GPS**, quant à lui, devait être câblé sur **l’interface UART0** du microcontrôleur.

Malheureusement, nous avons rencontré des problèmes techniques lors de l’intégration du GPS : dès que ce dernier était connecté, le microcontrôleur cessait de recevoir des données. Ce dysfonctionnement pourrait être lié à un conflit matériel ou une erreur de câblage que nous n’avons pas pu identifier à temps.


## <span style="color:#d62828;">ÉProblèmes lors de l’assemblage final</span>

La veille de la **Journée des Projets**, en procédant à l’assemblage final dans le boîtier, nous avons constaté que la boussole ne fonctionnait plus correctement une fois intégrée. Après analyse, nous suspectons que des **interférences électromagnétiques** entre l’écran et la boussole — qui étaient collés l’un à l’autre — ont perturbé son fonctionnement.

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

<a class="bouton-suivant" href="../6-Prototype/etape-2mod_boitier">Next→</a>

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
