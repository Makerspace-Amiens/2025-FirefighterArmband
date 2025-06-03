---
layout: default
title: Modélisation d'un boitier
parent: Prototype
nav_order: 2
---

# Sélection et Préparation des Composants

Cette section décrit la première étape du processus de développement : la sélection et la préparation des composants nécessaires à la conception du brassard GPS.

## Liste des Composants

- **Microcontrôleur** : ESP32, Arduino, ou autre selon les besoins.
- **Module GPS** : Ublox NEO-6M, NEO-M8N ou équivalent.
- **Batterie et Gestion d’Alimentation** : Li-Po avec circuit de protection.
- **Capteurs supplémentaires** : Accéléromètre, capteur de température (si nécessaire).
- **Matériaux de fabrication** : Textile résistant à la chaleur, boîtier de protection.
- **Outils nécessaires** : Fer à souder, multimètre, câbles de connexion.

## Procédure de Sélection et Préparation

1. **Recherche des composants adaptés** : Comparer les différents composants disponibles en fonction des besoins du projet.
2. **Commande des composants** : Passer commande auprès de fournisseurs fiables.
3. **Vérification des composants** : Tester chaque composant pour s’assurer qu’il fonctionne correctement.
4. **Préparation** : Effectuer les soudures et assemblages préliminaires si nécessaire.

## Conseils de Sécurité

- Toujours porter des équipements de protection individuelle lors des manipulations.
- Vérifier les tensions et connexions avant d’alimenter un circuit.
- Utiliser un environnement de travail bien ventilé lors des soudures.

---

Une fois cette étape terminée, passez à l'[intégration des composants](/integration).



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

<a class="bouton-suivant" href="6-Prototype/etapes-3prog">Next→</a>