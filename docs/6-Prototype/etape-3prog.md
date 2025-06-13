---
layout: default
title: Programmation du brassard
parent: Prototype
nav_order: 3
has_children: true
---

# Programmation 
 
<br>
<div style="border-bottom: 3px solidrgb(148, 38, 38); width: 100%; margin-top: -1em; margin-bottom: 1em;"></div>

# Programmation et interface du brassard

Dans cette section, je présente en détail les aspects liés à la programmation de mon brassard électronique pour les pompiers.  
Le développement logiciel du projet a nécessité de prendre en compte des contraintes spécifiques, de structurer le code de manière efficace et de concevoir une interface simple, intuitive et adaptée aux conditions d’utilisation sur le terrain.

---

## <span style="color:#d62828;">Contraintes techniques de programmation</span>

Avant d’écrire le moindre code, j’ai identifié et analysé plusieurs contraintes techniques directement liées au contexte opérationnel et aux limitations matérielles :

- Le microcontrôleur utilisé possède une mémoire limitée et une puissance de calcul restreinte, ce qui m’a obligé à optimiser chaque fonction pour garantir un fonctionnement fluide et fiable.
- L’autonomie énergétique du brassard dépend d’une consommation électrique maîtrisée : j’ai donc privilégié des algorithmes économes en ressources et mis en place des modes de veille intelligents.
- Le système doit être robuste face à des conditions environnementales difficiles (températures élevées, humidité, chocs) et continuer à transmettre les données de manière fiable.
- La programmation devait également respecter certaines contraintes de sécurité, notamment en ce qui concerne la transmission des données GPS et l’intégrité des informations partagées.

Cette phase de définition des contraintes a servi de base pour élaborer l’architecture logicielle du brassard.

---

## <span style="color:#d62828;">Programmation du brassard</span>

Sur la base de ces contraintes, j’ai développé le programme embarqué qui assure toutes les fonctions essentielles du brassard :

- Acquisition et traitement des données GPS en temps réel.
- Vérification de la qualité et de la précision des signaux reçus.
- Gestion des communications entre le brassard et une station de contrôle ou un smartphone, en privilégiant la stabilité et la rapidité de transmission.
- Implémentation d’un système de mise en veille automatique pour prolonger la durée de fonctionnement sur batterie.
- Organisation du code en modules clairs et documentés pour faciliter la maintenance et les éventuelles évolutions du projet.

Cette partie logicielle constitue le cœur du dispositif et garantit le bon fonctionnement de l’ensemble du système.

---

## <span style="color:#d62828;">Interface et interface graphique</span>

En complément de la logique embarquée, j’ai conçu une interface utilisateur et une interface graphique pour rendre l’utilisation du brassard simple et compréhensible :

- Un affichage succinct directement sur le brassard permet aux pompiers de vérifier rapidement l’état du GPS, la connectivité et l’autonomie de la batterie.
- Des boutons de commande simples limitent les risques d’erreur lors de l’utilisation en intervention.
- Une interface graphique plus détaillée est disponible sur un module PC ou une application mobile ; elle permet de suivre en temps réel les informations envoyées par le brassard, de consulter l’historique et de superviser l’état de chaque équipement.

Ces éléments d’interface complètent la partie programmation et assurent une bonne ergonomie pour les utilisateurs, même en conditions extrêmes.

---

> Cette page fournit ainsi une vision complète de la partie logicielle et des choix réalisés pour garantir un brassard efficace, fiable et adapté aux besoins réels des pompiers.


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

<a class="bouton-suivant" href="../6-Prototype/etape-3-1contraintes">Next→</a>

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
