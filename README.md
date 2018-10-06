# PHP-OSYN-Libs
Clases y funciones PHP para diferentes usos.


***
**class.dineroaletras.php**

Convertir un número que equivale a moneda (precio de algún artículo) a su equivalente en palabras/letras/texto,
he perdido las referencias de orígen del archivo, pero no es de autoría propia, aún así considero relevante su 
publicación debido a su practicidad de uso.

Originalmente eran funciones separadas, las he encapsulado en una clase sencilla, su manera de invocarla es:

$variable_invoca_clase = new dineroaletras;

- echo $variable_invoca_clase->numeroaletras("4321"); /* Ejecutar numero entero */

- echo $variable_invoca_clase->numeroaletras("4321.56"); /* Ejecutar numero flotante */


**Restricciones:**
- No acepta decimales de más de 3 cifras.
- Los decimales equivalentes a 00 centavos, no los imprime.
***
