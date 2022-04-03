# My_Project
Le but du projet est de pouvoir mettre en place un dispositif permettant d’analyser un packet. L’analyse mettra en évidence la compréhension de l’encapsulation des données et de l’utilisation des bibliothèques adéquates pour le faire. Il sera aussi mis en évidence une maitrise assez minimaliste de la programmation shell.

#Environnement technique :
Pour le choix de l'environnement technique on a utilisé  le modéle Ubuntu 20.04 pour les  deux machines clientes et  le kali Linux pour  le man in the  middle tout en prenant en compte les installations prérequises pour le bon fonctionnement du projet tels:
  -Pour la machine serveur :
   - Mise en place d’une base de données MYSQL
- Mise en place d’un analyseur de communication
- Mise en place du service DNS et du service DHCP       
 -Pour la machine  cliente  :
  Installer python   
- Installer des dépendances pour python
- Pour la machine  kali linux 
   -Installation de toutes les dépendances
- Installation de wireshark

En outre l'installation des machines virtuelles ont été effectués sur VMware  Workstation qui a l'image  du virtuelBox  permet  la mise en  place de  machines virtuelles dans  un meme  réseau  local. 
On a choisie VMnet 3 avec le  réseau  : 192.168.10.0  pour toutes les trois machines


 #Lancement des  scripts :
En ce qui concerne les scrit.sh leur lancement se fait comme suit : 
 -./script.sh   
Pour les  script.py leur lancement se fait comme suit :
-  python3 script.py

# Fonctionnement des scripts :
 #client.py
 
 
 -interagit avec le serveur pour inscrire les identifiants d'un clients dans la base de donnée
-interagit avec le serveur pour se connecter
-permet d'initialiser une connexion avec un serveur et d'interagir avec celui ci afin d'avoir la possibilité de s'inscrire,
#de se connecter ou de terminer la connexion


#server.py
 -permet au serveur de recupérer les informations d'inscription d'un client
-permet au serveur de recupérer les informations de connexion d'un client
-permet au serveur d'initialiser une connexion en attente d'un client et d'interagir avec celui ci


#database.py
-permet de vérifier le mail de s'inscrire dans la base et de se connecter à celle-ci
