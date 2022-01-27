# Codigo 13

## Comando para GIT

```
git init
```
- este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git
- crea una carpeta oculta llamda ```.git```

```
git status
```
- poder listar y ver si los archivos estan listados para subir
- ojo en caso los archivos no esten listos se veran color rojo


```
git add .
```
-s e encarga de agregar los archivos a la memoria GIT, es decir los guarda en el stash

```
git commit -m "comentario"
```
- crea un ounto en la linea de tiempo de nuestro cambio y se le es posible adjuntar un comentario
- :eye: los comentarios deben de estar relacionados a los cambios.

```
git push origin main
```
- sirve para subuer los cambios a nuestro repositorio en la nube


```
git pull origin main
```
- sirve para descargar nuestro repositorio de la nube a nuestra computadora.


```
git branch
```
- sirve para listar los branch que tengo localmente y me dice en cual me encuentro actualmente.


```
git checkout -b "nombre"
```
- sirve para descargar nuestro repositorio de la nube a nuestra computadora.


```
git checkout -b nombre_del_branch
```
- crea un branch nuevo.

```
git checkout nombre_del_branch
```

- Sirve para poder moverme entre ramas
- 👁️ Si el checkout no tiene el -b solo es para moverse