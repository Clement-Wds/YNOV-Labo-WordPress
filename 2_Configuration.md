# Configuration de WordPress

## Extraction de l'archive
Copiez l'archive wordpress-6.3.x et coller là dans votre répertoire web de votre serveur local :
- Pour Wamp : `C:/wamp64/wwww`
- Pour Mamp : `/Applications/MAMP/htdocs`
- Pour Lamp : `/var/www/html`

Extraire l'archive, vous pouvez ensuite renommer le nom du répertoire wordpress par le nom de votre choix. ATTENTION, ne pas mettre de caractères spéciaux, accents ou espaces.

## Configuration de la base de données
Lancer PHPMyAdmin depuis Wamp, Mamp, Lamp puis créer une base de donnée avec les paramètres suivants : 

<img width="342" alt="image" src="https://github.com/Clement-Wds/YNOV-Labo-WordPress/assets/71884576/0ba09adf-2179-4dc6-891e-a85150cf5726">

Ouvrez ensuite le répertoire de votre site wordpress avec un éditeur de code.
Renommer le fichier "wp-config-sample.php" en "wp-config.php". Ouvrez-le et entrez les informations de base de données :

<img width="491" alt="image" src="https://github.com/Clement-Wds/YNOV-Labo-WordPress/assets/71884576/14f8f106-c6a9-47ea-b06b-96d083d5f9b7">

Pour le moment on ne touche pas aux autres paramètres. Sauvegardez bien votre fichier.

## Configuration du site
Ouvrez votre navigateur et accéder à l'URL suivant : http://localhost/wordpress/ (a la place de wordpress entrez le nom de votre répertoire de site).
- Sélectionner la langue :

<img width="336" alt="image" src="https://github.com/Clement-Wds/YNOV-Labo-WordPress/assets/71884576/88158ea3-8155-45c6-b135-182c22607c91">

- Entrer les informations de votre site et créer le compte admin puis cliquer sur "Installer WordPress" :

<img width="572" alt="image" src="https://github.com/Clement-Wds/YNOV-Labo-WordPress/assets/71884576/b5659b9c-a1d6-4704-8026-df7142d56914">

- Se connecter avec votre compte admin et ensuite vous devriez tomber sur votre tableau de bord WordPress :

<img width="1252" alt="image" src="https://github.com/Clement-Wds/YNOV-Labo-WordPress/assets/71884576/c8682eb2-051e-4b3c-bd05-d3b64f3ebeb7">

Et voilà votre site WordPress est installé et configuré, vous pouvez commencer à le créer !
