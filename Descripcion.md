Crearemos una parte de un sistema, el cual ya cuenta con la aplicación de "autopartes", tiene una base de datos y
tiene su propio servidor. Estamos encargados de hacer una aplicación extra para ese sistema el cual ilustraremos
con un modelado de la aplicación en c4, viendo el nivel del software de manera práctica y ágil.

-Diagrama de contexto (imagen1): mostramos el sistema y sus dependencias con otros sistemas

-Diagramas de contenedores (imagen2):  Del sistema veremos una entidad para mostrar la composición interna 
 de “mi aplicación”, podemos ver mas de cerca quien y como se va a conectar con las aplicaciones externas
 ya hechas.

 -Componentes (imagen3): veremos el “servicio web” y toda su estructura interna pero también seguiremos
  viendo el dispositivo y la base de datos de “mi aplicación” en tipo diagrama de contenedores, en este caso
  vemos más de cerca el “servicio web” que va tener su controlador, repositorio y lista de correos, en esta
  capa vemos muy de cerca quien se conectara a la BD del sistema y a los servidores.