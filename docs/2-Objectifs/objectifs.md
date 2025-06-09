---
layout: default
nav_order: 2
title: Objectifs du projet
---

# Objectifs du Projet

<br>
<div style="border-bottom: 3px solid #d62828; width: 100%; margin-top: -1em; margin-bottom: 1em;"></div>

Le <strong>FirefighterArmband</strong> vise à fournir un outil embarqué permettant aux pompiers de localiser rapidement les points d’eau les plus proches, même dans des contextes d’urgence ou de faible visibilité. Il s’agit d’un <strong>dispositif GPS intégré à un brassard</strong>, conçu pour fonctionner dans des conditions extrêmes (chaleur, humidité, chocs) et afficher les données essentielles de manière claire, ergonomique et intuitive.
</div>

---

## <span style="color:#d62828;">Contexte opérationnel</span>

Lors des interventions, les pompiers doivent accéder rapidement à une source d’eau (bouche, poteau, citerne, point naturel). Actuellement, ces informations sont souvent disponibles uniquement depuis les véhicules via des cartographies embarquées, ce qui ralentit la prise de décision sur le terrain, en particulier dans :

- des zones forestières ou rurales éloignées,
- des sites industriels étendus,
- des environnements à visibilité réduite (fumée dense, nuit, etc.).

Le besoin d’un outil individuel, mobile, accessible **directement sur l’équipement du pompier** devient alors une évidence opérationnelle.

---

##  <span style="color:#d62828;">Objectifs techniques</span>

Le dispositif vise à répondre à plusieurs impératifs :

- **Localisation GPS précise** des points d’eau à proximité et de notre possition.
- **Affichage ergonomique** : flèche directionnelle ou carte dynamique.
- **Utilisation intuitive**, même avec des gants de feu.
- **Autonomie suffisante** pour une intervention complète (> 6h).
- **Robustesse** face aux conditions extrêmes (IP68/IP69K, températures élevées).
- **Fixation sécurisée** à la manche (poche à scratch renforcée).
- **Mode connecté & hors-ligne** via base de données locale.

---

##  <span style="color:#d62828;">Existant et inspiration</span>

Des solutions partielles existent déjà :

- Applications de localisation de points d’eau,
- Systèmes GPS embarqués dans les véhicules,
- Brassards connectés dans l’industrie logistique.

Cependant, aucune ne répond entièrement aux **contraintes d’usage terrain des pompiers**. Le FirefighterArmband ambitionne de réunir les meilleures pratiques de ces solutions tout en respectant les exigences spécifiques du domaine incendie.

---

##  <span style="color:#d62828;">Cahier des charges fonctionnel (résumé)</span>

- Localisation des points d’eau par GPS
- Indication directionnelle + distance
- Affichage cartographique (mode avancé)
- Alerte vibratoire ou sonore
- Interface simple, lisible, tactile
- Résistance thermique, étanchéité, fiabilité

Ce projet inclut également un prototype réel, basé sur un écran tactile 7 pouces, un ESP32-S3, un module GPS et une boussole Grove.


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

<a class="bouton-suivant" href="../3-Recherches_etudes/etudes">Next→</a>

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
