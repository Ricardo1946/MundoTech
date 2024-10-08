Cuáles son las pseudoclases
Una pseudoclase define el estilo de un estado especial de un elemento.

Índice de pseudo-clases estándar.
Sintaxis
selector : pseudoclase { 
    propiedad: valor;
}
:hover
Representa el estado en el cual el cursor está encima del elemento.

:active
Representa el estado de un elemento que no ha sido visitado.

:visited
Representa el estado de un elemento que ya ha sido visitado.

:not()
Representa el estado en el cual no coinciden los selectores que se indiquen.

:nth-child()
Representa el estado en el cual coinciden los hijos del elemento según el valor indicado.

Valores de palabras clave:

odd: los elementos hijos en posiciones impares.
even: los elementos hijos en posiciones pares.
Fórmula matemática: An+B donde A y B son números enteros.

Cuáles son los pseudoselementos
Un pseudoelemento define el estilo de una parte específica de un elemento.

Lista de pseudo-elementos.
Sintaxis
selector :: pseudo-elemento { 
    propiedad: valor;
}
::before
Sirve para agregar un contenido antes del elemento. El contenido es agregado mediante la propiedad content de CSS.

::after
Sirve para agregar un contenido después del elemento. El contenido es agregado mediante la propiedad content de CSS.

::first-letter
Sirve para añadir estilos a a la primera letra del texto de cualquier elemento.

