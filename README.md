# docker_tp03

# 1. Créez un nouveau repository git <br>

# 2. Initialisez un projet React vierge <br>
  ```npx create-react-app mon-app```

# 3.  Vérifiez que l'application fonctionne correctement en local** <br>
  ```npm start```
  ```http://localhost:3000```

# 4.  Créez un fichier Dockerfile à la racine du projet. Celui-ci doit se diviser en deux grandes parties** <br>
  ```npm start```

# 5.  Instanciez l’image créé précédemment afin d’observer le même résultat que lors de la question 3** <br>
  ```docker build -t my-app .```
  ```docker run -p 80:80 my-app```