---
layout: default
title: Projets Similaires
nav_order: 4
parent: Recherches
---

# Recherche de Projets Similaires

Avant de démarrer la conception, une analyse approfondie des projets existants a été réalisée afin de s’inspirer des bonnes pratiques, identifier les défis courants et orienter le développement du **FirefighterArmband**.

---

## <span style="color:#d62828;">Méthodologie de Recherche</span>

<div style="background-color:#f9f9f9; padding: 1rem 1.5rem; border-left: 5px solid #d62828; border-radius: 6px; margin-bottom: 2rem;">

1. <strong>Identification des projets pertinents</strong>  
   Recherche de brassards électroniques industriels (logistique, santé) et de solutions mobiles de localisation GPS.

2. <strong>Analyse des fonctionnalités clés</strong>  
   Étude des technologies de communication, des matériaux utilisés, de l’ergonomie, et des interfaces utilisateur.

3. <strong>Comparaison des contraintes et des solutions adoptées</strong>  
   Focus sur l’autonomie, la robustesse, la résistance aux environnements extrêmes, et les normes de protection.

</div>

---

## <span style="color:#d62828;">Exemples étudiés</span>

### <u>Brassards et dispositifs portables</u>

<div style="background-color:#f0f0f0; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 Brassard sport Cdiscount</strong><br/>
<a href="https://www.cdiscount.com/le-sport/sports-individuels/brassard-sport-poignet-pour-iphone-7-smartphone-co/f-12103040405-auc3006014899095.html" target="_blank">Lien vers le produit</a><br/>
Utilisé pour les activités sportives avec smartphone. Léger, pratique mais non adapté aux environnements extrêmes.
</div>

<div style="background-color:#f0f0f0; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 Zebra RS51 (scanner entrepôt)</strong><br/>
<a href="https://www.barcodefactory.com/zebra/mobile-computers/wearable/rs51c0-tbdnwr" target="_blank">Lien vers le produit</a><br/>
Scanner professionnel mains-libres pour entrepôts. Robuste, mais non adapté au guidage ou localisation.
</div>

<div style="background-color:#f0f0f0; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 Support Squids 5545</strong><br/>
<a href="https://www.seton.fr/support-scanner-bras-poignet-squids-5545.html#311IVA100" target="_blank">Lien vers le produit</a><br/>
Support de poignet pour appareil professionnel. Fixation fiable, mais pas de système électronique intégré.
</div>

---

### <u>Applications de localisation des points d’eau</u>

<div style="background-color:#eef3f7; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 FreeTaps</strong><br/>
<a href="https://freetaps.earth" target="_blank">Site officiel</a><br/>
Application communautaire pour localiser les points d’eau publics. Carte interactive simple. Non adaptée à un usage pompier.
</div>

<div style="background-color:#eef3f7; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 Owater</strong><br/>
<a href="https://www.owater.fr" target="_blank">Site officiel</a><br/>
Application similaire avec interface moderne. Utile pour le grand public, non prévue pour un fonctionnement hors-ligne ou en conditions extrêmes.
</div>


### <u>Projets open source ou universitaires</u>

<div style="background-color:#f6f0ff; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 Firefighter Finder GPS (GitHub)</strong><br/>
<a href="https://github.com/lukeskywokka/firefighterFinderGPS.git" target="_blank">Voir le projet GitHub</a><br/>
Projet universitaire avec guidage GPS vers un point fixe. Concept proche, sans boîtier terrain ni écran avancé.
</div>

<div style="background-color:#f6f0ff; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 Vidéo de présentation</strong><br/>
*Firefighter Finder – SJSU Spring 2019 CMPE Demo* (YouTube)<br/>
Démonstration du projet, utile pour comparer la logique de guidage. Limité au niveau matériel.
</div>


### <u>Solution professionnelle – DECI Escort CR+</u>

<div style="background-color:#fff7eb; padding: 1rem; border-radius: 6px; margin-bottom: 1rem;">
<strong>🔹 DECI Escort CR+ – Berger-Levrault</strong><br/>
<a href="https://www.berger-levrault.com/fr/produit/escort-cr-points-deau/" target="_blank">Site du produit</a><br/>
Logiciel professionnel pour la gestion des points d’eau incendie (cartographie + inventaire). Réservé aux SDIS, non portable.
</div>

---

## Points d’attention majeurs

- **Technologies de communication** : Bluetooth, Wi-Fi, GPS  
- **Ergonomie et confort** : Adaptabilité au port prolongé et aux conditions d’intervention  
- **Matériaux** : Résistance à la chaleur, chocs et aux normes IP spécifiques  
- **Autonomie** : Entre 4 et 12 heures selon les projets  
- **Interface utilisateur** : Simplicité pour ne pas distraire l’utilisateur en intervention  
- **Normes de protection** : IP67 à IP69K principalement  

---

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
