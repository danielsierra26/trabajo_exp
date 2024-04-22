# trabajo_exp

## String 

Un string en Java es una secuencia de caracteres, como palabras o frases, y se utiliza para almacenar y manipular texto. Aquí tienes algunos detalles sobre su uso:

## Manipulación de Cadenas:

- **Concatenación de cadenas** : La clase String proporciona el método concat() que permite unir dos cadenas en una sola. Por ejemplo, puedes combinar "Hola" y "mundo" para obtener "Hola mundo".

- **Obtener la longitud de una cadena** : El método length() de la clase String devuelve la cantidad de caracteres en una cadena. Por ejemplo, "Hola mundo".length() daría como resultado 10.

- **Comparar cadenas** : Utilizando el método equals(), puedes verificar si dos cadenas son iguales.

# Propiedades y Metodos

## Propiedades:

- **Inmutabilidad**: Los objetos String son inmutables, lo que significa que no se pueden modificar después de su creación. Cualquier operación que parezca modificar un String en realidad crea un nuevo objeto String.

- **Internamiento**: Java almacena internamente una sola copia de cada cadena literal en un pool de cadenas. Esto mejora la eficiencia y ahorra memoria.

## Metodos:

- charAt(int index): Devuelve el carácter en la posición especificada.

- length(): Devuelve la longitud de la cadena.

- concat(String str): Concatena la cadena actual con otra cadena.

- equals(Object obj): Compara dos cadenas para verificar si son iguales.

- compareTo(String anotherString): Compara lexicográficamente dos cadenas.

- substring(int beginIndex, int endIndex): Devuelve una subcadena de la cadena actual.

- toUpperCase() y toLowerCase(): Convierten la cadena a mayúsculas o minúsculas, respectivamente.

- startsWith(String prefix) y endsWith(String suffix): Verifican si la cadena comienza o termina con la subcadena especificada.

- indexOf(String str) y lastIndexOf(String str): Encuentran la posición de la primera o última ocurrencia de una subcadena.

- replace(char oldChar, char newChar): Reemplaza caracteres en la cadena.

- trim() : Elimina espacios en blanco al principio y al final de la cadena.


