# Alejandro Escalante — CV digital

Currículum digital bilingüe (ES/EN) de **Gerardo Alejandro Escalante Orellana**, *AI Solutions Engineer · Google Cloud Professional Machine Learning Engineer*.

🔗 **En vivo:** https://aleescalante.github.io

## Sobre el sitio

Página estática de una sola pieza (`index.html`), sin dependencias de build. El contenido bilingüe se gestiona desde un objeto `DATA` en el `<script>` y se alterna con el selector **ES / EN**.

- **Diseño:** dossier editorial técnico — tipografía Fraunces + JetBrains Mono, tema tinta cálida, retícula y grano sutil.
- **Stack:** HTML + CSS + JS puro. Tipografías vía Google Fonts.
- **Hosting:** GitHub Pages.

## Editar el contenido

Todo el texto vive en el objeto `DATA` dentro de `index.html`. Cada campo tiene versión `es` y `en`. Edita ahí y haz commit; GitHub Pages se actualiza solo.

## Desarrollo local

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python -m http.server 8000
# http://localhost:8000
```
