# Publicar la versión de 2 h (curso base) en GitHub Pages

Los QR de esta presentación apuntan a `https://lalot127-coder.github.io/jornada40multas/curso2h/manual.html`
(pestañas `#diagnostico`, `#m2`, `#repaso`, `#evaluacion`). **Funcionan hasta que subas la carpeta `curso2h`.**

1. En https://github.com/lalot127-coder/jornada40multas → **Add file → Upload files**.
2. Arrastra la **carpeta** `curso2h` completa (GitHub conserva la subcarpeta): `manual.html` y
   `simulador_costos_jornada.html`.
3. **Commit changes**, espera 1–2 minutos y prueba: https://lalot127-coder.github.io/jornada40multas/curso2h/manual.html
4. El checklist completo es el mismo de la raíz (`index.html`), que ya sube la versión del simposio.

Antes de cada sede: cambia en `contenido.py` sede, fecha y horario y vuelve a generar
(`python generar_presentacion.py`, `python generar_documentos.py`, `python 05_herramientas/manual_digital.py <carpeta>`),
o edita solo la portada en PowerPoint: el pie ya no lleva datos de la sede.
