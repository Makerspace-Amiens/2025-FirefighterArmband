---
layout: default
parent: Premiers pas vers la création du site
nav_order: 2
title: Modifier facilement Votre Site Jekyll sur GitHub
---

# Modifier Votre Site Jekyll sur GitHub

Ce guide explique comment modifier votre site Jekyll, utilisant le thème "Just the Docs", directement depuis l'interface de GitHub.

## <span style="color:#d62828;">Étape 1 : Accéder au Repository</span>

1. Connectez-vous à votre compte GitHub.
2. Naviguez jusqu'au repository de votre site Jekyll.

## <span style="color:#d62828;">Étape 2 : Trouver le Fichier à Modifier</span>

1. Dans le repository, trouvez le dossier qui contient les fichiers de votre site (Dossier `/docs`).
2. Cliquez sur le fichier que vous souhaitez modifier. Les fichiers de contenu sont généralement écrits en Markdown (`.md`).

## <span style="color:#d62828;">Étape 3 : Modifier le Fichier</span>

1. Une fois que vous avez ouvert le fichier, cliquez sur l'icône de crayon (🖉) en haut à droite du fichier pour commencer à éditer.
2. Effectuez vos modifications dans l'éditeur. Utilisez la syntaxe Markdown pour formater le texte. [(Voir syntaxe Markdown)](markdown_cheatsheet).

## <span style="color:#d62828;">Étape 4 : Prévisualiser Vos Changements</span>

1. Descendez en bas de la page de l'éditeur.
2. Cliquez sur l'onglet `Preview changes` pour prévisualiser vos modifications.

## <span style="color:#d62828;">Étape 5 : Enregistrer les Modifications</span>

1. Après avoir vérifié et validé vos modifications, descendez en bas de la page.
2. Entrez un titre de commit décrivant les modifications que vous avez effectuées.
3. Optionnel : ajoutez une description plus détaillée.
4. Choisissez de commiter directement dans la branche actuelle ou de créer une nouvelle branche pour une demande de pull (pull request).
5. Cliquez sur `Commit changes`.

##  <span style="color:#d62828;">Étape 6 : Mettre à Jour le Site</span>

Une fois que vous avez commis vos changements, Jekyll va automatiquement reconstruire le site avec les nouvelles modifications. Cela peut prendre quelques minutes. Une fois terminé, vos changements seront visibles sur le site.

---

Ce guide est destiné à aider les utilisateurs débutants avec GitHub et Jekyll. Pour des modifications plus complexes, il est nécessaire d'utiliser un IDE ou d'autres outils de développement.


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

<a class="bouton-suivant" href="../11-1-Premiers-pas-pour-creer-le-site/premiers-pas-3markdown_cheatsheet">Next→</a>

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
  <img src="../../images/logoULS.png" alt="Logo ULS" />
  <a href="../../12-Contacts/contacts">Contacts</a>
</div>
