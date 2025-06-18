# Sportboard App

Sportboard App es una aplicación web diseñada para gestionar y visualizar información relacionada con deportes, incluyendo partidos en vivo, próximos partidos, noticias recientes y estadísticas generales.

## Estructura del Proyecto

El proyecto está organizado en dos carpetas principales:

### Archivos y Carpetas

- **`.vscode/tasks.json`**: Configuración de tareas para Visual Studio Code.
- **`APE _Vista_login/`**: Contiene la vista principal y la página de inicio de sesión.
  - `index.html`: Página principal del dashboard.
  - `login.html`: Página de inicio de sesión.
  - `styles.css`: Estilos compartidos para las páginas.
  - `img/`: Imágenes utilizadas en las páginas.
    - `Barcelona.png`
    - `fondo-verde-abstracto.jpg`
    - `Manchester.jpg`
    - `Sport.png`

## Características

### Página Principal (`APE _Vista_login/index.html`)
- Barra de navegación con enlaces a secciones como Inicio, Partidos, Noticias, Equipos y Competiciones.
- Secciones destacadas:
  - **Partidos en vivo**: Muestra resultados de partidos recientes.
  - **Próximos partidos**: Lista de partidos programados.
  - **Noticias recientes**: Últimas noticias deportivas.
  - **Estadísticas generales**: Información resumida de goles, equipos activos y jornadas jugadas.

### Página de Inicio de Sesión (`APE _Vista_login/login.html`)
- Formulario para iniciar sesión con campos de correo electrónico y contraseña.
- Función para mostrar/ocultar la contraseña.
- Opción de "Recuérdame" y enlace para recuperar contraseña.
- Enlace para registrarse si no se tiene una cuenta.

## Configuración del Entorno

### Requisitos
- Navegador web moderno.
- Visual Studio Code (opcional, para desarrollo).

### Ejecución
1. Abre el archivo `APE _Vista_login/login.html` en tu navegador para acceder a la página de inicio de sesión.
2. Una vez autenticado, accede al archivo `APE _Vista_login/index.html` para visualizar el dashboard.

### Tarea en Visual Studio Code
El archivo `.vscode/tasks.json` incluye una tarea para abrir la página de inicio de sesión directamente:
```bash
start [login.html](http://_vscodecontentref_/0)
Estilos
Los estilos están definidos en el archivo APE _Vista_login/styles.css y son compartidos entre las páginas.
 Incluyen:
Diseño responsivo para dispositivos móviles.
Animaciones y sombras para mejorar la experiencia visual.
Imágenes
Las imágenes utilizadas en el proyecto están almacenadas en la carpeta APE _Vista_login/img/.

Futuras Mejoras
Completar la implementación de la carpeta sportboard-ui/.
Agregar funcionalidad de backend para autenticación y gestión de datos.
Mejorar la experiencia de usuario con más interactividad.
Créditos
Desarrollado por @Elias Poma
