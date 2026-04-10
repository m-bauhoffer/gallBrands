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

**Nota: Esta es una traducción no oficial de la Licencia MIT al español. Para efectos legales, consulta la versión original en inglés en https://opensource.org/licenses/MIT. La traducción no tiene validez jurídica.**

Licencia MIT

Copyright (c) 2026 gallBrands

Se concede permiso, libre de cargos, a cualquier persona que obtenga una copia de este software y de los archivos de documentación asociados (el "Software"), a utilizar el Software sin restricción, incluyendo sin limitación los derechos a usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar, y/o vender copias del Software, y a permitir a las personas a las que se les proporcione el Software a hacer lo mismo, sujeto a las siguientes condiciones:

El aviso de copyright anterior y este aviso de permiso se incluirán en todas las copias o partes sustanciales del Software.

EL SOFTWARE SE PROPORCIONA "COMO ESTÁ", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A GARANTÍAS DE COMERCIALIZACIÓN, IDONEIDAD PARA UN PROPÓSITO PARTICULAR E INCUMPLIMIENTO. EN NINGÚN CASO LOS AUTORES O PROPIETARIOS DE LOS DERECHOS DE AUTOR SERÁN RESPONSABLES DE NINGUNA RECLAMACIÓN, DAÑOS U OTRAS RESPONSABILIDADES, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O DE OTRO TIPO, DERIVADAS DE, FUERA DE O EN CONEXIÓN CON EL SOFTWARE O EL USO U OTRO TIPO DE ACCIONES EN EL SOFTWARE.

---

*Este README fue generado automáticamente basado en el análisis del código fuente del proyecto gallBrands.*