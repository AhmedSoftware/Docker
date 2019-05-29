# Docker

# lancement du conteneur Nginx 

commande : `docker run -d -p 8080:80 p`.

`-d`: pour détacher le conteneur du processus principal de la console. 
 il va nous permettre de continuer à utilisr la console pendant que le conteneur tourne sur un autre proccess.
 
`-p` : pour définir l'uitilisation de port, on transfert le trafic du port 8080 vers le port 80 du conteneur.

  `http://127.0.0.1:8080`: la page s'ouvre ici.
