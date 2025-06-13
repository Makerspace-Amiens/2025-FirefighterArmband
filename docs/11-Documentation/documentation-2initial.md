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
    <a href="javascript:void(0);" onclick="openDocModal('modal-dossier-tech')">Dossier technique initial</a><br>
    Ce dossier complet décrit en détail le contexte du projet, le **cahier des charges** précisant les besoins et contraintes, ainsi que les objectifs fonctionnels et techniques que nous souhaitons atteindre.  
    Il présente également la méthodologie envisagée, les différentes étapes du projet, un planning prévisionnel, et une estimation des ressources nécessaires (budget, matériel, etc.).  
    Ce document a servi de base à la validation officielle du projet par les enseignants.
  </li>
  <li>
    <a href="javascript:void(0);" onclick="openDocModal('modal-liste-composants')">Liste des composants techniques</a><br>
    Ce document liste tous les composants et modules électroniques sélectionnés pour le prototype, avec leurs caractéristiques principales et références.  
    Il s’agit d’un inventaire technique précis qui a permis de planifier les achats et d’assurer la cohérence matérielle du projet.
  </li>
</ul>

---

## Présentation des consignes de la matière

<ul>
  <li>
    <a href="javascript:void(0);" onclick="openDocModal('modal-presentation-projet')">Présentation officielle du Projet I3 (enseignants)</a><br>
    Document fourni par les enseignants responsables de la matière, il décrit les objectifs pédagogiques du projet, les attentes concernant le travail à réaliser, les critères d’évaluation, ainsi que les contraintes spécifiques.  
    Cette présentation a encadré l’ensemble de notre démarche et nous a guidés dans la réalisation du projet.
  </li>
</ul>

<!-- Modales -->

<div id="modal-dossier-tech" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeDocModal('modal-dossier-tech')">&times;</span>
    <h3>Dossier technique initial</h3>
    <p>
      <a href="../Docs_Tech/Initial_Dossier-Tech.pdf" target="_blank" rel="noopener noreferrer">Ouvrir dans un nouvel onglet</a><br>
      <a href="../Docs_Tech/Initial_Dossier-Tech.pdf" download>Télécharger</a>
    </p>
  </div>
</div>

<div id="modal-liste-composants" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeDocModal('modal-liste-composants')">&times;</span>
    <h3>Liste des composants techniques</h3>
    <p>
      <a href="../Docs_Tech/Initial_Liste-composants-tech.pdf" target="_blank" rel="noopener noreferrer">Ouvrir dans un nouvel onglet</a><br>
      <a href="../Docs_Tech/Initial_Liste-composants-tech.pdf" download>Télécharger</a>
    </p>
  </div>
</div>

<div id="modal-presentation-projet" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeDocModal('modal-presentation-projet')">&times;</span>
    <h3>Présentation officielle du Projet I3</h3>
    <p>
      <a href="../Docs_Tech/Présentation-Projet-I3_Prof.pdf" target="_blank" rel="noopener noreferrer">Ouvrir dans un nouvel onglet</a><br>
      <a href="../Docs_Tech/Présentation-Projet-I3_Prof.pdf" download>Télécharger</a>
    </p>
  </div>
</div>

<style>
.modal {
  opacity: 0;
  visibility: hidden;
  position: fixed;
  top: 0; left: 0; width: 100%; height: 100%;
  background: rgba(0,0,0,0.5);
  display: flex; justify-content: center; align-items: center;
  z-index: 1000;
  transition: opacity 0.3s ease;
}
.modal.show {
  opacity: 1;
  visibility: visible;
}
.modal-content {
  background: #fff;
  padding: 20px 30px;
  border-radius: 12px;
  max-width: 400px;
  width: 90%;
  position: relative;
  box-shadow: 0 6px 20px rgba(0,0,0,0.3);
  text-align: center;
}
.close {
  position: absolute;
  top: 8px; right: 15px;
  font-size: 28px;
  font-weight: bold;
  color: #888;
  cursor: pointer;
  user-select: none;
}
.close:hover {
  color: #333;
}
.modal-content a {
  display: inline-block;
  margin: 8px 0;
  font-weight: 600;
  color: #d62828;
  text-decoration: none;
  transition: color 0.25s ease;
}
.modal-content a:hover {
  color: #a61c1c;
}
</style>

<script>
function openDocModal(id) {
  document.getElementById(id).classList.add('show');
}
function closeDocModal(id) {
  document.getElementById(id).classList.remove('show');
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

<a class="bouton-suivant" href="../11-Documentation/documentation-3technique.md">Next→</a>

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
