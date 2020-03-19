# Some docker commands

Launch docker image
> docker run image_name

Lancer des dockers dans un docker-compose.yml
> docker-compose up -d

> docker-compose up -d --build

Enter a container interactive mode
>docker exec -it container_name "bash"

Désactiver les containers d'un docker-compose.yml
> docker-compose down

Effacer les images containers arrêté
> docker system prune