# RUMBO EDUCA — Laboratorio de aprendizaje y orientación

**Marca:** RUMBO EDUCA · Laboratorio de aprendizaje y orientación  
**Identidad:** OAKTREESKY

## Estructura

```
RUMBO-EDUCA/
├── index.html
├── oaktree.webp
├── orientacion/index.html      ← Test vocacional
├── resiliencia/index.html      ← Test resiliencia
├── play/elementum-modelos.html ← Juego Elementum
├── play/mision-laboratorio.html ← MISIÓN LABORATORIO 3.0
├── ciencias/
│   ├── index.html              ← Catálogo (12 guías)
│   └── *.html                  ← Guías interactivas
├── admin/index.html            ← Panel administrador global
└── README-PUBLICACION.md
```

## Cómo abrir

1. Descomprime el ZIP y abre `index.html`.
2. **Admin:** `admin/index.html` — clave por defecto: `rumbo2026`

## Panel administrador

- Publicar / ocultar guías (estado en este navegador)
- Acceso directo al editor de preguntas de cada guía (`#admin`)
- Registrar nuevas guías en el catálogo local
- Exportar catálogo JSON

Cada guía de química ya incluye su propio panel para agregar, editar o eliminar preguntas (localStorage).

## Publicar en GitHub Pages

Repo con `index.html` en la raíz → Settings → Pages → branch `main` → `/ (root)`.

## Nota

Test de resiliencia: prototipo educativo, resultados descriptivos no diagnósticos.  
Cambia la clave de admin antes de publicar en producción.
