# FLAG3
L'entreprise INSI possède un document important insi.jpg, l'adminstrateur a cacher des informations dans les metadonnées et dans l'image insi.jpg </br> </br>

Manipulation à faire pour preparer les images : 
```
docker load -i image_flag_v3.tar.gz
```
```
docker run -itd --name conteneur_flag3 --hostname conteneur_flag3 image_flag:v3
```
Si vous vouler copier l'image : </br> 
```
docker cp conteneur_flag3:/home/insi.jpg .
```
Demarrer le conteneur
```
docker exec -it conteneur_flag3 bash -c "cd /home; exec bash"
```
Rechercher le flag
