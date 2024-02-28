## CSS - SASS ##

1. Desventajas de CCS plano = CSS plano genera códigos excesivos y muchas veces difíciles de comprender.

2. ¿Qué es un preprocesador?    = Permite generar CSS a partir de la syntax única del preprocesador, añadira características que no existen en CSS puro. Estas características hacen la estructura de CSS más legible y fácil de mantener.

3. ¿Qué es SASS?    = SASS es un preprocesador CSS es una herramienta que nos permite permite tener una organización modular de los estilos, lo cual es vital para proyectos grandes y reduce el tiempo para crear y mantener el CSS.

    3.1 Compilación: Primero se debe instalar la extensión Live Sass Compiler seguido de ello crear un archivo.scss. en la parte inferior de OUTPUT se habilitara la opción WATCH SASS, al dar click ahí genera 2 archivos más, un .css y .css.map
    
    3.2 Variables: Para un desarrollo ordenado y rápido en el archivo .sccs se crea variables con el simbolo ($), con estas se puede crear varibales de colores, tamaños, efectos, entre otros
    
    3.3 Anidamiento: Para dar a estilos a varias etiquetas de una sección dento de la etiqueta su pone otra etiqueta con los elementos que se desea dar al CSS.
    
    3.4 Nesting: Cuando nombramos clases para dar estilos a la relación padre e hijo de las clases normalmente se hace .padre .hijo. En SASS para hace que el anidamiento sea corto se usa el simbolo (&) quedando & .hijo
    
    3.5 Modularidad: Separa CSS en pequeños trozos los estilos por bloques de un componente esto quiere decir que se creará archivos parciales los cuales despues se deben importar en .scss 