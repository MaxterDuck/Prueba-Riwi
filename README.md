# Prueba-Riwi
Aqui esta mi prueba de riwi de el modulo 2 
Tomas David Restrepo Osorio 
Clan: Linus
Correo: Trestrepoo13@gmail.com
Ti: 1022147805

🧠 Estructura General
HTML5 con lenguaje en español (lang="es").
Incluye CSS externo para estilos (style.css).
Diseño responsivo (adaptable a móvil).

🧭 Header / Navegación
Título: "My presentation".
Botón hamburguesa para menú móvil.
Menú con enlaces a secciones: About me, Projects, Contacto.

🧑‍💻 Main / Contenido Principal
About Me
Imagen enlazada a Instagram.
Presentación personal y cita inspiradora.
Botón que enlaza a Projects.


Projects
Muestra tres proyectos:
Dos en Python (Inventory, Ratings management).
Uno en CSS (Ninja).
Cada uno con imagen, título y enlace a GitHub.

More about me
Explica aspiraciones profesionales y pasión por la programación.

Contacto
Formulario con campos: nombre, email, servicio a contratar.
Botón para enviar.

🔚 Footer
Texto de derechos de autor con el nombre del creador.

🧩 Script
JavaScript simple para mostrar u ocultar el menú en móviles al hacer clic en el botón.

🎨 Resumen del CSS

🔹 1. Variables Globales (:root)
Define colores y tipografía reutilizables:

--color-primario: gris oscuro (#656565)
--color-secundario: gris claro (#868686)
--color-fondo: blanco
--fuente-principal: Segoe UI
🔹 2. Estilos Generales
Elimina márgenes (body { margin: 0; })
Usa la fuente global y fondo blanco.
Imágenes adaptativas, centradas, sin desbordes laterales.
🔹 3. Imagen de perfil
.imageprofile:

Pequeña, flotando a la derecha, bordeada, con hover que aumenta su tamaño.
🔹 4. Encabezado y Navegación
Fijo en la parte superior (position: sticky).
.navbar: flexbox para alinear logo y menú.
.nav-links: enlaces en horizontal, blancos.
.menu-toggle: oculto por defecto, aparece en móvil.
🔹 5. Sección "About Me"
Fondo blanco, texto centrado, padding amplio.
Usa clase .aboutme (⚠️ Recuerda corregir el ID en el HTML).
🔹 6. Botón (.btn)
Estilo general reutilizable: color, padding, bordes redondeados.
Cambia de color y muestra sombra al pasar el mouse.
🔹 7. Proyectos
.projects: se organizan con flexbox.
.categoria: separa tipos de proyecto (Python, HTML).
.project: tarjetas individuales con hover animado.
🔹 8. Secciones: "MoreMe" y "Contacto"
Centradas, con padding.
.MoreMe: bordeado.
form: formulario estilizado, con separación y borde redondeado.
🔹 9. Enlaces (a)
Con hover cambian de color y se agrandan.
🔹 10. Pie de página
Color de fondo gris oscuro, texto blanco centrado.
📱 Responsive Design

Se adapta según el tamaño de pantalla:
🖥️ Max 1024px

Reduce márgenes y tamaño de imagen/proyectos.
📱 Max 768px

.projects en columna.
Muestra el botón hamburguesa.
El menú se despliega con .nav-links.active.
📱 Max 480px

Reduce padding y tamaño de fuente.
.project ocupa 90% del ancho.
