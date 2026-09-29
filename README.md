# 📚 Clásicos — catálogo de obras de dominio público

Aplicación web **estática** (HTML + CSS + JS puro, cero dependencias) para explorar un
catálogo de **2.400 obras clásicas de dominio público**: búsqueda por título, autor y
género; listados por autores, géneros y años; ficha bibliográfica por obra; modo
claro/oscuro/automático; diseño mobile-first.

Publicada en GitHub Pages: **https://hrodres.github.io/clasicos-web/**

## ✨ Funcionalidades

- 🔎 **Búsqueda instantánea** sobre título, autores y géneros, con resaltado de términos
- 👤 **Autores A–Z** con filtro por letra y carga incremental ("Mostrar más")
- 🏷️ **Géneros** y 📅 **años** con recuento de obras
- 📖 **Ficha de obra**: título, autor, año, páginas y géneros
- 🌗 **Tema claro / oscuro / automático**: sigue al sistema por defecto, con elección manual persistente (localStorage)
- 📱 **Mobile-first**: navegación inferior tipo app en móvil, tarjetas adaptativas en pantallas grandes
- ⚡ Sin frameworks, sin CDN, sin dependencias — funciona sin conexión

## 🗂️ Estructura

```
clasicos-web/
├── index.html          # Aplicación completa (HTML + CSS + JS en un solo archivo)
├── data/
│   └── books.json      # Metadatos bibliográficos (título, autor, año, género, páginas)
├── README.md
├── LICENSE             # MIT
├── DISCLAIMER.md       # Aviso legal
└── .nojekyll           # Desactiva Jekyll en GitHub Pages
```

## 🚀 Uso local

Cualquier servidor estático sirve:

```bash
python3 -m http.server 8000
# abre http://localhost:8000
```

## 📄 Datos

El catálogo contiene **únicamente metadatos bibliográficos** (título, autor, año,
género, nº de páginas) de obras cuyos autores fallecieron hace más de 70 años — es
decir, obras de **dominio público** según la legislación española (y en la mayoría de
países con el criterio de vida + 70 años).

**No se incluye ni se distribuye el texto de ninguna obra.** Este proyecto es una
demostración de interfaz web de catálogo, y los metadatos son datos factuales
(título, autor, año) no sujetos a derechos de autor.

## ⚖️ Licencia y aviso legal

- Código: licencia **MIT** (ver [LICENSE](LICENSE))
- Datos y uso: ver [DISCLAIMER.md](DISCLAIMER.md)

---
Hecho con ❤️ y cero dependencias.