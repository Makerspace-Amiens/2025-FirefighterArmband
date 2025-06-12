# Brassard GPS pour Pompiers

Ce repository centralise l’ensemble des ressources liées au développement d’un brassard GPS innovant destiné aux interventions des sapeurs-pompiers. L’objectif : permettre une localisation rapide et intuitive des points d’eau les plus proches (bouches, poteaux, citernes, etc.) en situation d’urgence, grâce à un module GPS intégré à un brassard résistant et ergonomique.

## Objectif du Projet

Développer un dispositif portable et robuste, intégré à la manche des vestes anti-feu, qui guide les pompiers en temps réel vers la source d’eau la plus proche via :

- Une flèche directionnelle et un affichage de la distance,

- Une interface cartographique dynamique (mode avancé),

- Une utilisation intuitive même avec des gants,

- Une résistance aux chocs, à la chaleur et à l’eau (IP68/IP69K).

## Contenu du Repository

| Dossier         | Description |
|-----------------|-------------|
| `docs/`         | Documentation technique, guides, cahier des charges. |
| `hardware/`     | Schémas électroniques, liste des composants, PCB. |
| `software/`     | Code source ESP32 (GPS, écran OLED, boutons, alertes). |
| `3D_models/`    | Fichiers STL pour impression 3D du boîtier. |
| `tests/` *(à venir)* | Plans de tests (autonomie, robustesse, précision GPS...). |



## Utilisation du Repository

1. Lire la documentation dans `docs/` pour comprendre la structure du projet.
2. Flasher le code du dossier `software/` sur une carte **ESP32-S3 CrowPanel**.
3. Imprimer le boîtier final à partir des modèles disponibles dans `3D_models/`.
4. Intégrer les modules (GPS, boussole) et procéder aux tests.



## Contribution

Ce projet est ouvert aux retours, idées et propositions d’amélioration.

Si vous souhaitez contribuer ou en savoir plus :

- Consultez notre **documentation complète** sur le site du projet : [makerspace-amiens.fr/firefighter-armband](https://makerspace-amiens.fr/firefighter-armband) *(ou lien direct vers le GitHub Pages si différent)*  
- Contactez directement l’équipe via la page **[Contact](./docs/12-Contacts/contacts.md)** ou par email (voir documentation).

> Toute contribution technique ou logicielle devra être discutée en amont pour garantir la cohérence du projet avec ses objectifs pédagogiques et fonctionnels.



## Contact

Vous avez des questions, suggestions ou retours ?

- Ouvrez une **issue GitHub**
- Ou contactez l’équipe projet à l’adresse email indiquée dans les documents du dépôt.



> Ce projet est à visée expérimentale et pédagogique. Il pourra être développé plus en profondeur par des professionnels en sécurité incendie si les conditions le permettent.
