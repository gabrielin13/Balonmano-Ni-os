🦁 ¡Aprende Balonmano! — Infografía PWA Interactiva
Una aplicación web progresiva (PWA) educativa e interactiva diseñada para enseñar los fundamentos del balonmano a niños de 8 a 12 años. Construida como un único archivo HTML autocontenido, sin dependencias de servidor ni archivos externos.

HTML5CSS3JavaScriptPWA

🎯 Propósito Pedagógico
Basada en los principios de diseño instruccional de Mayer, esta infografía digital:

Transmite UNA sola idea central → El objetivo del balonmano: marcar goles.
Presenta solo 3 a 5 datos clave → 7 jugadores, 3 pasos, 30 minutos, zona de 6m.
Usa narrativa y personaje-guía → Un león animado que guía al niño con tono lúdico.
Estructura visual lineal → Desplazamiento vertical simple, sin menús complejos.
Elimina elementos decorativos sin función → Principio de Coherencia.
✨ Funcionalidades Principales
🦁 Mascota Animada: Un león con animaciones de salto y cabeceo que guía la experiencia.
🃏 Flip Cards Interactivas: Tarjetas con efecto 3D al pasar el cursor o tocar, que revelan información detallada.
🏟️ Diagrama del Campo: Representación SVG interactiva del campo de balonmano con zonas, medidas y posición de jugadores.
🧠 Quiz Interactivo: Evaluación de 4 preguntas con retroalimentación visual inmediata (correcto/incorrecto) y puntaje final.
📱 PWA Instalable: Funciona offline mediante un Service Worker embebido y permite su instalación en dispositivos móviles y de escritorio.
♿ Accesibilidad: Uso de etiquetas ARIA, aria-live para el quiz, soporte de navegación por teclado y respeto a prefers-reduced-motion.
🎨 Diseño Responsivo: Adaptado para móviles, tablets y escritorio (desde 375px).
🛠️ Tecnologías Utilizadas
HTML5 Semántico: <header>, <main>, <section>, <footer>.
CSS3: Animaciones @keyframes, perspective, transform-style: preserve-3d, Grid, Flexbox.
JavaScript Vanilla: IntersectionObserver para scroll reveal, lógica de quiz, registro de Service Worker.
SVG: Diagrama vectorial del campo de balonmano.
Google Fonts: Baloo 2 (títulos) y Nunito (cuerpo).
🚀 Cómo Usar
Descarga el archivo index.html (o balonmano-ninos.html).
Ábrelo directamente en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
¡Listo! La aplicación funcionará inmediatamente.
Para probar la funcionalidad PWA (Offline / Instalable)
Los Service Workers requieren un servidor HTTP para funcionar correctamente. Puedes usar uno local rápido:

Con Python:

# Python 3python -m http.server 8000
Luego abre http://localhost:8000 en tu navegador.

Con Node.js:

bash

npx serve .
🎨 Especificaciones de Diseño
Elemento
Especificación
Tipografía	Baloo 2 (títulos), Nunito (cuerpo) — Mínimo 18px
Colores	Naranja #FF6B35, Amarillo #FFD60A, Azul #1B74E4, Verde #2ECC71, Rojo #E74C3C
Fondo	Cálido y limpio: #FFF9F0
Estilo	Flat / cartoon, emojis figurativos, cards grandes
Touch Targets	Mínimo 44x44px en todos los botones

📂 Estructura del Archivo
Al ser un archivo único autocontenido, toda la estructura vive dentro de index.html:

👤 Autor
Gabriel Adrian Navarro Puertas

📝 Créditos y Fuentes
Contenido basado en la infografía de balonmano publicada por EL MUNDO (Coordina: F.A. Anguís · Textos: Carolina G. Miranda).
Prompt elaborado para uso docente en diseño de infografías digitales interactivas.
Este proyecto fue diseñado con fines educativos para uso en el aula o en dispositivos móviles de niños de primaria.
```



