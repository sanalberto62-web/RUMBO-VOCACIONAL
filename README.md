# RUMBO EDUCA

**Laboratorio de aprendizaje y orientación** · Una iniciativa de **OAKTREESKY**

Plataforma educativa de acceso libre con:

- **Test de Resiliencia** (90 ítems, 8 dimensiones, plan personal)
- **Orientación Vocacional**
- **RUMBO CIENCIAS** — 12 guías interactivas de química (10° y 11°)
- **RUMBO PLAY** — Elementum y MISIÓN LABORATORIO 3.0 (Química PREICFES)
- **Panel administrador** (edición de preguntas y catálogo)

## Cómo ver el sitio en local

1. Descarga o clona este repositorio.
2. Abre `index.html` en el navegador.

## Publicación con GitHub Pages

1. Fork o sube este repositorio a tu cuenta de GitHub.
2. En el repositorio: **Settings → Pages**.
3. **Source:** Deploy from a branch.
4. **Branch:** `main` (o `master`) · carpeta `/ (root)`.
5. Guarda. En 1–2 minutos la URL será:

   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

Si el repositorio se llama `RUMBO-EDUCA` y tu usuario es `ejemplo`:

   `https://ejemplo.github.io/RUMBO-EDUCA/`

## Estructura

```
├── index.html              Portada
├── orientacion/            Test de orientación vocacional
├── resiliencia/            Test de resiliencia
├── play/                   Juegos educativos interactivos
│   ├── elementum-modelos.html
│   └── mision-laboratorio.html
├── ciencias/               Catálogo + 12 guías de química
├── admin/                  Panel administrador
└── oaktree.webp            Identidad OAKTREESKY
```

## Panel administrador

- Ruta: `/admin/`
- Clave por defecto del prototipo: `rumbo2026`
- Cambia la clave en `admin/index.html` (constante `PIN`) antes de un uso amplio en producción.
- Cada guía de química tiene su propio editor de preguntas (sección Administrador dentro de la guía). Los cambios se guardan en el navegador (localStorage).

## Notas

- Acceso libre: no requiere registro ni pago.
- El test de resiliencia es un **prototipo educativo**; los resultados son descriptivos, no un diagnóstico clínico.
- Todo funciona en el navegador, sin servidor obligatorio.

## Marca

- **RUMBO EDUCA** — marca educativa visible  
- **OAKTREESKY** — identidad corporativa  
