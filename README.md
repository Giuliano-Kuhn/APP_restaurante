# APP Restaurante

Esta aplicación web en un proyecto para entregar como final de etapa de una materia de la Universidad.
La aplicacion es principalmente para la gestión de un restaurante, desarrollada en Java(servlets), con MySQL, y corriendo en un XAMPP, todos requisitos especificos de la entrega. 
Principalmente lo que hace es permitir mostrar los menús, realizar y gestionar pedidos con interfaz gráfica y conexión a base de datos. 

Los lenguajes utilizados son:
- Lenguaje: Java
- Base de datos: MySQL
- Frontend: HTML

## Idea general
La idea general es ahorrar tiempo tanto para el cliente como al restaurante.
Todo parte de que un cliente llega al restaurante y se sienta en una mesa libre, cada mesa tendria un codigo de 6 numeros visible, y un codigo qr con el link de la pagina.
en la pagina se tendria que ingresar el numero de 6 digitos, en caso de ser cierto, se mostraria el menú del restaurante.
El ciente seleccionaria lo que quiere pedir, y realiza el pedido. 
Ese pedido se guarda en una base de datos, se le asignaria a un mozo ordenadamente, y "se mostraria" al chef y mozos como pedidos pendientes.
Una vez este preparado el chef "marcaria" como listo y uno de los mozos lo llevaria a la mesa.
Mientrastanto los pedidos se podrian utilizar tambien en la caja para llevar el conteo y poder luego cobrar a los comenzales, sus ordenes.


## Funcionalidades principales
- Mostrar menu del restaurante
- Crear pedido
- Asignacion igual a cada mozo
- Guardado en base de datos
- Conteo del total



## Ejecucion
Se abre XAMPP, se inicia Tomcat, Mysql y Apache.
se inicia desde el archivo Main.java para que pueda crear y cargar las listas enlazadas para la gestion de los pedidos
En la pagina que se muestra, introducir un codigo de mesa EJ:556675.
En la siguiente pagina seleccionar algo del menú y realizar el pedido.
En el Backend
El pedido se guardará como un nodo y se lo colocara en una lista enlazada, con otros pedidos
Luego se le asignara a un nodo mozo de una lista de mozos
Para despues guardar el pedido (nodo) en la base de datos.



## Autor
Desarrollado por **Giuliano Kuhn**  
Correo electronico: giulianokuhn@hotmail.com  
LinkedIn: https://www.linkedin.com/in/giulianokuhn/

