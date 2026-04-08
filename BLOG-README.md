# Blog Posts Template para CELC Systems

Este archivo te permite agregar posts al blog fácilmente.

## Cómo agregar un nuevo post:

1. Copia la estructura de abajo
2. Pega en ~/celc-website-pro/blog.html (dentro del área marcada)
3. Cambia el título, fecha, contenido, etc.

## Estructura de cada post:

```html
<article class="blog-card reveal">
    <div class="blog-image">
        <span class="blog-category">CATEGORÍA</span>
    </div>
    <div class="blog-content">
        <div class="blog-meta">
            <span><i class="fas fa-calendar"></i> FECHA</span>
            <span><i class="fas fa-clock"></i> TIEMPO_LECTURA</span>
        </div>
        <h3 class="blog-title">TÍTULO DEL POST</h3>
        <p class="blog-excerpt">Resumen o extracto del contenido...</p>
        <a href="#" class="blog-link">
            Leer más <i class="fas fa-arrow-right"></i>
        </a>
    </div>
</article>
```

## Ejemplo posts sugeridos:

1. "Cómo automatizar las reservas de tu restaurante con n8n"
2. "5 señales de que tu negocio necesita automatización YA"
3. "Caso práctico: Cómo JM Travel ahorra 15 horas semanales"
4. "PC lento vs PC nuevo: ¿Cuándo vale la pena reparar?"
5. "Guía: Backup automático para pequeños negocios"

## Instrucciones para crear blog completo:

1. Copiar la página principal (index.html)
2. Eliminar secciones que no apliquen (hero, servicios, etc)
3. Mantener nav + header
4. Reemplazar contenido principal con grid de posts
5. Agregar paginación si son muchos posts

Todo el CSS ya está en index.html, solo necesitas copiar la estructura.
