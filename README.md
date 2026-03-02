# Landing Medicales - FarmaPlus

Landing page estática para promocionar productos de farmacia, desarrollada con **Astro**.

## 🚀 Características

- **Framework**: Astro 4.x (output estático)
- **Secciones**: Header, Hero Slider, Promociones, Productos Recientes, Nosotros, Contacto, Footer
- **Diseño**: Responsive, HTML5 semántico, CSS con variables, Grid/Flexbox
- **Configuración**: Lista para GitHub Pages (output en carpeta `/docs`)

## 📋 Requisitos Previos

- Node.js 18+ 
- npm o yarn

## 🛠️ Instalación

```bash
# Clonar el repositorio
git clone https://github.com/mbarriosRojas/landing-medicales.git
cd landing-medicales

# Instalar dependencias
npm install
```

## 💻 Desarrollo

```bash
# Iniciar servidor de desarrollo
npm run dev

# El sitio estará disponible en http://localhost:4321
```

## 🏗️ Construcción

```bash
# Generar sitio estático (output en /docs)
npm run build

# Vista previa del build
npm run preview
```

## 📦 Estructura del Proyecto

```
/
├── public/              # Archivos estáticos
│   ├── favicon.svg
│   └── images/
├── src/
│   ├── components/      # Componentes Astro reutilizables
│   │   ├── Header.astro
│   │   ├── HeroSlider.astro
│   │   ├── Promotions.astro
│   │   ├── Products.astro
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/         # Layouts de página
│   │   └── Layout.astro
│   ├── pages/           # Páginas (rutas automáticas)
│   │   └── index.astro
│   └── styles/          # Estilos globales
│       └── global.css
├── astro.config.mjs     # Configuración de Astro
├── package.json
└── tsconfig.json
```

## 🌐 Despliegue en GitHub Pages

El proyecto está configurado para GitHub Pages:

1. El build genera archivos en la carpeta `/docs`
2. En GitHub: Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: /docs
3. El sitio estará disponible en: `https://mbarriosRojas.github.io/landing-medicales/`

## 🎨 Personalización

### Colores (variables CSS en `src/styles/global.css`)

```css
--color-primary: #00a8cc;    /* Color principal */
--color-secondary: #005f73;  /* Color secundario */
--color-accent: #0a9396;     /* Color de acento */
```

### Configuración del Sitio (`astro.config.mjs`)

```js
export default defineConfig({
  output: 'static',
  outDir: 'docs',
  site: 'https://mbarriosRojas.github.io',
  base: '/landing-medicales',
});
```

## 📱 Secciones del Sitio

1. **Header**: Navegación sticky con menú responsive
2. **Hero Slider**: Carrusel automático con 3 slides
3. **Promociones**: Grid de ofertas especiales
4. **Productos Recientes**: Catálogo de productos con precios
5. **Nosotros**: Características y valores de la farmacia
6. **Contacto**: Formulario e información de contacto
7. **Footer**: Enlaces, redes sociales y copyright

## 🔧 Tecnologías

- Astro (Framework)
- HTML5 Semántico
- CSS3 (Variables, Grid, Flexbox)
- TypeScript (configuración relajada)
- JavaScript Vanilla (interactividad)

## 📄 Licencia

ISC

## 👨‍💻 Autor

Desarrollado para landing-medicales
