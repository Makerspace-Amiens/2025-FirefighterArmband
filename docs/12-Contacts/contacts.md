---
layout: default
title: Contacts
nav_order: 12
---

# Contacts des Collaborateurs

<br>
<div style="border-bottom: 3px solid #d62828; width: 100%; margin-top: -1em; margin-bottom: 1em;"></div>


<div style="text-align: center; font-size: 1.3em; margin-bottom: 1.5em;">
  Retrouvez ci-dessous la photo d’équipe, puis les profils cliquables des membres du projet et des encadrants.
</div>

<!-- PHOTO DE GROUPE -->
<p align="center">
  <img src="photo_groupe.webp" alt="Photo de groupe FirefighterArmband" style="width:100%; max-width:800px; border-radius:12px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" />
</p>

---

##  <span style="color:#d62828;">Membres du projet</span>

<div class="team-container">

<!-- Max -->
<div class="team-member">
  <img src="photo_max.png" alt="Max Mallevays">
  <p><a href="javascript:void(0);" onclick="openModal('modal-max')">Max Mallevays</a></p>
</div>

<!-- Roméo -->
<div class="team-member">
  <img src="photo_romeo.jpg" alt="Roméo Smagghe">
  <p><a href="javascript:void(0);" onclick="openModal('modal-romeo')">Roméo Smagghe</a></p>
</div>

<!-- Iléana -->
<div class="team-member">
  <img src="photo_ile.jpg" alt="Iléana Laurent">
  <p><a href="javascript:void(0);" onclick="openModal('modal-ileana')">Iléana Laurent</a></p>
</div>

</div>

---

##  <span style="color:#d62828;">Encadrants du Projet I3</span>

<div class="team-container">

<!-- Adrien -->
<div class="team-member">
  <img src="photo_adrien.jpg" alt="Adrien Bracq">
  <p><a href="javascript:void(0);" onclick="openModal('modal-adrien')">Adrien Bracq</a></p>
</div>

<!-- Rémi -->
<div class="team-member">
  <img src="photo_remi.jpg" alt="Rémi Lacombe">
  <p><a href="javascript:void(0);" onclick="openModal('modal-remi')">Rémi Lacombe</a></p>
</div>

</div>

---

##  <span style="color:#d62828;">Makerspace Amiens</span>

<p style="text-align: center; font-size: 1.1em;">
🔗 <a href="https://makerspace-amiens.fr" target="_blank" rel="noopener noreferrer">https://makerspace-amiens.fr</a>
</p>

---

<!-- Modales -->

<!-- Max -->
<div id="modal-max" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal-max')">&times;</span>
    <h2>Max Mallevays</h2>
    <p><strong>Email :</strong> <a href="mailto:max.mallevays@etu.unilasalle.fr">max.mallevays@etu.unilasalle.fr</a></p>
  </div>
</div>

<!-- Roméo -->
<div id="modal-romeo" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal-romeo')">&times;</span>
    <h2>Roméo Smagghe</h2>
    <p><strong>Email :</strong> <a href="mailto:romeo.smagghe@etu.unilasalle.fr">romeo.smagghe@etu.unilasalle.fr</a></p>
  </div>
</div>

<!-- Iléana -->
<div id="modal-ileana" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal-ileana')">&times;</span>
    <h2>Iléana Laurent</h2>
    <p><strong>Email :</strong> <a href="mailto:ileana.laurent@etu.unilasalle.fr">ileana.laurent@etu.unilasalle.fr</a><br />
    <a href="mailto:ileana.laurent.80@gmail.com">ileana.laurent.80@gmail.com</a></p>
    <p><strong>LinkedIn :</strong> <a href="https://www.linkedin.com/in/iléana-laurent" target="_blank">Profil LinkedIn</a></p>
  </div>
</div>

<!-- Adrien -->
<div id="modal-adrien" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal-adrien')">&times;</span>
    <h2>Adrien Bracq</h2>
    <p><strong>Rôle :</strong> Enseignant-chercheur, responsable du Projet I3</p>
    <p><strong>Email :</strong> <a href="mailto:adrien.bracq@unilasalle.fr">adrien.bracq@unilasalle.fr</a></p>
    <p><strong>LinkedIn :</strong> <a href="https://www.linkedin.com/in/adrien-bracq-783b54267/" target="_blank">Profil LinkedIn</a></p>
  </div>
</div>

<!-- Rémi -->
<div id="modal-remi" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal-remi')">&times;</span>
    <h2>Rémi Lacombe</h2>
    <p><strong>Rôle :</strong> Étudiant apprenti, assistant encadrant</p>
    <p><strong>Email :</strong> <a href="mailto:remi.lacombe@etu.unilasalle.fr">remi.lacombe@etu.unilasalle.fr</a></p>
    <p><strong>LinkedIn :</strong> <a href="https://www.linkedin.com/in/lacombe-r/" target="_blank">Profil LinkedIn</a></p>
  </div>
</div>

<!-- Styles et scripts -->
<style>
.team-container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
  margin-top: 20px;
}
.team-member {
  background-color: #f8f8f8;
  width: 200px;
  height: 250px;
  text-align: center;
  padding: 15px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
  transition: 0.3s ease;
}
.team-member:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}
.team-member img {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  object-fit: cover;
}
.team-member p a {
  display: block;
  margin-top: 12px;
  font-weight: bold;
  text-decoration: none;
  color: #333;
}
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
  padding: 30px;
  border-radius: 10px;
  max-width: 500px;
  width: 90%;
  position: relative;
}
.close {
  position: absolute;
  top: 10px; right: 20px;
  font-size: 24px;
  cursor: pointer;
  color: #aaa;
}
.close:hover {
  color: black;
}
</style>

<script>
function openModal(id) {
  document.getElementById(id).classList.add('show');
}
function closeModal(id) {
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

<a class="bouton-suivant" href="../index">Retour à l'Accueil→</a>

<!----------------------------------------------------------------------------->

<style>
.footer-bandeau {
  background-color: #f8d7da; /* rouge pastel */
  padding: 1rem 2rem;
  display: flex;
  justify-content: center; /* centre horizontalement le contenu */
  align-items: center;
  margin-top: 3rem;
  border-top: 2px solid #d62828;
  font-weight: bold;
}

.footer-bandeau img {
  height: 40px;
}
</style>

<div class="footer-bandeau">
  <img src="../images/logoULS.png" alt="Logo ULS" />
</div>
