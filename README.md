## UML
Desarrollo de un modelado de una plataforma web para un concesionario de vehículos de alta gama, usando UML

# Integrantes:
 - Angee Paola Ballesteros Maldonado Cod. 20201099027
 - Jeison Jair Ariza Pulido Cod. 20201099026
 - Luigi Santiago Fajardo Toloza Cod. 20201099029

# Asignatura INFORMATICA 1
__Docente__
 - Alejandro Paolo Daza

__Ejercicio__
Modelado de plataforma web de concesionaria de vehículos de alta gama, usando UML, la plataforma debe permitir al usuario cambiar la configuración de las partes del vehículo de acuerdo a las posibles existencias para el modelo seleccionado y probar el vehículo en una simulación que informe al usuario sobre:
 - El consumo de combustible.
 - La aceleración del vehículo.
 - La potencia del motor.

# Solución Planteada
Haciendo uso de la herramienta de modelado StarUML, se plantea el modelado para el porblema presentado mediante la construcción de Modelos estructurales, Modelos Funcionales y Modelos de Interaccion, el desarrollo de los mismos se presenta a continuación.
 - Modelo Estructural: mediante la construccion del diagrama de clase, se puede observar la solución que se plantea para la necesidad que se busca suplir en la creacion de la plataforma web de concesionario de alta gama, mediante el uso de los patrones Builder y Prototype se obtiene el resultado presentado a continuación.
 ![Diagrama_Clases](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/0%20DiagramaClases.PNG)
 - Modelo Funcional: mediante la construcción del diagrama de casos de uso, podemos observar la manera en la cual se realiza el despliegue de la pagina web, y de igual forma, la manera en que los usuarios interactuarian con la misma, mediante las decisiones que el usuario vaya tomando a traves de su navegación, encontrara una serie de nuevas opciones para cada una de la decisiones que este tome.
 ![Diagrama_Casos_Uso](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/1%20CasosUso.PNG)


Diagramas de secuencia
A continuacion son mostrados los diagramas de secuencia para cada uno de los escenarios.

Desplegar Plataforma Web
Refleja el despliegue en el navegador de los componentes graficos con los que el usuario podra interactuar.



Construir Auto
El Usuario oprime el boton para la creacion de un auto.



Especificar Marca
Dependiendo de la eleccion del usuario se creara un constructor y un auto.



Construir Motor
Refleja la creacion de un motor dependiendo de la eleccion de un usuario.



Especificar Categoria Motor
Dependiendo de la eleccion del usuario se creara un motor.



Construir Neumaticos
Refleja la creacion de los neumaticos dependiendo de la eleccion de un usuario.



Especificar Categoria Neumaticos
Dependiendo de la eleccion del usuario se creara los Neumaticos.



Construir Transmision
Refleja la creacion de la Transmision dependiendo de la eleccion de un usuario.



Especificar Categoria Transmision
Dependiendo de la eleccion del usuario se creara la Transmision.



Probar Auto
El usuario oprime el boton ProbarAuto y se encadena un simulacion del rendimiento de este dependiendo de sus componentes.



Realizar Simulacion del Auto
Se calucula el rendimiento del auto en base a 3 propiedades como la Potencia del motor, Aceleracion, Consumo de Combustible, y esto dependera del tipo de componente que tenga el carro.



Mostrar Rendimiento del Auto
Una vez calculadas las propiedades del auto se obtiene los atributos del auto y se genera un informe que sera mostrado al usuario.



Obtener Informe del Estado del Auto
Una vez creado el reporte se obtiene para ser mostrado al usuario.



Modificar Tipo de Motor
Cuando el usuario ha creado un auto tiene la posibilidad de cambiar el motor, para esto oprime el boton ModificarMotor.



Modificar Neumaticos
Cuando el usuario ha creado un auto tiene la posibilidad de cambiar los Neumaticos, para esto oprime el boton ModificarNeumaticos.



Modificar Transmision
Cuando el usuario ha creado un auto tiene la posibilidad de cambiar la transmision, para esto oprime el boton ModificarTransmision.



Diagrama de estados


© 2020 GitHub, Inc.
