# Portafolioo
# Propósito de la página
El objetivo principal de este sitio web es servir como portafolio profesional para estudiantes de ingeniería de software. Está diseñado para presentar de manera clara y organizada el perfil, los proyectos y la información de contacto, asegurando que el contenido sea accesible para cualquier usuario, incluyendo aquellos que utilizan tecnologías asistivas.

# Estructura Semántica (HTML5)
He utilizado etiquetas semánticas de HTML5 para proporcionar significado al contenido y mejorar el SEO técnico:

*header*: Contiene el título principal y la presentación del autor.

*nav*: Define el menú de navegación principal del sitio.
  
*main*: Encapsula el contenido central y único de la página.
  
*section*: Divide el contenido en bloques temáticos (Perfil, Proyectos, Contacto).
  
*article*: Utilizado para el detalle de proyectos individuales, indicando que es contenido independiente.
  
*footer*: Contiene los créditos y la información de validación.

# Accesibilidad Web (WCAG)
Para cumplir con los criterios de accesibilidad, implementé lo siguiente:

*Atributos ARIA*: Se usó aria-label en la navegación y botones para dar contexto a lectores de pantalla.

*Contraste de Color*: Se seleccionó una paleta de colores (Azul marino sobre gris claro/blanco) que garantiza una legibilidad óptima.

*Formularios Accesibles*: Cada campo de entrada (input) está vinculado a un <label> mediante el atributo id, facilitando la interacción.

*Imagen Accesible*: La ilustración del computador (SVG) incluye un role="img" y una descripción detallada en aria-label para que usuarios con discapacidad visual comprendan lo que se muestra.

*Navegación por teclado*: Se añadieron estilos de :focus para asegurar que un usuario pueda navegar por todo el sitio usando únicamente la tecla TAB.

# Instrucciones de Visualización
Descargue el archivo index.html.
Ábralo en cualquier navegador (Chrome, Firefox, Edge).
No requiere archivos externos de imagen, ya que los gráficos están integrados mediante código SVG.
