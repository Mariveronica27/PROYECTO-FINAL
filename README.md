# ------Instrucciones del Programa-----

1. Descargue la carpeta completa del programa depositada en el repositorio de Github
2. Llamar dicha carpeta "Proyecto 2(python)"
NOTA: En dado caso que el programa no corra al visualizarlo en el Visual Studio Code , cambiar la ruta del archivo  
tanto el del json como en el txt y asi el programa funcionara eficientemente.
3. Debe saber que a pesar del que el sistema no corra tiene que aparecer el archivo txt del "listado de materiales"
4.En la linea 7, donde se encuentra el archivo 'JSON', coloque la ruta relativa del mismo que se genera en su 
computador , para que el programa lo pueda reconocer.Ejemplo with open('ruta del archivo','r') as f:
NOTA: Como al descargar la carpeta completa de todo el programa estara el archivo txt , en el momento de colocar 
la ruta relativa del archivo le sera suficiente colocar . Ejemplo with open('Listado de Materiales1.txt','r') as f:
5. Es importante que tome en cuenta cambiar todas las rutas relativas donde aparezcan la ruta relativa del "Listado 
de Materiales1"es decir , en las lineas siguientes 11,17,25,31,51,87,111,132,171,172,178,196,247,248,254,271,314,315,
320,324,329,330,333,395.
5. Criterios que debe considerar en el omento de utilizar el programa:
         - Lo primero que debe hacer es leer la lista ( que se encuentra en la 'Opcion 2')
         - Se sugiere que antes de registrar un material verifique su existencia en la lista , lo debe buscar 
            primero ( se encuentra en la 'opcion 3')
            - Si se encuentra en la lista y desea:
                - Disminuir o aumentar la cantidad del material debe elegir la opcion 5 o 6 segun sea el caso
                - Si desea cambiar atributos elija la opcion 4 
                NOTA: Todas estas opciones pueden observarse en el 'Menu'
                - Si el material no se encuentra en la lista puede agregarlo con la opcion registrar ('Opcion 7')
                - Si se cometiera el error de registar un material existente en la lista , debe eliminar el registro
                con la opcion eliminar material de la lista ('Opcion 8') y despues agregarlo con la opcion agregar 
                cantidad de material en inventario ('Opcion 5') y tambien podria utilizar la opcion actualizar lista 
                de materiales ('Opcion 4')
6. Si se comete el error de registar dos veces el mismo material haga lo siguiente :
        -Debe eliminar el registro del material que tenga la mayor cantidad en el atributo 'cantidad' por lo que se 
        aconseja recordar la cantidad del material que posea el numero mayor en el atributo 'cantidad'
        -Proceda a eliminarlo (-Opcion 8') y coloque la cantidad mayor
        -Seleccione agregar cantidad de material en inventario ( 'Opcion 5') y anote la cantidad mayor         
7.IMPORTANTE---> En el momento que quiera salir del programa utilice la opcion de salir ('Opcion 9'),para evitar que el
 programa haga una lista imposible de leer debido al encriptado, si llegara a suceder tal error use lo que esta 
 en la en la Lista de emergencia.txt para colocarlo en el Listado de Materiales1.txt
	-Debe actualizar la lista de emergencia constantemente

