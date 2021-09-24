I - Fonction du scipt

Le script install_apache.py configure un serveur Web avec apache2 et configure un site www.monsite.com
Les fichiers du site web sont hebergés sur le serveur dans le dossier pagesweb
Les étapes de la configuration du serveur permettent:

1 /  d'installaler le serveur apache2
2/   De configurer le fichier du  site à partir des informations du site fourni	    es par l'utilisateur. Cest informations de base sont: - le nom de domaine 	   et l'adresse mail de l'administrateur du site. Ce fichier est généré ainsi "001-adressedusite.conf". Il est basique mais sa modification manuelle peut perm     ettre d'améliorer le site
3/   de créer un dossier pour heberger les fichiers du site (dans /var/www/html /adressedusite
4/   de copier les fichier du site du dossier pagesweb dans le dossier du site

II - Utilisation du programme

1/ Lancement du script
python3.9 install_apache.py
1/
i = Installer et configurer Apache
d = désinstaller apache
q = Quiter
votre choix SVP 
2/ tapez une lettre qui correspond et quitter avec "q" (pas sensible à la casse)
Durant toute la procédure d'installation, l'utilisateur n'interviendra que pourrépondre par 'o' à l'invite du système.

3/Modifier le /etc/hosts manuellement 
127.0.1.1 en adressedemonsite
Si tout se passe bien, 
