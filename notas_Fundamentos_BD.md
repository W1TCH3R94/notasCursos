![Data](https://static.platzi.com/media/achievements/badge-fundamentos-de-bases-de-datos-cc5eff2a-a7e0-4110-af5d-a47b628611da.png)
# Fundamentos de Bases de Datos

## ___Clase 1___

### **Historia de las bases de datos:**

Antiguamente, se usaban tablillas de arcilla, eran poco transportables y generaban problemas. Luego se utilizó el pergamino, era más portátil y liviano, pero era basado en materia animal o vegetal, se descomponía.

Los chinos llegaron a una revolución con el papel, tenía una gran ventaja de portabilidad, y no se degradaba tan rápido como el papiro o el pergamino. Muchos siglos después, específicamente en el siglo 20, con el microfilm, fue una tecnología que puede almacenar datos de manera infinita y vivir miles de años. Su desventaja es la modificación de información, es muy complejo.

Luego llegaron los medios digitales incluyen los discos duro, cd’s, etc. Se guardaba información en formato de bits y bytes. También llego la ***nube*** fue una gran revolución, tiene muchas ventajas frente a los otros medios de almacenamiento, gracias a su fácil acceso desde cualquier parte del mundo.

### **Tipos de bases de datos:**

1. Relacionales:

    * SQL server
    * MariaDB
    * Oracle
    * PostgreSQL
    * Mysql

2. No relacionales

    * Cassandra
    * Elasticsearch
    * Neo4j
    * MongoDB

*[Bases de datos relacionales vs. no relacionales: ¿qué es mejor?](https://aukera.es/blog/bases-de-datos-relacionales-vs-no-relacionales/)*

![Data](https://aukera.es/blog/imagenes/SQL-vs-NoSQL.jpg)

### Servicios:

* Autoadministrados: Son las bases de datos que instalamos en nuestro PC, nos encargamos de la parte de mantenimiento, updates, etc.

* Administrados: No lo llevamos nosotros, los ofrecen las compañías de nubes como Amazon.
___

## ___Clase 2___

### **Historia de las RDB(Bases de Datos Relacionales):**

Las bases de datos surgen de la necesidad de conservar la información más allá de lo que existe en la memoria RAM. Algunas bases de datos iniciales fueron basadas en archivos eran datos guardados en texto plano, fáciles de guardar, pero muy difíciles de consultar y por la necesidad de mejorar esto nacen las bases de datos relacionales. Su inventor Edgar Codd dejó ciertas reglas para asegurarse de que toda la filosofía de las bases de datos no se perdiera, estandarizando el proceso.

*[Las 12 reglas de Codd del modelo relacional.](https://www.mindmeister.com/es/1079684487/las-12-reglas-de-codd-del-modelo-relacional?fullscreen=1#)*
___

## ___Clase 3___

### **Entidades y atributos:**

Una ***entidad*** es algo similar a un objeto (programación orientada a objetos) y representa algo en el mundo real, incluso algo abstracto. Tienen atributos que son las cosas que los hacen ser una entidad y por convención se ponen en plural, para representarlo gráficamente se encierra en un cuadrado.

**Entidades fuertes:** son entidades que pueden sobrevivir por sí solas.

**Entidades débiles:** no pueden existir sin una entidad fuerte y se representan con un cuadrado con doble línea.

* Identidades débiles por identidad: no se diferencian entre sí más que por la clave de su identidad fuerte.

* Identidades débiles por existencia: se le da su propio ID para diferenciarse de la entidad fuerte.

***Atributo:*** Las entidades poseen atributos, estos se ligan a la entidad y se representan con un círculo.

* Atributos multivaluado: Significa que es un atributo que tiene múltiples valores; Se representan encerrándolos en un doble círculo.

* Atributo compuesto: Se puede dividir en subpartes es decir, de él salen otros atributos.

* Atributo especial o derivados: Su valor se puede obtener a partir de valores de otros atributos. Se encierra en un óvalo punteado.

    * Los atributos llave tienen características o propiedades únicas de la entidad, lo que lo diferencia de los demás. Existen:

        * Llave natural: son inherentes al objeto como el número de serie.

        * Llave artificial: No son partes de la entidad y se les asignan de manera arbitraria para facilitar el manejo de la información.

![Data](https://static.platzi.com/media/user_upload/ENTIDAD%20LAPTOPS-4910405e-b261-44c6-9193-a68d85a92541.jpg)

*[Modelo entidad - relación ](https://www.youtube.com/watch?v=l5PDQtUVye8 "MODELO ENTIDAD - RELACIÓN (CONCEPTOS BÁSICOS)")*

___

## ___Clase 4___

### **:**