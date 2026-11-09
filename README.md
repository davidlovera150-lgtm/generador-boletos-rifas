Generador Profesional de Boletos y Rifas
Manual de usuario — Versión 1.0
Introducción
Este programa sirve para crear un archivo PDF con muchos boletos numerados de forma consecutiva. Cada boleto puede llevar una imagen de fondo (tu plantilla) y un número encima, en el lugar que tú elijas. También puedes ponerle prefijo, sufijo, cambiar el tipo de letra, el tamaño y el color.
El programa funciona en el navegador. No se sube nada a internet, todo se procesa en tu computadora. Solo la primera vez necesita conexión, porque descarga una librería para generar el PDF.
Qué necesitas para usarlo
•	Un navegador actualizado: Chrome, Edge, Firefox o Safari.
•	Conexión a internet la primera vez (después ya no es necesaria si guardas la librería).
•	Una imagen de fondo para los boletos (JPG, PNG, WEBP o BMP).
•	Opcionalmente, una impresora o un visor de PDF para imprimir.
Cómo abrir el programa
1.	Busca el archivo app_rifas.html en tu computadora.
2.	Haz doble clic sobre él. Se abrirá en tu navegador.
3.	Si no se abre, haz clic derecho, elige "Abrir con" y selecciona tu navegador.
Recomiendo crear un acceso directo en el escritorio si lo vas a usar seguido.
Cómo está organizado
El programa tiene cuatro pestañas en la parte de arriba. Conviene llenarlas en orden:
1.	Imagen y Área
2.	Rango y Texto
3.	Configuración PDF
4.	Generar y Previsualizar
Puedes ir y volver entre pestañas sin perder lo que ya escribiste.
 
Pestaña 1 — Imagen y Área
Aquí cargas la plantilla del boleto y marcas dónde va el número.
Cargar la imagen:
Haz clic en el botón para elegir archivo y selecciona tu imagen. Aparecerá en el panel de la derecha.
Marcar el área del número:
Tienes dos maneras.
La primera es arrastrando con el mouse. Haz clic sobre la imagen, mantén presionado y arrastra para dibujar un rectángulo. Al soltar, el área queda marcada con un borde turquesa.
La segunda es escribiendo los valores X1, Y1, X2, Y2 a mano y luego pulsando el botón "Aplicar Coordenadas".
Las coordenadas son en píxeles de la imagen original. X1 y Y1 son la esquina superior izquierda del área; X2 y Y2 son la esquina inferior derecha.
Un detalle importante: la imagen se estira para llenar todo el boleto, sin importar sus proporciones originales. Si tu plantilla no tiene la misma proporción que el boleto, se va a deformar un poco. Por eso conviene revisar la vista previa en la pestaña 4 antes de generar cientos de páginas.
Pestaña 2 — Rango y Texto
Aquí defines qué números se van a imprimir y cómo se ven.
Rango de números:
•	Número Inicial: el primero del rango. Por ejemplo, 1.
•	Número Final: el último. Por ejemplo, 500.
•	Paso: de cuánto en cuánto avanza. Normalmente 1.
•	Cantidad de Dígitos: cuántos ceros a la izquierda llevará. Si pones 3, el número 5 se convierte en 005.
•	Prefijo: texto antes del número. Por ejemplo, "RIFA-" o "A-".
•	Sufijo: texto después del número. Por ejemplo, "-VIP".
Un ejemplo: inicial 1, final 100, paso 1, dígitos 4, prefijo "A-". El resultado serían cien boletos que van del A-0001 al A-0100.
Estilo del texto:
•	Familia de fuente: eliges entre Arial, Times New Roman, Courier, Verdana, Georgia, Impact, Comic Sans, o una fuente propia.
•	Fuente personalizada: puedes cargar un archivo .ttf, .otf, .woff o .woff2. Cuando lo cargues, selecciona "CustomFont" en el desplegable.
•	Tamaño en puntos. Por defecto está en 72 puntos, que son como 2.5 centímetros de alto.
•	Color del texto: con el selector eliges el color del número.
•	Alineación horizontal: izquierda, centro o derecha.
•	Alineación vertical: arriba, medio o abajo.
•	La casilla "Encoger automáticamente" reduce el número si no cabe en el área. Nunca lo agranda.
Pestaña 3 — Configuración PDF
Aquí decides cómo se acomodan los boletos en la hoja.
Tamaño de hoja y márgenes:
•	Tamaño de hoja: A4, Oficio, Legal o Personalizado.
•	Si eliges Personalizado, aparecen los campos para escribir ancho y alto en centímetros.
•	Orientación: vertical u horizontal.
•	Márgenes superior, inferior, izquierdo y derecho, en centímetros.
Los valores que vienen por defecto son Oficio, vertical, con márgenes de 1 cm.
Medidas del boleto y cuadrícula:
•	Ancho y alto del boleto en centímetros.
•	Separación horizontal y vertical entre boletos, en milímetros.
•	Modo de cuadrícula: Automático (el programa calcula cuántos caben) o Manual (tú decides cuántas columnas y filas).
•	Casilla "Dibujar líneas de corte": pone un borde negro fino alrededor de cada boleto, útil para recortar.
•	Nombre del PDF: el nombre del archivo que se va a descargar.
Un consejo: si quieres boletos pegados uno al lado del otro para recortar con guillotina, deja las separaciones en 0. Si vas a recortar con tijera, dale 2 o 3 milímetros de separación para tener margen.
 
