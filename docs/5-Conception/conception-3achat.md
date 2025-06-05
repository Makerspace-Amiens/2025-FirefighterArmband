---
layout: default
title: Achats
nav_order: 3
parent: Conception
---

# Approvisionnement et Budget

## Objectif

Rester sous un budget de **250 € TTC**, frais de port compris, pour l’ensemble du prototype.

## Dépenses par catégorie

| Élément | Détail | Coût approximatif |
|--------|--------|-------------------|
| ESP32-S3 CrowPanel 7” | Wi-Fi, BLE, écran intégré | ~110 € |
| Module GPS TEL0094 | Compatible ESP32 | ~25 € |
| Module Boussole Grove V2 | Orientation | ~15 € |
| Batterie Li-ion 3.7V + câbles | Alimentation | ~20 € |
| Matériaux impression 3D | PLA + mousse | ~25 € |
| Connectique divers (Grove, câbles, etc.) | Tests et montage | ~15 € |
| **Total estimé** |  | **~210 €** |

## Fournisseurs

- **DFRobot** : GPS, boussole Grove, connectique
- **Mouser / Digikey** : composants électroniques
- **Amazon / Aliexpress** : éléments standards, câbles
- **Fablab / imprimante perso** : impression 3D en interne

> Nous avons conservé une **marge de 40 €** pour pallier d’éventuels imprévus (batterie défectueuse, connectique supplémentaire…).


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

<a class="bouton-suivant" href="../6-Prototype/etapes">Next→</a>

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
