# L1_Projet_candys_turn
Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l’Université Côte d'Azur
Nous avons commencer par établir le code qui sera la base de notre projet, ils nous a fallu déterminés une certaine distance avec le capteur ultrason pour que quand on tend la main celui-ci déclenche le servomoteur qui permet de faire basculer le mécanisme et nous donnerai une certaine quantité de bonbon.
Comme on avait accès qu'a un servomoteur capable de tourner a 180°, nous avons donc penser à un mécanisme de rotation d'une piece circulaire dans laquelles est creusé un réservoire destiné au transport des bonbons. Aussi il était nécessaire pour compléter le mécanisme d'entourer la piece circulaire d'une autre piece permettant le bon acheminement des bonbons lors de la rotation.
Voici les deux pieces principales de notre mécanisme que nous avons designé sur tinkercad afin de les imprimer en 3D:

![image](https://user-images.githubusercontent.com/83219755/118818155-4bc8b180-b8b4-11eb-9508-61d0cb4b5c7d.png)

commençons donc a façonner sur tinkercard la pièces principale(réservoir amovible), et une autre pièce qui l'entoure(pour éviter un maximum de frottement). Malheureusement l'imprimante 3d nous plante au bout de quasiment 1H de préparation, il nous a fallu improvisé est terminer le travail a sa place, de même pour l'autre pièce(l'imprimante a bacler son travail).
Par manque de matériel et d'imagination nous prenons une boite a chaussure comme base pour le distributeur. Nous l'aménageons correctement pour pouvoir y mettre aisément la carte UCA le servomoteur, le capteur ultrason et les pièces imprimé. Pour compléter notre projet nous avons crée sur node red un système qui nous envoie un email quand le moteur tourne ou reviens a ça position initiale.
