---
name: LeonardSF GitHub Profile
description: Bitácora de ingeniería con un plano técnico cyan que conecta identidad, proceso y productos reales.
colors:
  hero-ink: "#06111a"
  hero-depth: "#0a1f2d"
  hero-node: "#0a1a25"
  hero-build: "#0d2836"
  signal-cyan: "#22d3ee"
  signal-soft: "#67e8f9"
  hero-text: "#f8fafc"
  hero-subtitle: "#c7f9ff"
  hero-muted: "#8ab9c5"
  hero-technical: "#5fa6b6"
  hero-stroke: "#1b5668"
  hero-grid: "#164254"
  canvas-dark: "#0d1117"
  canvas-light: "#ffffff"
  text-dark: "#f0f6fc"
  text-light: "#1f2328"
  text-muted-dark: "#8b949e"
  text-muted-light: "#656d76"
  link-dark: "#58a6ff"
  link-light: "#0969da"
  rule-dark: "#30363d"
  rule-light: "#d0d7de"
  code-dark: "rgba(110, 118, 129, 0.4)"
  code-light: "rgba(175, 184, 193, 0.2)"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: "2em"
    fontWeight: 600
    lineHeight: 1.25
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: "1.5em"
    fontWeight: 600
    lineHeight: 1.25
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: "1.25em"
    fontWeight: 600
    lineHeight: 1.25
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, monospace"
    fontSize: "0.85em"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  none: "0"
  code: "6px"
  node: "14px"
  hero-desktop: "20px"
  hero-mobile: "24px"
spacing:
  tight: "4px"
  inline: "8px"
  paragraph: "16px"
  section: "24px"
components:
  technical-hero:
    backgroundColor: "{colors.hero-ink}"
    textColor: "{colors.hero-text}"
    rounded: "{rounded.hero-desktop}"
    width: "100%"
  link-primary:
    textColor: "{colors.link-light}"
    typography: "{typography.body}"
  technical-label:
    backgroundColor: "{colors.code-light}"
    textColor: "{colors.text-light}"
    typography: "{typography.label}"
    rounded: "{rounded.code}"
    padding: "2px 6px"
  section-rule:
    backgroundColor: "{colors.rule-light}"
    height: "1px"
    width: "100%"
---

# Design System: LeonardSF GitHub Profile

## Overview

**Creative North Star: "Bitácora de ingeniería"**

El perfil se siente como un registro técnico escrito por una persona que construye: directo, abierto y verificable. Un plano azul-negro abre la lectura y convierte proceso, áreas de trabajo y conexiones reales en geometría técnica; el resto conserva el lenguaje nativo de GitHub, no una página promocional disfrazada dentro de Markdown.

El cyan funciona como señal: recorre conexiones, marca estados y subraya identidad sin teñir todo el documento. El hero contiene la única expresión principal de nombre y especialidad; debajo sólo continúan la acción dominante, la navegación secundaria, los proyectos, las herramientas y el contacto. Los bloques editoriales permanecen abiertos; los nodos cerrados pertenecen únicamente al diagrama.

**Key Characteristics:**

- Hero azul-negro con cyan de señal sobre la paleta nativa de GitHub.
- Diagrama técnico geométrico que representa BUILD → productos.
- Composición específica para escritorio y móvil mediante `picture`.
- Movimiento lento de flujo, pulso y escaneo con alternativa de movimiento reducido.
- Identidad expresada una sola vez dentro del hero, seguida únicamente por acciones.
- Jerarquía editorial compacta, con una sola llamada principal al portafolio.
- Secciones abiertas separadas por espacio y reglas finas.
- Etiquetas monoespaciadas reservadas para datos técnicos reales.
- Evidencia textual por encima de adornos, métricas o autoelogios.

## Colors

La paleta combina un hero azul-negro autónomo con el lienzo nativo de GitHub. Cyan identifica señal y proceso; el azul estándar sigue reservado para navegación; los neutros ordenan la lectura.

