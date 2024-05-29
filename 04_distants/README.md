# Devoir 4 : Historique et dépôts distants

Veuillez suivre les étapes ci-dessous. Lorsque vous aurez terminé,
poussez vos changements vers le dépôt distant « origin ».

1.  Créez une nouvelle branche appelée « devoir4 ».
2.  Ajoutez un fichier texte nommé « historique ». À l'intérieur de
    celui-ci, expliquez brièvement les effets de la commande `merge` sur
    l'historique d'un dépôt. Validez ensuite vos changements avec un
    *commit*.
3.  Dans le même fichier, ajoutez une brève description des effets de la
    commande `merge` sur l'historique d'un dépôt. Validez ensuite vos
    changements.
4.  Ajoutez un autre fichier nommé « distants ». À l'intérieur de
    celui-ci, expliquez brièvement ce qu'est un dépôt distant, ainsi que
    les commandes utilisées pour interagir avec ceux-ci. Validez ensuite
    vos changements.
5.  Réécrivez l'historique de votre branche de sorte à ce que les
    *commits* des étapes 2 et 3 soient un seul *commit* (cette opération
    est parfois appelée *squash*).
6.  À l'intérieur du fichier « historique », ajoutez deux adresses URL :
    une première vers la documentation officielle de Git sur la commande
    `merge`, et une seconde vers la documentation concernant la commande
    `rebase`. Si votre description de ces deux commandes entre en
    conflit avec la documentation, veuillez corriger votre description.
7.  Faites un *commit* de type *fixup* qui pointe vers le *commit* des
    étapes 2 et 3.
8.  Réécrivez l'historique de votre branche de sorte à ce que le
    *commit* précédent soit désormais intégré dans le *commit* de
    l'étape 3. Autrement dit, le *commit* précédent ne devrait plus
    apparaître dans votre historique.
9.  Corrigez le message de validation du *commit* des étapes 2 et 3 afin
    que son *corps* explique les changements effectués à la description
    des commandes. Si aucun changement n'a été fait, écrivez « Je suis
    vraiment bon·ne ».
10. À l'aide de la commande `git init --bare`, créez un dépôt distant
    ailleurs sur votre ordinateur. Ajoutez la référence à ce dépôt
    distant dans votre dépôt « devoirs ». Le nom de la référence doit
    être « serveur ». L'adresse URL correspondra au chemin du répertoire
    dans lequel se trouve le dépôt distant.
11. Clonez ce dépôt distant ailleurs sur votre ordinateur, dans un
    répertoire nommé « collègue ». Attention de ne pas créer de
    répertoire superflu ; le dépôt devrait être à la racine du
    répertoire « collègue ».
12. À partir de votre dépôt « devoirs », poussez les *commits* de votre
    branche « devoir4 » vers une branche nommée « main » sur le dépôt
    distant « serveur ».
13. À partir du dépôt « collègue », récupérez les changements qui sont
    maintenant sur la branche « main » du dépôt distant « serveur ».
14. Toujours à partir du dépôt « collègue », ajoutez dans le fichier
    nommé « distant » la description officielle de la commande `git
    remote`. Validez votre changement, et poussez votre commit vers le
    dépôt distant « serveur ».
15. À partir du dépôt « devoirs », récupérez les nouveaux changements
    qui sont maintenant sur la branche « main » du dépôt distant 
    « serveur ».

Fin. N'oubliez pas de poussez les changements faits sur la branche 
« devoir4 » vers le dépôt distant « origin ».
