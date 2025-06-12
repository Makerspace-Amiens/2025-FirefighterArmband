---
layout: default
title: Site Web
parent: Supports
nav_order: 5
---

# Création du Site Web

## <span style="color:#d62828;">Objectif</span>

Centraliser toutes les informations du projet **FirefighterArmband** dans une interface claire, technique, consultable en ligne, afin de faciliter sa compréhension, sa présentation et sa reproduction.

---

## <span style="color:#d62828;">Contexte de création</span>

<div style="background-color:#f9f9f9; border-left: 5px solid #d62828; padding: 1rem 1.5rem; border-radius: 6px; margin-bottom: 1.5rem;">

Le site n’a pu être créé qu’après avoir résolu les problèmes liés à la modification du dépôt GitHub.  
En effet, pendant plusieurs semaines, nos tentatives de mise à jour échouaient : push non pris en compte, erreurs silencieuses, ou site non actualisé.

Grâce à l’usage de **github.dev**, une interface d’édition directement accessible via navigateur, nous avons enfin pu intervenir sur les fichiers du dépôt et **déployer un site fonctionnel via GitHub Pages**.

</div>

---

## <span style="color:#d62828;">Fonctionnalités du site</span>

- Organisation du contenu en sections thématiques : recherches, cahier des charges, conception, tests, supports
- Ajout de styles personnalisés pour une lecture claire et technique
- Affichage d’illustrations, de schémas, et de visuels du prototype
- Navigation simplifiée par menu latéral (architecture type documentation technique)

---

## <span style="color:#d62828;">Aperçu de la programmation du site</span>

<div style="text-align: center; margin-top: 2rem; margin-bottom: 1rem;">
  <img src="../images/sitegitdev.png" alt="Capture du site web GitHub Pages" style="width:100%; max-width:700px; border-radius:8px; box-shadow:0 4px 12px rgba(0,0,0,0.2);" />
  <p style="font-size: 0.9em; margin-top: 0.5rem;">Site de documentation créé via GitHub Pages</p>
</div>

---

## <span style="color:#d62828;">Bilan</span>

Ce site constitue la **forme finale et complète** du projet. Il regroupe tous les éléments nécessaires à sa compréhension et à sa reproduction.  
Accessible publiquement, il peut être utilisé comme support technique, vitrine de compétences ou démonstrateur pédagogique.

> L’expérience acquise lors de sa mise en place nous a permis de découvrir concrètement les outils de documentation web open source.


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

<a class="bouton-suivant" href="../7-Supports/supports-6video">Next→</a>

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
