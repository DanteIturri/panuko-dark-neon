# Panuko Dark Neon

Panuko Dark Neon es un tema oscuro y vibrante diseñado para Visual Studio Code. Este tema utiliza colores neón llamativos para resaltar diferentes elementos del código, mejorando la legibilidad y la experiencia de desarrollo.

## Estructura del Tema

El archivo principal del tema es `panuko-theme.json`, que contiene dos secciones principales:

1. **`colors`**: Define los colores generales de la interfaz de usuario de Visual Studio Code.
2. **`tokenColors`**: Especifica los colores y estilos para los diferentes elementos del código fuente.

A continuación, se detalla cada sección:

### Sección `colors`

Esta sección define los colores de la interfaz de usuario, como el fondo del editor, el color del cursor, y los colores de las barras de herramientas. Aquí hay una descripción de las claves más importantes:

- **`editor.background`**: Color de fondo del editor. En este tema, es `#0A0A0F` (un tono oscuro).
- **`editor.foreground`**: Color del texto principal en el editor, definido como blanco (`#FFFFFF`).
- **`editor.lineHighlightBackground`**: Color de fondo para resaltar la línea actual, configurado como `#1A1A1A`.
- **`editor.selectionBackground`**: Color de fondo para las selecciones de texto, con un efecto translúcido (`rgba(180, 0, 255, 0.3)`).
- **`editorCursor.foreground`**: Color del cursor, definido como un azul neón (`#00C8FF`).
- **`statusBar.background`**: Color de fondo de la barra de estado, configurado como `#0A0A0F`.
- **`button.background`**: Color de fondo de los botones, definido como un púrpura neón (`#B400FF`).

### Sección `tokenColors`

Esta sección define los colores y estilos para los diferentes elementos del código fuente. Cada entrada tiene:

- **`scope`**: Especifica los elementos del código a los que se aplica el estilo.
- **`settings`**: Define el color y el estilo (como cursiva o negrita).

#### Ejemplos de Configuraciones

- **Palabras clave y almacenamiento (`keyword`, `storage`)**:
  ```json
  {
    "scope": ["keyword", "storage"],
    "settings": {
      "foreground": "#96FF32"
    }
  }
  ```
  Las palabras clave y los elementos de almacenamiento se muestran en verde neón (`#96FF32`).

- **Cadenas de texto (`string`)**:
  ```json
  {
    "scope": ["string"],
    "settings": {
      "foreground": "#FF41B4"
    }
  }
  ```
  Las cadenas de texto se muestran en rosa neón (`#FF41B4`).

- **Variables globales (`variable.other.global`)**:
  ```json
  {
    "scope": ["variable.other.global"],
    "settings": {
      "foreground": "#FF6400",
      "fontStyle": "italic"
    }
  }
  ```
  Las variables globales se muestran en naranja (`#FF6400`) y en cursiva.

- **Funciones (`entity.name.function`, `support.function`)**:
  ```json
  {
    "scope": ["entity.name.function", "support.function"],
    "settings": {
      "foreground": "#00C8FF"
    }
  }
  ```
  Los nombres de las funciones se muestran en azul neón (`#00C8FF`).

- **Comentarios (`comment`, `comment.line`)**:
  ```json
  {
    "scope": ["comment", "comment.line"],
    "settings": {
      "foreground": "#00FFFF",
      "fontStyle": "italic"
    }
  }
  ```
  Los comentarios se muestran en cian (`#00FFFF`) y en cursiva.

### Personalización

Puedes personalizar este tema editando el archivo `panuko-theme.json`. Cambia los valores de `foreground` o `fontStyle` para ajustar los colores y estilos según tus preferencias.

## Instalación

1. Descarga el archivo `.vsix` del tema.
2. Abre Visual Studio Code.
3. Ve a la paleta de comandos (`Ctrl+Shift+P` o `Cmd+Shift+P` en macOS) y selecciona `Extensions: Install from VSIX...`.
4. Selecciona el archivo `panuko-dark-neon-0.0.1.vsix`.
5. Activa el tema desde la configuración de temas.

## Licencia

Este tema está disponible bajo la licencia especificada en el archivo `LICENSE.md`.

---

¡Disfruta de Panuko Dark Neon y haz que tu código brille con estilo!
