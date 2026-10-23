# Portafolio Académico - Brayneer Joseph Luis Soto

Portafolio web académico moderno, profesional y minimalista creado con HTML5, CSS3 y JavaScript puro.

## Características

- **Diseño moderno**: Fondo oscuro con detalles en azul y blanco
- **Responsive**: Adaptable a computadoras, tablets y celulares
- **Navegación**: Menú fijo con navegación entre secciones
- **Menú móvil**: Menú hamburguesa funcional
- **Animaciones suaves**: Efectos al pasar el cursor
- **Accesible**: Uso de etiquetas semánticas y atributos ARIA
- **Sin dependencias**: Solo HTML5, CSS3 y JavaScript puro

## Secciones

1. **Inicio** - Información personal y académica
2. **Sobre mí** - Presentación académica y objetivos profesionales
3. **Habilidades** - HTML, CSS, JavaScript, Python, Git, GitHub
4. **Proyectos** - Proyectos académicos, prácticas de laboratorio y trabajos universitarios
5. **Contacto** - Correo electrónico, GitHub y LinkedIn

## Datos

- **Estudiante:** Brayneer Joseph Luis Soto
- **Código Universitario:** 2231895533
- **Carrera:** Ingeniería de Sistemas
- **Curso:** Cloud computing y arquitecturas digitales
- **Docente:** Claudio Isaias Huancahuire Bravo
- **Fecha de Presentación:** 23 de octubre de 2026
- **Correo:** bluiss@autonoma.edu.pe

## Personalización

Para personalizar el portafolio:

1. **Habilidades**: Edita las tarjetas en `index.html` en la sección "Habilidades". Reemplaza `[POR COMPLETAR/EDITAR]` con el nivel y estado real (ej., "Intermedio", "En proceso").
2. **Proyectos**: Agrega tus proyectos reales en la sección "Proyectos". Reemplaza los placeholders con nombre, tipo, descripción y tecnologías.
3. **Contacto**: Agrega tus enlaces de GitHub y LinkedIn en la sección "Contacto". Reemplaza `[USUARIO_GITHUB]` y `[USUARIO_LINKEDIN]` con tus nombres de usuario reales.

## Cómo ejecutar localmente

### Opción 1: Abrir directamente
1. Descarga o clona este repositorio
2. Abre el archivo `index.html` en tu navegador web

### Opción 2: Servidor local (recomendado)
Si tienes Python instalado:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Luego abre `http://localhost:8000` en tu navegador.

Con Node.js (usando npx):

```bash
npx serve .
```

## Cómo publicar en GitHub Pages

1. **Crear repositorio en GitHub**
   - Ve a [github.com](https://github.com) e inicia sesión
   - Crea un nuevo repositorio con un nombre (ej., `portafolio` o `mi-portafolio`)
   - No inicialices con README, .gitignore o licencia

2. **Subir archivos al repositorio**
   ```bash
   git init
   git add .
   git commit -m "Inicial: Portafolio académico"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   git push -u origin main
   ```

3. **Configurar GitHub Pages**
   - Ve a tu repositorio en GitHub
   - Haz clic en "Settings" > "Pages" (en el menú lateral)
   - En "Source", selecciona "Deploy from a branch"
   - En "Branch", selecciona `main` y `/ (root)`
   - Haz clic en "Save"
   - Espera unos minutos, tu sitio estará disponible en `https://TU_USUARIO.github.io/TU_REPOSITORIO/`

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- Google Fonts (Inter)

## Estructura de archivos

```
portafolio/
├── index.html      # Estructura HTML
├── style.css       # Estilos y diseño responsive
├── script.js       # Funcionalidad JavaScript
└── README.md       # Este archivo
```

## Licencia

Este proyecto es de uso académico.
