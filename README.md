# clientes
Sistema Web S&H - Mantenimiento de Fachadas (Cliente)
¡Hola! Este es el proyecto web desarrollado para S&H, una empresa dedicada al mantenimiento, restauración y pintura de fachadas en Medellín, Antioquia. El objetivo principal fue crear una plataforma digital funcional que permitiera a los clientes conocer los servicios y gestionar sus cotizaciones de manera sencilla.
¿Cómo está construido el sitio?
Para que el proyecto fuera ordenado y escalable, dividimos el trabajo en tres pilares fundamentales:
1. La estructura (HTML)
Optamos por una estructura modular. Creamos cinco archivos HTML (index.html, somos.html, servicios.html, galeria.html y cotizacion.html). Cada página es independiente, pero todas comparten una base común para que la navegación sea fluida. 
2. El diseño visual (CSS)
Para que el sitio tuviera una identidad coherente, centralizamos todos los estilos en un archivo llamado style.css. 
•	Organización: Utilizamos Flexbox para la barra de navegación y CSS Grid para organizar la galería de fotos y el formulario, asegurando que el sitio se vea bien tanto en computadores como en celulares. 
•	Estilo: Elegimos una paleta de colores neutros y añadimos transiciones suaves en las imágenes para que la experiencia fuera moderna y dinámica. 
3. La parte interactiva (JavaScript)
Para añadir dinamismo, usamos un archivo llamado funcion.js. 
•	Lo que hace: Programamos una ventana de bienvenida (modal) que aparece automáticamente cuando el usuario entra al sitio mediante el evento window.onload. 
•	Funcionamiento: Es una lógica sencilla que controla la propiedad display del elemento, permitiendo al usuario cerrar el mensaje de bienvenida de forma intuitiva. 
El motor de cotizaciones
Para la parte comercial, integramos el formulario de la página cotizacion.html con Formspree. Esto nos permite recibir todos los datos que los clientes ingresan (nombre, servicios de interés, dirección y mensaje) directamente en el correo electrónico de la empresa, evitando la necesidad de un servidor backend complejo. 
Proceso de desarrollo
Para llegar a este resultado, seguimos estos pasos:
1.	Planificación: Definimos las secciones necesarias para cubrir toda la información de la empresa.
2.	Maquetación: Diseñamos la parte visual asegurando que el logo y los colores fueran coherentes en cada página. 
3.	Conexión: Vinculamos correctamente los archivos style.css y funcion.js en todos nuestros archivos HTML. 
4.	Despliegue: Publicamos el proyecto mediante GitHub Pages para que el sitio sea accesible públicamente desde cualquier dispositivo. 