### Primary

- **Cyan de señal:** traza conexiones, pulsos, la barra de identidad y puntos de estado dentro del plano técnico.
- **Azul de enlace GitHub:** identifica destinos accionables fuera del diagrama y nunca funciona como relleno ornamental.

### Secondary

- **Azul-negro de plano:** gradiente profundo que separa el hero del lienzo de GitHub sin depender del tema activo.
- **Cyan suave:** texto técnico y énfasis secundarios dentro del plano.

### Neutral

- **Lienzo GitHub:** fondo claro u oscuro controlado por el tema del lector.
- **Tinta principal:** títulos, descripciones y datos con contraste suficiente en ambos temas.
- **Tinta secundaria:** contexto y navegación de menor prioridad.
- **Regla fina:** divisores estructurales entre grandes bloques.
- **Fondo de código:** soporte discreto para etiquetas técnicas inline.

### Named Rules

**The Native Theme Rule.** Toda elección debe seguir siendo legible en los temas claro y oscuro de GitHub; no se depende de un color de fondo fijo.

**The Blue Means Destination Rule.** El azul se reserva para enlaces reales y mantiene visible qué texto conduce a otro lugar.

**The Cyan Means Signal Rule.** El cyan pertenece al sistema técnico del hero: indica conexión, proceso o estado; no sustituye el azul de enlace.

## Typography

**Display Font:** pila sans serif del sistema de GitHub

**Body Font:** pila sans serif del sistema de GitHub

**Label/Mono Font:** pila monoespaciada del sistema de GitHub

**Character:** sobria, familiar y altamente legible. La variación viene de escala, peso y cambio funcional a monoespaciada; no de combinar familias decorativas.

### Hierarchy

- **Display** (semibold, `2em`, `1.25`): nombre del perfil y única entrada de máxima jerarquía.
- **Headline** (semibold, `1.5em`, `1.25`): títulos de sección.
- **Title** (semibold, `1.25em`, `1.25`): nombres de proyectos.
- **Body** (regular, `16px`, `1.5`): descripciones breves y concretas.
- **Label** (regular, `0.85em`, `1.5`): tecnologías y datos de stack exclusivamente.

### Named Rules

**The Evidence Before Adjectives Rule.** El peso tipográfico destaca nombres, acciones y resultados; no convierte frases promocionales en titulares.

## Layout

El documento usa una sola columna fluida dentro del ancho de lectura que GitHub proporciona. El plano técnico ocupa el 100% del ancho disponible y asume por completo la identidad principal. Debajo quedan sólo el CTA dominante y la navegación secundaria, centrados como una transición compacta hacia el registro de proyectos. El contenido vuelve después a alineación izquierda para facilitar el escaneo técnico. El ritmo avanza en incrementos compactos de 4, 8, 16 y 24 píxeles.

El `picture` bifurca la composición en `600px`: escritorio usa un plano panorámico (`1200 × 360`) con identidad a la izquierda y red a la derecha; móvil usa un plano más alto (`720 × 420`) con identidad arriba y tres nodos en la base. No se encoge el layout panorámico. El CTA puede envolver en móvil, pero nombre, especialidad o avatar no reaparecen fuera del SVG.

**The Single Identity Rule.** El hero es la única identidad principal; después de él no se repiten avatar, nombre, especialidad ni frase de presentación.

**The Open Block Rule.** Los proyectos se separan con ritmo y encabezados, no con tarjetas, fondos individuales o cuadrículas que compitan con el contenido.

## Elevation & Depth

El sistema editorial es plano y no usa sombras. El hero obtiene profundidad de un gradiente azul-negro, retícula tenue, capas tonales y un resplandor focal reservado a puntos cyan. Flujo de líneas (`7–8s` lineal), pulsos escalonados (`3.6s`) y barrido de escritorio (`9s`) comunican actividad sin bloquear la lectura; `prefers-reduced-motion: reduce` detiene todas las animaciones.

