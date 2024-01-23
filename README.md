# SASS = Syntarically Awesome StyleSheet

__Autor__ : Laura López Alonso

***GitHub***: 

-Es un estándar en la industria.
-Compatible con muchos Frameworks.

## Ventajas

1. Mejor orden y estructura.
2. Tiene características que no existen en CSS.
3. Podemos incorporar CSS sin problema.
4. Menos código (SASS) -> ANIDACIÓN.

## Desventajas

1. Nueva sintáxis que aprender.
2. Se debe de compilar (NO ES NATIVO EN EL NAVEGADOR).
3. La anidación puede dar problemas.
4. Está en capa caída.

## Sintáxis de SASS

1. Variables (custom properties) -> :root {} (Lo mismo)

    ``$color : #e1e1e1;``

2. Anidación en SASS:

>div
>    display: flex
>    h1
>        margin-top: 10rem;
>    p
>        margin-top: 10rem;

3. EXTENSIONES

- .sass: (antiguo)
>.header
>    display: flex
>    .logo
>       margin-top: 10rem

- .scss: (moderno)

>.header{
>    display: flex;
>    .logo{
>        margin-top: 10rem;
>    }
>}

## SAS se compila -> .css (Node.js, webpack, Gulp) 

