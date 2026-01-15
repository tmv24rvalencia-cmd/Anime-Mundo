# 🎌 Anime-Mundo – Catálogo de Anime

Este proyecto es un sitio web personal para mostrar un catálogo organizado de animes, con menú desplegable de géneros, búsqueda avanzada y descripciones individuales.

---

## 📁 Estructura de Archivos

anime-mundo/
│
├── index.html → Página de inicio
├── anime.html → Página principal de Anime (con buscador y filtros)
├── contacto.html → Página de contacto
│
├── css/
│ └── style.css → Estilos globales (diseño tipo AnimeFLV / Amazon)
│
├── js/
│ └── script.js → Funcionalidad: búsqueda, filtros, modales de descripción
│
└── data/ → (opcional)
└── animes.json → Base de datos en JSON con metadatos de cada anime

> ✅ Solo 3 páginas HTML principales. Toda la navegación por categorías se gestiona desde el menú desplegable y la página `anime.html`.

---

## 🖥️ Barra de Navegación (en todas las páginas)

La barra superior incluye:

- **Inicio** → `index.html`  
- **Anime** → `anime.html`  

▼ Al pasar el cursor, se despliega un **menú de categorías (géneros)**:

Acción | Aventura | Comedia | Drama | Ecchi | Escolar | Fantasía | Histórico | Isekai | Josei | Mecha | Misterio | Música | Psicológico | Romance | Ciencia Ficción | Seinen | Shojo | Shonen | Slice of Life | Deportes | Supernatural | Terror | Yaoi | Yuri


Cada género en el menú desplegable **filtra directamente en `anime.html`** (ej. al hacer clic en "Romance", se aplica un filtro por ese género mediante JavaScript o URL params).

- **Contacto** → `contacto.html`

> 🔹 El menú desplegable es **responsive** y funciona en escritorio y dispositivos móviles.

---

## 📄 Descripción de las Páginas

### 1. `index.html`
- Bienvenida al sitio.
- Enlaces a: **Anime**, **Contacto**.

### 2. `anime.html` *(página central)*
Contiene:
- La misma barra de navegación (con menú desplegable de géneros).
- **Buscador avanzado** estilo AnimeFLV con los siguientes filtros:
  - 🔍 **Búsqueda por nombre** (campo de texto)
  - 🎭 **Género**: Acción, Romance, Yaoi, Yuri, Comedia, etc.
  - 📺 **Tipo**: TV, Película, OVA, Especial
  - 🟢 **Estado**: En emisión / Finalizado
  - 🔤 **Orden**: Alfabético (A-Z), Más recientes, Popularidad
- **Lista dinámica de animes** que se actualiza automáticamente al aplicar filtros.
- **Modal de descripción emergente** al hacer clic en cualquier anime, que muestra:
  - Título
  - Sinopsis breve (1–3 líneas)
  - Géneros
  - Tipo y estado

> 💡 También se puede incluir una **lista alfabética de géneros** como menú rápido debajo del buscador (opcional).

### 3. `contacto.html`
- Información de contacto (email, redes sociales, formulario, etc.).

---

## 🧩 Características Clave

- ✅ Menú desplegable de géneros integrado en la barra de navegación (estilo Amazon/Crunchyroll).
- ✅ Diseño limpio, moderno y **totalmente responsive**.
- ✅ Búsqueda y filtrado **sin recargas** (todo en `anime.html` con JavaScript).
- ✅ Fácil de mantener, escalar y personalizar.
- ✅ Ideal para portafolio personal, catálogo freelance o proyecto de pasión.

---

## 🚀 Próximos Pasos (Opcional)

- Añadir `data/animes.json` para cargar los animes desde un archivo estructurado.
- Implementar sistema de **favoritos** o lista de seguimiento.
- Agregar **imágenes de portada** para cada anime.
- Conectar con APIs externas (MyAnimeList, AniList, etc.).
- Soporte para modo oscuro/claro.

---

> 💡 Este diseño combina la usabilidad de plataformas como **Crunchyroll**, **AnimeFLV** y **Amazon**, con un enfoque minimalista y funcional para una experiencia de usuario intuitiva.
