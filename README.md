# Post-contenido — Unidad 2: Programación Web

## Descripción
Repositorio correspondiente al laboratorio de la Unidad 2 de la materia Programación Web (Ingeniería de Sistemas — UFPS, Cúcuta). El proyecto reúne dos partes desarrolladas con HTML5 nativo: una página de portafolio personal estructurada con etiquetas semánticas y un formulario de registro universitario con validación nativa.

---

## Estructura del Repositorio

- `parte-1-pagina-semantica/`: Contiene la maquetación semántica del portafolio personal (`index.html`), recursos gráficos, multimedia y metadatos SEO.

---

## Decisiones de Diseño

### 1. Estructura semántica de "Logros y Certificaciones" (Parte 1)
Se eligió la **Opción A** (marcar cada logro académico como un elemento `<article>` independiente con la etiqueta `<time>`). Se tomó esta decisión aplicando el criterio semántico de la guía teórica ("*¿tiene sentido por sí solo fuera del sitio?*"), considerando que cada hito de formación o proyecto relevante posee un valor descriptivo autocontenido que puede ser citado o redistribuido de manera independiente del portafolio.

### 2. Formato multimedia de la introducción personal (Parte 1)
Se eligió la **Opción B** (audio en formato `.mp3` acompañado de su transcripción completa y literal dentro de un elemento colapsable `<details>` / `<summary>`). Se tomó esta decisión aplicando las pautas de accesibilidad WCAG (principio Perceptible), garantizando que todo el contenido hablado en el audio sea accesible de forma textual palabra por palabra para cualquier usuario o tecnología de asistencia sin depender de un reproductor de video[cite: 1].

---

## Cómo visualizar el proyecto

1. Clonar el repositorio desde GitHub:
   ```bash
   git clone [https://github.com/diegoalferez/Alferez-post1-u2.git](https://github.com/diegoalferez/Alferez-post1-u2.git)