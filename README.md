# app3
Ce projet est un test d'utilisation de Git avec Android Studio.

Conseil :
comme il n'est pas facile de determiner les fichiers a inclure dans le commit initial de Git,
voici ce que je propose :
## Preparer le repository local
* definir un repository avec l'application __Github Desktop__
* au moment de creer le repository, utiliser le modele de .gitignore  "Android". C'est la l'astuce.
* avec Android Studio, creer un nouveau projet : __ce projet doit se etre enregistre dans le meme dossier que le dossier defini pour le repository__.

Exemple :
Je veux partager un nouveau projet Android qui s'appelera App1.

Avec GitHub Desktop je cree le repository : d:\repo\app1, sans oublier le fichier .gitignore sur le modele Android.

Ensuite avec Android Studio, je cree un nouveau projet du nom de "app1" dans le dossier "d:\repo". Android Studio va donc creer l'ensemble des fichiers necessaires, qui seront detectes par Github Desktop et ajoutes au premier commit.

On fera ensuite un premier push vers Github ou tout autre __remote repository__.

## Cloner le projet
Une fois le push realise, le projet devient disponible pour etre clone.

Avec Android Studio sur une autre machine, on fera un import d'un projet : commande __File__, __New__, __Project from version control__, avec l'option GitHub.

On indiquera ensuite l'URL du projet Github.

Enfin, malgre une alerte pour l'absence d'un fichier iml (pour IntelliJ), on devrait avoir un projet compilable et pret au controle de version avec Git.
