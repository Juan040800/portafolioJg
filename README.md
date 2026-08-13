# Portafolio — Fotografía, Pintura y Escultura

Sitio de una sola página para presentar el trabajo en tres disciplinas: fotografía, pintura y escultura. Diseño oscuro, tipografía expandida y una sección de índice navegable por catálogo.

**Sitio en vivo:** `https://tu-usuario.github.io/nombre-del-repo/`

## Estructura

```
.
├── index.html      # Página completa (HTML + CSS + JS en un solo archivo)
└── img/
    ├── perfil.jpg       # Foto de la sección "Sobre mí"
    └── fotografia-01.jpg # Foto del tile de Fotografía
```

## Secciones

| Sección | Descripción |
|---|---|
| `#perfil` | Hero a pantalla completa con nombre y disciplinas |
| `#sobre-mi` | Foto de perfil con acento circular + bio |
| `#obra` | Índice/catálogo en grid: Fotografía, Pintura, Escultura |
| `#contacto` | Botón de contacto y redes |

## Diseño

- **Paleta:** negro carbón `#1A1A1A` · blanco roto `#EDEAE4` · gris piedra `#8C8880` · beige arena `#C9B79C`
- **Tipografía:** [Unbounded](https://fonts.google.com/specimen/Unbounded) (títulos y nombre) + Work Sans (texto de cuerpo)
- **Efectos:** parallax sutil en el hero y reveal progresivo de las secciones al hacer scroll (respeta `prefers-reduced-motion`)

## Personalizar

1. Reemplazá `Nombre Apellido` y los textos en `index.html` por los tuyos.
2. Cambiá las fotos dentro de `img/` (mantené los mismos nombres de archivo o actualizá las rutas en el CSS).
3. Editá los tiles de la sección `#obra` para agregar o quitar disciplinas.

## Publicar con GitHub Pages

Settings → Pages → Source: rama `main`, carpeta `/root` → Guardar. El sitio queda publicado en un par de minutos.
