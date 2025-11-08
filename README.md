# APP Restaurante

Esta aplicación web en un proyecto para entregar como final de etapa de una materia de la Universidad siglo XXI.
La aplicacion es principalmente para la gestión de un restaurante, desarrollada en Java(servlets), con MySQL, y corriendo en un XAMPP, todos requisitos específicos de la entrega. 
Principalmente lo que hace es permitir mostrar el menú, realizar y gestionar pedidos con interfaz gráfica y conexión a base de datos. 

Los lenguajes utilizados son:
- Lenguaje: Java
- Base de datos: MySQL
- Frontend: HTML

## Idea general
La idea general es ahorrar tiempo tanto para el cliente como al restaurante.
Todo parte de que un cliente llega al restaurante y se sienta en una mesa libre, cada mesa tendría un código de 6 números visible, y un código QR con el link de la página.
En la página se tendría que ingresar el número de 6 dígitos, en caso de ser cierto, se mostraría el menú del restaurante.
El cliente seleccionaría lo que quiere pedir y realiza el pedido. 
Ese pedido se guarda en una base de datos, se le asignaría a un mozo ordenadamente, y "se mostraría" al chef y mozos como pedidos pendientes.
Una vez que esté preparado el chef "marcaría" como listo y uno de los mozos lo llevaría a la mesa.
Mientras tanto los pedidos se podrían utilizar tambien en la caja para llevar el conteo y poder luego cobrar a los comenzales, sus ordenes.


## Funcionalidades principales
- Mostrar menú del restaurante.
- Crear pedido.
- Asignacion igual a cada mozo.
- Guardado en base de datos.
- Conteo del total.



## Ejecución
Se abre XAMPP, se inicia Tomcat, Mysql y Apache.
se inicia desde el archivo Main.java para que pueda crear y cargar las listas enlazadas para la gestión de los pedidos.
En la página que se muestra, introducir un código de mesa EJ: 556675.
En la siguiente página seleccionar algo del menú y realizar el pedido.
En el Backend:
El pedido se guardará como un nodo y se lo colocará en una lista enlazada, con otros pedidos.
Luego se le asignará a un nodo mozo de una lista de mozos.
Para despues guardar el pedido (nodo) en la base de datos.



## Autor
Desarrollado por **Giuliano Kuhn**  
Correo electronico: giulianokuhn@hotmail.com  
LinkedIn: https://www.linkedin.com/in/giulianokuhn/

