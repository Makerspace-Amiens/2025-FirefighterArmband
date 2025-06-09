---
layout: default
title: Contraintes Techniques
nav_order: 1
parent: Cahier des Charges Projet
---

# Contraintes du Prototype Réel

## <span style="color:#d62828;">Techniques</span>

<div style="background-color:#f0f0f0; padding: 1rem 1.5rem; border-left: 5px solid #d62828; border-radius: 6px; margin-bottom: 2rem;">

- Composants sélectionnés pour leur disponibilité <br>
- Résistance aux chocs modérée (boîtier imprimé en 3D)<br>
- Pas d'étanchéité certifiée<br>
- Utilisation de coordonnées fictives<br>
- Récupération d'une veste de feu et Intégration du brassard <br>

</div>

---

## <span style="color:#d62828;">Fonctionnelles</span>

<div style="background-color:#f0f0f0; padding: 1rem 1.5rem; border-left: 5px solid #d62828; border-radius: 6px; margin-bottom: 2rem;">

- Obtention et réadaptation du logiciel des pompiers<br>
- Mode direction uniquement (pas de carte interactive)<br>
- Affichage sur écran tactile 7” (CrowPanel ESP32)<br>
- Guidage par flèche et distance GPS<br>
- Interface utilisable avec gants (testée) <br>

</div>

---

## <span style="color:#d62828;">Limites</span>

<div style="background-color:#fff7f7; padding: 1rem 1.5rem; border-left: 5px solid #d62828; border-radius: 6px;">

- Délais d'obtention du logiciel et dee la veste de feu par le SDIS<br>
- Projet partant de rien et nécessitant une grande phase de recherches au préalable (donc moins de temps pour la phase technique)<br>
- Batterie non certifiée (Li-ion classique)<br>
- Matériaux courants (non résistants)<br>
- Absence de test en conditions extrêmes<br>
- Pas de validation professionnelle <br>

</div>


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

<a class="bouton-suivant" href="../Projet/cahier-2-4objectifs">Next→</a>

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
