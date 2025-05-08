# Oinsa atu utiliza

Asegura katak ita-boot iha aplikasaun no pasta mysql iha diretóriu hanesan ho docker-compose.yml. Pasta app nian kontein ita-boot nia arkivu PHP sira, enkuantu pasta mysql kontein ita-boot nia dadus MariaDB nian.
Ita-boot bele hala'o docker-compose up -d hodi hahú servisu.
Ita-boot bele asesu Adminer iha http://localhost:8080.

atu asesu ba programa php
http://localhost:80/

login ba adminer <br>
server = db <br>
user= myuser <br>
pass = mypassword <br>
db = mydb <br>

server = db <br>
user = root <br>
password = root <br>
db = (husik mamuk) <br>

kona ba down docker <br>
docker-compose down --volume
