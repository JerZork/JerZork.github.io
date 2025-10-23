# Stack.Dev - Transformación Completa

## Cambios Realizados

He transformado completamente tu proyecto para que se parezca a la plantilla Stack.Dev con las siguientes mejoras:

### 🎨 Diseño y Tema
- **Tema oscuro completo** con colores tech-dark (#0a0a14), tech-purple (#7c3aed) y tech-teal (#06b6d4)
- **Fuente Space Grotesk** de Google Fonts para un look moderno
- **Efectos neon** y gradientes en botones y textos
- **Cursor personalizado** con efecto de seguimiento suave

### 🏠 Hero Section
- **Hero a pantalla completa** con fondo degradado oscuro
- **Animación Matrix** con números hexadecimales cayendo
- **Título "Building Digital Solutions"** con la palabra "Digital" en gradiente
- **Avatar circular** con anillo giratorio y etiquetas posicionadas (SYSTEM, CREATIVE, DEVELOPMENT, DESIGN)
- **Animación flotante** en el avatar
- **Dos botones** con estilos diferentes (gradiente y outline)
- **Badge de premio** "Best Web Developer Award 2021"

### 📊 Sección de Estadísticas
- **Contadores animados** que se activan al hacer scroll
- **4 métricas**: Years Experience, Projects Completed, Client Satisfaction, Happy Clients
- **Diseño responsive** en grid

### 🧭 Navegación
- **Nav fijo** en la parte superior con backdrop blur
- **Logo STACK.DEV** con los corchetes { }
- **Menú responsive** con hamburguesa en móvil
- **Botón Contact** con gradiente
- **Hover effects** en todos los enlaces

### 🎯 Componentes Creados
1. **CustomCursor.astro** - Cursor personalizado con efecto neon
2. **MatrixBg.astro** - Animación de números matrix en el fondo
3. **Stats.astro** - Sección de estadísticas con contadores animados

### 📝 Componentes Modificados
1. **Hero.astro** - Rediseño completo con el estilo Stack.Dev
2. **Nav.astro** - Navegación fija con nuevo diseño
3. **Footer.astro** - Footer con tema oscuro
4. **BaseLayout.astro** - Incluye cursor y tema oscuro por defecto
5. **global.css** - Nuevos estilos, colores y animaciones

### ⚙️ Configuración
- **site-config.ts** actualizado con nuevo título, descripción y enlaces

## 🚀 Cómo Probar

Abre tu terminal y ejecuta:

```bash
cd "/c/Users/jerpa/Desktop/Proyeectos personales/portafolio/JerZork.github.io"
npm install
npm run dev
```

Luego abre tu navegador en http://localhost:4321 (o la URL que muestre la consola).

## 📱 Características Responsive

- ✅ Hero con layout de 2 columnas en desktop, apilado en móvil
- ✅ Avatar flotante que se adapta al tamaño de pantalla
- ✅ Menú hamburguesa funcional en dispositivos móviles
- ✅ Estadísticas en grid adaptable (2 columnas en móvil, 4 en desktop)
- ✅ Botones y texto con tamaños responsive

## 🎨 Efectos Especiales

- **Cursor personalizado** que cambia de tamaño al pasar sobre enlaces y botones
- **Números Matrix** animados en el fondo del hero
- **Anillo giratorio** alrededor del avatar (20s de rotación)
- **Contadores animados** que cuentan desde 0 hasta el valor final
- **Efectos hover** con transiciones suaves
- **Gradientes** en textos y botones

## 📋 Notas Técnicas

Los "errores" que aparecen en `global.css` son advertencias del linter que no reconoce las directivas de Tailwind CSS como `@apply`, `@plugin`, `@theme`, etc. Estas directivas funcionan perfectamente cuando Astro compila el proyecto con PostCSS y Tailwind CSS.

## 🎯 Próximos Pasos Opcionales

Si quieres mejorar aún más:
1. Añadir más secciones como About, Services, Portfolio
2. Integrar un formulario de contacto funcional
3. Añadir más animaciones y transiciones
4. Optimizar imágenes para web
5. Configurar PWA para una mejor experiencia

¡Disfruta tu nuevo portafolio estilo Stack.Dev! 🚀
