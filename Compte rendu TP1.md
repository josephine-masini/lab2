# Compte rendu TP1 - Lab2

Partie I : Configuration de Git

1. On installe les git packages en tapant la commande : sudo apt install git gitk git-email, on tape  yes puis entrer pour confirmer la commande.
2. Pour la configurer à notre nom on tape : git config --global user.name "Josephine" et git config --global user.email josephinemasini@gmail.com
Ensuite on utilise la flèche du haut pour avoir ces lignes et on supprime les infos de manière à n'avoir que : git config --global user.name, on voit bien s'affciher 
le nom enregistré : Josephine, idem avec le mail git config --global user.email

Partie II : Manipulation de fichiers

1. On crée dans home/student qui est le répertoire local où on se situe un nouveau répertoire : mkdir lab2 et on va dedans en tapant : cd lab2
2. On met : touch masini.txt et echo "hello M2 syscom" >> masini.txt, pour insérer du texte dedans, pour vérifier que le texte est dedans on tape : cat masini.txt, ce qui nous affiche le contenu.
3. On se place dans lab2 : cd lab2 et on fait : git init pour signaler à lab2 que ce sera un git repository.
4. git status nous indique : No commits yet => il n'y a rien dans le dossier pour l'instant.
5. git add permet de rajouter un fichier : git add masini.txt pour ajouter mon fichier, je fais un git status, le message suivant s'affiche : new file : masini.txt no commits yet, ce qui signifie que le fichier a été crée, mais pas mis en ligne sur le git repository local.
6. Pour le mettre en ligne, on tape : git commit-m "update1", et on peut lire : 1 file changed, 1 insertion.
7. On crée un compte git hub, on exporte notre git repository local sur le compte en ligne avec : git remote add origin https://gihub.com/josephine-masini/lab2.git
et git push -u origin master, pour exporter tout le contenu du repository local à l'URL donnée.
9. Sur le github, on crée un README.md vide et on clique sur commit.
10. Avec git pull, on récupère le fichier README.md sur notre local repository.
11. On fait cd .. pour retourner dans le home, qui est home/student pour nous et on clone notre répertoire présent dans lab2 avec la commande suivante : git clone https://gihub.com/josephine-masini/lab2.git. On clique dans le dossier ou on fait un ls pour voir si lab2.git a été cloné dans home.

Pour mettre le répertoire lab2 dans notre bureau on tape : mv lab2 /home/student/Desktop, il est déplacé sur le bureau, on le voit quand on quitte le terminal ou on fait : cd home/student/Desktop/lab2, pour se placer dedans. 






