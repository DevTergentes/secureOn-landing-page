# SecureOn Landing Page

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen)](https://devtergentes.github.io/secureOn-landing-page/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

## Demo en Vivo
**[Visita SecureOn Landing Page](https://devtergentes.github.io/secureOn-landing-page/)**

---

## Descripción del Proyecto

**SecureOn** es una plataforma innovadora diseñada para gestionar la seguridad en el transporte de productos peligrosos mediante tecnología IoT avanzada. Nuestra landing page presenta una solución integral que combina monitoreo en tiempo real, sensores inteligentes y un sistema de alertas para garantizar el transporte seguro de materiales peligrosos.

### Objetivo Principal
Proporcionar a los transportistas y empresas de logística una herramienta confiable que les permita transportar productos peligrosos con total seguridad y tranquilidad, minimizando riesgos y optimizando operaciones.

---

## Características Principales

### Funcionalidades
- **Sitio Bilingüe**: Disponible en Español e Inglés con switch de idioma intuitivo
- **Diseño Responsive**: Optimizado para desktop, tablet y móvil
- **Interfaz Moderna**: Diseño profesional con paleta de colores corporativa
- **Navegación Suave**: Scroll suave entre secciones con highlighting automático
- **Tarjetas de Equipo Interactivas**: Efecto flip 3D para mostrar información del team
- **Animaciones CSS**: Transiciones y efectos hover elegantes
- **Testimonios de Clientes**: Sistema de rating con estrellas
- **Enlaces de Descarga**: Badges para App Store y Google Play

### Servicios Ofrecidos
1. **Servicio de Transporte Especializado**
2. **Monitoreo en Tiempo Real**
3. **Sensores IoT Avanzados**
4. **Sistema de Transporte Seguro**

---

## Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| **Azul Principal** | `#183856` | Fondos, navegación, títulos principales |
| **Verde Activo** | `#74c04a` | Elementos interactivos, botones, highlights |
| **Gris Técnico** | `#444444` | Texto secundario, párrafos |
| **Blanco Legibilidad** | `#FFFFFF` | Texto sobre fondos oscuros |
| **Amarillo Accent** | `#ffdd57` | Logo, elementos destacados |

---

## Estructura del Proyecto

```
secureOn-landing-page/
├── index.html              # Página principal (Español)
├── indexEN.html            # Página en Inglés
├── assets/
│   ├── css/
│   │   └── styles.css      # Estilos principales
│   ├── js/
│   │   └── index.js        # JavaScript funcional
│   └── images/
│       ├── team/           # Fotos del equipo
│       ├── logo_securon.png
│       ├── foto1.webp      # Hero background
│       └── ...             # Otras imágenes
├── README.md
└── LICENSE
```

---

## Tecnologías Utilizadas

### Frontend
- **HTML5**: Estructura semántica
- **CSS3**: Estilos avanzados, Grid, Flexbox, Animations
- **JavaScript ES6+**: Funcionalidad interactiva
- **Bootstrap 5.3**: Framework CSS responsive

### Dependencias
- **Font Awesome 6.4.0**: Iconografía
- **Google Fonts**: Tipografías Heebo & Jost
- **Bootstrap Bundle**: Componentes y utilidades

### Hosting
- **GitHub Pages**: Despliegue automático desde repositorio

---

## Equipo de Desarrollo - DevTergentes

| Integrante | Código | Rol | Especialización |
|------------|--------|-----|-----------------|
| **Camila Elena Amaro Villanueva** | u202114248 |
| **Jherson David Astuyauri Calderon** | u202218451 | 
| **Claudio Sandro Quispesivana Torres** | u202215099 | 
| **Jose Daniel Mario Calderon Huaman** | U202213076 | 
| **Jeremi Jose Antonio Fretel** | U202219022 | 
**Institución**: Universidad Peruana de Ciencias Aplicadas (UPC)  
**Año**: 2025

---

## Secciones de la Landing Page

### 1. Hero Section
- Título llamativo con call-to-action
- Fondo con overlay profesional
- Botón de navegación a sección "Acerca de"

### 2. Servicios
- 4 tarjetas de servicios con iconos Font Awesome
- Efectos hover elegantes
- Descripción detallada de cada servicio

### 3. Quiénes Somos & Equipo
- Información corporativa de SecureOn
- Tarjetas interactivas del equipo (efecto flip 3D)
- Perfiles individuales con foto y descripción

### 4. Testimonios
- Reseñas de clientes con sistema de rating
- Diseño en grid responsive
- Fotos de perfil y títulos profesionales

### 5. Descarga
- Enlaces a tiendas de aplicaciones
- Badges oficiales de App Store y Google Play
- Descripción de la aplicación móvil

### 6. Footer
- Información de contacto con iconos
- Enlaces a redes sociales
- Mapa del sitio y links legales
- Gradiente de marca con efectos visuales

---

## Responsive Design

### Breakpoints
- **Desktop**: 1024px+ (5 tarjetas de equipo por fila)
- **Tablet**: 768px - 1023px (3 tarjetas por fila)
- **Mobile**: <768px (1 tarjeta por fila, navegación colapsada)

### Optimizaciones Móviles
- Navegación hamburguesa
- Tipografía escalable
- Imágenes optimizadas
- Touch-friendly buttons
- Menús colapsables

---

## Instalación y Uso

### Clonar el Repositorio
```bash
git clone https://github.com/DevTergentes/secureOn-landing-page.git
cd secureOn-landing-page
```

### Servidor Local
```bash
# Con Python
python -m http.server 8000

# Con Node.js (live-server)
npx live-server

# Con PHP
php -S localhost:8000
```

### Navegación
1. Abre `http://localhost:8000` en tu navegador
2. Para versión en inglés: navega a `indexEN.html`
3. Usa el toggle de idioma en la navegación

---

## Funcionalidades JavaScript

### Toggle de Idiomas
```javascript
function toggleLanguage(checkbox) {
  if (checkbox.checked) {
    window.location.href = 'indexEN.html';
  } else {
    window.location.href = 'index.html';
  }
}
```

### Highlighting de Sección Activa
- Detección automática de sección visible
- Actualización de clases CSS en navegación
- Scroll suave entre secciones

---

## Características de Diseño

### Animaciones CSS
- **Hover Effects**: Transform, scale, translateY
- **Tarjetas 3D**: Rotación en eje Y para efecto flip
- **Transiciones**: 0.3s ease para suavidad
- **Gradientes**: Fondos degradados profesionales

### Tipografía
- **Heebo**: Títulos y elementos destacados
- **Jost**: Párrafos y texto secundario
- **Pesos**: 300, 400, 700 para jerarquía visual

---

**Desarrollado por el equipo DevTergentes**