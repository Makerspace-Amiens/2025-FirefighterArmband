---
layout: default
title: Modélisation d'un boitier
parent: Prototype
nav_order: 2
---

# Modélisation du boitier

## <span style="color:#d62828;">Objectif</span>

Concevoir un boîtier sur mesure pour accueillir l’ensemble des composants électroniques, tout en s’adaptant aux contraintes physiques de l’écran, des capteurs et d’une fixation possible sur une tenue pompier.

---

## <span style="color:#d62828;">Conception sur OnShape</span>

<div style="background-color:#f9f9f9; border-left: 5px solid #d62828; padding: 1rem 1.5rem; border-radius: 6px; margin-bottom: 1.5rem;">

La modélisation 3D du boîtier a été réalisée sur la plateforme en ligne **OnShape**, en intégrant les dimensions précises du CrowPanel, de la batterie et des connecteurs Grove.  
Le boîtier a été conçu en deux parties emboîtables avec emplacements prévus pour des inserts vissés (finalement inutiles grâce à un ajustement parfait).

</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; align-items: flex-start; margin-bottom: 2rem;">

  <div style="flex: 1 1 45%; text-align: center;">
    <img src="../images/protoonshape.png" alt="Modélisation OnShape Vue 1" style="width:100%; max-width:320px; border-radius:8px; box-shadow:0 4px 10px rgba(0,0,0,0.15);" />
    <p style="font-size: 0.9em; margin-top: 0.5rem;">Modèle sur OnShape – Vue globale</p>
  </div>

  <div style="flex: 1 1 45%; text-align: center;">
    <img src="../images/protomodfin.png" alt="Modèle prêt à l'impression" style="width:100%; max-width:320px; border-radius:8px; box-shadow:0 4px 10px rgba(0,0,0,0.15);" />
    <p style="font-size: 0.9em; margin-top: 0.5rem;">Modèle final prêt pour l'impression 3D</p>
  </div>

</div>

---

## <span style="color:#d62828;">Étapes de prototypage</span>

<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 30px; margin-bottom: 2rem;">

  <div style="flex: 1 1 420px;">
    <ul>
      <li>Création de maquettes plates à la découpeuse laser pour valider les dimensions de l’écran et des modules.</li>
      <li>Impression d’un premier boîtier 3D pour tester l’encombrement général et les passages de câbles.</li>
      <li>Échec d’un prototype final (défaut d’impression), mais validation de tous les ajustements nécessaires.</li>
      <li>Conception finale modifiée et ajustée pour une impression réussie et un emboîtement propre.</li>
    </ul>
  </div>

  <div style="flex: 1 1 300px; text-align: center;">
    <img src="../images/protosmod.png" alt="Prototypes de test" style="width:100%; max-width:320px; border-radius:8px; box-shadow:0 4px 10px rgba(0,0,0,0.15);" />
    <p style="font-size: 0.9em; margin-top: 0.5rem;">Maquettes testées (laser + 3D)</p>
  </div>

</div>

---

## <span style="color:#d62828;">Résultat final</span>

<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 30px;">

  <div style="flex: 1 1 420px;">
    <p>Le boîtier final, imprimé en PLA, s’ajuste parfaitement autour de l’écran tactile et des composants embarqués.  
    Les inserts prévus n’ont finalement pas été nécessaires grâce à un système d’emboîtement précis et solide.</p>
    <p>Le tout reste démontable, réutilisable, et prêt pour être fixé à une tenue de pompier dans une version ultérieure.</p>
  </div>

  <div style="flex: 1 1 300px; text-align: center;">
    <img src="../images/protofinal3D.png" alt="Prototype final assemblé" style="width:100%; max-width:320px; border-radius:8px; box-shadow:0 4px 10px rgba(0,0,0,0.15);" />
    <p style="font-size: 0.9em; margin-top: 0.5rem;">Prototype final assemblé</p>
  </div>

</div>

---

> Cette modélisation offre une base fiable et réplicable pour une intégration future dans un boîtier certifié anti-feu.


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

<a class="bouton-suivant" href="../6-Prototype/etape-3prog">Next→</a>

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
