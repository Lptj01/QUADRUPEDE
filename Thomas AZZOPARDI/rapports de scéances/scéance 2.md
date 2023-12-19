Durant cette scéance j'ai pu me focaliser sur le début du programme permettant de faire avancer notre futur Quadrupède.

J'ai tout d'abbord effectué des test sur un servo moteur : il faut faire attention à ne pas le brancher directement sur la carte Arduino mais à le faire passer par une "palette" (inderectement, ce cas ci suffit).
Il a donc fallut tout d'abbord implémenter la librairie "Servo" qui permet l'accès aux commandes "Servo.write(angle)" pouvant modifier l'angle de rotation du Servo-moteur (allant de 0 à 180 degrès MAX).

L'avantage d'avoir commencer par la liason bluetooth, c'est que tout le reste du projet pourra se faire via bluetooth : il n'y aura aucun changement ou imprévu suplémentaire à la fin.

J'ai donc réalisé un petit motage simple pour faire fonctionner 1 Servo-moteur à l'aide d'une commande bluetooth :

<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/5f86f527-37db-47b2-809b-4408b06c61ba"/>


