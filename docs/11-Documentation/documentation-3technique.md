---
layout: default
title: Documents Techniques Globaux de Présentation du Projet
nav_order: 3
parent: Documentation
---

<section class="documentation">

  <h1 style="text-align:center; color:#d62828;">Documentation Technique détaillée du projet</h1>

  <p style="text-align:justify; max-width:900px; margin:auto;">
    Cette section rassemble tous les documents techniques de référence que j’ai utilisés ou créés pour développer le <strong>Firefighter Armband</strong>. 
    Ces ressources détaillent les normes d’étanchéité visées, les spécifications techniques de l’écran principal, les guides de mise en œuvre et l’utilisation du logiciel métier des pompiers.
    L’objectif est de garantir la conformité technique et de faciliter le transfert du projet pour un développement ultérieur plus abouti.
  </p>

  <h2 style="text-align:center; color:#d62828;">Documents PDF</h2>

  <div class="doc-grid">

    <div class="doc-box">
      <a href="../Docs_Tech/Certif_normes-etanch.pdf" target="_blank">
        Normes d'étanchéité
      </a>
    </div>

    <div class="doc-box">
      <a href="../Docs_Tech/DocTech_EcranCrowPanel.pdf" target="_blank">
        Document technique de l'écran
      </a>
    </div>

    <div class="doc-box">
      <a href="../Docs_Tech/esp32-display-datasheet.pdf" target="_blank">
        Datasheet de l'écran ESP32
      </a>
    </div>

    <div class="doc-box">
      <a href="../Docs_Tech/esp32-user-manual.pdf" target="_blank">
        Manuel utilisateur de l'écran ESP32
      </a>
    </div>

    <div class="doc-box">
      <a href="../Docs_Tech/Guide_LogicielPompier.pdf" target="_blank">
        Guide logiciel pompier
      </a>
    </div>

  </div>

  <h2 style="text-align:center; color:#d62828;">Liens utiles</h2>

  <div class="links-list" style="max-width:900px; margin:auto; text-align:left;">
    <h3 style="color:#d62828;">Achats composants</h3>
    <ul>
      <li><a href="https://eu.robotshop.com/fr/products/crowpanel-esp32-ecran-tactile-hmi-7-pouces-800x480-wi-fi-ble?qd=aa333dea406c3f1735552f31bd18a365" target="_blank">Écran tactile CrowPanel ESP32</a></li>
      <li><a href="https://www.gotronic.fr/art-module-boussole-grove-v2-101020492-27807.htm" target="_blank">Module boussole Grove V2</a></li>
      <li><a href="https://www.gotronic.fr/art-module-gps-tel0094-25732.htm" target="_blank">Module GPS TEL0094</a></li>
    </ul>

    <h3 style="color:#d62828;">Liens multimédia pour l’écran</h3>
    <ul>
      <li><a href="https://www.elecrow.com/wiki/esp32-display-702727-intelligent-touch-screen-wi-fi26ble-800480-hmi-display.html?h=crow+panel+esp32" target="_blank">Wiki technique Elecrow</a></li>
      <li><a href="https://www.elecrow.com/wiki/Tutorials.html" target="_blank">Tutoriels d’implémentation Elecrow</a></li>
    </ul>
  </div>

</section>

<!-- CSS interne pour un affichage élégant -->
<style>
  .documentation {
    padding: 40px 20px;
    font-family: Arial, sans-serif;
  }

  .doc-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin: 30px auto;
    max-width: 1000px;
  }

  .doc-box {
    background-color: #f1f1f1;
    border: 2px solid #d62828;
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    width: 200px;
    transition: 0.3s;
  }

  .doc-box a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
  }

  .doc-box:hover {
    background-color: #d62828;
  }

  .doc-box:hover a {
    color: #fff;
  }

  .links-list ul {
    list-style-type: none;
    padding-left: 0;
  }

  .links-list li {
    margin: 8px 0;
  }

  .links-list a {
    color: #333;
    text-decoration: underline;
  }

  .links-list a:hover {
    color: #d62828;
  }
</style>


<!----
doc en local pdf:
doc de normes d'étanchéité :
[text](../Docs_Tech/Certif_normes-etanch.pdf)

document technique et d'inplémentation de l'écran
[text](../Docs_Tech/DocTech_EcranCrowPanel.pdf)

manuel de l'écran : 
[text](../Docs_Tech/esp32-display-datasheet.pdf)
[text](../Docs_Tech/esp32-user-manual.pdf)

logiciel pompier manuel :
[text](../Docs_Tech/Guide_LogicielPompier.pdf)


liens : 
achats:
écran:
https://eu.robotshop.com/fr/products/crowpanel-esp32-ecran-tactile-hmi-7-pouces-800x480-wi-fi-ble?qd=aa333dea406c3f1735552f31bd18a365
boussole :
https://www.gotronic.fr/art-module-boussole-grove-v2-101020492-27807.htm
gps:
https://www.gotronic.fr/art-module-gps-tel0094-25732.htm

liens multimédia associé à l'écran :
wiki : 
https://www.elecrow.com/wiki/esp32-display-702727-intelligent-touch-screen-wi-fi26ble-800480-hmi-display.html?h=crow+panel+esp32
tuto d'inplémentation :
https://www.elecrow.com/wiki/Tutorials.html

-->

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
