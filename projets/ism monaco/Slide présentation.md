---
marp: true
theme: arthur-github
paginate: true
footer: Arthur Mougin
lang: fr
tags: 
- ISM
- Apple Vision Pro
class:
---

# Créer une application pour Apple Vision Pro 🥽
Compatible avec Shariiing XR
<!-- 
_paginate: false 
_class: lead
-->

---

## Programme
- Technologie
- Design général
- Types d'expériences

---

## Parlons Tech
<!-- 
_paginate: false 
_class: lead
-->

---

## Tech : Retour d'entretien avec Immersion
### Plugin Unity compatible **Quest** et **AVP**
- Retransmission sur les écrans du contenu du casque*
- Interaction depuis l'écran vers le casque 
Il n'inclue pas de multijoueur a proprement parlé, mais ca serait facile à implémenter de notre coté.
<!--
_footer: Arthur Mougin - *uniquement en réalité virtuelle 
-->
---
## Tech : Retour d'entretien avec Immersion
## Pionniers
Premiers à développer ce type d'applications
➡ Apport de support par email

![bg right:40%](annexes/Pasted%20image%2020241211103951.png)


---

## Tech : Ce que le casque d'Apple permet
- Inputs : suivi mains, regarder et pincer (recommandé)
- Taille d'expériences : un petit carré ou un univers entier.
- Capacités graphiques et de calcul bien supérieures au casque Meta Quest 3

---

