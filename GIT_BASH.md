git ///

control C pour sortir d'une mauvaise commande sur terminal

github en ligne
gitbash TERMINAL sur ordi

1 -TERMINAL
ouverture de COMMANDE BASH A CONNAITRE
Ouverture de Git Bash
Vous tombez sur quelque chose qui ressemble à ceci : EDW2425@DESKTOP-KRAR4R1 MINGW64 ~ (main)
> cd Desktop pour rentrez dans votre dossier principal de travail ou tous vos dossier/fichiers sont stockés
Normalement vous avez ceci maintenant : EDW2425@DESKTOP-KRAR4R1 MINGW64 ~/Desktop (main) ((ou (master) ))

dessert ok sur git hub
on veut le mettre sur loval via terma=inalgit


Se déplacer dans le terminal

cd : Change de répertoire  (se déplacer dans un dossier) dans arborescence passer de desktop (=bureau sur Github) à dossier (ex=cours_muehl) à sous-dossier (ex=15jan)
cd ..  : Revenir au répertoire précèdent =>quand on est dans bordel, et qu'on veut aller dans cours_muehl cd :
ls : Liste les fichiers et dossiers d'un répertoire.
code . : ouvrir vscode depuis le termina
GIT dossiers:  cours_muehl +dossiers +fichiers
                bordel  etc

Création / Lecture

mkdir : Crée un nouveau répertoire.
touch : Crée un fichier vide ou met à jour la date de modification d'un fichier.
cat fichier.txt : Affiche le contenu d'un fichier.



EDW2425@DESKTOP-JCSOBVI MINGW64 ~ (master)
$ cd desktop
SI ON OUBLIE CD DESKTOP, le doss est cloné ds C:/utilisateur
((((( TOUJOURS POUR VERIF LES DOSSIERS: AFFICHAGE
EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ ls
 13_14jan/  '2024-2025 Pantin EdW Planning.pdf'  'COURS MU'/  'Nouveau dossier'/
))))))))))))))))))))

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ cd COURS\MU
bash: cd: COURSMU: No such file or directory

ON PASSE A COMMANDES A CONNAITRE GITHUB
5EX AVEC DOSS DESSERT

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ git clone https://github.com/mu93100/dessert.git
Cloning into 'dessert'...
warning: You appear to have cloned an empty repository.

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ ls
'2024-2025 Pantin EdW Planning.pdf'   bordel/        dessert/
'COURS MU'/                           coursgithub/
'Visual Studio Code.lnk'*             desktop.ini

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ cd dessert

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/dessert (main)
$ ls

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/dessert (main)
$ code .

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/dessert (main)
$ cd ..

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ ls
'2024-2025 Pantin EdW Planning.pdf'   bordel/        dessert/
'COURS MU'/                           coursgithub/
'Visual Studio Code.lnk'*             desktop.ini

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ ls
'2024-2025 Pantin EdW Planning.pdf'   bordel/     coursgithub/   dessert/
'Visual Studio Code.lnk'*             cours_mu/   desktop.ini

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ cd cours_mu

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/cours_mu (master)
$ ls
13_14jan/  html_css/

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/cours_mu (master)
$ cd html_css

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/cours_mu/html_css (master)
$ ls
'13_14jan - Copie'/   16jan/   21jan/            rodrigue/
 15jan/               20jan/  'Corection Exo'/

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/cours_mu/html_css (master)
$ cd ..

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop/cours_mu (master)
$ cd ..

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)
$ ^C

EDW2425@DESKTOP-JCSOBVI MINGW64 ~/desktop (master)

COMMANDES A CONNAITRE GITHUB
 pour GIT
 
Clone votre repo
 
git clone  url_du_dossier  ->  Copie un dépôt Git distant sur votre machine locale pour commencer à travailler sur le projet. 
 
 
3 commandes pour push son travail sur Github depuis VS code (terminal)
 
git add nom_du_fichier  (avec extension)

ls
->  ajouter un fichier au suivi git 
git add  .   ->   ajouter tous les fichiers au suivi git 
 
git commit -m "Message du commit"  ->  permet de valider les modifications que vous avez ajoutées avec git add = commentaire sur ce que tu envoies à GIT (ex: git commit -m "ajout fichier.html")
 
git push  ->  permet d'envoyer vos commits locaux vers un dépôt distant (Github en l’occurrence) 
 
(après on actualise la p. Github et on peut voir les modifs en clickant sur fichier)
avoir les modifs en vert sur Github dans "blame
 ----------------------------------------------------------------------------------

 
git status  ->  affiche l'état actuel de votre dépôt, indiquant les fichiers qui ont été modifiés, ceux qui sont prêts à être validés et ceux qui ne sont pas suivis. 



SI ON CHARGE UN PROJET DU GITHUB DE QQ4UN ON NE PEUT PAS PUSH SUR SON PROPRE REPOSITORY
>>>tu supprimes l'adresse origine du dépot : 
>git remote remove origin  //ça supprime l'adresse d'origine du repo
>git remote add origin https://github.com/TON ADRESSE DE DEPOT A TOI
>git push -u origin main


ON CREE UN DOSS ff SUR ORDI
> ds VScode terminal
git add .

git commit -m "tt"
on crée un repository sur GitHub ff
git remote add origin https://github.com/mu93100/ff.git (adresse repo ff)
git push --set-upstream origin master

ET C'EST PUSHé ds GitHub

git remote -v POUR VERIFIER SI IL Y A UNE CONNEXION AVEC UN REPO GITHUB
REPONSE TERMINAL
origin  https://github.com/mu93100/ff.git (fetch) ::: tiré de
origin  https://github.com/mu93100/ff.git (push)  ::: aller vers, pushé 

pour vérif si on est ds un repository git status
ls -la ou ls -a pour voir les fichiers cachés
ls --help === pour avoir de la doc sur comment fonctionne ls
pour quitter : on fait q
mkdir nom_du_DOSS créer un doss
touch nom_du_FICHIER nom_du_FICHIER nom_du_FICHIER ..créer un ou des fichiers à la racine
touch doss1/fichier1 : créer fichier 1 ds doss1
rm nom_du_FICHIER supp un fichier
rm -r nom_du_DOSS supp un doss

cat nom_du_FICHIER  ouvrir le contenu du fichier ds terminal

fichier .fichier

POUR QUITTER QD ON ARRIVE PLUS à ECRIRE DS TERMINAL VSCODE :
ctrl C +sieurs fois

qd on W chez soi on a avancé et on veux enregistrer l'avancement sur fichiers lepoleS : git pull

git log   pour voir les diff commits

:x ::: si on arrive à une fenetre bizarre Merge branch 'master' of https://github.com/mu93100/klikFast (VIM)
terminal est devenu git ou :q! pour quitter

Principe de responsabilité unique


SRP principe de responsabilité unique comme suit : « une classe ne doit changer que pour une seule raison » (a class should have only one reason …
DRY Don't repeat yourself



git stash pour enlever tt les modif après un commit et on ^peut les récup après
git stash list pr voir les stach précédent
git stash show
git stash --help

pwd  affiche le chemin complet du dossier dans lequel tu te trouves actuellement

envoyer repo à collaborateur (facundo)
> repo > setting (en haut à Dte) > collaborators à Gche en haut > add people (ex : poleS-dev)