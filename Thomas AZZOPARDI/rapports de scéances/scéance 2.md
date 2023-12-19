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
Après m'être Familiarisé avec l'utilisation des Servo-Moteur, j'ai pu attaqué un début de marche avant de notre quadrupède à l'aide de fonction :
<br></br>
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/856cb46a-56c5-41b2-8c9c-6b014b06be58" />
<br></br>
