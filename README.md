# SSL-TP1

7.1 Investigación de diferentes opciones y funcionalidades del compilador

    Funcionalidades encontradas  para el compilador MinGW

    + -ansi: Intentará ser todo lo compatible con ANSI posible.
    + -traditional-cpp: Intentará hacer que el preprocesador se comporta como lo hacían los tradicionales.
    + -w: No se mostrarán mensajes de advertencia.
    +  -fexceptions Activar manejo de excepciones
    +-fshort-double
    + -fverbose-asm: El código ensamblador intermedio de los archivos tendrá información extra en forma de comentarios. Sólo es útil si son guardados (usando el comando en línea de comandos -S).
    + -pg: escribe información extra en el programa generado para usarla en el análisis del perfil. El análisis del perfil te permite saber qué cantidad de tiempo de ejecución utiliza tu programa, y así cuando lo optimices intentar optimizar más las partes que marcan las diferencias mayores. Esta opción debería desactivarse en la versión final / retail. Debe usarse sólo para construcciones para depuración.
    + -lobjc (Linker)
    + -g3 (Linker): Escribe información para depurar en los binarios generados. Esto permite depurarlo con el depurador integrado.
    + -nostdlib (Linker)
    + -mwindows (Linker): Obliga a GCC a construir una aplicación con interfaz gráfico GUI para Windows.
    + -fexpensive-optimizations
    + -O1, -O2, -O3: optimizaciones

7.2 Poner en uso lo encontrado en el punto anterior
    TODO

7.3 Secuencia de pasos
    1. Preprocesar
        b.para este paso se utilizó "gcc -E hello2.c -o hello2.i". En el archivo hello2.i se puede visualizar como esta declarada la libreria stdio y luego el código que esta escrito en hello2.c pero reemplazando el comentario por un espacio.
        d. TODO: Investigar e indicar la semántica de la primera línea. *************************
        e. 

7.4 Restricciones

7.5 Productos
