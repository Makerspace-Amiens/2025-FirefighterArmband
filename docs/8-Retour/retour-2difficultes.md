---
layout: default
title: Difficultés rencontrées
parent: Retour
nav_order: 2
---

# <span style="color:#d62828;">Difficultés rencontrées</span>

## <span style="color:#d62828;">Problème d’intégration du module GPS</span>

L’un des principaux obstacles a été l’intégration du **module GPS**. Malgré plusieurs tentatives, nous n’avons pas réussi à établir une communication stable entre le GPS et l’**ESP32**. Des problèmes de compatibilité matérielle et de configuration logicielle ont bloqué l’acquisition des données en temps réel.  
En conséquence, pour la démonstration finale, les coordonnées ont été **simulées** afin de présenter le fonctionnement général du brassard.

## <span style="color:#d62828;">Problème de calibration de la boussole</span>

La **boussole numérique** installée dans le boîtier posait aussi problème : à cause de perturbations magnétiques internes et d’un manque de place pour un étalonnage correct, elle tournait de manière aléatoire, rendant son utilisation impossible pour orienter le pompier de façon fiable.

## <span style="color:#d62828;">Erreur de format d’écran</span>

Nous avions commandé un écran aux dimensions compatibles avec le brassard (environ **6 × 10 cm**). Or, à la livraison, l’écran mesurait **16 × 10 cm**, soit **10 cm de plus en largeur** qu’annoncé sur le site fournisseur.  
Cette erreur a eu plusieurs impacts :

- Obligation de **revoir le design du boîtier** pour accueillir l’écran surdimensionné.
- Déséquilibre du brassard une fois porté au bras.
- **Perte d’ergonomie**, car l’écran dépasse du format compact initialement prévu.

## <span style="color:#d62828;">Accès limité aux ressources logicielles et matérielles</span>

Nous n’avons pas pu intégrer le **logiciel métier des pompiers** dans notre prototype, faute d’autorisation et de délai suffisant pour collaborer directement avec le service concerné. De même, nous n’avons pas pu obtenir une **veste de feu** officielle pour tester l’intégration du brassard directement sur l’équipement réel, car les démarches administratives ont dépassé la durée du projet.

## <span style="color:#d62828;">Problèmes avec le dépôt GitHub</span>

Au début du projet, nous n’avions pas d’accès fonctionnel au **dépôt GitHub** de l’équipe. Cela a retardé la mise en commun du code et la gestion collaborative, compliquant le suivi et les tests partagés entre membres.

## <span style="color:#d62828;">Contraintes de temps et imprévus</span>

Une contrainte majeure a été le **temps limité** : nous partions de zéro, sans base de prototype existant. Il a donc fallu consacrer une part importante du calendrier à la **recherche documentaire**, à la comparaison de solutions techniques et à l’apprentissage des outils nécessaires (ESP32, modules GPS, affichage TFT, etc.).  
Cette phase de préparation, indispensable pour prendre de bonnes décisions techniques, a réduit le temps disponible pour le développement pratique.  
Au final, il n’est resté **quasiment aucun créneau pour gérer les imprévus matériels ou techniques**, ce qui a limité l’avancement sur certaines fonctionnalités pourtant prévues initialement.


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

<a class="bouton-suivant" href="../8-Retour/retour-3amelio">Next→</a>

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
