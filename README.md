# microservicio
Un microservicio desarrollado con SpringBoot en lenguaje java 17 para ser consumido por una aplicación

En esta versión contiene lo principal para poder ir trabajando.
Contenido:
 	Controller:
              - Puedes crear un usuario 
              - Puedes listar los usuarios con /listar
      	Model:
              - Está construido el usuario como una entidad
              - Se define la tabla como "usuario"
              - Constructores Sin/Con argumentos
              - Definidas las caracteristicas de los atributos (Cosas como si puede ser nulo, largo, etc)
	Repository:
							- Se extiende como JPA para ocupar las funciones incluidas

	Service:
 							- Se define como Transaccional 
							- Se crea el metodo de crearUsuario 
			 				- Se crea el metodo de obtener todos los usuarios
