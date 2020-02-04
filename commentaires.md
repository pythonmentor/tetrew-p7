# Commentaires généraux

- Eviter de nommer un package classes. Dans un projet comme celui-là, pratiquement tout est classe. Nommer les packages et les modules avec des noms descriptifs.
- Ajouter un Pipfile ou requirements.txt dès le début du projet. Il est difficile de deviner quelles sont les dépendances que tu utilises dans ton projet.
- A priori, éviter dans ce projet d'utiliser un wrapper python pour accéder aux APIs. Utiliser la bibliothèque requests ou un autre client http pour accéder aux APIs REST de google maps et de wikipedia.
- De manière générale, ajouter des docstrings au niveau des modules, des classes, des méthodes, des fonctions. Lors d'une approche en TDD, ces docstrings sont rédigées avant l'écriture des tests, soit avant l'écriture du code.
- Attention, le nom du package grandPy n'est pas conforme à la PEP8.
- Ne pas définir le gestionnaire d'événement du formulaire avec onsubmit dans la balise form. Utiliser addEventListener dans ton code javascript.
- A mon avis, les messages de grandpy devraient venir du serveur, pas être codés en dur côté front-end.