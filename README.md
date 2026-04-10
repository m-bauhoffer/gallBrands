# gallBrands - Sitio Web de Agencia de Branding

## Descripción del Proyecto

gallBrands es un sitio web interactivo para una agencia de branding especializada en el método de la piedra preciosa. El sitio presenta una experiencia visual rica con animaciones, temas oscuros/claros, y un formulario de contacto integrado con Google Sheets.

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica con elementos SVG extensivos para logos, fondos e interactividad
- **SCSS/CSS**: Sistema de estilos modular con cambio de temas entre oscuro y claro usando propiedades personalizadas de CSS
- **JavaScript (ES6+)**: Interactividad principal incluyendo animaciones, manejo de formularios y cambio de temas
- **GSAP**: Biblioteca de animaciones para secuencias complejas como revelaciones de mapas mentales y efectos de texto
- **Lenis**: Biblioteca de desplazamiento suave para una mejor experiencia de usuario
- **TSParticles**: Efectos de partículas de fondo para atractivo visual
- **Google Apps Script**: Envío seguro de datos de formularios a Google Sheets

## Estructura del Proyecto

### Archivos HTML
- **index.html**: Página principal con todas las secciones principales (hero, mapa mental, servicios, método de piedra preciosa, marcas, órbita, pie de página)
- **form.html**: Formulario de contacto de múltiples pasos para consultas de clientes
- **terms.html**: Página dedicada a términos y condiciones

### Archivos JavaScript
- **counter.js**: Implementa un temporizador de cuenta regresiva hasta el 15 de julio de 2025
- **form.js**: Maneja el envío de formularios a Google Sheets
- **themeSwitch.js**: Gestiona el cambio entre temas oscuro y claro
- **mindMapShortAni.js**: Controla la secuencia de animación del mapa mental
- **Otros archivos JS**: Incluyen animaciones, navegación, efectos de partículas, etc.

### Archivos SCSS/CSS
- **index.scss**: Archivo principal SCSS que importa todos los módulos
- **scss/abstract/**: Variables, mixins, keyframes y utilidades globales
- **scss/components/**: Estilos para botones, contadores, etc.
- **scss/layout/**: Estilos para secciones como hero, navegación, servicios, etc.
- **scss/form/**: Estilos específicos del formulario

## Características Principales

### Animaciones y Interactividad
- Animaciones GSAP para revelaciones de texto y mapas mentales
- Desplazamiento suave con Lenis
- Efectos de partículas de fondo
- Cambio dinámico de temas

### Formulario de Contacto
- Flujo de múltiples pasos (nombre → email → marca → fuente → confirmación → términos → agradecimiento)
- Envío seguro a Google Sheets vía Google Apps Script

### Diseño Responsivo
- Sistema de cuadrícula PureCSS
- Optimizado para escritorio y móvil

### Tema Oscuro/Claro
- Interruptor de tema con sincronización automática
- Inversión de logos y colores

## Instalación y Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/gallBrands.git
   ```

2. Abre `index.html` en tu navegador web.

3. Para desarrollo, asegúrate de que los archivos estén servidos desde un servidor local para evitar problemas de CORS con las dependencias externas.

## Dependencias Externas

- GSAP (CDN)
- Lenis (CDN)
- TSParticles (CDN)
- Google Apps Script (para envío de formularios)

## Arquitectura

El proyecto sigue una arquitectura modular con:
- Separación clara de responsabilidades en SCSS
- JavaScript basado en componentes
- Diseño responsivo con PureCSS
- Envío seguro de formularios

## Estado del Código

- **Estado Actual**: Completamente analizado y documentado
- **Problemas**: Ninguno identificado durante el análisis
- **Validación**: Estructura del sitio web y funcionalidad completamente documentadas

## Contribución

Si deseas contribuir:
1. Haz un fork del repositorio
2. Crea una rama para tu feature
3. Envía un pull request

## Licencia

MIT License

Copyright (c) 2026 gallBrands

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

*Este README fue generado automáticamente basado en el análisis del código fuente del proyecto gallBrands.*