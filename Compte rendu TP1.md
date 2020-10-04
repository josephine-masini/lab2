# Compte rendu TP1 - Lab2

Partie I : Configuration de Git

1. On installe les git packages en tapant la commande : sudo apt install git gitk git-email, on tape  yes puis entrer pour confirmer la commande.
2. Pour la configurer à notre nom on tape : git config --global user.name "Josephine" et git config --global user.email josephinemasini@gmail.com
Ensuite on utilise la flèche du haut pour avoir ces lignes et on supprime les infos de manière à n'avoir que : git config --global user.name, on voit bien s'affciher 
le nom enregistré : Josephine, idem avec le mail git config --global user.email

Partie II : Manipulation de fichiers

1. On crée dans home/student qui est le répertoire local où on se situe un nouveau répertoire : mkdir lab2 et on va dedans en tapant : cd lab2
2. On met : touch masini.txt et echo "hello M2 syscom" >> masini.txt, pour insérer du texte dedans, pour vérifier que le texte est dedans on tape : cat masini.txt, ce qui nous affiche le contenu
3. On se place dans lab2 : cd lab2 et on fait : git init pour signaler à lab2 que ce sera un git repository.
4. git status nous indique : No commits yet => il n'y a rien dans le dossier pour l'instant



