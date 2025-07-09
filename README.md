# ⚽ Football Fan Survey Form

## 📝 Descripción del Proyecto

Este proyecto es un **formulario de encuesta interactivo** diseñado para la comunidad de aficionados al fútbol. Construido como un proyecto requerido para obtener la certificación en **Responsive Web Design de freeCodeCamp**, esta aplicación web permite a los usuarios compartir sus preferencias y opiniones sobre temas relacionados con el fútbol, como equipos favoritos y sugerencias para mejorar la experiencia futbolística. Destaca por su **diseño responsivo**, asegurando una experiencia óptima en cualquier dispositivo.

---

## ✨ Características Principales

- **Formulario Completo**: Recopila información básica (nombre, correo, edad), preferencias (equipo favorito, recomendación de la Champions League) y sugerencias (mejoras).
- **Validación HTML5**: Incluye validaciones integradas para campos obligatorios (nombre, email), formato de correo electrónico y rango de edad (entre 13 y 120 años).
- **Campos Variados**: Utiliza diferentes tipos de entrada como texto, email, números, desplegables (`<select>`), botones de radio y casillas de verificación.
- **Área de Comentarios**: Permite a los usuarios dejar comentarios adicionales o sugerencias.
- **Diseño Limpio y Centrado**: Presenta una interfaz de usuario ordenada, con el contenido principal centrado para una fácil interacción.
- **Adaptabilidad Móvil**: Optimizado para verse y funcionar bien tanto en dispositivos móviles como en pantallas de escritorio.

---

## 💻 Tecnologías Utilizadas

Este formulario está construido exclusivamente con las tecnologías fundamentales de la web, cumpliendo con los requisitos de la certificación:

- **HTML5**: Proporciona la estructura semántica y los elementos del formulario, asegurando accesibilidad y validaciones.
- **CSS3**: Se encarga del diseño visual, los estilos, la tipografía y la implementación del diseño responsivo para diferentes tamaños de pantalla.

---

## 📦 Instalación y Ejecución Local

Para ver y probar este formulario en tu máquina, sigue estos sencillos pasos:

1.  **Clona el repositorio:** Abre tu terminal o línea de comandos y ejecuta el siguiente comando para descargar el proyecto:
    ```bash
    git clone https://github.com/josecervera20/Formulario-de-Encuesta.git
    ```
2.  **Navega al directorio del proyecto:**
    ```bash
    cd Formulario-de-Encuesta
    ```
3.  **Abre el formulario en tu navegador:** Simplemente abre el archivo `index.html` directamente desde tu explorador de archivos. No necesitas ningún servidor local. También puedes usar comandos de terminal:
    ```bash
    open index.html   # Para usuarios de macOS
    start index.html  # Para usuarios de Windows
    xdg-open index.html # Para usuarios de Linux
    ```

---

## 🚀 Cómo Usar el Formulario

Una vez que el formulario esté abierto en tu navegador:

1.  **Información Personal**: Completa los campos "Name", "Email" y "Age" (edad entre 13 y 120 años). Estos campos son obligatorios.
2.  **Equipo Favorito**: Selecciona tu equipo de fútbol favorito de la lista desplegable.
3.  **Recomendación de Champions League**: Elige si recomendarías la Champions League usando los botones de radio.
4.  **Mejoras Sugeridas**: Selecciona una o varias opciones para indicar qué mejoras te gustaría ver.
5.  **Comentarios Adicionales**: Usa el área de texto para cualquier comentario o sugerencia extra.
6.  **Enviar Formulario**: Haz clic en el botón **"Submit"** para enviar tus respuestas. (Ten en cuenta que este es un formulario de demostración y los datos no se almacenarán).

---

## 📂 Estructura del Proyecto

El proyecto está organizado de manera sencilla y clara:

```
Formulario-de-Encuesta/
├── index.html       # El archivo principal que contiene la estructura del formulario.
├── styles.css       # La hoja de estilos que define la apariencia y responsividad del formulario.
└── README.md        # Este documento de información del proyecto.
```

---

## 🤝 Contribuciones

¡Las contribuciones son siempre bienvenidas\! Si tienes ideas para mejorar este formulario, encuentras algún error o quieres añadir nuevas funcionalidades que sigan los principios de freeCodeCamp, ¡no dudes en participar\!

1.  **Haz un Fork** del repositorio a tu cuenta de GitHub.
2.  **Crea una Rama**: Clona tu fork localmente y crea una nueva rama para tus cambios:
    ```bash
    git checkout -b feature/nombre-de-tu-mejora
    ```
    (o `bugfix/descripcion-del-bug` si es una corrección).
3.  **Realiza tus Cambios**: Implementa tus mejoras o correcciones. Asegúrate de probar bien tus cambios para que cumplan con los requisitos de freeCodeCamp.
4.  **Haz Commit**: Guarda tus cambios con un mensaje de commit claro y descriptivo (siguiendo la convención `feat:` para nuevas características o `fix:` para correcciones de errores):
    ```bash
    git commit -m 'feat: Añadir funcionalidad X'
    # o 'fix: Corregir el diseño responsivo en Y sección'
    ```
5.  **Sube tus Cambios**: Empuja tu rama a tu repositorio bifurcado en GitHub:
    ```bash
    git push origin feature/nombre-de-tu-mejora
    ```
6.  **Abre un Pull Request (PR)**: Finalmente, ve a GitHub y crea un Pull Request hacia el repositorio original. Describe detalladamente los cambios que realizaste y por qué son beneficiosos.

---

## 📄 Licencia

Este proyecto es de código abierto y se publica bajo la [Licencia MIT](LICENSE). Siéntete libre de usar, modificar y distribuir este código para tus propios proyectos.
