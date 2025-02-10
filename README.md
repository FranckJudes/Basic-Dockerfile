#  Bonjour, Capitaine ! - Projet Docker

##  Description
Ce projet contient un **Dockerfile** permettant de créer une image Docker ultra-légère basée sur **Alpine Linux**. Lorsque cette image est exécutée en tant que conteneur, elle affiche **"Bonjour, capitaine !"** dans la console avant de quitter.

##  Structure du projet
```
├── Dockerfile  # Fichier contenant les instructions pour construire l'image Docker
└── README.md   # Documentation du projet
```

##  Installation & Exécution
### Construire l'image Docker
Exécutez la commande suivante pour construire l'image Docker :
```sh
docker build -t bonjour-capitaine .
```

###  Exécuter le conteneur
Une fois l'image construite, vous pouvez l'exécuter avec la commande suivante :
```sh
docker run --rm bonjour-capitaine
```
 **Sortie attendue :**
```
Bonjour, capitaine !
```


This project is part of [roadmap.sh](https://roadmap.sh/projects/basic-dockerfile) DevOps projects.




