# Portafolio de Gabriela Martinez

Sitio de una sola página construido con Astro para presentar los reportes y tableros en Excel de Gabriela Martinez, ingeniera en sistemas de San Francisco (Estado Zulia) enfocada en análisis de datos.

## Stack
- Astro 5 como generador de sitios estáticos
- Colecciones de contenido en Markdown dentro de `src/content`
- CSS personalizado en `src/styles/global.css`

## Qué incluye
- Portada, navegación y pie de página personalizados para Gabriela
- Listado de proyectos impulsado por la colección `work` con casos de análisis en Excel
- Página "Sobre mí" con biografía, formación y habilidades orientadas a datos
- Sección de habilidades con foco en Excel, adaptabilidad, trabajo en equipo y analítica

## Desarrollo local
```sh
npm install
npm run dev
```
El servidor se abre en `http://localhost:4321/` y recarga al modificar archivos en `src/`.

## Compilación y vista previa
```sh
npm run build   # genera la versión estática en dist/
npm run preview # sirve la compilación para revisión final
```

## Despliegue
Ejecuta `npm run build` y sube el contenido de `dist/` al servicio estático que prefieras (Netlify, Vercel, GitHub Pages, etc.).
