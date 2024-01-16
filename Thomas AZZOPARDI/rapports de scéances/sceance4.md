Durant cette scéance, j'ai pu configurer l'application qui sera développer de manière optimiser pour notre quadrupède et pu réaliser la connexion bluetooth dont nous avions besoin.
J'ai completement changé l'interface et j'ai pu tout mettre sur 1 seul écran cette fois ci.

Malheureusement j'ai rencontrer beaucoup de problème via la connexion bluetooth en elle même tel que : le non affichage des appareils "connecté" ou encore la connexion qui ne se faisait tout simplement pas.
Après quelque temps dessus, j'ai donc réussis à faire une interface fonctionnelle :
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/eb22d731-8da6-4af7-a5e2-fee1a4b8052e"/>


avec le code (par block) suivant :
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/4522cd76-95b0-4a22-9e70-47fdf14cff1a"/>

ce qui me permet donc d'afficher les commande seulement si notre téléphone est connecter a notre quadrupède lui permettant d'envoyer les "char" a,g,d,r. 
Comme test, nous avons pu assembler 1 pate completement ce qui m'a donc permis de tester si mon appli marchait bien, ce qui est le cas

L'interface sur téléphone donne donc ceci :
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/663a530f-e81c-4986-a3c9-af1971a66296"/>


Lorsqu'on se connece elle donne ceci :
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/2862fcfb-19ff-41e7-b076-ca0d96e62b99"/>



Et lorsque l'on appuie sur "commencer elle affiche les boutons comme ceci :
<img src="https://github.com/Lptj01/QUADRUPEDE/assets/153199410/8f04bd4a-55a7-4599-ac12-99f28b150f92"/>


Lors de mon test j'ai donc faire en sorte de mettre la fleche du haut pour monter la pate et droite gauche pour aller a gauche/ droite via le 2eme servo moteur.
Tout à bien fonctionner, j'ai donc pu tester tout les servo moteurs afin de vérifier leur bon fonctionnement et il n'y a seulement 1 seul qui a "disfonnctionner".

Malheureusement je trouve que la rotation de la pate s'effectue trop rapidement. Lors de la prochaine scéance j'essayerai d'attaquer la partie de la fonction "coucou" ainsi que le début concret de la marche avant.
Il faudrait aussi trouver un moyen pour que les servos moteur aillent moins "vite" (meme si les test a cette vitesse sur le vrai quadrupede n'ont pas encore été réalisé.
