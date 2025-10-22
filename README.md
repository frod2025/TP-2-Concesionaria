README:

Trabajo Práctico 2 : Concesionaria de Autos y Motos
El proyecto se creó con Spring Boot. Se gestiona con Maven. Y se utilizaron herramientas Lombok para reducir el código repetitivo y seguir buenas prácticas de desarrollo. 
Se utilizan: Interface, API Stream, List y ArrayList, Comparable y Lombok.
Esta dividido en 3 paquetes: Entidades, Interfaces y Tests.

Entidades: Contiene la clase padre abstracta Vehiculo, la cuál implementa la interfaz Comparable con el generic Vehiculo, para sobreescribir el método compareTo. 
                 Las clases Auto y Moto extienden de la clase padre vehiculo e implementan la interfaz IDatos.
                 ListaVehiculo gestiona una lista de vehículos mediante una ArrayList. Utiliza API Stream para implementar los métodos de búsqueda y ordenamiento: 
                 vehículo más caro, vehiculo más barato, vehículo que contiene la letra “Y”, Vehículos ordenados por precio descendente y vehículos ordenados por orden natural.

Interfaces: Contiene la interfaz IDatos con el método mostrarDatos( ), que va a ser implementado por Auto y Moto, para mostrar los datos de cada vehículo.

Tests: Contiene el método main para crear vehiculos, agregar a la lista y hacer las pruebas.
