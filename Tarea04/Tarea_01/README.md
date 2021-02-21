# DIW / 
Curso Diseño Interfaces Web / 
Estudiante y Autor: Pedro.J / 
Calificación: 8. / 
Observaciones: 
Uso correcto de etiquetas HTML
-Abuso de la etiqueta div, existiendo otras etiquetas semánticas de HTML que se ajustan mucho mejor a algunos de los contenidos del documento. Por ejemplo, para la cabecera en lugar de usar un div con identificador “cabecera”, lo ideal es usar la etiqueta “header”. Para la navegación lo mejor es usar la etiqueta “nav”. El uso de las etiquetas adecuadas es importante para que los buscadores puedan indexar mejor la página. Estas etiquetas son semánticas, es decir, tienen un significado importante para los buscadores.
En el placeholder del correo electrónico, para colocar la “@” con FontAwesome, debería haber usado el código “&#xF1fa” en lugar de poner la “@” de forma literal
Colores y tamaños
-Los bordes rojos del contenedor de imágenes y del menú izquierdo, sobran.
-En las imágenes, la regla “background-position: 50%;”, sobra.
-Los bordes del “chat” debían ser de 20px, no de 10px.
El selector “*.” No es correcto, en todo caso sería “*”, sin el punto a continuación.
Las reglas “.menu_nav” y “.menu_nav button”, son prácticamente idénticas. Me vi forzado a esto porque dentro de cada elemento de la lista “ul” coloqué elementos “button”.
El selector div[class="footer"] p, div[class="chat"] p Debería haberlo implementado como: div.footer p, div.chat p Pues a efectos de especificidad del selector es mayor la de una clase que la de un atributo y en mi solución se está usando la clase como si fuese un atributo normal (que no lo es).

//************************************************************************************************************
                                               TAREA 04
************************************************************************************************************//

//************************ Unidad 4. Hojas de estilo ***********************************//

Enunciado Tarea 1:
Esta tarea consiste en desarrollar un sitio Web con HTML y CSS, de forma que se parezca lo máximo posible al que se presenta:
Usa HTML5 y CSS3. Ten en cuenta los siguientes criterios:

Cabecera
Margen superior e inferior de 20px.
Ancho de 1000px.
Alto de 120px.
Logo:
Ancho de 200px.
Alto de 60px.
Tamaño de fuente: 50px.
Tipo letra: KaushanScript-Regular.ttf
Alineación vertical.
Redes sociales:
Tres iconos de FontAwesome.
Colocar a cada icono el correspondiente color.
Alto de 48px. El ancho será el que corresponda a dicha altura. Investiga cómo dar tamaños a iconos de FontAwesome.
Barra de navegación.
Margen superior e inferior de 20px.
Alto de 48px.
Ancho de 1000px.
Cinco botones con margen horizontal de 2px, cada uno:
Alto de 48px.
Ancho de 192px.
Tipo letra: sans-serif (color blanco).
Fondo: #6400ff
Fondo cuando pasa el ratón: #6400ff con opacidad (40 por ciento).
Tres contenedores con imágenes:
Alto de 192px.
Ancho de 1000px.
Margen superior e inferior de 20px.
Cada contenedor tiene:
Imagen:
Alto de 100px.
Ancho de 100px.
Forma redonda.
Título:
Tamaño fuente: 28px.
Tipo de fuente: KaushanScript-Regular.ttf
Párrafo:
Tamaño de fuente: 14px.
Tipo de fuente: sans-serif.
Márgenes de 10px.
Sección:
Márgenes superior e inferior de 20px.
Alto de 453px.
Ancho de 1000px.
Compuesta por:
Columna izquierda con 5 enlaces:
Ancho de 200px.
Alto de 453px.
Color de fondo: #aaa
Margen interior: 10px.
Margen horizontal de 2px.
Margen vertical de 10px.
Artículo (medio):
Ancho de 600px.
Alto de 453px.
Título:
Tamaño de fuente: 40px
Tipo de fuente: KaushanScript-Regular.ttf
Márgenes 20px.
Imagen
Tamaño: 300x200px.
Margen derecho 10px.
Párrafo:
Tamaño de fuente: 16px.
Tipo de fuente: sans-serif.
Alineación texto: justificado.
Margen vertical de 5px.
Margen derecho de 20px.
Margen izquierdo de 0px;
Columna a la derecha:
Ancho de 200px.
Alto de 453px.
Compuesto por:
Encabezado: INICIAR
Color del texto: #fff
Color de fondo: #6400ff
Ancho de 200px.
Alto de 50px.
Margen inferior: 5px.
Formulario:
Campo de tipo texto.
Campo de tipo contraseña.
Campo de tipo email.
Estos campos tienen:
Ancho de 176px.
Margen interno de 10px.
Margen vertical de 5px.
Margen horizontal de 0px.
Los iconos del placeholder deben ser Fontawesome. Investiga como añadirlos en el placeholder.
Botón de enviar
Ancho: 40 por ciento.
Color de fondo: #640064
Margen horizontal del 30 por ciento.
Pie de página:
Margen vertical 20px.
Ancho de 1000px.
Alto de 70px.
Fuente: sans-serif, color blanco.
Chat (DEBE ESTAR FIJO AL FINAL DE LA PÁGINA, de forma que si hago scroll se mueva):
Ancho de 200px.
Alto de 40px.
Esquinas superiores (derecha e izquierda) redondeadas 20px.
Posición fija y por encima de todos los elementos.
Margen derecho de 50px.
Texto: sans-serif, color blanco.
Icono con Fontawesome.
Color de fondo: #ff0064
Fondo cuando pasa el ratón: #6400ff
Otras consideraciones:

Las fuente KaushanScript-Regular.ttf debe ser incrustada localmente (se adjunta como recurso).
Debes utilizar Fontawesome versión 4.7.0 de forma local (no puedes utilizar CDN) para los iconos de redes sociales (facebook, twitter, youtube), para el marcador de posición (placeholder) de los campos de formulario, y para el botón de chat.
Puedes descargar FontAwesome del siguiente enlace: FontAwesome
Aquí puedes encontrar un listado de los iconos de esta versión de FontAwesome: Iconos
