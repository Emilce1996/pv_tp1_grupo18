# Trabajo Práctico Nº1 – HTML / CSS / Git / GitHub

## Integrantes del Grupo 18
- Cruz Alexander – [@usuarioGithub](https://github.com/usuarioGithub)
- Goyochea Kevin – [@usuarioGithub](https://github.com/usuarioGithub)
- Maidana Agustin Hugo Franco – [@usuarioGithub](https://github.com/usuarioGithub)
- Medina Brisa Lourdes – [@xLouux](https://github.com/usuarioGithub)
- Sivila Emilce Andrea – [@Emilce1996](https://github.com/Emilce1996)

### Descripción del proyecto
Este repositorio contiene el desarrollo del **Trabajo Práctico Nº1** de la materia *Programación Visual*.  
El objetivo fue construir un sitio web educativo utilizando **HTML y CSS**, aplicando buenas prácticas de organización y versionado con Git y GitHub.

### Estructura de las páginas
- **index.html**: Página principal con bienvenida, navegación, estadísticas y novedades.  
- **proyectos.html**: Explorador de proyectos, con filtros y listado en formato de tarjetas (imagen, título, descripción y enlace).  
- **detalle.html**: Página de detalle de un proyecto, mostrando encabezado, descripción, recursos y equipo.  
- **perfil.html**: Perfil de usuario con información personal (imagen, nombre y rol).  

### Breve descripcion de la construccion de las paginas html

- **detalle.html**: Dentro del <body>, en la parte del encabezado, se utilizó la etiqueta <h1> para el título del proyecto, y <p> para colocar la fecha de inicio del proyecto y sus respectivos autores. Posterior a eso se aplicó la etiqueta <main> como contenedor principal, mientras que para los subtítulos con mayor jerarquía se usaron <h2> y para el resto <h3>. 
El contenido se dividió en tres secciones con <section> (Objetivos, Recursos y Equipo).
Dentro de las secciones, se utilizó la etiqueta <article> para agrupar la información en cada sección, y la etiqueta <p> para los párrafos de texto. Para la lista de recursos, se usó una lista desordenada <ul> y etiquetas <li> para cada ítem. Cada recurso contiene dichos enlaces <a> con el atributo href para la dirección del archivo y el atributo target="_blank", que permitirá abrir los documentos en una nueva pestaña sin abandonar la página principal. 
Por último, en la sección del equipo se empleó un <table>, diferenciando encabezados (<th>) y datos (<td>).

### Estilos aplicados
- Se utilizaron las tres formas de CSS:
  - **Inline CSS**: aplicado en algunos encabezados para demostrar su uso.  
  - **Internal CSS**: pequeños bloques dentro del `<head>` de páginas específicas.  
  - **External CSS**: archivo central `css/styles.css` con la mayor parte de los estilos.  
- Uso de **Grid y Flexbox** para organizar el layout.  
- Variables CSS en `:root` para colores y tipografía.  
- Estados interactivos (`:hover`, `:focus`, `:active`) en botones y enlaces.  

## Tecnologías utilizadas
- HTML5  
- CSS3  
- Git & GitHub  

## Licencia
Este proyecto se publica bajo la licencia **MIT**, lo que permite su uso, copia y modificación siempre que se mantenga la autoría original.
