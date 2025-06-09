---
layout: default
parent: Premiers pas vers la création du site
nav_order: 3
title: Guide de Syntaxe Markdown
---

# Guide de Syntaxe Markdown

Markdown est un langage de balisage léger conçu pour être converti en HTML. Il est souvent utilisé pour formater des fichiers README, pour écrire des messages dans des forums en ligne, et pour créer des documents texte riches en utilisant un éditeur de texte brut. Son objectif principal est la lisibilité et la facilité d'utilisation.

## <span style="color:#d62828;">Qu'est-ce que Markdown ?</span>

Markdown a été créé en 2004 par John Gruber avec l'aide d'Aaron Swartz, avec l'idée de permettre aux gens d'écrire en utilisant un format de texte brut facile à lire et à écrire, qui pourrait être converti en HTML de manière transparente.

## <span style="color:#d62828;">Pourquoi utiliser Markdown ?</span>

- **Simplicité et facilité d'apprentissage :** La syntaxe de Markdown est très simple à apprendre, ce qui en fait un bon choix pour ceux qui ne sont pas familiers avec les langages de balisage plus complexes comme HTML.
- **Portabilité :** Les fichiers Markdown sont des fichiers texte brut, donc ils sont légers et compatibles avec de nombreuses plateformes et éditeurs de texte.
- **Flexibilité :** Markdown est souvent utilisé pour la documentation de projets, les fichiers README, et les forums en ligne, mais il peut également être utilisé pour créer des livres, des présentations et d'autres types de documents.
- **Conversion en d'autres formats :** Il est facile de convertir des fichiers Markdown en HTML, PDF, et d'autres formats.

## <span style="color:#d62828;">Comment utiliser ce guide ?</span>

Ce guide fournit des exemples de la syntaxe de base de Markdown. Vous pouvez vous référer à ce guide pour comprendre comment formater vos textes en Markdown.


## <span style="color:#d62828;">Titres</span>

Les titres sont créés en utilisant le symbole `#`. Le nombre de `#` détermine le niveau du titre.

```
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
```

## <span style="color:#d62828;">Texte en gras et en italique</span>

*Texte en italique* s'écrit en entourant le texte de `*` ou de `_`.
**Texte en gras** utilise deux `*` ou `_` de chaque côté.
***Texte en gras et en italique*** combine les deux.

```
*Texte en italique*
_Texte en italique_
**Texte en gras**
__Texte en gras__
***Texte en gras et en italique***
```

## <span style="color:#d62828;">Listes</span>

### Listes non ordonnées

Utilisez `*`, `+`, ou `-` pour les éléments de la liste.

```
* Élément 1
* Élément 2
  * Sous-élément 2.1
  * Sous-élément 2.2
```

### Listes ordonnées

Les nombres suivis d'un point créent une liste ordonnée.

```
1. Premier élément
2. Deuxième élément
   1. Sous-élément 2.1
   2. Sous-élément 2.2
```

## <span style="color:#d62828;">Liens</span>

Pour créer un lien, mettez le texte du lien entre crochets `[]` et l'URL entre parenthèses `()`.

```
[OpenAI](https://www.openai.com)
```

## <span style="color:#d62828;">Images</span>

Les images sont similaires aux liens, mais avec un point d'exclamation `!` devant.

```
![Alt text](url_de_l'image.jpg)
```

## <span style="color:#d62828;">Citations</span>

Les citations sont créées en utilisant le symbole `>`.

```
> Ceci est une citation.
```

## <span style="color:#d62828;">Code</span>

Pour un bloc de code, utilisez trois backticks `` ``` `` ou quatre espaces d'indentation. Pour du code inline, utilisez un seul backtick.

```
    Ceci est un bloc de code
```

```
`Ceci est du code inline`
```

*Exemple* :

```cpp
// Code Arduino pour faire clignoter une LED
void setup() {
  pinMode(13, OUTPUT); // Initialise la broche 13 en tant que sortie
}

void loop() {
  digitalWrite(13, HIGH);   // Allume la LED
  delay(1000);              // Attend une seconde
  digitalWrite(13, LOW);    // Éteint la LED
  delay(1000);              // Attend une seconde
}
```

## <span style="color:#d62828;">Lignes horizontales</span>

Utilisez trois ou plus de `*`, `-`, ou `_` pour créer une ligne horizontale.

```
---
```

## <span style="color:#d62828;">Tableaux</span>

Créez des tableaux en séparant les textes par des barres verticales `|` et des tirets `-`.

```
| En-tête 1 | En-tête 2 |
| --------- | --------- |
| Cellule 1 | Cellule 2 |
| Cellule 3 | Cellule 4 |
```


## <span style="color:#d62828;">Aller plus loin</span>

Si vous souhaitez aller plus loin, vous pouvez vous rendre sur la page de documentation du template du site ["Just the Docs"](https://just-the-docs.com).


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

<a class="bouton-suivant" href="../11-1-Premiers-pas-pour-creer-le-site/premiers-pas-4modifier_mon_site_avance">Next→</a>

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
