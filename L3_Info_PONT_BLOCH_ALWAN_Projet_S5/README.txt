- Si vous n'avez ni Java et/ou ni Wamp (ou Lamp) vous devez avoir une connexion internet afin de t�l�charger les diff�rents installateurs.

- Si ce n'est pas d�j� fait t�l�chargez Java � cette adresse:
https://java.com/fr/

- Installez le.

- Si ce n'est pas d�j� fait t�l�chargez
Wamp (pour Windows) � cette adresse:
https://sourceforge.net/projects/wampserver/files/
(pour Wamp vour aurez besoin (si non install�) de
Redistribuable Visual C++ pour Visual Studio� 2015:
https://www.microsoft.com/fr-FR/download/details.aspx?id=48145 
et Redistribuable Visual C++ pour Visual Studio� 2013:
https://www.microsoft.com/fr-FR/download/details.aspx?id=40784 
Si vous �tes sur Windows 10 vous devrez d�sactiver IIS pour executer correctement Wamp:
https://openclassrooms.com/forum/sujet/probleme-wampserver-windows-10#message-89111670 )
Installez le (lancer l'installateur avec les droits d'administrateurs).

ou Lamp (pour Linux):
https://doc.ubuntu-fr.org/lamp
https://doc.ubuntu-fr.org/phpmyadmin

Pour Wamp (Windows):

- Copier le fichier "adminer.php" � la racine du dossier de Wamp, par d�faut "C:\wamp64".

- Executer Wampserver (wampmanager.exe)

- Si ce n'est pas d�j� fait lancez votre navigateur de recherche.Puis tapez "localhost" dans la barre de recherche de site.

- Dans la partie "Vos alias" cliquez sur "phpmyadmin"

- Mettez "root" dans le champ "Utilisateur" et laissez le champ "Mot de passe" vide. Le champ �Choix du serveur� doit �tre sur �MySQL�. Connectez-vous.

- Cliquez sur "Bases de donn�es" dans la barre du haut.

- Dans la partie "Cr�er une base de donn�es" rentrez un nom de base de donn�es (par d�faut "ProjetS5bdd") et cliquez sur "cr�er".

- Tapez "localhost" dans la barre de recherche de site.

- Dans la partie "Vos alias" cliquez sur "adminer".

- Mettez "root" dans le champ "Utilisateur" et laissez le champ "Mot de passe" vide. Dans le champ �Base de donn�es� mettez le nom de la base de donn�es que vous avez cr��e � partir de phpmyadmin. Connectez-vous.

- Cliquez sur �Requ�te SQL� dans les menus � gauche. Copiez le contenu du fichier BDD_Create.sql (ou importez le fichier avec le menu �Importer�). La base de donn�es est cr��e et est vide.

- Si vous avez pris un nom de base de donn�es autre que "ProjetS5bdd" vous devez changez le nom dans le fichier "serveur_config.txt" � la ligne 2.

(vous pouvez aussi cr�er et modifier les tables � partir de phpmyadmin)


Pour les utilisateurs Linux vous pouvez aussi utiliser adminer:
http://www.ubuntuboss.com/how-to-install-adminer-on-ubuntu/
Sinon vous pouvez aussi utiliser phpmyadmin pour cr�er et modifier les tables. Vous pouvez executer une requete SQL comme le contenu de l'un des fichiers sql fourni avec le projet comme "BDD_Create.sql".