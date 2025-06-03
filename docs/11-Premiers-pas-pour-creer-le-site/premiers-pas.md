---
layout: default
title: Premiers pas vers la création du site
nav_order: 11
has_children: true
---

# Introduction aux Sites Jekyll

<br>
<div style="border-bottom: 3px solid #d62828; width: 100%; margin-top: -1em; margin-bottom: 1em;"></div>

Ce document vise à expliquer ce qu'est un site Jekyll et comment il est utilisé dans ce repository pour la documentation et la gestion de votre projet.

## Qu'est-ce que Jekyll ?

Jekyll est un générateur de sites statiques simple, blog-aware, utilisé pour créer un site web ou un blog à partir de texte brut. Il est particulièrement bien adapté pour créer des sites de documentation de projets.

### Caractéristiques Principales

- **Simplicité :** Pas de bases de données, pas de serveurs complexes. Jekyll fonctionne avec des fichiers texte.
- **Blog-Aware :** Prise en charge intégrée pour les blogs, y compris les posts, les pages, les tags, etc.
- **Personnalisable :** Thèmes modulables et système de plugins pour étendre les fonctionnalités.
- **Markdown :** Utilise la syntaxe Markdown pour le contenu, ce qui facilite la rédaction et la mise en page.

## Utilisation de Jekyll dans ce Repository

Dans ce repository, Jekyll est utilisé pour créer et gérer la documentation de votre projet. 

### Documentation et Projet

- **Documentation :** Toute la documentation de votre projet, y compris les guides, tutoriels et références, sera hébergée sur le site Jekyll.
- **Sources du Projet :** En plus de la documentation, les sources de votre projet seront disponibles ici, permettant aux autres de découvrir, de reproduire ou de s'inspirer de votre travail.

### Premiers Pas avec Jekyll

Dans la section `docs` de ce repository, vous trouverez des informations et des guides sur la façon de modifier et de créer de nouveaux contenus pour votre documentation Jekyll. Que vous soyez un contributeur expérimenté ou un débutant, ces ressources vous aideront à prendre en main la gestion de votre site Jekyll.


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

<a class="bouton-suivant" href="../11-Premiers-pas-pour-creer-le-site/premiers-pas-1introduction_git_github">Next→</a>

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
