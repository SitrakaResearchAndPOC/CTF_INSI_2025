# FLAG2
Vous venez de pirater un ordinateur de l'entreprise insi ayant un document caché dans l'OS. Ce document contient le flag </br> </br>

Manipulation à faire pour preparer les images : 
```
docker load -i image_flag_v2.tar.gz
```
```
docker run -itd --name conteneur_flag2 --hostname conteneur_flag2 image_flag:v2
```
```
docker exec -it conteneur_flag2 bash
```
Rechercher le flag
