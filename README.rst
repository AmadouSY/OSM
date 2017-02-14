Utilisation 

make clean : Nettoie les .o
make : Lance la compilation
./cproj : Lance un fichier par défaut
./cproj fileOsm.osm : Lance un fichier osm

[Installation de Libxml2]
Vérifier que l'installation de python est effective.
Taper : Python3 --version
Si il demande l'installation alors Installer sinon passer à l'installation de libxml2
sudo apt-get install libxml2-dev
sudo apt-get install libxml2-utils

[Installation de SDL]
Taper : sudo apt-get install libsdl1.2-dev

Puis installer les paquets suivant 
libsdl-image1.2,
libsdl-image1.2-dev,
libsdl-ttf2.0-0,
libsdl-ttf2.0-dev,
libsdl-mixer1.2,
libsdl-mixer1.2-dev
libsdl-gfx1.2-dev

A l'aide de la commande:

sudo apt-get install libsdl-image1.2 libsdl-image1.2-dev libsdl-ttf2.0-0 libsdl-ttf2.0-dev libsdl-mixer1.2 libsdl-mixer1.2-dev libsdl-gfx1.2-dev libsdl1.2-dev
