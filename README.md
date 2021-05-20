# L1_Projet_candys_turn
Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l’Université Côte d'Azur

Nous avons commencé par réfléchir au mécanisme que nous allions utiliser. Etant donné que l'on avait accès qu'a un servomoteur capable de tourner a 180°, nous avons donc penser à un mécanisme de rotation d'une piece circulaire dans laquelles est creusé un réservoire destiné au transport des bonbons. Aussi il était nécessaire pour compléter le mécanisme d'entourer la piece circulaire d'une autre piece permettant le bon acheminement des bonbons lors de la rotation.
Voici les deux pieces principales de notre mécanisme que nous avons designé sur tinkercad avant de les imprimer en 3D:

![image](https://user-images.githubusercontent.com/83219755/118818155-4bc8b180-b8b4-11eb-9508-61d0cb4b5c7d.png)

Malheureusement nous avons rencontré de nombreux problèmes avec les imprimante 3D (stabilité de plateau, acheminement de fil, densité). il nous a fallu improvisé et rafistolé les pieces à la mains.
![2021-05-19 23_19_01-118840908-1af27780-b8c8-11eb-95ea-d15bce4889ef jpg (3000×4000)](https://user-images.githubusercontent.com/83219755/118886153-ddf2a900-b8f8-11eb-8523-97bd884b6858.png)

Ensuite, nous avons commencer par établir le code qui permet de contrôler le capteur et le servo moteur. Ils nous a fallu déterminés une certaine distance avec le capteur ultrason pour que quand on tend la main celui-ci déclenche le servomoteur qui permet de faire basculer le mécanisme et nous donnerai une certaine quantité de bonbon. 
(voir code1)


Nous avons pris une boite a chaussure comme base pour le distributeur. Nous l'avons aménagé correctement pour pouvoir y mettre aisément la carte UCA le servomoteur, le capteur ultrason et les pièces du mécanisme. 

Pour compléter notre projet nous avons crée sur node red un système qui nous envoie un email quand le moteur tourne ou reviens a ça position initiale. 
(voir code2)


