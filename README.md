# VlcMaster
Telecommande de pilotage de VLC pour HD HOMERUN 

📺 VLC Master - Contrôleur IPTV Intelligent

VLC Master est une interface de contrôle déportée pour VLC, conçue pour piloter un flux IPTV (comme une passerelle HD HOMERUN lineup.m3u) avec une gestion de fenêtres adaptative (Normal, Moyen, Nano, Géant).

✨ Caractéristiques

🎛️ 4 Modes d'Affichage : Basculez instantanément entre une vue complète et un mode "Nano" ultra-discret pour garder vos commandes toujours au-dessus des autres fenêtres.


🔗 Contrôle VLC à distance : Utilise l'interface HTTP de VLC pour gérer la lecture, le plein écran, la pause et le volume.


📡 28 Chaînes Pré-configurées : Accès direct aux chaînes avec possibilité de les renommer via un clic droit.


🔊 Gestion intelligente du Volume : Inclut une fonction Mute qui mémorise votre niveau sonore précédent pour un retour au confort immédiat.


💾 Sauvegarde Automatique : Vos paramètres (chemin VLC, URL du flux, noms des chaînes) sont automatiquement sauvegardés dans un fichier vlc_config.json.


🔝 Toujours au premier plan : L'application reste visible au-dessus de vos autres travaux (Topmost).

🚀 Installation
Prérequis :

Python 3.x installé.

VLC Media Player installé sur votre PC.

Configuration de VLC :

Allez dans Outils > Préférences > Tous (en bas à gauche).

Interface > Interfaces principales > Cochez Web.


Interface > Interfaces principales > Lua > Entrez un mot de passe (par défaut dans le script : pass).


Lancement :

Bash
python Vlcmaster.pyw

🛠️ Utilisation

Bouton 🚀 LANCER : Ouvre VLC avec votre flux réseau.


Bouton + (Jaune) : Change cycliquement la taille de l'interface.


Clic Gauche sur une chaîne : Change de chaîne immédiatement.


Clic Droit sur une chaîne : Renomme la chaîne pour personnaliser votre grille.


Touches Fléchées : Utilisez Gauche / Droite sur votre clavier pour zapper.

📂 Structure des fichiers

Vlcmaster.pyw : Le script principal (l'extension .pyw permet un lancement sans console Windows).


vlc_config.json : Fichier de configuration généré automatiquement pour vos réglages.


👨‍💻 Note technique
L'application utilise la bibliothèque standard tkinter pour l'interface graphique et urllib pour communiquer avec l'API HTTP de VLC, garantissant une légèreté maximale sans dépendances lourdes.
By Popov et Gemini ©2026
