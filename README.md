# Las Mejores Series de Netflix

Un sitio web que presenta un catálogo interactivo de las mejores series de Netflix, mostrando estadísticas de reproducción, calificaciones y más información detallada sobre cada serie.

## 📋 Características

- **Tabla de series**: Listado principal con información de las series más populares
- **Calificaciones con estrellas**: Sistema de valoración visual usando iconos de Font Awesome
- **Páginas individuales**: La mayoría de series cuentan con páginas dedicadas con más detalles
- **Diseño responsivo**: Interfaz moderna con gradientes y animaciones
- **Accesibilidad**: Uso de semántica HTML correcta

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica del sitio
- **CSS3**: Estilos personalizados con:
  - Flexbox para el layout
  - Gradientes lineales
  - Effectos de sombra (box-shadow)
  - Bordes redondeados
- **Font Awesome 6.5.1**: Iconos de estrellas y elementos visuales
- **Normalize.css**: Normalización de estilos entre navegadores
- **Animate.css**: Animaciones CSS predefinidas
- **Sin JavaScript**: Construcción puramente con HTML y CSS

## 📁 Estructura del Proyecto

```
Series-de-Netflix/
├── index.html                          # Página principal
├── assets/
│   ├── css/
│   │   └── main.css                   # Estilos personalizados
│   ├── imagenes/                      # Carpeta para imágenes
│   └── scripts/
│       └── main.js                    # Archivo JS (sin usar actualmente)
├── fontawesome-free-6.5.1-web/        # Librería Font Awesome
│   ├── css/                           # Estilos de iconos
│   ├── js/                            # Scripts de iconos
│   ├── scss/                          # Fuentes SCSS
│   └── webfonts/                      # Fuentes web
└── series/                            # Páginas individuales de cada serie
    ├── El-juego-del-calamar.html
    ├── Estamos-muertos.html
    ├── Hechos-polvo.html
    ├── Inventando-a-Anna.html
    ├── Jeffrey-Dahmer.html
    ├── Las-cosas-por-limpiar.html
    ├── Miercoles.html
    └── Stranger-Things.html
```

## 🎨 Diseño Visual

- **Tema oscuro**: Fondo con gradiente de púrpura a gris
- **Contenedor principal**: Panel semitransparente con efecto glassmorphism
- **Animaciones**: Entrada suave del contenido con efecto `backInDown`
- **Colores**: Paleta oscura (#242424, #11003f) con rojo para la acción (#dd1818)

## 📊 Datos Presentados

La tabla principal muestra para cada serie:

- Posición (#)
- Nombre
- Calificación (estrellas)
- Horas vistas
- Duración
- Visualizaciones
- Enlaces a páginas detalladas

## 🚀 Cómo Usar

1. Abre `index.html` en tu navegador
2. Explora la tabla de series principales
3. Haz clic en "Ver mas" para acceder a las páginas individuales de cada serie

## 💡 Notas de Desarrollo

Estos fueron tus primeros pasos con **HTML y CSS puro**, sin utilizar JavaScript. El proyecto demuestra:

- Buenas prácticas en HTML semántico
- Manejo avanzado de CSS (flexbox, gradientes, sombras)
- Integración de bibliotecas CSS externas
- Estructura modular con páginas separadas por serie

## 📝 Próximas Mejoras Potenciales

- Agregar interactividad con JavaScript
- Implementar búsqueda y filtros
- Hacer el diseño completamente responsive para dispositivos móviles
- Agregar base de datos o API para datos dinámicos
- Mejorar accesibilidad (ARIA labels, contraste)

## 👤 Autor

Tu proyecto personal de aprendizaje en desarrollo web.

---

**Última actualización**: 2026
