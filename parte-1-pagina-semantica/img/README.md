# Post-contenido — Unidad 2: Programación Web

## Descripción
Repositorio correspondiente al laboratorio de la Unidad 2 de la materia Programación Web (Ingeniería de Sistemas — UFPS, Cúcuta). El proyecto reúne dos partes fundamentales desarrolladas con HTML5 nativo: una página de portafolio personal estructurada con etiquetas semánticas y un formulario de registro universitario con validación nativa.

---

## Estructura del Repositorio

- **`parte-1-pagina-semantica/`**: Contiene la maquetación semántica del portafolio personal (`index.html`), recursos gráficos, multimedia y metadatos SEO.
- **`parte-2-formulario-registro/`**: Contiene el formulario de registro universitario (`registro.html`) con más de 10 tipos de input y atributos de accesibilidad ARIA.

---

## Decisiones de Diseño

### 1. Estructura semántica de "Logros y Certificaciones" (Parte 1)
Se elegió la **Opción A** (marcar cada logro académico como un elemento `<article>` independiente con la etiqueta `<time>`)[cite: 1]. Se tomó esta decisión aplicando el criterio semántico de la guía teórica ("*¿tiene sentido por sí solo fuera del sitio?*"), considerando que cada hito de formación o proyecto relevante posee un valor descriptivo autocontenido que puede ser citado o redistribuido de manera independiente del portafolio[cite: 1].

### 2. Formato multimedia de la introducción personal (Parte 1)
Se elegió la **Opción B** (audio en formato `.mp3` acompañado de su transcripción completa y literal dentro de un elemento colapsable `<details>` / `<summary>`)[cite: 1]. Se tomó esta decisión aplicando las pautas de accesibilidad WCAG (principio Perceptible), garantizando que todo el contenido hablado en el audio sea accesible de forma textual palabra por palabra para cualquier usuario o tecnología de asistencia sin depender de un reproductor de video[cite: 1].

### 3. Marcado del campo opcional "teléfono" (Parte 2)
*(Se completará al desarrollar la Parte 2 del laboratorio)*[cite: 1].

---

## Cómo visualizar el proyecto

1. Clonar el repositorio desde GitHub:
   ```bash
   git clone [https://github.com/diegoalferez/Alferez-post1-u2.git](https://github.com/diegoalferez/Alferez-post1-u2.git)