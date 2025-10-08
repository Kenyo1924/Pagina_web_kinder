# Página web Kinder (PJ Jardín)

> Sitio web estático para un jardín infantil, con páginas de Inicio, Sobre Nosotros, Matrícula y Galería. Construido con HTML y CSS usando Bootstrap 5 e iconos de Bootstrap por CDN.

## Estructura del proyecto

- `Principal.html` — Página de inicio.
- `SobreNosotros.html` — Información institucional.
- `Matricula.html` — Requisitos y proceso de matrícula.
- `Galeria.html` — Galería de fotos.
- `css/` — Hojas de estilo globales y por página.
- `imagenes/` — Recursos gráficos organizados en carpetas.

## Tecnologías

- Bootstrap 5.3 (CDN)
- Bootstrap Icons (CDN)
- Google Fonts (Lobster) en la portada
- HTML5 + CSS3 (no hay JavaScript propio; solo el bundle de Bootstrap recomendado para el navbar)

## Uso local

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Kenyo1924/Pagina_web_kinder.git
   cd Pagina_web_kinder
   ```
2. Abre cualquier archivo HTML en tu navegador (por ejemplo `Principal.html`).
   - Consejo: establece un archivo `index.html` para que los proveedores estáticos tomen esa página como inicio.

## Despliegue con GitHub Pages

1. En GitHub, ve a `Settings` → `Pages`.
2. En "Source", elige "Deploy from a branch".
3. Selecciona `Branch: main` y `/ (root)`.
4. Guarda. GitHub generará una URL del sitio. Opcionalmente, configura un dominio personalizado.

## Recomendaciones de mejora (pendientes)

- Internacionalización: cambiar `lang="en"` a `lang="es"` en todas las páginas.
- Codificación: corregir caracteres mal renderizados ("Menú", "Matrícula", "Galería", "Educación", etc.) y asegurar guardado en UTF‑8.
- Head: mover `<title>` dentro de `<head>` en todas las páginas; añadir `meta description` y favicon.
- Navbar: incluir `bootstrap.bundle.min.js` antes de `</body>` para que funcione el menú hamburguesa.
- CSS: corregir `border-radius: 8px, 8px;` por `8px 8px;` en `css/principal.css`.
- Iconos: eliminar la importación duplicada de Bootstrap Icons (dejar solo la versión minificada con versión fija).
- Accesibilidad: evitar IDs duplicados (usar clases), añadir `alt` descriptivo a imágenes y `loading="lazy"` donde aplique.
- Inicio: agregar `index.html` (redirección a `Principal.html` o renombrar `Principal.html`).

## Contribuir

- Crea una rama para tus cambios y abre un Pull Request.
- Mantén estilos y estructura consistentes con el proyecto.

## Licencia

- No se ha especificado una licencia. Añádela si deseas permitir usos externos.

## Autor

- Kenyo (propietario del repositorio)
