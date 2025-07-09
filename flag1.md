# FLAG1
Vous venez de pirater un ordinateur pour la première fois dons l'image est alpine. Quelle est la manipulation à faire en premier? Rechercher le flag </br> </br>

Manipulation à faire pour preparer les images : 
```
docker load -i image_flag_v1.tar.gz
```
```
docker run -itd --name conteneur_flag1 --hostname conteneur_flag1 image_flag:v1
```
```
docker exec -it conteneur_flag1 bash
```
Rechercher le flag

