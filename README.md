The Hacking Pinterest

Ce projet contient une base de données avec des users, des comments et des pins. Les utilisateurs peuvent créer des "pins", chaque pin contient une URL d'une image sur le net. Les utilisateurs peuvent commenter les pins, mais ne peuvent pas commenter les commentaires.

Pour lancer ce magnifique projet vous devez d'abord faire :

    bundle install

ensuite:

    rails db:migrate

Puis :

    rails db:seed

Enfin pour pourrez lancer la console et voir les commentaires, pins ou utilisateurs.

Il y a 3 tables, comments, pins et users.

Pour les display, vous pouvez taper dans la console (rails c):

    User.all
    Pin.all
    Link.all

