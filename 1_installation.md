# Installation de WordPress

## Environnement de développement

> Afin de pouvoir développer en toute sénérité, vous allez avoir besoin d'un environnement de développement fonctionnel comprenant PHP et MySQL. Voici les configurations que je vous recommande en fonction de votre système d'exploitation :

### Windows :
Télécharger et installer WampServer depuis ce lien : https://www.wampserver.com/
- ATTENTION : lors de l'installation, veuillez à utiliser les plus récentes de PHP (8.2.0 recommandée) et MySQL (8.0.31)

### MacOS :
Télécharger et installer Mamp depuis ce lien : https://www.mamp.info/en/downloads/
- ATTENTION : lors de l'installation, veuillez à utiliser les plus récentes de PHP (8.2.0 recommandée) et MySQL (8.0.31)

### Linux :
Télécharger et installer Lamp avec la commande suivante : `sudo apt install apache2 php libapache2-mod-php mysql-server php-mysql`
Si vous souhaitez installer les modules de développement supplémentaires vous pouvez utiliser la commande suivante : `sudo apt install php-curl php-gd php-intl php-json php-mbstring php-xml php-zip`
Documentation disponible sur : https://doc.ubuntu-fr.org/lamp

## Installation de WordPress :
- Télécharger l'archive de WordPress la plus récente sur : https://wordpress.org/download/
- Déplacer puis extraire l'archive dans le répertoire www de Wamp / Mamp ou Lamp en fonction de votre système d'exploitation
- Assurez-vous que les fichiers sont bien dans le répertoire racine /www/wordpress
- Vous pouvez renommer le répertoire wordpress par le nom de votre choix

Et voilà votre environnement de développement est prêt et WordPress installé sur votre machine. Prochaine étape, la configuration de WordPress !
