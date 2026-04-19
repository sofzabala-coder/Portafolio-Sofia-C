**SZ Studio** — Portafolio Personal
**Sofia Alejandra Cubillos Zabala**  
Lenguajes Digitales III · 2026


##  Estructura del proyecto


Portafolio-Sofia-C/
├── index.html        → Página principal (Home)
├── about.html        → Sobre mí
├── project.html      → Template de proyecto
├── README.md         → Este archivo
├── css/
│   ├── styles.css    → Estilos globales compartidos
│   ├── about.css     → Estilos exclusivos de about.html
│   └── portafolio.css   → Estilos exclusivos de portafolio.html


**Bitácora de desarrollo**

 **Estructura base**
- Creación del repositorio  en GitHub
- Definición de la paleta de colores del sitio:
  - Verde oscuro: `#115e58`
  - Crema: `#F5F5DC`
  - Verde menta: `#d7fcf0`
  - Azul acento: `#1582e8`
  - Fondo oscuro: `#1d1d1d`
- Configuración de la tipografía principal: **Montserrat** (Google Fonts)
- Creación del archivo `styles.css` con reset, variables base y estilos del header y footer compartidos entre las 3 páginas. Aparte la transcripción de codigos previos que tenia en Codepen.

---

### ✅ 11-04— Página Home (`index.html`)
- Mejora en la maquetación del **header** con navegación y botón de contacto con scroll suave
- La **sección hero**: layout flex con foto de perfil, texto de presentación, subtítulo animado y dos botones de acción
- Sección **About** con fondo oscuro y estadísticas 
- Sección **Skills** con barras de progreso usando CSS
- Sección **Portafolio** con grid de 3 columnas que enlaza al template de proyecto
- Sección **Contacto** con layout flex oscuro: info a la izquierda, formulario a la derecha
- Footer con logo, links de navegación y redes sociales


### ✅ 18-04 — Separación de estilos
- Corrección del `styles.css` original:
  - Se añadió el selector de reset `*, *::before, *::after`
  - Se reemplazaron selectores frágiles 
  - Se añadieron clases reutilizables
  - Se agregó bloque `@media` responsive 
- Creación de **`css/about.css`**: estilos exclusivos de `about.html` separados del CSS global
- Creación de **`css/project.css`**: estilos exclusivos de `project.html` separados del CSS global
- Cada página vincula solo los CSS que necesita. Para prevalecer los diseños que queria en cada uno sin mezclar.


### ✅  Página About (`about.html`)
- Hero con foto a la izquierda y texto a la derecha (estructura basada en referencia Figma)
- Sección de **Filosofía** con cita en blockquote y barra lateral decorativa
- Grid de **estadísticas** 2×2 debajo de la cita
- Sección **Technical Skills** con barras de progreso animadas
- Sección de **Contacto** en grid 2 columnas: datos + redes sociales a la izquierda, formulario a la derecha

---

### ✅ 16-04— Template de Proyecto (`project.html`)
- Botón `← Volver a proyectos` con animación de gap en hover
- Sección **Overview** en grid 2 columnas: descripción del proyecto y el desafío
- Sección **Proceso** con 6 pasos numerados sobre fondo oscuro; los números se iluminan en hover
- Sección **Herramientas** con pills circulares que invierten colores en hover
- **Galería** en grid asimétrico (2fr / 1fr) con efecto zoom y brillo al hover
- Sección **CTA final** con texto decorativo posicionado con `::before` y dos botones de acción
- Footer con navegación interna


## De lo que hice uso:
| HTML5 | Estructura semántica de las 3 páginas |
| CSS3 | Estilos, animaciones, transiciones y responsive |
| Google Fonts | Tipografía Montserrat |
| Git & GitHub | Control de versiones y despliegue |
| Figma | Referencia de diseño y prototipado |
| Codepen | Donde tenia mis codigos iniciales | link: https://codepen.io/SOFIA-ALEJANDRA-CUBILLOS-ZABALA/pen/emdNEPq 
https://codepen.io/SOFIA-ALEJANDRA-CUBILLOS-ZABALA/pen/gbMJJZG





##  Decisiones de diseño

- **Paleta bicolor**: el verde oscuro `#115e58` como color principal transmite seriedad y creatividad; el crema `#F5F5DC` como fondo da calidez y diferencia el sitio de portafolios genéricos con fondo blanco
- **Tipografía única**: Montserrat en sus diferentes estilos de grosor y tamaño que genera jerarquía visual clara sin necesitar una segunda fuente
- **Secciones alternadas**: los fondos oscuros (`#1d1d1d`) y claros (`#d7fcf0`, `#fff`) crean ritmo visual y guían el scroll del usuario
- **Animaciones con propósito**: las transiciones de hover y las barras de skill animadas enriquecen la experiencia sin distraer del contenido
- **CSS modular**: un archivo por página permite mantener el código limpio y escalar el proyecto fácilmente

---

##  Responsive

El sitio es adaptable a pantallas desde 360px. Los breakpoints principales son:

- `max-width: 900px` → navegación en columna, hero apilado, grids de 1 columna
- `max-width: 560px` → servicios en 1 columna, stats en 2 columnas

-- Este es el proyecto de portafolio 2026:)
