
_ **Nombre:** _

*Victor Jose*

_ **Apellido:** _

*Matos Coss*

_ **ID:** _

*1093812*

_ **Prof:** _

*Lorenzo Solano*

_ **Asignatura:** _

*Programación II Laboratorio.*

##### **Responder, Proveer la información solicitada o realizar los ejercicios según aplique:**

**0. URL del repositorio de github.com**

**Rep github:**

**Playlist:**

[**https://www.youtube.com/playlist?list=PL5K8kPa4QpEFWJnPREdQi_VxooLGl57m7**](https://www.youtube.com/playlist?list=PL5K8kPa4QpEFWJnPREdQi_VxooLGl57m7)

**1. ¿Cómo sabemos si un programa o script termina de manera exitosa desde el shell / consola?**

*En el momento cuando ponemos nuestro programa en la consola muestra el archivo que se está compilando, la cantidad de líneas que se compilan y luego el tiempo en que se compilo, y luego muestra que el archivo puede ejecutarse en la consola y corre el código. Si hay un error en el código, al momento de compilar lo notifica y no se podrá ejecutar el código.*

**2. Cree un script que escriba "Hola <nombre>.".**

**El script debe recibir el nombre como argumento de línea de comando. Si el usuario digita algún nombre el script escribe al STDOUT el mensaje indicado y termina retornando exitosamente (return code apropiado). Si el usuario no digita ningún nombre entonces el script termina con error (return code 100). No usar ningún lenguaje de programación compilado o interpretado sólo el propio scripting language. El vídeo debe evidenciar los dos casos: salida exitosa y salida de error.**

[**https://youtu.be/9PStw3oGuME**](https://youtu.be/9PStw3oGuME)

**3. Cree un script similar al del punto 2 pero la lógica debe implementarse en un lenguaje de programación (no scripting).**

**Ejemplo desde un script de bash (windows), puede invocar un programa creado previamente en lenguaje C. El Script debe transferir el parámetro con el nombre a saludar. El script debe devolver el mismo código de retorno del programa.**

[**https://youtu.be/msAf6u-h5PM**](https://youtu.be/msAf6u-h5PM)

**4. ¿Qué es el redireccionamiento en el contexto de la ejecución de un programa, script o comando de consola?**

*Cambiar la dirección de una información del programa ya sea lo que se muestra en pantalla o lo que la máquina registre de entrada a otra dirección y que no afecte de gran manera al funcionamiento del programa.*

**5. ¿Cuáles números o constantes representan los streams de I/O clásicos (Standard Input, Standard Output y Standard Error) en los siguientes sistemas operativos: Unix/Linux, MacOS y Windows?**

*Standar Input : 0*

*Standard Output : 1*

*Standard Error : 2*

**6. Cree un programa que reciba un número como argumento de línea de comando, si el número es negativo o cero debe escribir por el Standard Error el mensaje "Invalid input <numero>.". Si el número es positivo, debe escribir por el Standard Output el mensaje "Good one <numero>.".**

[**https://youtu.be/Rua--fl3yXE**](https://youtu.be/Rua--fl3yXE)

[**https://youtu.be/GNwwIAKRfeI**](https://youtu.be/GNwwIAKRfeI)

**7. Desde la consola corra el programa 6, redireccionando el Standard Output a un archivo de nombre out.txt, corra el programa con valores positivos, negativos y cero.**

**Muestre el contenido del archivo, desde la consola, con cada ejecución, para confirmar que sólo contiene el mensaje cuando prueba con un valor positivo. Prueba con más de un valor positivo.**

[**https://youtu.be/DT8kZb7E8m0**](https://youtu.be/DT8kZb7E8m0)

**8. Desde la consola corra el programa 6, redireccionando el Standard Error a un archivo de nombre err.txt, corra el programa con valores positivos, negativos y cero.**

**Muestre el contenido del archivo, desde la consola, con cada ejecución, para confirmar que sólo contiene el mensaje cuando prueba con valores negativos o cero. Pruebe con más de un valor invalido.**

[**https://youtu.be/tCRYUGbBKS0**](https://youtu.be/tCRYUGbBKS0)

**9. Cree un programa similar al 6, pero que reciba su entrada desde el Standard Input, no desde los argumentos de línea de comando.**

[**https://youtu.be/zboD4e1SE0k**](https://youtu.be/zboD4e1SE0k)

**10. ¿Qué es el Piping en Unix y Linux, para qué sirve? de algunos ejemplos? Referencia:** [**https://www.geeksforgeeks.org/piping-in-unix-or-linux/**](https://www.geeksforgeeks.org/piping-in-unix-or-linux/)

*Es una forma de redirección, transfiere el standard output a otro destino, es usado en Linux y otros operadores Unix para mandar el output de un comando, programa entre otros. Los sistemas de Unix y Linux permiten al standard output de un comando conectarse con otro comando. Pipe se usa para combinar 2 o mas comandos, el output de un comando sirve como input de otro.*

**11. Cree un programa que escriba al Stdout los números del 1 hasta N.**

**N será un número capturado como argumento de línea de comando. Ejemplo: ($ simboliza el prompt)**

**$ Contador.exe 3**

**1**

**2**

**3**

**$**

**Note que hay una línea vacía entre el último número y el prompt. Esto quiere decir que el programa debe imprimir una línea en blanco antes de terminar. Si la entrada no es un número positivo entero, el programa debe imprimir un error por el Std. Error. Ejemplo:**

**$ Contador.exe Tres**

**Invalid input Tres.**

**$**

**Note que sigue habiendo una línea en blanco antes de salir, y recuerda que ese mensaje fue enviado al Std. Error no al Std. Output.**

[**https://youtu.be/NPH5FlHbzd8**](https://youtu.be/NPH5FlHbzd8)

**12. Cree un programa que reciba números desde el Std. Input hasta recibir una linea en blanco, vacía, para luego escribir al Std. Output la sumatoria de los valores.**

**Ejemplo (std-in), (std-out) y (std-err) representan la fuente y salidas de cada línea según aplique.**

**$ Sum.exe**

**1 (std-in)**

**2 (std-in)**

**3 (std-in)**

**(std-in)**

**6 (std-out)**

**(std-out)**

**$**

**En este ejemplo el usuario invoco el programa y luego escribió los números 1, 2 y 3 en cada línea (presionando Enter luego de cada uno). Luego para señalar que desea terminar y obtener la sumatoria dejo una linea en blanco (solo presionando Enter), luego el programa escribió al Std. Out. la sumatoria de los valores (6), y antes de salir dejo la linea en blanco mandatoria.**

**Si el programa recibe una entrada que no es un número entero debe escribir un mensaje de error al Std. Error. Ejemplo:**

**$ Sum.exe**

**1 (std-in)**

**Hola mundo cruel (std-in)**

**Invalid input "Hola mundo cruel" (std-err)**

**3 (std-in)**

**(std-in)**

**4 (std-out)**

**(std-out)**

**$**

**13. Cree un programa similar al 12, pero en lugar de sumar debe escribir al Std. Out el cuadrado de los números recibidos.**

**Ejemplo:**

**$ Square.exe**

**1 (std-in)**

**1 (std-out)**

**2 (std-in)**

**4 (std-out)**

**Hola mundo cruel (std-in)**

**Invalid input "Hola mundo cruel" (std-err)**

**3 (std-in)**

**9 (std-out)**

**$**

**14. Combine, desde el shell y utilizando piping, los 3 programas para obtener la sumatoria del cuadrado de los números de 1 a N.**

**Ejemplo (con N=10):**

**$ Counter.exe 10 | Square.exe | Sum.exe**

**385 (std-out)**

**(std-out)**

**$**

**15. Ponga los tres programas disponibles en cualquier lugar del shell, agregandolos a la variable PATH. Demuestre que puede invocarlos desde cualquier lugar en el shell, y no solo desde la ruta donde están guardados.**

**16. Cree un script para combinar los tres programas utilizando piping.**

**Ejemplo:**

**$ SumOfSquares.bat 10**

**385 (std-out)**

**(std-out)**

**$**

**17. Ponga disponible el script desde cualquier lugar en el shell, agregándole al PATH. Demuestre que puede ejecutarlo desde cualquier lugar, no solamente desde donde está guardado.**