Un selector combinador es la unión de dos o más selectores básicos.

selector1 selector2 selector3 {
    /* Estilos */
}

    1. Combinador de descendientes
    Selecciona todos los elementos del selector de la derecha que son hijos del selector de la izquierda, independientemente de la profundidad. Estos selectores están separados por un espacio.

    padre hijos {
    /* Todos los hijos del padre */
    }

    div p{
    /* Todos los hijos <p> de <div>*/
    }

    .container img{
    /* Todos los hijos <img> de la clase "container"*/
    }
    
    2. Combinador de hijo directo
    Selecciona todos los elementos del selector de la derecha que son hijos directos del selector de la izquierda. Estos selectores están separados por >.

    padre > hijos_directos {
    /* Todos los hijos directos del padre */
    }

    div > p{
    /* Todos los hijos directos <p> de <div>*/
    }

    .container > img{
    /* Todos los hijos directos <img> de la clase "container"*/
    }       

    3. Combinador de elemento adyacente
    Selecciona todos los elementos del selector de la derecha que están adyacente al selector de la izquierda. Estos selectores están separados por +.

    elemento + adyacente {
    /* Elementos adyacentes */
    }

    div + p{
    /* Todos los <p> adyacentes a <div>*/
    }

    .container + img{
    /* Todos los <img> adyacentes a la clase "container"*/
    }
    Adyacente significa que comparten el mismo padre y está situado inmediatamente hacia abajo de otro elemento. Por ejemplo, en el siguiente código, <div> está adyacente a <h1> y <p> está adyacente a <div>. Sin embargo, <h1> no está adyacente a <div> y <div> no está adyacente a <p>.

    <!--archivo HTML -->
    <h1>Soy un título </h1>
    <div>Soy un div</div>
    <p>Soy un párrafo</p>

    4. Combinador general de hermanos
    Selecciona todos los elementos del selector de la derecha que son hermanos del selector de la izquierda. Estos selectores están separados por ~.

    elemento ~ hermanos {
    /* Elementos hermanos */
    }

    div ~ p{
    /* Todos los <p> hermanos de <div>*/
    }

    .container ~ img{
    /* Todos los <img> hermanos de la clase "container"*/
    }
    Hermanos significa que comparten el mismo padre y están situados hacia abajo de otro elemento. Por ejemplo, en el siguiente código, <div> y <p> son hermanos de <h1>, pero <h1> no es hermano de <div> y <p>.

    <!--archivo HTML -->
    <h1>Soy un título </h1>
    <div>Soy un div</div>
    <p>Soy un párrafo</p>

    