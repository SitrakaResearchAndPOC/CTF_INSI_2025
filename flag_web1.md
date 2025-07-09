# FLAG_WEB1
L'administrateur a oublié de changer le compte admin pour gerer son siteweb. </br>
De plus, il a utilisé le mot de passe de l'ancien administrateur qui est faible qui contient seulement les caractère a-z et les chiffres  0-9. </br>
Un fois le mot de passe trouvé, le flag s'affichera instantanément </br></br>

Manipulation à faire pour preparer les images : 
```
docker load -i image_flag_web_v1.tar.gz
```
```
docker run -itd -p 80:80 --name conteneur_flag_web1 --hostname conteneur_flag_web1 image_flag_web:v1
```
Tapez sur le navigateur
```
localhost
```
Rechercher le mot de passe puis le flag


