# Net_practice
# Net_practice

## En ce project vous découvrirez le NETWORKING(réseautage).

## **Qu'est-ce qu'une adresse IP ?**

Une adresse IP est une représentation numérique de l'endroit où un appareil est connecté à Internet.

## **Les différentes parties du adresse IP?**

Une adresse IP se compose de deux parties : l'***ID de
 réseau***, composé des trois premiers chiffres de l'adresse, et un ***ID d'hôte***, le quatrième chiffre de l'adresse.
 par exemple **(192.168.1.1)**, les chiffres *192.168.1* correspondent à **l'ID du réseau** et les derniers **.1, .2, .3**, et ainsi de suite désignent **l'ID de l'hôte**.


**L'ID**: de réseau est exactement ce que son nom indique : l'identité du réseau sur lequel l'appareil est connecté. 

**L'ID d'hôte**: fait référence à l'appareil spécifique sur ce réseau. (Habituellement, votre routeur est le .1, et chaque appareil suivant se voit attribuer les numéros .2, .3, etc.).


## Adresses IP locales et adresses IP publiques

Il existe deux types d'adresses IP : les adresses IP externes, ou publiques, et les adresses IP internes, également appelées adresses locales ou privées. Votre fournisseur de services Internet (FAI) (l'entreprise à qui vous payez votre accès en ligne) vous donne l'adresse externe. Lorsque vous naviguez sur le Web, le site récepteur doit savoir qui s'y connecte (pour des raisons de surveillance du trafic), et votre adresse IP externe est la façon dont votre FAI vous présente sur le site.

## TCP/IP

Le protocole TCP/IP (Transmission Control Protocol/Internet Protocol) est un ensemble de règles et de procédures permettant de connecter des appareils via Internet.
TCP définit la façon dont les applications communiquent sur le réseau. Il gère la façon dont un message est divisé en une suite de petits paquets, qui sont ensuite transmis sur Internet, puis réassemblés dans le bon ordre à l'adresse de destination.

La partie IP du protocole définit comment adresser et diriger chaque paquet pour s'assurer qu'il atteint la bonne destination. Chaque ordinateur passerelle du réseau vérifie cette adresse IP pour déterminer où transmettre le message.


## IPv4

**la différence entre IPV4 et IPV6?**

Le protocole Internet version 4, généralement appelé IPv4, a été développé au début des années 1980. Une adresse IPv4 comprend quatre chiffres, chacun compris entre 0 et 255.

Le protocole Internet version 6, ou IPv6, a été présenté pour la première fois à la fin des années 1990, en remplacement d'IPv4. Les constructeurs d'Internet s'étaient rendu compte des limites d'IPv4 et des risques de pénurie.
IPv6 utilise des adresses de 128 bits, ce qui, en théorie, donne 340,282,366,920,938,463,463,374,607,431,768,211,456 ou 340 undécillions d'adresses. Les adresses IPv6 se composent de huit groupes de quatre chiffres hexadécimaux.

## Switch

un switch est un boîtier doté de quatre à plusieurs centaines de ports Ethernet, et qui sert à relier en réseau différents éléments du système informatique. Il permet notamment de créer différents circuits au sein d’un même réseau, de recevoir des informations et d’envoyer des données vers un destinataire précis en les transportant via le port adéquat. Le switch présente plusieurs avantages dans la gestion de votre parc informatique. Il contribue à la sécurité du réseau et à la protection des données échangées via le réseau. D’autre part, il permet de connecter davantage de postes de travail sur le même réseau Ethernet. Le switch permet avant tout de répartir l’information de manière « intelligente » au sein de l’entreprise. Il contrôle et sécurise au maximum votre réseau pour vous éviter les intrusions. Une fois paramètré par un technicien informatique, le switch distribue l’information seulement aux utilisateurs prédéfinis en fonction de la typologie de collaborateurs

## Routeur

Un routeur est un dispositif qui relie deux ou plusieurs réseaux ou sous-réseaux à commutation de paquets. Il remplit deux fonctions principales : gérer le trafic entre ces réseaux en transférant les paquets de données vers les adresses IP auxquelles ils sont destinés, et permettre à plusieurs appareils d'utiliser la même connexion Internet.

## Table de routage

Une table de routage est un ensemble de règles, représentées sous forme de tableau, qui permet de déterminer où seront acheminés les paquets de données circulant sur un réseau IP. Tous les dispositifs IP, y compris les routeurs et les commutateurs, utilisent des tables de routage.
Une table de routage contient les informations requises pour transférer un paquet via le meilleur chemin vers sa destination.

Chaque paquet contient des informations indiquant son origine et sa destination. A réception d'un paquet, le dispositif relié au réseau l'examine et recherche dans la table de routage la meilleure route à lui faire emprunter. La table indique alors au dispositif comment acheminer le paquet vers le prochain saut du parcours sur le réseau.

Une table de routage élémentaire comprend les informations suivantes :

-Destination : adresse IP de la destination finale du paquet
-Saut suivant : adresse IP vers laquelle le paquet est transmis
-Interface : interface réseau de sortie que le dispositif doit utiliser pour envoyer le paquet vers le saut suivant ou vers la destination finale
-Indicateur : coût attribué à chaque route disponible afin que le chemin le plus efficace soit sélectionné
-Routes : comprend les sous-réseaux directement connectés, les sous-réseaux indirects, qui ne sont pas connectés au dispositif, mais sont accessibles via un ou plusieurs sauts, et les routes par défaut à emprunter pour certains types de trafics ou en l'absence d'information.

Les tables de routage peuvent être gérées manuellement ou dynamiquement.

## All solution levels(in file solution).
