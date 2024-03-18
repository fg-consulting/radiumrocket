## Herramientas curso de desarrollo seguro RadiumRocket
### [Link descarga Burp Suite Community](https://portswigger.net/burp/communitydownload) 

### Ejecución contenedor Docker Juice-Shop
```
docker run -d -e "CTF_KEY=RadiumRocketSecret"\
              -e "NODE_ENV=ctf"\
              -p 3000:3000\
               bkimminich/juice-shop

docker run -d -e "CTF_KEY=RadiumRocketSecret" -e "NODE_ENV=ctf" -p 3000:3000 bkimminich/juice-shop
```
### [Link a la plataforma de CTF](http://fg-ctf.duckdns.org/)
Utilizar nomenclatura de usuarios 'napellido' donde la 'n' corresponde a la primer letra del nombre de pila.
No es necesario ingresar un correo válido.
