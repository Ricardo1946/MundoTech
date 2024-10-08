CSS
Una declaracion de CSS es un bloque que especifica el conjunto de estilos que se añadiran
a un elemento HTML. su estructura contiene lo siguiente:

    - Selector: Define el elemento o conjunto de elementos a los cuales se añadiran los estilos
    - Propiedad: Es el nombre de estilo de CSS
    - Valor: es el valor que omara la propiedad. 


    
    */ ESTE ES UN COMENTARIO DE VARIAS LINEAS */
    
    /*
    Este es un comentario de varias LINEAS
    */


    propiedades iniciales de CSS

    Antes de empezar con CSS utilizaremos alguna propiedades de CSS

    - Color: establece el color del texto de un elemento.
    - background-color : Establece un color de fondo del elemento
    - font-size: establece el tamaño de la fuente.
    - width: establece la anchura
    - height: Establece la altura de un elemento


    Medidas iniciales 
    
    - PX: ESTABLECE UNA LONGITUD DE PIXELES
    - %: ESTABLECE UN PORCENTAJ CON RESPECTO A UNA MEDIDA BASE.


    selector {
     /* Estilos*/
     }

    - de tipo :  div {...}
    - de clase : elemento {.....}
    - de id : #id-del-elemento
    - de atributo : a[href =".."{...}
    - universal : *{....}

    1. Selector de tipo
    Seleciones todos los elementos que coincidan con el nombre
    de la etiqueta HTML

        div {
            /* Todos los div en el documento */
        }
    Background == es un atajo para definir los valores individuales del fondo en una regla de CSS

    2. Selector de clase

    Selecciona  todos los elementos que coincidan con las etiquetas HTML que contengan el atributo class

     <!--archivo HTML>
     <div clase "card"> Soy un carta </div>

     Para seleccionar estos elementos, se empieza por un punto .
     y seguido el valor exacto del atributo  class de la etiqueta 
     . Puede ser cualquier valor que deseas colocar.
        
        /* archivos CSS */
        .card {
            /* Todas las etiquetas  con la clase "card" */
        }

        <!--archivo HTML-->
        <div class="card card1"> Soy una carta </div>
        <div class="card card2"> Soy una carta </div>
        .card {
        /* Todas las etiquetas con la clase "card" */
        }

.card1 {
    /* Todas las etiquetas con la clase "card1" */
}

.card2 {
    /* Todas las etiquetas con la clase "card2" */
}
    3. Selector de identificador único (id)
    Selecciona el único elemento que coincida con la etiqueta HTML que contenga el atributo id. Solo puede existir un valor id para todo el documento.

    <!--archivo HTML-->
    <button id="eliminar"> Eliminar  </button>
    Para seleccionar el elemento, se empieza por el símbolo de hashtag # y seguido el valor exacto del atributo id de la etiqueta. Puede ser cualquier valor que desees colocar.

    /* archivo CSS */
    #eliminar {
    /* La única etiqueta con el id "eliminar" */
}
    4. Selector de atributo
Selecciona los elementos que coincidan con la etiqueta HTML que contenga el atributo y valor especificado.

    <!--archivo HTML-->
    <a href="https://platzi.com"> Ir a Platzi </a>
    Para seleccionar los elementos, se empieza por el nombre de la etiqueta, seguido de corchetes [] que contiene el atributo y valor especificado.

    /* archivo CSS */
    a[href=""https://platzi.com"] {
    /* Todas las etiquetas <a> con una propiedad href con valor "https://platzi.com" */
}

    5. Selector universal
    Selecciona todos los elementos del documento mediante un asterisco *.

    * {
    /* Todos los elementos */
    }