**The Flat Record Rule.** Ningún bloque editorial recibe sombra, brillo o elevación; el resplandor queda confinado a las señales del diagrama.

**The Motion Is Status Rule.** Movimiento sólo explica flujo o estado y siempre ofrece una versión estática equivalente.

## Shapes

La geometría es funcional. El hero es un panel redondeado (`20px` en escritorio, `24px` en móvil); sus nodos técnicos usan radios de `12–14px` y conectores ortogonales. Las reglas son rectas; los bloques editoriales no tienen contorno. Las etiquetas de código heredan esquinas discretamente redondeadas (`6px`) de GitHub.

## Components

### Technical Hero

- **Surface:** gradiente azul-negro, retícula geométrica y borde azul petróleo fino.
- **Desktop:** nombre y disciplina a la izquierda; nodo BUILD central; MI SAES, WEB y AUTOMATIZACIÓN conectados a la derecha.
- **Mobile:** variante dedicada con identidad arriba, BUILD centrado y tres nodos inferiores legibles.
- **Signal:** cyan para conectores, pulsos, scan y subrayado; blancos azulados para texto.
- **Motion:** `flow`, `pulse` y `scan` son lentos, desfasados y se desactivan por completo con movimiento reducido.
- **Delivery:** ambos SVG se sirven mediante `picture`; el texto alternativo resume identidad y ámbitos, no describe cada adorno.

### Action Block

- **Structure:** CTA textual al portafolio y navegación secundaria inmediatamente después del hero.
- **Priority:** `leonardsf.dev` es la única acción dominante; repositorios y Telegram permanecen subordinados.
- **Behavior:** contenido centrado, sin repetir nombre, avatar, especialidad ni descripción personal.

### Project Entry

- **Structure:** nombre, explicación del problema o utilidad y stack comprobable.
- **Container:** bloque abierto sin borde, fondo ni sombra.
- **Link state:** el nombre usa azul sólo cuando existe un destino público.

### Technical Labels

- **Style:** código inline monoespaciado, fondo neutral tenue, padding compacto y radio discreto.
- **Content:** nombres de lenguajes, plataformas, herramientas o capacidades verdaderas; nunca categorías aspiracionales.

### Navigation

- **Primary:** enlace textual explícito al portafolio, visible antes del registro de proyectos.
- **Secondary:** enlaces de GitHub y Telegram en una línea compacta y separada con puntuación neutral.
- **States:** subrayado y color quedan bajo el comportamiento accesible nativo de GitHub.

## Do's and Don'ts

### Do:

- **Do** presentar cada proyecto con nombre, utilidad concreta y stack verificable.
- **Do** mantener `leonardsf.dev` como acción principal inequívoca.
- **Do** usar encabezados semánticos, texto alternativo útil y enlaces comprensibles fuera de contexto.
- **Do** probar la lectura en los temas claro y oscuro y en ancho móvil.
- **Do** dejar que espacio, peso y reglas finas construyan la jerarquía.
- **Do** mantener variantes SVG separadas para escritorio y móvil en vez de escalar una sola composición.
- **Do** incluir `prefers-reduced-motion` en cualquier movimiento futuro del plano técnico.
- **Do** tratar el texto accesible del SVG como respaldo de la identidad visual principal.

### Don't:

- **Don't** añadir badges decorativos, contadores, barras de progreso o métricas sin contexto real.
- **Don't** usar emojis como iconografía, separadores o sustitutos de etiquetas.
- **Don't** encerrar cada proyecto en una tarjeta ni simular una landing page con tablas HTML.
- **Don't** usar etiquetas técnicas para conceptos vagos o competencias no demostradas.
- **Don't** escribir copy genérico, grandilocuente o con tono de agencia.
- **Don't** reutilizar el cyan como color de enlace o acento decorativo fuera del sistema de señal.
- **Don't** añadir movimiento que no represente flujo, estado o escaneo técnico.
- **Don't** repetir debajo del hero avatar, nombre, especialidad o frase de presentación.
