# DOCUMENTATION LINUX
## LES COMMANDES USUELLES
  1) ### cd (change directory)

     permet de changer de repertoire. il a plusieurs sous options:
     
     cd .. (répertoire parent)
     
     cd ~ (répertoire de base)
     
     cd - (répertoire précedent)
     
     cd / (répertoire racine)
  2) ### pwd (print working directory )

       permet d'afficher le chemin d'accès vers le répertoire où se situe ..
  3) ### ls (list)

       affiche les répertoires et les fichiers du répertoire actif
  4) ### cp (copie)
  
  5) ### mv (move)

     renomme et deplace un dossier

     mv source destination

     mv * dossier (déplace tous les fichiers du répertoire actif vers le répertoire
    bdossier)

  6) ### mkdir (make directory)      

     crée un repertoire

     *mkdir dossier

  7) ### rmdir (remove directory)

       efface un repêrtoire

       rmdir dossier (supprime un dossier vide)

   8) ### rm (remove ou efface) 

      rm -R (enlèvement récursif!!!)rm fichier

      rm -i fichier (interactivement, avec demande de confirmation)

      rm -f fichier (avec force, sans demande de confirmation)

      rm -r fichier (avec récursivité, avec les sous répertoires)

      rm -rf dossier (supprime le répertoire et tou son contenu, sans confirmation)

## LES COMMANDES D'EDITIONS

 1)  ### more ("pager" qui affiche page par page sans retour en arrière, "h" affiche l'aide contextuelle)

       more fichier

       more fichier1 fichier2

      more *.txt

 2) ### cat (concatenate avec le code de fin de fichier eof=CTRL + D)

      cat fichier-un fichier-deux > fichier-un-deux

       cat -n fichier > fichier-numéroté (crée un fichier dont les lignes son numérotés)

       cat -nb fichier (affiche sur la sortie standard les lignes numéroté, sauf les lignes vides)

  3) ### head (affiche les 10 première  lignes               d'un           fichier)

      head -n22 fichier (affiche les 22 premières lignes)

  4) ### vi (l'éditeur en mode texte universel)

   5) ### emacs (l'éditeur GNU Emacs multi fonction pour l'édition, les mails, les news,
       la programmation, la gestion des fichiers,...)

   6) ### xemacs (l'éditeur GNU Emacs sous X)

   7) ### diff (différence entre deux fichiers, utiles pour chercher les modifications)

      diff fishier1 fichier2

## LES COMMANDES D'IMPRESSION ET DE CONVERSION

   1) ### lp (la commande d'impression sur les systèmes Unix Système V)
   2) ### lpr (la commande d'impression sur les systèmes BSD et Linux)
        lpr fichier
        
        
        echo $PRINTER


   3) ### lpc status (affiche l'état de la file d'attente)
   4) ### lpq (affiche les travaux d'impression et leur numéro)


   5) ### lprm (supprime un travail d'impression avec son numéro comme argument)


   6) ### gv ("ghostview" permet de visualiser des fichiers POST SCRIPT)


      gv fichier.ps
      
   7) ### a2ps (convertit les fichiers ASCII en POST SCRIPT)
       a2ps -4 fichier -P fichier-post-script
   8) ### suite

