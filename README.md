# Laboratorio #1
## level 0
En este primer nivel, se nos conectarnos al servidor ssh de `bandit.labs.overthewire.org` por el puerto `2220`, con las credeciales usuario:`bandit0` y contraseña:`bandit0`.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
### Contraseña Encontrada
Para Encontrar la contraseña una vez conectado al servidor se realizo una busqueda en el directorio principal del usuario, en el cual se encontro el archivo `readme`
```
cat readme
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```
### Contraseña
```
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```
