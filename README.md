# GITHUB ACTIVIDAD
## Clonar Repositorio

``git clone https://github.com/ladriank-education/masteruah``   

## Crear/Modificar README.md
> Marqué la creación automatica del fichero **README.md** a la hora de crear el repositorio

## Primer Commit
> Como no tengo ningun nuevo cambio en el repositorio primero creare un fichero.
> Para ello, usare el siguiente comando:


``touch fichero``   


![imagen](.img/1.png)


> Posteriormente lo agregare al 'Staging Area' con el uso del siguiente comando:

``git add fichero``   


![imagen](.img/2.png)
> Ahora si puedo ejecutar un commit mediante el siguiente comando:


``git commit -m "Commit Inicial"``


![imagen](.img/3.png)
## Subiendo archivos
> Para subir los archivos al repositorio he usado el siguiente comando:


``git push``


![imagen](.img/4.png)

## Crear fichero '1.txt' en el repositorio local
> Para crear un fichero volvemos a usar el comando:

``touch 1.txt``

![imagen](.img/5.png)

## Crear etiqueta 'v0.1'
> Creamos la etiqueta con el nombre **'v0.1'**
> Esto hace que los ficheros que vayamos a incluir en el commit tengan la etiqueta designada

``git tag "v0.1"``

![imagen](.img/6.png)

## Subir etiqueta 'v0.1'
> Para subir la etiqueta tan solo debemos ejecutar el siguiente comando, aunque no es recomendado

``git push --tags``

![imagen](.img/7.png)

## Subir los cambios
> Usamos el comando

``git push``