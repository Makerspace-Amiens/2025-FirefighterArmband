---
layout: default
title: Projets Similaires
nav_order: 4
parent: Recherches
---

# Recherche de Projets Similaires

Avant de démarrer la conception, une analyse approfondie des projets existants a été réalisée afin de s’inspirer des bonnes pratiques, identifier les défis courants et orienter le développement du **FirefighterArmband**.

## Méthodologie de Recherche

1. **Identification des projets pertinents**  
   Recherche de brassards électroniques industriels (logistique, santé) et de solutions mobiles de localisation GPS.

2. **Analyse des fonctionnalités clés**  
   Étude des technologies de communication, des matériaux utilisés, de l’ergonomie, et des interfaces utilisateur.

3. **Comparaison des contraintes et des solutions adoptées**  
   Focus sur l’autonomie, la robustesse, la résistance aux environnements extrêmes, et les normes de protection.

## Points d’attention majeurs

- **Technologies de communication** : Bluetooth, Wi-Fi, GPS  
- **Ergonomie et confort** : Adaptabilité au port prolongé et aux conditions d’intervention  
- **Matériaux** : Résistance à la chaleur, chocs et aux normes IP spécifiques  
- **Autonomie** : Entre 4 et 12 heures selon les projets  
- **Interface utilisateur** : Simplicité pour ne pas distraire l’utilisateur en intervention  
- **Normes de protection** : IP67 à IP69K principalement  

## Synthèse comparative

| Critère             | Projets existants                         | Notre projet FirefighterArmband                 |
|---------------------|-----------------------------------------|------------------------------------------------|
| **Communication**    | Bluetooth / Wi-Fi / GPS                  | GPS avec base locale (fonctionnement offline)  |
| **Autonomie**        | 4 à 12 heures                           | Minimum 6 heures, optimisée pour interventions |
| **Matériaux**        | Textile, plastique dur                   | Boîtier rigide + tenue compatible feu          |
| **Interface**        | Écran tactile, boutons physiques        | Affichage directionnel et distance simplifié   |
| **Normes**           | IP67 souvent                            | Objectif IP68/IP69K, adapté aux conditions extrêmes |

---

Cette étude a permis de **cibler les adaptations nécessaires** pour concevoir un brassard robuste, fiable et parfaitement adapté aux besoins opérationnels des pompiers, sans chercher à reproduire un système existant mais en l’optimisant pour le terrain.


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

<a class="bouton-suivant" href="../4-Cahier-des-Charges/cahier">Next→</a>

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
