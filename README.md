<p align="center"> <img width="250" height="370" src="https://github.com/user-attachments/assets/13594b3b-a153-47a2-865c-064814e34018"> </p>

<h1><p align="center">Conversor de monedas</p></h1>


🔢Índice

1️⃣[Descripción del proyecto](#descripción-del-proyecto)

2️⃣[Estado del proyecto](#Estado-del-proyecto)

3️⃣[Características de la aplicación y demostración](#Características-de-la-aplicación-y-demostración)

4️⃣[Acceso al proyecto](#acceso-proyecto)

5️⃣[Tecnologías utilizadas](#tecnologías-utilizadas)

6️⃣[Personas Contribuyentes](#personas-contribuyentes)

7️⃣[Desarrolladores del Proyecto](#personas-desarrolladores)

8️⃣[Licencia](#licencia)

9️⃣[Conclusión](#conclusión)

============================================================================================

1️⃣Descripción del proyecto:
Implementación de una consulta mediante utilización de REST API para generar una conversión entre 2 monedas.

2️⃣Estado del proyecto:
Proyecto finalizado y publicado en github. Versión 1.0.

3️⃣Características de la aplicación y demostración:
  
:heavy_check_mark: Al ejecutar la aplicación, se muestra un menú donde hay 6 opciones de conversión disponibles.

<p align="center"> <img width="200" height="300" src="https://github.com/user-attachments/assets/4b7d52d3-368b-4d0c-bf7d-f16612d3c046"> </p>

:heavy_check_mark:  Al seleccionar una de las opciones, el sistema muestra la moneda "base" (ubicada en la opción del lado izquierdo de la aplicación) y la moneda "destino" (ubicada a la derecha de la opción previamente mencionada). 
Con esta información, la aplicación realiza una consulta -mediante el uso de una API Key- al sitio [https://v6.exchangerate-api.com/](https://v6.exchangerate-api.com/) y obtiene una tasa de cambio entre las monedas que se encuentran listadas en la opción seleccionada. Este valor se almacena en una variable para su uso posterior.

<p align="center"> <img width="200" height="300" src="https://github.com/user-attachments/assets/83c11cbe-3966-495d-b685-e5a75ce9c8e3"> </p>  

:heavy_check_mark:  Luego el sistema solicita al usuario el ingreso de un monto a convertir entre ambas monedas, y usando la tasa de cambio previamente obtenida realiza el cálculo del importe convertido.

<p align="center"> <img width="300" height="150" src="https://github.com/user-attachments/assets/47de3343-58b4-4ac6-a500-14ebf14ba50c"> </p>
  
:heavy_check_mark: Se agrega la posibilidad de volver a realizar una nueva conversión entre monedas seleccionando "s" o de finalizar la ejecución del programa seleccionando "n". Si la opción seleccionada es "s", el sistema realiza una limpieza de pantalla agregando líneas en blanco antes del menú inicial.

:heavy_check_mark: Hay una séptima opción que finaliza la ejecución del programa, mostrando un mensaje por pantalla. 

4️⃣ Acceso al proyecto:


5️⃣Tecnologías utilizadas:

6️⃣Desarrollado mediante lenguaje Java utilizando IntelliJ como IDE y Maven como manejador de dependencias.
* [Java](https://docs.oracle.com/en/java/) - Lenguaje de programación
* [IntelliJ](https://www.jetbrains.com/idea/) - IDE
* [Maven](https://maven.apache.org/) - Manejador de dependencias


7️⃣Desarrolladores:

[<img src="https://avatars.githubusercontent.com/u/178737341?v=4" width=115><br><sub>Rafael Battagini</sub>](https://github.com/RafaelBattagini)
