# Fanuc CRx

## Liens vers les règles de sécurité et de rangement
 - [Règles de sécurité](../../secu/securite.md)
 - [Règles de rangement](../../secu/rangement.md)

## Poste de travail
<img class="img-no-border" src="../../../images/crx.jpg" alt="Photo de la cellule robotisée Fanuc CRx">

## Travail à effectuer
Chaque étape doit être validée par un enseignant avant de passer à la suivante.

### Prise en main du robot
 - Démarrer et éteindre le robot
 - Changer de repère (joint/world/tool/user)
 - Changer de charge utile
 - Modifier la vitesse du robot
 - Déplacer le robot grâce au teach
 - Déplacer le robot à la main
 - (optionnel) Sauvegarder les données sur un support externe

### Création des repères et de la charge utile
 - Créer un repère outil avec la méthode des 3 points
 - Créer un repère outil par entrée directe
 - Créer un repère utilisateur avec la méthode des 3 points
 - Créer une nouvelle charge utile

### Utilisation du robot
 - Utiliser les entrées/sorties (ouverture/fermeture de la pince, mise en marche/arrêt du convoyeur, récupération des données capteur)
 - Accéder à : la liste des programmes, la page d'édition des programmes et la liste des variables
 - Executer un programme en mode manuel
 - Executer un programme en mode pas à pas

### Création de programme

⚠ Les repères et les charges utiles devront être déclarés dans tous les programmes de mouvement.

 - Créer différents programmes séquentiels permettant de :
    - Prendre une pièce dans une position donnée sur la première palette  (utiliser les registres et registres de position) et la déposer sur le départ du convoyeur
    - Prendre une pièce sur l'arrivée du convoyeur et la palettiser dans une position donnée (utiliser les registres et registres de position)
    - Prendre une pièce palletisée dans une position donnée et la replacer sur la première palette dans une position donnée (utiliser les registres et registres de position)

 - Créer un programme principal permettant d'effectuer la palletisation et la dépalletisation en boucle
