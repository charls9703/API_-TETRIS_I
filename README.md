# API_TETRIS_I
Esta es la dirrecion donde se encuentra la documentacion de esta api http://142.44.246.92//docApi-I/index.html
para ejecutar esta api se ncesita descarga node.js e instalar por emdio de npm los paquetes express y morgan 
 ## intalacion
 -primero instalamos node.js del siguiente link https://nodejs.org/es/ despues de isntalarlo
 
 -descomprimimos la carpeta que descargamos de este repositorio e ingresamos a ella en la carpeta src abra un archivo de nombre figura .js que sera nuestra aplicacion para poder ejecutarla,
 
 -nos dirigimos al simbolo del sistema con la siguiente linea de comando:
 
 -inicio+r 
 
-este comando nos llevara a simbolo del sistema una ves hay digitamos:

 -npm i express morgan
 
 -despues en el mismo simbolo del sistema nos dirigimos al interior de la carpeta src.
 
 -D:\Users\cobd\Desktop\Api_I\src>
 
-la anterior linea muestra un ejemplo de como ingresar y una vea alli digitamos

-node figura.js start y emepezara a ejecutar el api 


## prueba
{
    "pos": {
        "x": -1,
        "y": 6
    },
    "matriz": [
        [
            0,
            0,
            0,
            0
        ],
        [
            1,
            1,
            1,
            1
        ],
        [
            0,
            0,
            0,
            0
        ],
        [
            0,
            0,
            0,
            0
        ]
    ]
}

con el dato de arriba en formato json se puede probar utilizando la aplicacion postman y utlizando sentencias post y get.

o utilizando las siguientes urls y postman para enviarle datos

http://142.44.246.92:3000/matriz

http://142.44.246.92:3000/rotate

http://142.44.246.92:3000/drop

http://142.44.246.92:3000/move

