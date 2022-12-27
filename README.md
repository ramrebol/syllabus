# syllabus

Mi versión en org-mode (emacs) y latex del syllabus de un curso de la Universidad de Concepción, versión 2022.

Como la institución sólo provee de la versión MS-Word del syllabus, comparto aquí mi versión para generar el syllabus de un curso en la Universidad de Concepción.

- syllabus.tex y syllabus.org es la versión minimal (el mismo ejemplo dado por la institución).

- syllabus_algebra.tex y syllabus_algebra.org es una versión para el curso de Álgebra y Trigonometría del segundo semestre del 2022.

- *.pdf son las salidas pdf de ambos archivo.


Los archivos *.tex están listos para compilar. Obviamente, también puedes editarlos como necesites.

Pero nota que los archivos LaTeX fueron generados usando org-mode de emacs (que si no lo conoces te recomiendo mirar de qué se trata), lo que hace que la generación del tex y pdf sea mucho más sencilla (incluso podemos saltarnos mirar el tex). Si usas emacs, puedes descargar los *.org y para generar el tex basta escribir los shorcuts

    C-x-e l-p

pero si sólo quieres usar los tex no es necesario saber nada sobre emacs y org-mode.

Notar que usar los archivos *.org tiene la ventaja de poder escribir tablas (por ejemplo, de la sección de la Planificación) en una forma más natural, usando C-c' (notar el apóstrofe luego del Control c).

BUG: El archivo tex es correcto, es decir, compila y genera el pdf sin problemas. Pero como la tabla en la sección Planificación ocupa muchas hojas, cuando generamos el tex a partir del archivo org los entornos tabular deben sustituirse por longtable, al menos el correspondiente a la sección Planificación, como puedes ver en los tex acá. Eso hará que las tablas grandes se distribuyan automáticamente en varias hojas.
