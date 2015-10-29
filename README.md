# Sistemas y tecnologias Web
La practica consiste en desplegar la practica de conversor de temperatura en la maquina virtual de la universidad de la laguna.

### Tutorial para implantación en iass.ull.es

* Acceder a  iaas.ull.es
* Logearse con el alu de la universidad
* Una vez dentro de la aplicacion deberemos cambiar la confighuración de la consola dejandola en la opcion noVNC
* Arrancar la maquina virtual con usuario y contraseña usuario


### Opciones de acceso

* Dentro de la universidad 
* Fuera de ella (establecer vpn)

### Conocer la ip de nuestra maquina virtual
```sh
$ ifconfig
```
Con ello sabremos la ip que necesitamos para acceder a nuestro servidor desde el interior o el exterior.

### Instalaciones Adicionales
```sh
$  sudo apt-get install nodejs
$  sudo apt-get install npm
```
Ademas deberemos hacer un npm install:
```sh
$  npm install
```
Para finalizar arrancaremos el servidor con:
```sh
$  node static-server.js
```



#Enlaces de interes

- Página de la asignatura: http://hectorinoman.github.io/
- Despliegue: http://10.6.128.89:8080/index.html
- Blanket: http://10.6.128.89:8080/tests/test_blanket.html
- Repositorio: https://github.com/hectorinoman/ConversorTemperatura4


[![Build Status](https://travis-ci.org/hectorinoman/ConversorTemperatura3.svg)](https://travis-ci.org/hectorinoman/ConversorTemperatura3)