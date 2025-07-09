# FLAG_WEB3
Lors du déploiement dans un serveur, un pirate constate que la fenêtre tester connectivité possède une faille </br>
Le but est de récuperer un fichier important dans le serveur du nom de flag.txt  </br>  
Dans cet exercice, un mini-parfeu a été installé </br>

Manipulation à faire pour preparer les images : 
```
docker load -i image_flag_web_v4.tar.gz
```
```
docker run -itd -p 8084:80 --name conteneur_flag_web4 --hostname conteneur_flag_web4 image_flag_web:v4
```
Tapez sur le navigateur
```
localhost:8084
```
Entrer : 
```
google.com
```
Résultat du ping est donc (attendre environ 5 à 10 séconde)
```
PING google.com (74.125.136.139) 56(84) bytes of data.
64 bytes from 74.125.136.139 (74.125.136.139): icmp_seq=1 ttl=63 time=280 ms
64 bytes from 74.125.136.139 (74.125.136.139): icmp_seq=2 ttl=63 time=283 ms
64 bytes from 74.125.136.139 (74.125.136.139): icmp_seq=3 ttl=63 time=294 ms
64 bytes from 74.125.136.139 (74.125.136.139): icmp_seq=4 ttl=63 time=280 ms

--- google.com ping statistics ---
4 packets transmitted, 4 received, 0% packet loss, time 3000ms
rtt min/avg/max/mdev = 279.643/284.218/293.802/5.737 ms
Rechercher le mot de passe puis le flag
```
