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
 - Modelos de Interacción: mediante el uso de Diagramas de Secuencia y Diagrama de Actividades, se presentan los escenarios posibles en la interacción de la plataforma web.
   - Diagramas de Secuencia:
     - Ingreso a la plataforma web: encontramos el login que el usuario debe ejecutar al ingresar a la pagina.
     ![Ingreso a la plataforma web](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/2%20Ingresoa%20a%20plataforma%20web.PNG)
     - Construcción del Vehículo: el usuario inicia el proceso de construcción del automovil.
     ![Construccion_Vehiculo](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/3%20Construccion%20Vehiculo.PNG)
     - Traer Motor: el usuario realiza la elección del motor con sus características correspondientes.
     ![Traer_Motor](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/4%20Traer%20motor.PNG)
     - Traer Turbo: el usuario selecciona el turbo del vehículo y recibe las estadísticas del mismo.
     ![Traer_Turbo](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/5%20Traer%20Turbo.PNG)
     - Traer Transmision: el usuario selecciona la transmisión del vehículo y recibe las estadísticas del mismo tanto para Manual como para automático.
     ![Traer_Transmision](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/6%20DiagramatraerTrasmision.png)
     - Traer Carroceria: el usuario selecciona la carroceria entre las opciones de fibre de carbono y convencional, recibiendo las estadísticas del mismo.
     ![Traer_Carroceria](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/7%20Carroceria%20Sequence%20Diagram.jpg)
     - Simulación: en esta seccion se realizan todas las pruebas de rendimiento del vehículo y en caso de ser necesario se realizan los ajustes correspondientes con las características del mismo.
     ![Simulacion](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/8%20Simulacion.PNG)
   - Diagramas de Actividades:
     - Proceso de Construcción del Vehículo: en esta seccion se presentan las actividades realizadas en todo el proceso de construccion del vehículo.
     ![Construccion_Proc](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/9%20Construir%20Vehiculo.PNG)
     - Proceso de Simulación del Vehículo: en esta seccion se presentan las actividades realizadas en todo el proceso de la simulación del vehículo.
     ![Simulacion_Proc](https://raw.githubusercontent.com/lsfajardot/UML/master/UML/10%20Simular%20Vehiculo.PNG)

© 2020 GitHub, Inc.