## Parlons design
[Design great visionOS apps - WWDC24](https://developer.apple.com/videos/play/wwdc2024/10086/)

<!-- 
_paginate: false 
_class: lead
-->
---
## Design : Recommandations d'Apple
### Interface intentionnelle
- Identifier ce qui rend la plateforme unique

![bg left:40%](annexes/Pasted%20image%2020241212103516.png)

---
## Design : Recommandations d'Apple
### Interface intentionnelle
- Explorer le champ des possibles

![bg right:40%](annexes/Pasted%20image%2020241212103557.png)


---
## Design : Recommandations d'Apple
### Interface intentionnelle
- Donner vie à des modèles photoréalistes

![h:250](annexes/Pasted%20image%2020241212103613.png)
<style>
 img
 {
	 margin-left:16em;
 }
</style>

---
## Design : Recommandations d'Apple
### Interface intentionnelle
- Si l'interface originelle est trop complexe, il faut alors proposer une expérience **complémentaire**.


![bg  right:55%](annexes/Pasted%20image%2020241212103653.png)
![bg](annexes/Pasted%20image%2020241212103726.png)

---

## Design : Recommandations d'Apple
### Exemple d'immersion
- Transporter les utilisateurs dans un autre monde
- Ces environnements doivent être fidèles à la réalité et inclure un sens de la profondeur et de l'échelle

![bg left:40%](annexes/Pasted%20image%2020241212103812.png)

---

## Design : Recommandations d'Apple

### Concevoir une expérience sonore qui ai du sens
- Le son est calculé par le casque pour donner l'impression de provenir de l'environnement réel de l'utilisateur

![bg right:50%](annexes/Pasted%20image%2020241212103851.png)

---

# Types d'expériences

<!-- 
_paginate: false 
_class: lead
-->
---
## Expériences : Parlons cartes

![bg right:70%](https://images.techhive.com/images/article/2016/11/googleearthvr_2-100693965-orig.jpg)
![bg](https://blogs.bing.com/BingBlogs/media/MapsBlog/2019/04/SpaceNeedle_1.png)

---
## Expériences : Parlons cartes
### Cartes à l'échelle de l'empire
Exemple : carte chronologique dont chaque strate représente une période historique.
→ [Carte de l'empire romain par strates](https://sketchfab.com/3d-models/roman-empire-3d-atlas-060cb0d7c4cb40aaad88fdd6f6e06c74)

---

## Expériences : Parlons cartes
### Cartes à l'échelle de l'empire
Travail de [Johan Åhlfeldt](https://x.com/JohanAhlfeldt) qui a créé un jeu de données cartographiques autour de l'empire romain : [Digital Atlas of the Roman Empire](https://imperium.ahlfeldt.se/).

---

## Expériences : Parlons cartes

### Cartes à l'échelle d'une ville
Exemple : carte de Rome en 3D
→ [Rome en 3D | Google Maps](https://www.google.fr/maps/place/Rome,+Ville+m%C3%A9tropolitaine+de+Rome+Capitale,+Italie/@41.8867832,12.4946981,149a,35y,323.74h,71.72t/data=!3m1!1e3!4m6!3m5!1s0x132f6196f9928ebb:0xb90f770693656e38!8m2!3d41.8967068!4d12.4822025!16zL20vMDZjNjI?entry=ttu&g_ep=EgoyMDI0MTIxMC4wIKXMDSoASAFQAw%3D%3D)


---

## Expériences : Parlons cartes

### Cartes à l'échelle d'une ville
Exemple : Scan d'une ancienne maquette de Rome
→ [Massive scale model of Ancient Rome by Benoît Rogez](https://sketchfab.com/3d-models/massive-scale-model-of-ancient-rome-2f9cb1fbc2eb470686eb8ba596b059cb)

---

## Expériences : Parlons cartes

### À l'échelle d'un bâtiment
Les bâtiments historiques sont numérisés dans leur état actuel.

→ [Baelo Claudia Roman amphitheatre, Cadiz, Spain](https://sketchfab.com/3d-models/baelo-claudia-roman-amphitheatre-cadiz-spain-1b4d87510ea846bd94e43e9bef699249)
→ [Vatican City State, Rome, Italy](https://sketchfab.com/3d-models/vatican-city-state-rome-italy-b35b1e866ead4fb385e48dd3f2a99663)


---


## Expériences : Parlons cartes

### À l'échelle d'un bâtiment
Les bâtiments peuvent être modélisés dans leur état d'origine.

→ [modèle 3D d'Amphithéâtre - TurboSquid](https://www.turbosquid.com/fr/3d-models/ancient-greek-architecture-roman-building-3d-model-1282755)
→ [Théâtre romain modèle 3D - Free3D](https://free3d.com/fr/3d-model/roman-theatre-3919.html)

---



## Expériences : Parlons Jeux

<!-- 
_paginate: false 
_class: lead
-->

---

## Expériences : Parlons Jeux
### Jeux de décision politique
- [Reigns](httpsyoutu.be/O2HnvpXqII4?si=rmjm9Ntzvkx3nka9)
- [Civilisation](https://www.youtube.com/watch?v=5KdE0p2joJw)
![bg left:40%](https://cdn.2kgames.com/civilization.com/Beginners_Civ_hero.jpg)
---

## Expériences : Parlons Jeux
### Jeux d'exploration
 - [The Climb 2](https://www.youtube.com/watch?v=YSNPalIihiE)
 - [Ocean Rift](https://www.youtube.com/watch?time_continue=22&v=4lCwRg9oQ1c&embeds_referring_euri=https%3A%2F%2Fwww.bing.com%2F&embeds_referring_origin=https%3A%2F%2Fwww.bing.com&source_ve_path=Mjg2NjMsMjg2NjY)
![bg right:40%](annexes/Pasted%20image%2020241212142759.png)

---

## Expériences : Parlons Jeux
### Jeux de réflexion
  - [The Curious Tale of the Stolen Pets](https://www.youtube.com/watch?v=EOuI6FGxYkA)
  - [Puzzling Places](https://www.youtube.com/watch?v=gmuGRIHfmRQ) 
![bg left:40%](annexes/Pasted%20image%2020241212142625.png)
---

## Expériences : Parlons Jeux
### Jeux de rapidité et combat
- [Fruit Ninja VR](https://store.steampowered.com/app/486780/Fruit_Ninja_VR/)
- [Gladius | Gladiator VR Sword fighting](https://store.steampowered.com/app/556640/Gladius__Gladiator_VR_Sword_fighting/)

![bg right:40%](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/556640/ss_bff92ce18e3dad04d227d5daa94751138a901c2b.jpg?t=1667122074)

---
## Conclusion
Le casque Apple Vision Pro est un outil puissant pour la réalité virtuelle et Augmentée. 
L'intégration avec ShariiingXR et l'utilisation des guidelines d'Apple permettent de créer des expériences Impactantes au sein de l'ISM.

---
## Retours
Les points qui sont ressortis de cette présentation sont :
- Le contenu cartographique que possède ISM est déjà très riche
- Par contre, les points suivants auraient une vrai valeur ajoutée et seront étudiés : 
	- **Course en char** dans le Circus Maximus
	- **Combats de gladiateurs** dans le Colisée