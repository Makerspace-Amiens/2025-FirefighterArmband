---
layout: default
title: Contraintes de programmation
parent: Programmation du brassard
nav_order: 1
---

# Contraintes techniques de programmation

## <span style="color:#d62828;">Introduction</span>

Notre objectif avec ce projet était clair : **concevoir un brassard GPS capable d’indiquer aux pompiers la direction et la distance jusqu’aux points d’eau les plus proches**, afin de leur faire **gagner un temps précieux en intervention**.  
Mais transformer cette idée en un outil simple, fiable et efficace a soulevé plusieurs **contraintes techniques**, notamment liées à la programmation et à l’intégration matérielle. Voici les principales.

---

## <span style="color:#d62828;">1. L’inconnu de l’écran Elecrow – S’adapter à une carte peu documentée</span>

Nous avons utilisé un écran tactile **Elecrow CrowPanel**, qui intègre un **ESP32**. Si ce composant répondait à nos attentes matérielles, la carte en elle-même était **mal documentée**.

- Nous avons dû **chercher et tester manuellement plusieurs bibliothèques**, car aucune bibliothèque officielle spécifique au CrowPanel n’était fournie.
- Il a fallu identifier et configurer les bons fichiers pour l’affichage graphique, notamment les bibliothèques **GFX** compatibles.
- Cette phase a demandé beaucoup de temps de tests pour simplement afficher nos premières interfaces, et comprendre comment communiquer avec les capteurs via cette carte.

Ce manque d’information a constitué l’une des **premières vraies difficultés du projet**.

---

## <span style="color:#d62828;">2. Une flèche directionnelle – Traduire une direction en visuel clair</span>

Afficher une **flèche qui indique la direction du point d’eau** peut sembler simple… mais ça ne l’est pas.

- Il a fallu convertir la **différence d’angle entre la position actuelle (détectée par la boussole)** et la **direction du point d’eau (calculée via GPS)**.
- Une fois cette différence calculée, nous devions afficher dynamiquement une flèche tournée dans le bon sens, avec un rafraîchissement fluide.
- Cela a nécessité la création de **fonctions trigonométriques** pour transformer ces données numériques en **repères visuels compréhensibles**.

Ce système est **au cœur de l’interface utilisateur** : les pompiers doivent comprendre instinctivement dans quelle direction aller.

---

## <span style="color:#d62828;">3. Distance et orientation – Le duo GPS + Boussole</span>

La navigation ne se limite pas à la direction : il faut aussi **connaître la distance** jusqu’au point d’eau, et la recalculer à chaque déplacement.

- Nous avons utilisé le **GPS NEO6M** pour connaître la position géographique du pompier.
- En parallèle, la **boussole Grove 3 axes** nous fournit l’orientation réelle (le cap).
- Le programme calcule la **distance entre les coordonnées GPS actuelles** et celles du point d’eau, à l’aide de la **formule de Haversine**.
- À chaque mise à jour du GPS, la distance et la direction sont recalculées en temps réel.

Ce traitement dynamique assure que le **pompier a toujours une information à jour**, même s’il change de direction ou de position.

---

## <span style="color:#d62828;">4. Affichage simple, clair, rapide, visible</span>

L’interface du brassard devait être **intuitive, minimaliste et lisible** dans n’importe quelle condition (fumée, faible lumière, stress…).

- Nous avons fait le choix d’un **affichage épuré** : une flèche, une distance, et parfois une icône pour signaler un point d’eau à proximité.
- Les couleurs et les polices ont été choisies pour être visibles rapidement.
- Le tout est **pensé pour une lecture immédiate**, sans que l’utilisateur ait besoin de réfléchir : **l’outil doit être une aide, pas un obstacle.**

Cet aspect était **fondamental** : en situation d’urgence, chaque seconde compte.

---

## <span style="color:#d62828;">Conclusion</span>

En résumé, chaque contrainte technique rencontrée avait un seul objectif : **offrir aux pompiers un outil fiable, intuitif, et immédiatement utile en intervention.**  
Entre choix de composants, adaptation aux bibliothèques, calculs GPS, et affichage clair, notre travail a toujours été guidé par le terrain et ses exigences.


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

<a class="bouton-suivant" href="../6-Prototype/etape-3-2prog">Next→</a>

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
