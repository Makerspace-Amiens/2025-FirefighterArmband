---
layout: home
nav_order: 1
title: Accueil
---

<style>
.titre-projet {
  text-align: center;
  font-size: 2.8em;
  font-weight: bold;
  margin-bottom: 0.2em;
  background: linear-gradient(to right, #ff5722, #ff9800);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.soustitre {
  text-align: center;
  font-size: 1.4em;
  color: #444;
  margin-bottom: 1.5em;
}

.banniere {
  display: block;
  margin: 0 auto 2em auto;
  max-width: 100%;
  height: auto;
}
</style>

<div class="titre-projet">FirefighterArmband</div>
<div class="soustitre">Brassard localisant les points d'eaux pour les pompiers</div>

<p align="center">
  <img src="images/banniere_pompiers.png" alt="Bannière FirefighterArmband"
       style="width: 100%; max-width: 900px; height: auto; display: block;" />
</p>

<!-- --------------------------------------------------------------------------------- -->

<style>
.titre-brassard {
  text-align: center;
  font-size: 2em;
  font-weight: bold;
  margin-top: 2rem;
  margin-bottom: 2rem;
}

.bloc-brassard {
  display: flex;
  align-items: flex-start;
  justify-content: center;
  gap: 2rem;
  flex-wrap: nowrap;
}

.bloc-brassard img {
  max-width: 320px;
  border-radius: 12px;
  box-shadow: -8px 8px 20px rgba(0, 0, 0, 0.25);
}

.bloc-brassard .texte {
  max-width: 600px;
}

@media (max-width: 900px) {
  .bloc-brassard {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
}
</style>

<div class="titre-brassard">Un brassard intelligent au service des pompiers</div>

<div class="bloc-brassard">
  <img src="images/brasprojet.png" alt="Brassard connecté pour pompiers" />
  <div class="texte">
  <p><strong>FirefighterArmband</strong> est un projet innovant pensé pour <strong>faciliter les interventions des sapeurs-pompiers</strong>.</p>
  <p>Notre objectif : leur permettre de <strong>localiser rapidement les points d’eau à proximité</strong>, grâce à un <strong>brassard connecté et autonome</strong>.</p>
  <p>Conçu pour être robuste, intuitif et facilement utilisable sur le terrain, ce dispositif combine <strong>technologie GPS</strong>, <strong>interface minimaliste</strong>, et <strong>ergonomie adaptée aux interventions d'urgence</strong>.</p>
  </div>
</div>


---

## Accès aux supports

- [Voir le poster du projet](7-Supports/supports-1poster.md)
- [Regarder la vidéo de présentation](7-Supports/supports-6vidéo.md)

---

## Structure du site

Vous trouverez dans les différentes sections :
- Le cahier des charges initial et idéal
- Les contraintes techniques
- Le dossier technique (matériel, logiciel)
- Les tests et prototypes
- Les supports de présentation (poster, vidéo)

> Ce site vise à fournir une documentation claire, complète et structurée pour comprendre et reproduire le projet dans un cadre professionnel ou pédagogique.

---

## À qui s'adresse ce projet ?

- Aux **services de secours** souhaitant intégrer des outils innovants
- Aux **étudiants en ingénierie** intéressés par les projets embarqués
- Aux **makers** passionnés par l’électronique et la sécurité publique

---

--> **Naviguez via le menu latéral** pour explorer chaque partie du projet.  
Bonne découverte !


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

<a class="bouton-suivant" href="2-Objectifs/objectifs.md">Découverte→</a>

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
}

.footer-bandeau a:hover {
  text-decoration: underline;
}
</style>

<div class="footer-bandeau">
  <img src="images/logoULS.png" alt="Logo ULS" />
  <a href="docs/12-Contacts/contacts.md">Contacts</a>
</div>
