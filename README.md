# TP-programmation-embarquee

Réflexion :
Notre nom d’hôte est « C106-IH-Pc » et notre nom d’utilisateur est « pabloilan ». Il est important de noter ces informations, car elles sont nécessaires lors du lancement du Raspberry Pi. En effet, la connexion au système d’exploitation du Raspberry Pi exige une authentification à l’aide d’un identifiant et d’un mot de passe.


1) TX est la broche qui permet de transmettre les données et RX permet de les recevoir. Les relier ainsi permet le bon échange des données dans les deux sens.

2) Le GND permet d’avoir une masse commune entre la Raspberry et l’adaptateur. Sans le GND, la communication n’est pas possible.

3) 115 200 représente la vitesse de transmission en bauds. 8 bits pour la taille de la donnée, N pour l’absence de parité (No parity) et 1 pour le nombre de bits d’arrêt.

4) La Raspberry Pi fonctionne à 3,3 V, elle ne tolère donc pas une tension de 5 V. Cela pourrait griller la carte.

5) Si la vitesse est différente, les bits sont lus au mauvais rythme et ne peuvent pas être décodés correctement. La communication échoue et le terminal affiche des caractères incompréhensibles.

6)


Réflexion : La connexion UART utilise un adaptateur USB-Série branché directement sur les broches de la carte, avec le port série activé et un terminal réglé sur la bonne vitesse. Son grand avantage est de fonctionner sans réseau dès le démarrage, mais sa limite reste la nécessité d'un câble et d'une proximité physique.

La connexion SSH passe par le réseau via Wi-Fi ou Ethernet, et demande simplement que le service SSH soit activé et que l'adresse IP soit connue. Elle permet de tout contrôler à distance, mais devient inutilisable si le réseau échoue ou si le système ne démarre pas.  


Réflexion : 

- L'adresse IP obtenue : 10.10.3.227
- Oui nous avons bien pu nous connecté a internet. 
- Sur le PC de la salle, n'étant pas administrateurs, nous ne possédons pas les droits "sudo" (les privilèges suprêmes). En revanche, comme nous avons flashé la carte SD avec un système d'exploitation dont nous sommes les seuls administrateurs, nous connaissons le mot de passe. Nous pouvons donc y exécuter la commande "sudo" grâce au mot de passe configuré lors du flashage.


