---
layout: default
title: Achats
nav_order: 3
parent: Conception
---

## <span style="color:#d62828;">Objectif</span>

Rester sous un budget de **250 € TTC**, frais de port compris, pour l’ensemble du prototype.

## <span style="color:#d62828;">Dépenses par catégorie</span>

| Élément                                   | Détail                                   | Coût exact (€)            |
|-------------------------------------------|-----------------------------------------|--------------------------|
| Écran 7” CrowPanel (RobotShop)             | Wi-Fi, BLE, écran intégré                | 46,80                    |
| Module GPS TEL0094 (GOTRONIC)               | Compatible ESP32                         | 18,60                    |
| Module Boussole Grove V2 (GOTRONIC)         | Orientation                             | 13,70                    |
| Batterie Li-ion 3.7V + câbles               | Alimentation                            | ~20                      |
| Matériaux impression 3D                      | PLA + mousse                           | ~25                      |
| Connectique divers (Grove, câbles, etc.)    | Tests et montage (fournis par labo)    | 0 (fourni par l’école)   |
| **Total estimé**                            |                                         | **~124,80 € + ~45 €** (batterie + impression 3D) |

## <span style="color:#d62828;">Fournisseurs et commande</span>

- **RobotShop** : écran 7” CrowPanel  
- **GOTRONIC** : GPS TEL0094 et module boussole Grove V2  
- **Laboratoires électroniques de l'école** : câbles et connectique supplémentaires  
- **Impression 3D** : matériaux PLA fournis par l'école  

> Pour les commandes, nous devions passer par un onglet dédié sur le Teams général de la matière, où chaque demande était soumise à validation. Chaque soumission comportait les informations suivantes : nom du composant, prix, lien vers le site fournisseur, capture d’écran, etc. Après approbation, l’école regroupait les commandes de plusieurs groupes par site de livraison afin de réduire les coûts, puis passait la commande globale.



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
