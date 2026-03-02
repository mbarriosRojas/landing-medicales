# feat: Landing page estática FarmaPlus con Astro

## 📋 Descripción
Landing page estática para promocionar productos de farmacia construida con **Astro framework**.

## ✅ Características Implementadas

### Framework & Configuración
- ✅ **Astro 4.x** con output estático
- ✅ **GitHub Pages ready**: Build configurado en carpeta `/docs`
- ✅ **Site URL**: https://mbarriosRojas.github.io/landing-medicales/
- ✅ **Base path**: `/landing-medicales` configurado en astro.config.mjs

### Diseño & Estilos
- ✅ **Responsive Design**: Grid/Flexbox con breakpoints móviles (768px)
- ✅ **HTML5 Semántico**: header, nav, main, section, footer, article
- ✅ **CSS Variables**: Sistema de diseño con colores, espaciado y tipografía personalizados
- ✅ **Animaciones**: Transiciones suaves y efectos hover

## 🎨 Secciones Implementadas

### 1. Header
- Navegación sticky fija en la parte superior
- Menú responsive con hamburger para móviles
- Logo SVG personalizado
- Enlaces de navegación a todas las secciones

### 2. Hero Slider
- Carrusel automático con 3 slides
- Controles de navegación (prev/next)
- Indicadores de slide (dots)
- Auto-play cada 5 segundos
- Gradientes de colores personalizados

### 3. Promociones
- Grid responsive de 4 ofertas especiales
- Cards con badges de categoría
- Efectos hover con elevación
- Información de descuento destacada

### 4. Productos Recientes
- Catálogo de 6 productos
- Grid adaptable (auto-fill)
- Categorías y precios
- Botón "Agregar al carrito" interactivo
- Gradientes de fondo únicos por producto

### 5. Nosotros (About)
- Texto introductorio sobre la farmacia
- Grid de 4 features/valores con iconos SVG:
  - Productos Certificados
  - Atención 24/7
  - Envío Rápido
  - Farmacéuticos Expertos

### 6. Contacto
- Formulario funcional con validación HTML5
- Información de contacto con iconos
- Dirección, teléfono, email, horario
- Grid 2 columnas (info + formulario)

### 7. Footer
- Grid de 4 columnas:
  - Información de la empresa
  - Enlaces rápidos
  - Categorías de productos
  - Legal
- Redes sociales (Facebook, Instagram, Twitter)
- Copyright dinámico
- Links hover con animación

## 🛠️ Tecnologías Utilizadas

- **Astro** - Framework SSG (Static Site Generation)
- **HTML5** - Semántico y accesible
- **CSS3** - Variables, Grid, Flexbox, Transitions
- **TypeScript** - Configuración relajada
- **JavaScript** - Vanilla para interactividad (slider, menú, formulario)

## 📦 Estructura del Proyecto

```
/workspace
├── docs/                    # Build output (GitHub Pages)
├── public/                  
│   └── favicon.svg         # Favicon personalizado
├── src/
│   ├── components/         # Componentes Astro reutilizables
│   │   ├── Header.astro
│   │   ├── HeroSlider.astro
│   │   ├── Promotions.astro
│   │   ├── Products.astro
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/            
│   │   └── Layout.astro    # Layout principal
│   ├── pages/              
│   │   └── index.astro     # Página principal
│   └── styles/             
│       └── global.css      # Estilos globales con variables
├── astro.config.mjs        # Configuración Astro
├── package.json            
├── tsconfig.json           
└── README.md               # Documentación completa
```

## 🚀 Comandos Disponibles

```bash
npm run dev      # Desarrollo en localhost:4321
npm run build    # Build estático a /docs
npm run preview  # Preview del build
```

## 🌐 Despliegue GitHub Pages

El proyecto está completamente configurado para GitHub Pages:

1. **Build output**: `/docs` (configurado en astro.config.mjs)
2. **URL del sitio**: https://mbarriosRojas.github.io/landing-medicales/

### Pasos para activar GitHub Pages:
1. Ir a Settings → Pages
2. Seleccionar Source: "Deploy from a branch"
3. Branch: `main`
4. Folder: `/docs`
5. Save

## ✨ Características Interactivas

- **Slider automático**: Cambia de slide cada 5 segundos
- **Menú móvil**: Se abre/cierra con animación
- **Formulario de contacto**: Validación HTML5 y envío simulado
- **Efectos hover**: En cards, botones y enlaces
- **Smooth scroll**: Navegación suave entre secciones

## 🎨 Sistema de Diseño

### Colores
```css
--color-primary: #00a8cc     /* Azul principal */
--color-secondary: #005f73   /* Azul oscuro */
--color-accent: #0a9396      /* Verde azulado */
--color-success: #2a9d8f     /* Verde */
--color-warning: #e76f51     /* Naranja */
```

### Espaciado
- xs: 0.5rem
- sm: 1rem
- md: 1.5rem
- lg: 2rem
- xl: 3rem
- 2xl: 4rem

## 📱 Responsive
- Mobile first approach
- Breakpoint principal: 768px
- Grid adaptable con auto-fit/auto-fill
- Menú hamburger en móviles

## 📝 Próximos Pasos Sugeridos

1. ✅ Activar GitHub Pages
2. 🔄 Agregar imágenes reales de productos en `/public/images`
3. 🔄 Integrar formulario con backend (ej. FormSpree, Netlify Forms)
4. 🔄 Agregar más productos al catálogo
5. 🔄 Implementar filtros de categorías
6. 🔄 Agregar carrito de compras funcional (si se requiere)

## 🔍 Testing
- ✅ Build exitoso sin errores
- ✅ Dev server funcional en localhost:4321
- ✅ HTML renderizado correctamente
- ✅ Estilos aplicados correctamente
- ✅ Scripts interactivos funcionando

## 📄 Documentación
El archivo README.md incluye:
- Instrucciones de instalación
- Comandos disponibles
- Estructura del proyecto
- Configuración de despliegue
- Guía de personalización

---

**URL del PR manual**: https://github.com/mbarriosRojas/landing-medicales/pull/new/cursor/landing-page-medicales-f2c7
