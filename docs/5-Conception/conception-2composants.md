---
layout: default
title: Composants
nav_order: 2
parent: Conception
---

# Composants Électroniques

## <span style="color:#d62828;">Objectif</span>

Rassembler les composants nécessaires pour assurer les trois fonctions essentielles du prototype :
- Acquisition de position GPS
- Orientation via boussole
- Affichage graphique clair et interactif

## <span style="color:#d62828;">Liste des composants</span>

| Composant | Référence | Fonction |
|----------|------------|----------|
| Microcontrôleur | **ESP32-S3 CrowPanel** | Affichage, GPS, gestion interface |
| Écran | intégré (7” tactile) | Interface utilisateur principale |
| GPS | **Module TEL0094** | Localisation des points d’eau |
| Boussole | **Grove 3-Axis Compass V2** | Orientation / calcul direction |
| Batterie | 3.7V Li-ion | Alimentation autonome (usage ponctuel) |
| Divers | Câbles, connecteurs Grove | Intégration simple, fiable et modulaire |

## <span style="color:#d62828;">Justification des choix</span>

- **ESP32-S3 CrowPanel** : puissant, compatible Arduino/Micropython, écran intégré
- **Connecteurs Grove** : simplifient le câblage, réduisent les erreurs
- **Modules compatibles entre eux**, testés dans des projets similaires

> Tous les composants ont été choisis pour leur **compatibilité logicielle**, leur **disponibilité** et leur **coût maîtrisé**.


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

<a class="bouton-suivant" href="../5-Conception/conception-3achat">Next→</a>

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
