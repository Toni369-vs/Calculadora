Calculadora con React
Este repositorio contiene una calculadora desarrollada con React, la cual puede realizar operaciones aritméticas básicas como sumar, restar, multiplicar y dividir. Además, incluye una limitación que evita que se ingresen dos operadores consecutivos, lo que podría causar un error en la operación.

Cómo utilizar
Para utilizar la calculadora, sigue estos pasos:

Clona el repositorio en tu máquina local utilizando git clone o descargando el archivo .zip.
Abre la carpeta del proyecto en tu editor de código preferido.
Instala las dependencias del proyecto con el comando npm install.
Ejecuta el comando npm start para iniciar la aplicación en modo de desarrollo.
Abre http://localhost:3000 en tu navegador para ver la calculadora.
Funcionalidades
La calculadora tiene las siguientes funcionalidades:

Puede realizar operaciones aritméticas básicas como sumar, restar, multiplicar y dividir.
No permite ingresar dos operadores consecutivos, ya que esto causaría un error en la operación.
Muestra el resultado de la operación en tiempo real.
Tiene un botón para limpiar la pantalla y empezar una nueva operación.
Desarrollo
La calculadora fue desarrollada utilizando React, un framework de JavaScript utilizado para la creación de interfaces de usuario. Se utilizó una combinación de componentes funcionales y de clase para crear la interfaz y la lógica de la calculadora. Además, se utilizó CSS para darle estilo a la aplicación.

La limitación de no permitir dos operadores consecutivos se logró utilizando una validación en la lógica de la calculadora. Cada vez que se presiona un botón de operador, se verifica si el último elemento ingresado fue también un operador. En caso de ser así, se desactiva la funcionalidad del botón para evitar que se ingresen dos operadores consecutivos.




![Calculadora](https://user-images.githubusercontent.com/125910370/230463382-09ed0874-fa9d-4f70-bf49-3320072a368e.PNG)

