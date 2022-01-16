![Data](https://static.platzi.com/media/achievements/badge-excel-basico-0d6a9f91-9a5f-4ad0-9642-a2e5665dc862.png)
# Excel Básico

## ___Comandos para agilizar excel:___

| **Necesidad**                              | **Comando**                    |
| ------------------------------------------ | :-------------------------:|
| Señalar una columna                        | `Ctrl + barra espaciadora`|
| Señalar una fila                           | `Shift + barra espaciadora`|
| Señalar una columna y eliminarla           | `Ctrl + barra espaciadora + signo menos`|
| Señalar una fila y eliminarla              | `Shift + barra espaciadora + signo menos`|
| Señalar una columna y añadir una nueva     | `Ctrl + barra espaciadora + signo mas`|
| Señalar una fila y añadir una nueva        | `Shift + barra espaciadora + signo mas`|
| Señalar una columna hasta donde haya datos | `Ctrl + shift + Flecha abajo`|
| Señalar una fila hasta donde haya datos    | `Ctrl + shift + Flecha derecha`|
| Guardar                                    | `Ctrl + g`|
| Copiar una celda                           | `Ctrl + c`|
| Cortar una celda                           | `Ctrl + x`|
| Pegar una celda                            | `Ctrl + v`|
| Formato Negrita de fuente                  | `Ctrl + n`|
| Formato cursiva de fuente                  | `Ctrl + k`|
| Formato subrayado de fuente                | `Ctrl + s`|
| Imprimir                                   | `Ctrl + p`|
| Ir al primer dato de una columna           | `Ctrl + flecha arriba`|
| Ir al primer dato de una fila              | `Ctrl + flecha izquierda`|
| Ir al último dato de una columna           | `Ctrl + flecha abajo`|
| Ir al último dato de una fila              | `Ctrl + flecha derecha`|

## **Consultas por buscarv y fijar valores:**

Use BUSCARV cuando necesite encontrar elementos en una tabla o un rango por fila. Por ejemplo, puede buscar el precio de una pieza de automóvil por el número de pieza o buscar el nombre de un empleado en función de su Id. de empleado.

En su forma más simple, la función BUSCARV indica lo siguiente:

=BUSCARV(Lo que desea buscar; dónde quiere buscarlo; el número de columna en el rango que contiene el valor a devolver; devuelve una Coincidencia exacta o Coincidencia aproximada, indicada como 1/TRUE o 0/FALSE).

*[Función BUSCARV](https://support.microsoft.com/es-es/office/funci%c3%b3n-buscarv-0bbc8083-26fe-4963-8ab8-93a18ad188a1?ui=es-es&rs=es-es&ad=es)*

### **Fijar valores:**

Representado por el símbolo $, nos ayuda a fijar ya sea una columna o fila.
* Fijar Columna ($A): esto hace que la formula tome información de diferentes filas sin alterar la información de una columna en especial.
* Fijar Filas ($1): al contrario Fijar una fila hace que la formula tome información de diferentes columnas sin alterar la información de una fija específica.

## **Consultas por buscarh y 5 tipos de errores al hacer formulas:**

***BUSCARH*** se usa para realizar búsqueda en sentido horizontal (Fila), al contrario de BUSCARV que se usa para realizar búsquedas en sentido Vertical (columnas).

Errores típicos:
* #N/D.- Este error sucede cuando el valor que buscas no existe en el original.

* #¿NOMBRE?.- Excel indica que el nombre que estas usando para realizar una formula no existe o no es reconocido por el programa.

* #¡REF!.- Indica que la columna o celda donde realizas la búsqueda no existe.

* #¡DIV/0!.- Este error sucede cuando intentas dividir un numero cualquiera por “0” , ya que Excel no puede darte un resultado numérico.

* #¡VALOR!.- Este error sucede cuando intentas realizar operaciones matemáticas en celdas que no tienen valor numérico.

*[Función BUSCARH](https://support.microsoft.com/es-es/office/buscarh-funci%c3%b3n-buscarh-a3034eec-b719-4ba3-bb65-e1ad662ed95f?ui=es-es&rs=es-es&ad=es)*

## **Formulas utiles:**

* Suma: La función suma agrega valores. Puede sumar valores individuales, referencias o rangos de celda o una combinación de las tres.

* Promedio: Devuelve el promedio (media aritmética) de los argumentos. Por ejemplo, si el intervalo A1:A20 contiene números, la fórmula =PROMEDIO(A1:A20) devuelve el promedio de dichos números.

* Contar: La función CONTAR cuenta la cantidad de celdas que contienen números y cuenta los números dentro de la lista de argumentos. Use la función CONTAR para obtener la cantidad de entradas en un campo de número de un rango o matriz de números.

* Sumar.si: Use la función sumar. Si para sumar los valores de un intervalo que cumplen los criterios especificados. Por ejemplo, supongamos que en una columna que contiene números, desea sumar solo los valores mayores que 5. Puede usar la fórmula siguiente: = sumar.Si (B2: B25, “>5”)

* Promedio.si: Devuelve el promedio (media aritmética) de todas las celdas de un rango que cumplen unos criterios determinados.

* Contar.si: Use CONTAR.SI, una de las funciones estadísticas, para contar el número de celdas que cumplen un criterio; por ejemplo, para contar el número de veces que una ciudad determinada aparece en una lista de clientes.

* Hoy: Devuelve el número de serie de la fecha actual. El número de serie es el código de fecha-hora que Excel usa para los cálculos de fecha y hora. Si el formato de celda es General antes de especificar la función, Excel cambia el formato de celda a Fecha. Si desea ver el número de serie, debe cambiar el formato de celda a General o Número.

* Mes: Devuelve el mes de una fecha representada por un número de serie. El mes se expresa como número entero comprendido entre 1 (enero) y 12 (diciembre).

* Espacios: Elimina los espacios del texto, excepto el espacio normal que se deja entre palabras. Use ESPACIOS en texto procedente de otras aplicaciones que pueda contener un espaciado irregular.

* Concatenar: La función CONCAT combina el texto de varios rangos o cadenas, pero no proporciona argumentos delimitadores o de IgnoreEmpty. CONCAT reemplaza la función concatenar. Sin embargo, la función CONCATENAR seguirá estando disponible por motivos de compatibilidad con versiones anteriores de Excel.

* Derecha: DERECHA devuelve el último carácter o caracteres de una cadena de texto, según el número de caracteres especificado. DERECHAB devuelve el último carácter o caracteres de una cadena de texto, según el número de bytes especificado.

* Izquierda: IZQUIERDA devuelve el primer carácter o caracteres de una cadena de texto, según el número de caracteres que especifique el usuario. IZQUIERDAB devuelve el primer carácter o caracteres de una cadena de texto, en función del número de bytes especificados.

* Redondear: La función REDONDEAR redondea un número a un número de decimales especificado.

* Promedio ponderado: La función SUMAPRODUCTO devuelve la suma de los productos de los rangos o matrices correspondientes. La operación predeterminada es la multiplicación, pero también es posible sumar, restar y dividir.

*[Esta información fue adaptada de la página de Microsoft donde puedes profundizar también en otras funciones.](https://support.microsoft.com/es-es/excel?ui=es-es&rs=es-es&ad=es)*
