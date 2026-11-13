# Undefined y Null


- undefined: Es una variable que aun no tiene valor asignado.
- null: Es una variable que intencionalmente se estableció sin ningún valor. 
        typeof null da "object", pero es un error histórico de JS que no cambiaron para no romper programas viejos.


# Object, Symbol y BigInt


- Un Object es una coleción de pares clave-valor. Son buenos para agrupar info que se relaciona

{
    name: "Gino",
    age: 23
};


- Un Symbol es un valor en JS que siempre es único y no se puede cambiar.

Symbol('mySymbol');


- BigInt se utiliza para los números enorme que se pasan del límite del tipo Number: Se agrega esa "n" al final

1234567890123456789012345678901234567890n;