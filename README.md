# 🐝 Mundo Amigo — ARG Educativo contra el Racismo y la Xenofobia

Experiencia transmedia (ARG educativo) de gamificación ética para el aula, dirigida a niñas y niños de **6 a 8 años**. Busca sensibilizar contra el racismo y la xenofobia promoviendo la empatía, la cooperación y el respeto a la diversidad.

Basado en la *Guía didáctica para sensibilizar contra el racismo y la xenofobia en las aulas* de la **Fundación Senara**, con fundamento en la ecología de los medios (Scolari / Jenkins).

## 🔗 Enlaces

- **Video introductorio (el que lee el código QR):** https://youtu.be/bvvmioCWK5I
- **Repositorio:** https://github.com/angie-beisy/antirracismo

> El código QR de la página de inicio apunta a ese video de YouTube. Al escanearlo con la cámara del móvil (o al hacer clic en él) se abre el video de iniciación para reflexionar sobre lo dañino que es excluir y discriminar.

## 🎯 Nodos de la experiencia

La actividad se organiza en cuatro nodos interactivos:

1. **Nodo 1 · Rompecabezas interactivo** — Arma escenas de convivencia arrastrando fichas (o por clic en móvil) y evalúa si la acción representada es adecuada, con retroalimentación pedagógica.
2. **Nodo 2 · Audiocuento inmersivo** — "El Nuevo Cole": un relato sonoro de inclusión con preguntas de reflexión y empatía, y un espacio para enviar mensajes al personaje.
3. **Nodo 3 · Entendiendo la xenofobia** — Casos sobre acento, costumbres y origen geográfico, con claves pedagógicas para valorar la diversidad.
4. **Nodo 4 · Mural colectivo** — Un lienzo de dibujo donde cada estudiante aporta su símbolo y una frase que lo hace único.

## 🛠️ Tecnologías

- **HTML5** (una sola página, `index.html`)
- **Tailwind CSS** (vía CDN — solo para desarrollo/prototipo)
- **JavaScript** puro (sin dependencias): rompecabezas arrastrable, canvas de dibujo y efectos de sonido con la Web Audio API
- **Google Fonts** (Fredoka e Inter) y **FontAwesome** para iconografía

## 🚀 Cómo usarlo

Es un proyecto estático sin build. Para abrirlo:

- Abre `index.html` directamente en el navegador, **o**
- Sírvelo con un servidor local, por ejemplo:

  ```bash
  python3 -m http.server 8000
  ```

  Luego visita `http://localhost:8000`.

## 📌 Pendientes conocidos

- Sustituir el audio de demostración por el **audiocuento oficial** una vez alojado.
- Reemplazar las imágenes del rompecabezas (actualmente desde el CDN de Unsplash) por imágenes propias con licencia.
- Para producción, **compilar Tailwind** con su CLI/PostCSS en lugar de usar el CDN.

## 🙌 Créditos

Diseño instruccional ético basado en la Guía didáctica de la **Fundación Senara**.
