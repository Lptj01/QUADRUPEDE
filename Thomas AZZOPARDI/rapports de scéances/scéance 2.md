Durant cette scéance j'ai pu me focaliser sur le début du programme permettant de faire avancer notre futur Quadrupède.

J'ai tout d'abbord effectué des test sur un servo moteur : il faut faire attention à ne pas le brancher directement sur la carte Arduino mais à le faire passer par une "palette" (inderectement, ce cas ci suffit).
Il a donc fallut tout d'abbord implémenter la librairie "Servo" qui permet l'accès aux commandes "Servo.write(angle)" pouvant modifier l'angle de rotation du Servo-moteur (allant de 0 à 180 degrès MAX).

L'avantage d'avoir commencer par la liason bluetooth, c'est que tout le reste du projet pourra se faire via bluetooth : il n'y aura aucun changement ou imprévu suplémentaire à la fin.

J'ai donc réalisé un petit motage simple pour faire fonctionner 1 Servo-moteur à l'aide d'une commande bluetooth :

<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/5f86f527-37db-47b2-809b-4408b06c61ba"/>


<br></br>
Ainsi qu'un code assez simple afin de prendre en main ce nouveau domaine :
<br></br>
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/701a24b0-8341-448a-9a82-a568a2f2fcd2"/>
<br></br>
Qui permet de faire tourner de 180° ou de 0° selon si on active ou non un bouton sur notre téléphone (qui renvoie 1 ou 0 selon s'il est activé ou non).

<br></br>
Après m'être Familiarisé avec l'utilisation des Servo-Moteur, j'ai pu attaqué un début de marche avant de notre quadrupède à l'aide de fonction, mais il a d'abbord fallut déclaré les futurs Servo-Moteur en fonction de leur emplacement sur notre Quadrupède (pates avant droite, gauche, arrière droite, gauche,...) dans le Setup :
<br></br>
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/856cb46a-56c5-41b2-8c9c-6b014b06be58" />
<br></br>
La déclaration des ports dans lesquels les Servo-Moteur serront connecté afin de les manipuler :
<img src ="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/171243e8-eb9c-4780-9e32-bc72cd0d982b"/>
<br></br>
Déclarer le Nom des Servo-Moteur (commande Servo + Name), et la librairie qui nous sera indispensable.
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/5e804060-4d61-438d-9dc0-beafc6b9fd97"/>
<br></br>
Et enfin le début de fonction qui permettront de déplacer notre Quadrupède vers l'avant en l'occurrence :
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/6bba289d-c644-4cf0-aa9e-4d5e0f496621" />
<br></br>
Ces fonctions permettent de faire une rotation d'un certain angle pour 2 moteurs : l'idée et de faire bouger chaque pâtes (constitué de 2 moteurs)  d'un certains angle aà partir d'un angle initial (décalré comme 0 au début), il faudra peut etre rajouter les paramètres "angle1,angle2" afin d'être plus précis et optimal dans le déplacement de notre Quadrupède.
Les tests pourront s'effectuer plus tard dès qu'une maquettes ou certains éléments de construction seront à disposition.

Pour la prochaine scéance : les objectifs seront de crée une Appli optimisé pour pouvoir déplacer notre Quadrupède et remodifier le programme pour tester nos 2 fonctions à l'aide de cette appli par connection bluetooth.

