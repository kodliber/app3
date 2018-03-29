# app3
Ce projet est un test d'utilisation de Git avec Android Studio.

Conseil :
comme il n'est pas facile de determiner les fichiers a inclure dans le commit initial de Git,
voici ce que je propose :

* definir un repository avec Github Desktop
* au moment de creer le repository, utiliser le modele de .gitignore  "Android". C'est la l'astuce.
* avec Android Studio, creer un nouveau projet : __ce projet doit se etre enregistre dans le meme dossier que le dossier defini pour le repository__.

Exemple :
Je cree un repository sur d:\repo\app1
Avec Android Studio, je donne un nom un projet app1 et le dossier de creation sera d:\repo
Android Studio va donc creer l'ensemble des fichiers necessaires, qui seront detectes par Github Desktop et inclus d'office pour le premier commit.

On fera ensuite un premier push vers Github ou tout autre remote repository.

Une fois le push realise, le projet devient disponible pour etre clone.

Avec Android Studio sur une autre machine, on fera un import d'un projet : commande __New__, __import project__.