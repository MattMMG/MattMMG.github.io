# 👤 Matias Maciel Gabriel — Personal Portfolio

> **IAM & Cybersecurity Specialist** · Zero Trust Advocate · Buenos Aires, Argentina

Portfolio web personal desarrollado en HTML/CSS/JS puro, sin frameworks ni dependencias de build. Diseñado para ser desplegado directamente en GitHub Pages.

---

## 🌐 Demo

**Live site:** [https://MattMMG.github.io](https://MattMMG.github.io)

---

## 📁 Estructura del repositorio

```
/
├── index.html              # Sitio completo (single-file)
├── CV foto.jpg             # Foto de perfil (hero section)
├── CV_Matias_Maciel.pdf    # CV en español (botón de descarga)
├── MMG CV 2026.pdf         # CV en inglés (botón de descarga)
└── README.md               # Este archivo
```

---

## ✨ Features

- **Multilenguaje** — Español, Inglés y Portugués con switch instantáneo sin recarga de página
- **Timeline interactiva** — Experiencia profesional en layout alternado (izquierda/derecha) en desktop, lineal en mobile
- **Descarga de CV bilingüe** — Botón flotante con popup para elegir entre CV en español o inglés
- **Starfield animado** — Fondo con partículas/estrellas generadas dinámicamente via JS
- **Scroll reveal** — Secciones con animación de entrada al hacer scroll (IntersectionObserver)
- **Responsive** — Adaptado para mobile, tablet y desktop
- **Menú mobile** — Hamburger menu con toggle para pantallas pequeñas
- **Fallback de foto** — Si no carga la imagen de perfil, muestra un avatar placeholder

---

## 🛠️ Stack técnico

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura y contenido |
| CSS3 + Tailwind CDN | Estilos y layout responsivo |
| JavaScript vanilla | Traducción, animaciones, interactividad |
| Font Awesome 6 | Iconografía |
| Google Fonts | Tipografías (Syne + Space Mono) |

> ⚠️ No requiere Node.js, npm ni proceso de build. Todo corre directamente en el browser.

---

## 🚀 Deploy en GitHub Pages

1. Cloná o subí este repositorio a GitHub
2. Andá a **Settings → Pages**
3. En *Source* seleccioná `Deploy from a branch`
4. Elegí la rama `main` (o `master`) y la carpeta `/ (root)`
5. Guardá — en unos minutos el sitio estará live en `https://<tu-usuario>.github.io`

> Asegurate de que `CV_Matias_Maciel.pdf` y `MMG CV 2026.pdf` estén en la raíz del repositorio para que los botones de descarga funcionen correctamente.

---

## ✏️ Cómo editar el contenido

### Cambiar textos / traducciones
Todos los textos traducibles usan el patrón `data-es`, `data-en`, `data-pt` en los elementos HTML:
```html
<span class="lang-text"
      data-es="Texto en español"
      data-en="Text in English"
      data-pt="Texto em português">
</span>
```

### Cambiar la foto de perfil
Reemplazá el archivo `CV foto.jpg` en la raíz del repositorio manteniendo el mismo nombre, o editá el atributo `src` en el `<img>` del hero:
```html
<img src="CV foto.jpg" alt="Matias Maciel Gabriel" ...>
```

### Agregar una nueva experiencia laboral
Copiá un bloque `.tl-item` dentro de `<div class="max-w-5xl mx-auto timeline-wrapper">` y editá los atributos `data-es`, `data-en`, `data-pt` con la nueva información.

### Actualizar los CVs descargables
Reemplazá los archivos PDF en la raíz del repositorio. Si cambiás los nombres, actualizá los `href` en el botón flotante:
```html
<a href="CV_Matias_Maciel.pdf" ...>   <!-- CV en español -->
<a href="MMG CV 2026.pdf" ...>        <!-- CV en inglés  -->
```

### Agregar un nuevo skill chip
Dentro de la sección `#skills`, agregá un `<span>` con la clase `skill-chip`:
```html
<span class="skill-chip">Nuevo Skill</span>
```

---

## 📬 Contacto

| Canal | Link |
|---|---|
| LinkedIn | [linkedin.com/in/matiasgmaciel](https://www.linkedin.com/in/matiasgmaciel/) |
| GitHub | [MattMMG.github.io](https://MattMMG.github.io) |
| Email | mati.maciel7@gmail.com |

---

<p align="center">
  © 2026 Matias Maciel Gabriel &nbsp;·&nbsp; Zero Trust Advocate
</p>
