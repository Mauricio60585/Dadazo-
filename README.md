# Dadazo-
Simulación de Lanzamiento de Dados en Java
Este programa simula el lanzamiento de un dado de seis caras múltiples veces y cuenta la frecuencia de aparición de cada cara. Utiliza la clase SecureRandom para generar números aleatorios y muestra los resultados en una tabla.

Requisitos
- Java Development Kit (JDK) instalado (versión 8 o superior).

- Un entorno de desarrollo integrado (IDE) como IntelliJ IDEA, Eclipse o cualquier editor de texto para Java.

Instrucciones de Uso
Clonar o descargar el repositorio:

Si tienes el código en un repositorio, clónalo usando:

git clone <URL_DEL_REPOSITORIO>
Si no, descarga el archivo SimulacionDado.java.

Compilar el programa:

- Abre una terminal o línea de comandos.
- Navega hasta la carpeta donde se encuentra el archivo dado1.java.
- Compila el programa con el siguiente comando:
  javac SimulacionDado.java

Ejecutar el programa:
Después de compilar, ejecuta el programa con:
java dado1

Ingresar el número de lanzamientos:

El programa solicitará que ingreses el número de lanzamientos que deseas simular.
Por ejemplo, puedes ingresar 60000000 para simular 60 millones de lanzamientos.
Ver los resultados:
El programa mostrará una tabla con la frecuencia de cada cara del dado.

Explicación del Código
Clases y Métodos
- Clase SimulacionDado:
Contiene el método main, que es el punto de entrada del programa.

- Método main:
Crea una instancia de SecureRandom para generar números aleatorios.
Usa un arreglo de enteros (frecuenciaCaras) para almacenar la frecuencia de cada cara del dado.
Solicita al usuario el número de lanzamientos.
Simula los lanzamientos usando un bucle for y una estructura switch para contar las frecuencias.
Muestra los resultados en una tabla.

Dependencias
SecureRandom:
- Se utiliza para generar números aleatorios de manera segura.
- Asegura que los números generados sean impredecibles.

Scanner:
- Se utiliza para leer la entrada del usuario (número de lanzamientos).

Contacto
Si tienes preguntas o sugerencias, no dudes en contactarme:

Nombre: [Mauricio Agudelo]
Email: [mauricio.agudelo60585@ucaldas.edu.co]
GitHub: Mauricio60585