Pestaña 4 — Generar y Previsualizar
El resumen:
El cuadro verde te muestra todos los parámetros actuales: cuántos boletos hay en el rango, el tamaño de la hoja, el tamaño del boleto, cómo se distribuyen en la cuadrícula y cuántas páginas va a tener el PDF.
Si algo está mal configurado (por ejemplo, si los boletos no caben en la hoja), el resumen se pone rojo y explica el problema.
Previsualizar un boleto:
Antes de generar todo el PDF, puedes pulsar "Previsualizar Boleto" para ver cómo se ve el primero del rango. Sirve para confirmar que la imagen y el número se ven bien, que la posición es correcta, que el color contrasta, etc.
Generar el PDF:
Pulsa el botón "Generar PDF". Aparece una barra de progreso que avanza boleto a boleto. Al terminar, el archivo se descarga solo a tu carpeta de descargas con el nombre que hayas puesto.
Unos 100 boletos toman entre 15 y 30 segundos en una computadora normal. Si intentas generar más de 800, el programa te pide confirmación antes de continuar, porque puede tardar varios minutos y consumir bastante memoria.
Consejos prácticos
Para la plantilla: conviene que la imagen ya tenga tu logo, los colores y el diseño, y que deje una zona más o menos limpia donde vaya el número. Si el fondo detrás del número es muy cargado, cambia el color del texto a blanco o negro para que contraste.
Sobre las medidas: antes de imprimir 500 boletos, imprime una sola página de prueba. Verifica que el número cae donde debe, que se lee bien y que las líneas de corte coinciden con tu guillotina o tijera. Perder un minuto aquí te ahorra desperdiciar papel.
Sobre el texto: empieza con tamaño 72 y ajusta mirando la previsualización. Para boletos pequeños (menos de 3 cm de alto), usa números de 3 o 4 dígitos con un prefijo corto.
Para imprimir: papel de 120 a 150 gramos va bien para boletos que se venden o se reparten. Activa la calidad alta en el diálogo de impresión.
Problemas comunes
La página se ve en blanco o no carga nada.
Revisa que tengas internet la primera vez, porque se necesita descargar la librería jsPDF. Si ya la tienes cargada, recarga con Ctrl+F5 (en Windows) o Cmd+Shift+R (en Mac). Prueba también en otro navegador.
Dice "No se pudo cargar jsPDF".
No hay conexión o el servidor está bloqueado. Si necesitas trabajar sin internet, descarga el archivo jspdf.umd.min.js desde cdnjs.cloudflare.com, colócalo en la misma carpeta que el HTML y cambia la línea que empieza con <script src="https://... por <script src="jspdf.umd.min.js">.
Dice "Los boletos no caben en la hoja".
Reduce el tamaño del boleto o los márgenes. Cambia la orientación a horizontal. O usa el modo manual de cuadrícula para poner menos columnas y filas.
El número no aparece en el boleto.
Verifica que el área marcada sea válida (que X2 sea mayor que X1 y Y2 mayor que Y1). Revisa que hayas puesto la cantidad de dígitos. Y fíjate que el color del texto no sea igual al del fondo.
El número se ve borroso en el PDF.
Sube la resolución de la imagen de fondo (mínimo 1600 píxeles de ancho). Aumenta el tamaño de la fuente. Usa fuentes .ttf que son escalables, no imágenes de texto.
El archivo PDF pesa demasiado.
Reduce la resolución de la plantilla antes de cargarla. O genera en partes: por ejemplo, 200 boletos por archivo y luego los unes.
La fuente personalizada no se aplica.
Espera a que aparezca el nombre del archivo con un check antes de generar. Verifica que sea un archivo de fuente real (.ttf, .otf, .woff, .woff2). Si no funciona, recarga la página y vuelve a cargar la fuente.
La aplicación va lenta con muchos boletos.
Es normal arriba de 500 boletos. Cierra otras pestañas del navegador. O divide el trabajo en archivos más pequeños.
Perdí mis datos al cerrar la pestaña.
El programa no guarda el estado entre sesiones. Si vas a cerrar, anota tus parámetros antes. Los PDFs que ya generaste sí se quedan en tu carpeta de descargas.

Lo que no hace
Para que no haya sorpresas, esto es lo que el programa no incluye:
•	No puedes elegir la carpeta de descarga. El navegador decide (normalmente Descargas).
•	No guarda perfiles ni configuraciones. Cada vez que abres empiezas de cero.
•	Solo maneja una imagen de fondo por PDF. No puedes mezclar plantillas en un mismo lote.
•	No hay vista previa de la página completa con todos los boletos acomodados. Solo se previsualiza un boleto individual.
•	La imagen siempre se estira para llenar el boleto. No respeta la proporción original.
Como ventaja, al no guardar nada, tus plantillas y rangos nunca salen de tu computadora.
Donaciones y contacto
Este programa lo hice de manera libre y gratuita. Si te sirvió para tu rifa, sorteo, negocio o evento, y quieres apoyar para que siga mejorándolo, puedes enviar una donación voluntaria al siguiente alias:
Alias: davidlovera150@gmail.com
Cualquier aporte, por pequeño que sea, se agradece de verdad. No es obligatorio, pero ayuda a mantener el proyecto vivo.
Si encuentras un error, tienes una sugerencia o quieres comentarme algo, escríbeme al mismo correo. Pon en el asunto "app_rifas" para que lo identifique rápido. Si es un error visual, mándame una captura y dime qué navegador y sistema operativo usaste.
Gracias por usar el programa. Ojalá te sirva para organizar tus rifas y sorteos de la manera más fácil posible.
Versión 1.0 — Última actualización: noviembre de 2026
Uso libre personal y comercial.
