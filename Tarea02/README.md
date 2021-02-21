# DIW / 
Curso Diseño Interfaces Web / 
Estudiante y Autor: Pedro.J / 
Calificación: 6,25. / 
Observaciones: 
    Pautas
    -Indicación textual del principio, pauta y criterio de éxito. No se indica el Principio, pauta y criterio de éxito. En este caso sería: Principio: Comprensible, Pauta: Legible, Criterio de éxito: Idioma de la página.
    Un problema
    -Indicación textual del principio, pauta y criterio de éxito. No se indica el Principio, pauta y criterio de éxito. En este caso sería: Principio: Robusto, Pauta: Compatible, Criterio de éxito: Procesamiento.
    Revisión manual
    -Indicación textual del principio, pauta y criterio de éxito. No se indica el Principio, pauta y criterio de éxito.
    Error2. 
    -“El primer enlace de la página no lleva al contenido principal de la página”. Este error indica que el primer elemento “a” de la página, es decir, el primer enlace, debería llevarnos al contenido fundamental de nuestra página. ¿Cuál es el contenido principal de nuestra página?. Si te fijas bien en el código, hay un contenedor (div) cuyo identificador es “main”, lo cual nos hace pensar que es ese contenedor el que incluye el contenido principal de la página. ¿Cómo hacemos que el primer enlace nos lleve a ese contenedor?, pues colocando en el atributo “href” del enlace el valor del identificador del contenedor principal (precedido del símbolo # que indica que es un enlace interno o ancla). Quedaría así: <a href=”#main”> ……….. </a>
    Propuesta de solución. No es correcto.
    Implementación de solución. No es correcto.
    Captura del error resuelto. No es correcto.

//************************************************************************************************************
                                               TAREA 02
************************************************************************************************************//

//************************ Unidad 2. Accesibilidad en la web. ***********************************//
Enunciado
El objetivo de esta tarea es probar el funcionamiento de varias herramientas que nos permiten evaluar de forma automática los estándares de accesibilidad de un sitio web.

Cuando trabajamos en accesibilidad web es importante tener como referencia el sitio del W3C sobre accesibilidad. En concreto, utilizaremos la guía rápida donde se establecen los diferentes principios, pautas, criterios de éxito y técnicas asociadas. Éste es el enlace (está referenciado en los contenidos de la unidad).

Utilizaremos TAW y eXaminator.

1. TAW: Es una herramienta que permite analizar la accesibilidad de un sitio web.
Sitio web: www.tawdis.net

Accede al sitio y en las "opciones" selecciona el nivel de análisis A. (Aunque indica que analizará HTML, CSS y JS, realmente lo hace para HTML y CSS).

Introduce la dirección del sitio Web a analizar que desees, procurando que no sea un sitio demasiado extenso.

La herramienta nos mostrará los resultados del análisis del siguiente modo:

Un resumen al inicio de la página en el que se exponen los problemas, advertencias y cuestiones no verificadas de los criterios de éxito para cada uno de los principios de accesibilidad. Los problemas indican que se deben realizar correcciones. Las advertencias que es necesaria una revisión manual. Las cuestiones no verificadas indican que se hace necesaria una comprobación totalmente manual. Además, nos ofrece la posibilidad de recibir el informe vía email.
Un detalle al final de la página donde se especifica para cada principio de accesibilidad qué pauta de accesibilidad y qué criterios de éxito presenta algún problema, advertencia o no ha podido verificarse.

SE PIDE:

Realiza una captura de pantalla del resumen resultante del análisis.
Envíate el informe al email y aportarlo como parte de la tarea.
En los principios de accesibilidad, selecciona:
Una PAUTA donde no se hayan encontrado problemas.
Otra donde se produzca un problema.
Otra donde se requiera revisión manual.
Otra que sea imposible realizar la comprobación automática.

//**************Para cada uno de los casos:*******************//

Haz una captura de pantalla donde se visualice la pauta y el problema concreto. 
Debes indicar textualmente el principio, la pauta y el criterio de éxito concreto.
Explicar brevemente qué problema se ha producido.
Proponer una solución al mismo.




2. eXaminator es otra herramienta que permite revisar la accesibilidad de una página web. A diferencia de TAW, esta herramienta permite evaluar páginas locales que tenemos alojados en nuestro equipo. Para ello tendremos que seleccionar la pestaña Archivo en la página principal de eXaminator.

Sitio web: http://examinator.net/

Tras pulsar en Aceptar, eXaminator nos ofrece los resultados de 13 pruebas, clasificadas como Excelente, Regular y Mal. En el apartado Tablero Se muestra un resumen de las pruebas realizadas, la nota obtenida en cada una de ellas, su ponderación y la puntuación ponderada obtenida.

SE PIDE:

Revisar con eXaminator la página index.html. 
Teniendo en cuenta los resultados, habrá que modificar el html original para eliminar al menos DOS de los errores detectados como Mal. Para ello, para cada uno de los dos errores que selecciones:
Haz una captura de pantalla donde se observe el error detectado en eXaminator.
Comenta la solución que propones y aplícala modificando el código html original.
Una vez realizados los dos cambios en el html, súbelo de nuevo a eXaminator, vuelve a realizar la validación y haz una captura de pantalla donde se observe el resultado. Los errores corregidos no deben aparecer en esta nueva validación.
