---
layout: default
title: Choix des Matériaux
nav_order: 1
parent: Conception
---

# Choix des Matériaux

## <span style="color:#d62828;">Objectif</span>

Sélectionner des matériaux simples, accessibles et compatibles avec notre environnement de test, tout en anticipant une future intégration dans une **tenue de pompier réelle**.  
L’enveloppe devait protéger efficacement l’électronique embarquée, sans viser la certification feu à ce stade du projet.

---

## <span style="color:#d62828;">Matériaux retenus</span>

<div style="background-color:#f0f0f0; padding: 1rem 1.5rem; border-radius: 6px; margin-bottom: 1.5rem;">

- <strong>Boîtier en PLA</strong> (impression 3D) : utilisé pour le prototype. Léger, facilement imprimable. Structure provisoire en attente d’intégration finale sur tenue. <br>

- <strong>Verre trempé transparent</strong> : protège l’écran tout en assurant lisibilité et utilisation avec des gants.<br>

- <strong>Mousse de calage interne</strong> : amortit les vibrations et protège les composants internes.<br>

- <strong>Système de fixation par inserts métalliques</strong> : permet d’ouvrir et refermer le boîtier proprement, en assurant sa robustesse.<br>

- <strong>Poche à scratch (prévue)</strong> : inspirée des poches ignifugées des tenues de feu. Non intégrée faute de temps, mais testée et validée comme solution d’intégration future.<br>

</div>

---

## <span style="color:#d62828;">Démarche et critères de choix</span>

<div style="background-color:#fff7f7; padding: 1rem 1.5rem; border-radius: 6px;">

- **Compatibilité avec la tenue de feu** : tests réalisés avec une veste réelle, prêtée par un pompier professionnel.<br>
- **Facilité de fabrication** : impression 3D, assemblage standard, découpe manuelle réalisable dans un Fablab.<br>
- **Solidité suffisante** : bon compromis entre rigidité, légèreté et coût.<br>
- **Évolutivité** : le boîtier et ses composants peuvent être intégrés dans un dispositif ignifugé dans une version avancée.<br>

</div>

---

> À noter : ces matériaux ne sont **pas certifiés feu**, mais ont été choisis pour une démonstration fonctionnelle cohérente avec l’environnement ciblé.


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

<a class="bouton-suivant" href="../5-Conception/conception-2composants">Next→</a>

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
