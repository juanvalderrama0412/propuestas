# Slides

¡Bienvenido al repositorio **Slides**! Este proyecto contiene todas las presentaciones basadas en [Reveal.js](https://revealjs.com/) que he creado hasta ahora, construido con [Astro](https://astro.build/).

---

## Tabla de contenidos

1. [Tecnologías](#tecnologías)
2. [Requisitos previos](#requisitos-previos)
3. [Instalación](#instalación)
4. [Estructura del proyecto](#estructura-del-proyecto)
5. [Desarrollo](#desarrollo)
6. [Construcción (Build)](#construcción-build)
7. [Vista previa de producción](#vista-previa-de-producción)
8. [Despliegue](#despliegue)
9. [Contribuciones](#contribuciones)
10. [Licencia](#licencia)

---

## Tecnologías

- **Astro**: Framework moderno para construir sitios estáticos y serverless.
- **Reveal.js**: Biblioteca para crear presentaciones HTML.
- **Node.js**: Entorno de ejecución de JavaScript.
- **npm / yarn / pnpm**: Gestor de paquetes.

---

## Requisitos previos

Antes de comenzar, asegúrate de tener instalados:

- **Node.js** (v16 o superior) y npm (incluido) — [Descargar aquí](https://nodejs.org/)
- **Astro CLI** (opcional si deseas usar comandos globales):
  ```bash
  npm install -g astro
  ```

---

## Instalación

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/TU_USUARIO/slides.git
   cd slides
   ```

2. **Instala dependencias**:

   Con npm:
   ```bash
   npm install
   ```

   Con yarn:
   ```bash
   yarn install
   ```

   Con pnpm:
   ```bash
   pnpm install
   ```

---

## Estructura del proyecto

```
slides/
├── public/             # Archivos estáticos (imágenes, favicons, etc.)
├── src/
│   ├── pages/          # Páginas y presentaciones
│   │   └── slides/     # Cada subcarpeta es una presentación Reveal.js
│   ├── layouts/        # Plantillas de página y presentaciones
│   ├── components/     # Componentes UI reutilizables
│   └── styles/         # Estilos globales o específicos
├── astro.config.mjs    # Configuración de Astro
├── package.json        # Metadatos y scripts
└── README.md           # Este archivo
```

---

## Desarrollo

Arranca el servidor de desarrollo para ver cambios en vivo:

```bash
npm run dev
# o yarn dev
# o pnpm dev
```

Luego abre tu navegador en `http://localhost:3000`.

---

## Construcción (Build)

Para generar los archivos estáticos de producción:

```bash
npm run build
# o yarn build
# o pnpm build
```

El contenido generado se ubicará en la carpeta `dist/`.

---

## Vista previa de producción

Para probar la versión de producción localmente:

```bash
npm run preview
# o yarn preview
# o pnpm preview
```

Abre `http://localhost:3000` para ver tu sitio optimizado.

---

