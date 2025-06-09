---
layout: default
title: Composants
nav_order: 2
parent: Conception
---

# Composants Électroniques

## <span style="color:#d62828;">Objectif</span>

Rassembler les composants nécessaires pour assurer les trois fonctions essentielles du prototype :

<div style="background-color:#f9f9f9; padding: 1rem 1.5rem; border-left: 5px solid #d62828; border-radius: 6px; margin-bottom: 1.5rem;">

- Acquisition de position GPS  <br>
- Orientation via boussole  <br>
- Affichage graphique clair et interactif<br>

</div>

---

## <span style="color:#d62828;">Liste des composants</span>

<table style="width:100%; border-collapse: collapse; margin-bottom: 2rem;">
  <thead>
    <tr style="background-color:#f0f0f0;">
      <th style="padding: 10px; text-align: left;">Composant</th>
      <th style="padding: 10px; text-align: left;">Référence</th>
      <th style="padding: 10px; text-align: left;">Fonction</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Microcontrôleur</td>
      <td><strong>ESP32-S3 CrowPanel</strong></td>
      <td>Affichage, GPS, gestion interface</td>
    </tr>
    <tr>
      <td>Écran</td>
      <td>Intégré (7” tactile)</td>
      <td>Interface utilisateur principale</td>
    </tr>
    <tr>
      <td>GPS</td>
      <td><strong>Module TEL0094</strong></td>
      <td>Localisation des points d’eau</td>
    </tr>
    <tr>
      <td>Boussole</td>
      <td><strong>Grove 3-Axis Compass V2</strong></td>
      <td>Orientation / calcul direction</td>
    </tr>
    <tr>
      <td>Batterie</td>
      <td>3.7V Li-ion</td>
      <td>Alimentation autonome (usage ponctuel)</td>
    </tr>
    <tr>
      <td>Divers</td>
      <td>Câbles, connecteurs Grove</td>
      <td>Intégration simple, fiable et modulaire</td>
    </tr>
  </tbody>
</table>

---

## <span style="color:#d62828;">Justification des choix</span>

<div style="display: flex; gap: 20px; flex-wrap: wrap; align-items: center;">

  <div style="flex: 1; min-width: 260px;">
    <p><strong>ESP32-S3 CrowPanel</strong> : puissant, compatible Arduino et Micropython, intégrant un écran tactile 7".</p>
    <p><strong>Connecteurs Grove</strong> : permettent un câblage modulaire et sécurisé, réduisant les erreurs de branchement.</p>
    <p><strong>Modules GPS et Boussole</strong> : éprouvés dans des projets similaires, tous deux compatibles avec l'ESP32.</p>
  </div>

  <div style="flex: 0 0 auto; text-align: center;">
    <img src="../images/ecran.png" alt="Écran 7 pouces" title="Écran tactile 7'' intégré au CrowPanel" style="width: 80px; margin-bottom: 10px;"><br/>
    <img src="../images/GPS.png" alt="Module GPS TEL0094" title="Module GPS utilisé pour la localisation" style="width: 80px; margin-bottom: 10px;"><br/>
    <img src="../images/boussole.png" alt="Module boussole Grove" title="Boussole Grove utilisée pour l’orientation" style="width: 80px;">
  </div>

</div>


> Tous les composants ont été choisis pour leur **compatibilité logicielle**, leur **disponibilité** et leur **coût maîtrisé**.


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

<a class="bouton-suivant" href="../5-Conception/conception-3achat">Next→</a>

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
