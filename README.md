# TP-programmation-embarquee

1) TX est la broche qui permet de transmettre les données et RX permet de les recevoir. Les relier ainsi permet le bon échange des données dans les deux sens.

2) Le GND permet d’avoir une masse commune entre la Raspberry et l’adaptateur. Sans le GND, la communication n’est pas possible.

3) 115 200 représente la vitesse de transmission en bauds. 8 bits pour la taille de la donnée, N pour l’absence de parité (No parity) et 1 pour le nombre de bits d’arrêt.

4) La Raspberry Pi fonctionne à 3,3 V, elle ne tolère donc pas une tension de 5 V. Cela pourrait griller la carte.

5) Si la vitesse est différente, les bits sont lus au mauvais rythme et ne peuvent pas être décodés correctement. La communication échoue et le terminal affiche des caractères incompréhensibles.

6)


Réflexion : Comparez la connexion UART et la connexion SSH : quelle équipements et quelles configurations sont nécessaires dans chaque cas? Donnez un avantage et une limite de chaque modéles.




Adresse de notre Rasberry : 10.10.3.227
