# Experimentos Cuánticos II - UNLP

En este repositorio los estudiantes pueden compartir código de análisis de las prácticas de laboratorio de la materia Experimentos Cuánticos II de la UNLP

http://www2.fisica.unlp.edu.ar/materias/Expcuan2/clases.html

## Grupos

Cada grupo pone su código en la carpeta que le corresponde. 


## Como me bajo esto?

Usando git!!

Hay dos protocolos para hacer esto. 

SSH:
``` git clone git@github.com:monticellifernando/EC2.git ```

ó HTTPS:
``` git clone https://github.com/monticellifernando/EC2.git ```

Elegí el que quieras. Ahí tienen todo. Cuando ponen su código hacen commit y lo mandan. 

* IMPORTANTE *:

Todos los comandos git hay que ejecutarlos *DENTRO* de la carpeta donte está el repositorio. 

```
cd EC2
```


Recordar *SIEMPRE* hacer git pull para obtener la versión más actualizada del código en tu repositorio local!

```
git pull
```

Ahora sí. Hacés tu desarrollo. Agregás archivos nuevos, o editás archivos que ya están. Una vez que terminás, tanto para los archivos nuevos como los archvos modificados hacés esto para agregarlos:

``` 
git add <myPath1/MyFile1> <mypath2/myfile2> 
git commit -m "Un comentario"
```

Ahora con su repositorio lo sincronizan en github

```
git push
```

Y listo!!!
