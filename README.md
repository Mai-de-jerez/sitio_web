# Página Web del Parque Juan Carlos I

Esta es una página web diseñada para brindar información sobre el **Parque Juan Carlos I**, destacando sus rutas de senderismo, monumentos, actividades y atractivos principales. La página permite a los visitantes obtener una experiencia virtual del parque, además de ofrecer datos útiles sobre su estructuración y cómo disfrutarlo.

## Estructura del Proyecto

- **index.html**: Archivo principal que contiene la estructura HTML de la página. Aquí se encuentran las secciones principales como la portada de la página, un video del parque, un atajo a Google maps, información sobre mí, una galería de las esculturas y las actividades deportivas que puedes hacer en el parque.

- **archivos HTML adicionales**:
  - **about.html**: Información sobre los encargados del parque.
  - **single.html**: contiene lugares emblemáticos del parque.
  - **contact.html**: para contactar con el parque.
  - **blog.html**: una galeria con las esculturas del parque más un video.
    

- **css/**: Carpeta que contiene los archivos de estilo para dar formato y diseño a la página web.
  - **style.css**: Estilos generales que definen el formato de texto, colores y disposición de los elementos.
  - **print.css**: Este archivo se utiliza generalmente para definir el formato cuando la página se imprime. Ajusta la apariencia de la página 
    para que sea más adecuada para imprimir (eliminando elementos innecesarios o ajustando el diseño a un formato de papel).
  - **ie.css**: Este archivo contiene reglas CSS específicas para Internet Explorer, ya que algunas versiones antiguas de este navegador 
    requieren estilos adicionales o específicos para corregir problemas de compatibilidad.

- **js/**: Carpeta con archivos JavaScript para la implementación de interactividad y funcionalidades avanzadas.
  - **global-plugind-min.js**: Archivo JavaScript que contiene complementos (plugins) globales utilizados en toda la página. Su propósito es 
    agregar funcionalidades adicionales como carruseles, efectos visuales, o interacciones con el usuario. Este archivo está minificado para 
    reducir su tamaño y mejorar el rendimiento.
  - **main.js**: Archivo JavaScript principal que contiene la lógica de la página web. Este archivo se utiliza para definir la interactividad y 
    el comportamiento de los elementos en la página, como menús, formularios y otras funcionalidades personalizadas. Se encarga de la ejecución 
    de tareas específicas para mejorar la experiencia del usuario.
  - **jquery.validate.min.js**: Archivo JavaScript que implementa la validación de formularios utilizando el plugin jQuery Validation. Asegura 
    que los datos ingresados en los formularios sean correctos (por ejemplo, que los campos obligatorios no estén vacíos, que las direcciones de      correo electrónico tengan el formato correcto, etc.).
  - **jquery-migrate-3.0.1.js**: Archivo JavaScript que proporciona compatibilidad entre versiones antiguas de jQuery y versiones más nuevas. Se      utiliza para garantizar que las funciones y métodos obsoletos sigan funcionando en jQuery 3.x, lo que permite que el código más antiguo no        deje de funcionar tras la actualización de la biblioteca jQuery.

- **img/**: Carpeta que almacena todas las imágenes utilizadas en el sitio web.
  - **iconos/**: Íconos utilizados para la interfaz de usuario (botones, menús, etc.).

Esta organización permite un desarrollo modular y fácil mantenimiento del proyecto, donde cada archivo y carpeta tiene una función específica dentro del sitio web.

## Tecnologías Utilizadas

- **HTML5**: Define la estructura y el contenido de la página web.
- **CSS3**: Utilizado para el diseño visual y la personalización de estilos, mejorando la apariencia y usabilidad de la página.
- **JavaScript** (opcional): Puede ser usado para agregar funcionalidades interactivas, aunque no es obligatorio para esta versión.

### Herramientas de Desarrollo

- **Visual Studio Code**: Editor de código utilizado para escribir y organizar los archivos del proyecto.
- **Extensiones CSS Reset**: Para garantizar la consistencia de los estilos en todos los navegadores.

## Estructura de la Página

1. **Encabezado**: Contiene el título de la página y un menú de navegación para facilitar el acceso a las distintas secciones.
2. **Sobre nosotros**: Breve descripción del parque, resaltando su historia y su esctructura.
3. **Lugares del parque**: Sección que muestra las zonas del oarque de interés.
4. **Galería de Imágenes**: Muestra fotografías de las esculturas del parque, así como de los lugares emblemáticos deñ mismo.
5. **Información de Contacto**: Detalles sobre cómo llegar al parque, enlaces de redes sociales y recomendaciones para los visitantes.

## Instalación y Uso

### Clonar el Repositorio

1. **Clonar el repositorio**: 
   Si aún no tienes el repositorio en tu máquina local, clónalo usando Git con el siguiente comando:

   ```bash
   git clone https://github.com/Mai-de-jerez/sitio_web.git

