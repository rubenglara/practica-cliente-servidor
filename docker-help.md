# Docker Help

Si queremos construir una imagen de docker necesetiaremos crear un fichero con el nombre **dockerfile**

```sh
# Así construimos una imagen anónima, donde el . es la ruta hasta el fichero dockerfile
docker build .

# y así imagen con nombre
docker build -t ElNombre .  
```

Si queremos lanzar un contenedor partiendo de una imagen:
```sh
docker run ElNombre
# si en una imagen anónima necesitaremos el identificador sería:
docker run  id
```