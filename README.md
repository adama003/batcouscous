# batcouscous
Cisse adama Susanna lapiccirella
![WhatsApp Image 2023-04-16 at 19 36 24 (1)](https://github.com/adama003/Batcouscous1/assets/128383731/92e82cb6-8140-44cb-a613-c749e352f5ab)
![WhatsApp Image 2023-04-16 at 19 36 24](https://github.com/adama003/Batcouscous1/assets/128383731/eee9e863-df80-4a08-b6db-bee154be51bb)
Batcouscous

Projet :
Comme projet on a décidé de faire une voiture capable de suivre une ligne sans être télécommandée par aucune application ou autre, elle a besoin juste d’un code qu’on téléverse sur notre cadre C.

Matériels :
On a utilisé CHEROKEY 4WD ROBOT KIT ; HUSKYLENS pour créer la voiture et pour la faire fonctionner sans fils on s’est servi du Code HuskyLens. 

Planning :
Tout d’abord on a dû mettre à jour la caméra, puis on l’a mise sur son support placé sur la voiture.
Dans un deuxième temps on a câblé les différents fils sur le cadre C et la voiture et donc aussi la batterie, une fois cela terminé on a fait des tests de fonctionnement de la voiture pour effectivement voir si elle marchait.
Pour fin terminer avec la création du code et donc son fonctionnement Wireless.

Problématiques :
Quand j’ai essayé pour la première fois de la faire marcher avec le code ça ne fonctionnait pas donc j’ai dû revoir tout le code pour comprendre que les réglages de la caméra devaient être réglés sur I2C pour être connecté au cadre C alors j’ai dû aller dans les réglages généraux celle-ci pour définir ce réglage.
Une fois fait ça j’ai re téléversé le code et je lui aie fait suivre une ligne qui avait un virage à droite et quand la caméra reconnaissait ce virage au lieu de tourner à droite elle tournait à gauche, donc les pins des directions du software étaient inversés. Une fois résolu ce problème j’ai à nouveau téléversé le code correct et cette fois tout allé bien, mais la vitesse de la voiture était trop grande donc elle n’arrivait pas à faire des virages un peu plus serrés par conséquent j’ai baissé la vitesse de 255 à 80 de ZUMO-FAST la variable pour régler la vitesse. 
