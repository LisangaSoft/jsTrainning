# jsTrainning
A repository for where member can push their code

# Etapes pour la prise en main

Bonjour les amis

Ce fichier text vous explique comment proceder pour envoyer votre travail dans le repertoire

Pour commnecer, j'ai creer une organisation LisangaSoft qui contient un repertoire appele jsTrainning
Le repertoire a son tour contient un fichier README.md et un dossier intitule travail1.

Comment proceder pour envoye son travail dans le repertoire?

# Installer git en local

Pour commencer a envoyer (push) et recevoir (pull) le code dans (a partir de ) ce repertoire, il faut installer un client git
voici la procedure : 

1. Aller dans le dossier de la formation Js-Trainning et installer le logiciel Git-2.8.2-64-bit
   Le fichier sera trouve dans la location : Js-Trainning/ressources/tools/Git-2.8.2-64-bit
   Double-cliquer pour lancer l'installation

2. Durant l'installation il y a plusieures etapes qui sont tous simples (donc un Next suffit), quand vous arrivez a l'etape 
   Adjusting your PATH environnement, choisissez la premiere option intitule Use Git from Git Bash only
   (la premiere option ou le premier choix) puis continuer l'installation normalement avec le button Next

3. Une fois votre installation terminee, aller dans le menu demarrer et cliquer sur tous les programmes,
   ensuite cliquer sur le dossier Git puis cliquer sur Git CMD (l'invite de commande de git) et vous aurez
   un ecran noir sur lequel lancer des commandes.

4. Voici les deux commandes importants que vous devez taper avant de commancer a utiliser votre client git
   
   * git config --global user.name "votre_user_name_git"
   * git config --global user.email "votre_adresse_email"

   ex : git config --global user.name "pierre"
        git config --global user.email "pieree@gmail.com"
NB : Les commandes sont a saisir sur l'invite de commande git, taper sur ENTER apres chaque commande

# Accepter l'invitation

1. Votre client git est installer puis configurer alors aller dans le site https://github.com pour vous connecter et 
   accepter l'invitation que je vous ai envoye, deux facons pour accepter l'invitation

   * Consulter votre boite email et accepter l'invitation (github vous a envoye un email)
   * Aller sur le lien https://github.com/LisangaSoft pour accepter votre invitation

# Faire le Forsk du Repertoire  

1. Vous avez accepter l'invitation et etes membre du LisangaSoft maintenant vous devez faire un fork du repertoire jsTrainning qui se trouve dans l'organisation
   * Aller sur le lien https://github.com/LisangaSoft et cliquer sur le repertoire jsTrainning
   * Regarder en haut du cote droit vous verez trois boutons parmis lequels vous trouverez un bouton fork
   * Cliquer ce bouton
   * Github va vous demander ou voulez vous que le fork soit fait, choisissez votre propre compte en cliquant sur votre compte sur la boite de dialogue
   * Alors github va creer ce repositoire dans votre propre compte


# Cloner le Repertoire Fork et Commencer votre travail

1. Vous avez le repertoire avec vous, aller dans votre invite de commande et taper les commandes suivants (appuyer sur ENTER apres chaque commande): 

   * cd (Cette commade vous amende dans votre dossier personnel)
   * cd Documents 
   * git clone https://github.com/votre_user_name_github/jsTrainning.git (ex : git clone https://github.com/pierre/jsTrainning.git) pour cette commande vous devez avoir une connexion internet

2. Constater qu'un dossier jsTrainning est cree sur votre repertoire personnel, alors faite ceci :
   
   * Lancer le terminal et taper les commandes suivants (ENTER a la fin de chaque commade) : 
        * cd
        * cd Documents/jsTrainning/
        * git checkout -b travail1 (creation d'une branche pour le travail)
        * copier le fichier angular.min.js dans le dossier librairies (le dossier se trouve au meme niveau que le dossier travail1)

3. Aller ensuite dans le dossier travail1 et creer un dossier avec votre prenom

4. Faites votre travaille a l'interieur de ce dossier, une fois le travail termine taper les commandes suivants : 

    * git add .
    * git commit -am "ma proposition pour le travail numero 1"
    * git push origin travail1

# Notifier moi

1. Ecrivez moi sur whatsapp ou gmail (kitamula@gmail.com) pour me signaler que votre travail est fini

Soyez libre de me demander ce que chacun de ces commandes signifie (leurs importances)
   
   