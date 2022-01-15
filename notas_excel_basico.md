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

### **Consultas por buscarv y fijar valores:**

Use BUSCARV cuando necesite encontrar elementos en una tabla o un rango por fila. Por ejemplo, puede buscar el precio de una pieza de automóvil por el número de pieza o buscar el nombre de un empleado en función de su Id. de empleado.

En su forma más simple, la función BUSCARV indica lo siguiente:

=BUSCARV(Lo que desea buscar; dónde quiere buscarlo; el número de columna en el rango que contiene el valor a devolver; devuelve una Coincidencia exacta o Coincidencia aproximada, indicada como 1/TRUE o 0/FALSE).

*[Función BUSCARV](https://support.microsoft.com/es-es/office/funci%c3%b3n-buscarv-0bbc8083-26fe-4963-8ab8-93a18ad188a1?ui=es-es&rs=es-es&ad=es)*

#### **Fijar valores:**

Representado por el símbolo $, nos ayuda a fijar ya sea una columna o fila.
* Fijar Columna ($A): esto hace que la formula tome información de diferentes filas sin alterar la información de una columna en especial.
* Fijar Filas ($1): al contrario Fijar una fila hace que la formula tome información de diferentes columnas sin alterar la información de una fija específica.

### **Consultas por buscarh y 5 tipos de errores al hacer formulas:**

***BUSCARH*** se usa para realizar búsqueda en sentido horizontal (Fila), al contrario de BUSCARV que se usa para realizar búsquedas en sentido Vertical (columnas).

Errores típicos:
* #N/D.- Este error sucede cuando el valor que buscas no existe en el original.

* #¿NOMBRE?.- Excel indica que el nombre que estas usando para realizar una formula no existe o no es reconocido por el programa.

* #¡REF!.- Indica que la columna o celda donde realizas la búsqueda no existe.

* #¡DIV/0!.- Este error sucede cuando intentas dividir un numero cualquiera por “0” , ya que Excel no puede darte un resultado numérico.

* #¡VALOR!.- Este error sucede cuando intentas realizar operaciones matemáticas en celdas que no tienen valor numérico.

*[Función BUSCARH](https://support.microsoft.com/es-es/office/buscarh-funci%c3%b3n-buscarh-a3034eec-b719-4ba3-bb65-e1ad662ed95f?ui=es-es&rs=es-es&ad=es)*

