---
layout: default
title: Documents Techniques Initiaux de Présentation du Projet
nav_order: 2
parent: Documentation
---

# Documentation Technique Initiale du projet

Cette page rassemble l’ensemble des documents techniques que j’ai préparés pour **concevoir, formaliser et proposer mon projet personnel** de brassard électronique destiné aux pompiers, dans le cadre de la matière **Projet I3**.  
Ces documents ont été essentiels pour clarifier la vision du projet, définir les objectifs, et obtenir l’accord des enseignants responsables avant de lancer la phase de réalisation.

---

## Mes documents de préparation

<ul>
  <li>
    <strong>Dossier technique initial</strong><br>
    <a href="../Docs_Tech/Initial_Dossier-Tech.pdf" target="_blank" rel="noopener noreferrer">Ouvrir dans un nouvel onglet</a> | 
    <a href="../Docs_Tech/Initial_Dossier-Tech.pdf" download>Télécharger</a><br>
    Ce dossier complet décrit en détail le contexte du projet, le **cahier des charges** précisant les besoins et contraintes, ainsi que les objectifs fonctionnels et techniques que nous souhaitons atteindre.  
    Il présente également la méthodologie envisagée, les différentes étapes du projet, un planning prévisionnel, et une estimation des ressources nécessaires (budget, matériel, etc.).  
    Ce document a servi de base à la validation officielle du projet par les enseignants.
  </li>
  <li>
    <strong>Liste des composants techniques</strong><br>
    <a href="../Docs_Tech/Initial_Liste-composants-tech.pdf" target="_blank" rel="noopener noreferrer">Ouvrir dans un nouvel onglet</a> | 
    <a href="../Docs_Tech/Initial_Liste-composants-tech.pdf" download>Télécharger</a><br>
    Ce document liste tous les composants et modules électroniques sélectionnés pour le prototype, avec leurs caractéristiques principales et références.  
    Il s’agit d’un inventaire technique précis qui a permis de planifier les achats et d’assurer la cohérence matérielle du projet.
  </li>
</ul>

---

## Présentation des consignes de la matière

<ul>
  <li>
    <strong>Présentation officielle du Projet I3 (enseignants)</strong><br>
    <a href="../Docs_Tech/Présentation-Projet-I3_Prof.pdf" target="_blank" rel="noopener noreferrer">Ouvrir dans un nouvel onglet</a> | 
    <a href="../Docs_Tech/Présentation-Projet-I3_Prof.pdf" download>Télécharger</a><br>
    Document fourni par les enseignants responsables de la matière, il décrit les objectifs pédagogiques du projet, les attentes concernant le travail à réaliser, les critères d’évaluation, ainsi que les contraintes spécifiques.  
    Cette présentation a encadré l’ensemble de notre démarche et nous a guidés dans la réalisation du projet.
  </li>
</ul>


---

<script>
function openDocPopup(url, title) {
  const popup = window.open('', '_blank', 'width=400,height=200,top=200,left=400,resizable=no');
  popup.document.write(`
    <html>
      <head><title>${title}</title></head>
      <body style="font-family: Arial, sans-serif; text-align: center; padding: 20px;">
        <h2>${title}</h2>
        <p>Que souhaitez-vous faire avec ce document ?</p>
        <button style="margin: 10px; padding: 8px 16px; font-size: 16px;" onclick="window.open('${url}', '_blank');">Ouvrir dans un nouvel onglet</button>
        <button style="margin: 10px; padding: 8px 16px; font-size: 16px;" onclick="window.location.href='${url}';">Télécharger</button>
      </body>
    </html>
  `);
  popup.document.close();
}
</script>

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

<a class="bouton-suivant" href="../12-Contacts/contacts">Next→</a>

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
