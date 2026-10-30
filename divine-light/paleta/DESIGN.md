---
version: alpha
name: Divine Light
description: Papel cálido y tinta azul marino, con un calipso apagado como acento principal y un rosa empolvado como segunda nota. Sin dorado y sin tierra oscura.
colors:
  primary: "#36374B"
  secondary: "#6A5C49"
  accent: "#70A3B2"
  accent-soft: "#B9D2D8"
  accent-ink: "#43616A"
  accent-deep: "#4E727C"
  rose: "#DAA79F"
  rose-soft: "#E6C5C0"
  rose-ink: "#775B57"
  gold: "#D9B26B"
  gold-soft: "#EFD9B4"
  gold-ink: "#7A5C26"
  sky: "#CFE4EC"
  glow: "#F7E3C4"
  dawn: "#FBEFDD"
  taupe: "#AB9D8B"
  page: "#F6F1EB"
  surface-0: "#FFFFFF"
  surface-1: "#FFFCF6"
  surface-2: "#F9F4EE"
  surface-3: "#F6F1EB"
  surface-4: "#F2EDE5"
  surface-5: "#E6DED5"
  surface-6: "#DED5CA"
  neutral: "#FFFCF6"
  sand: "#E6DED5"
  sand-soft: "#F2EDE5"
  line: "#CEC4B7"
  charcoal: "#353535"
  body-text: "#353535"
  white: "#FFFFFF"
typography:
  display-serif:
    fontFamily: Piazzolla
    fontSize: clamp(44px, 6.4vw, 92px)
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  heading-serif:
    fontFamily: Piazzolla
    fontSize: clamp(30px, 4vw, 54px)
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: "-0.015em"
  subtitle-serif-italic:
    fontFamily: Piazzolla
    fontSize: clamp(20px, 2.4vw, 28px)
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: "0em"
  lead:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: 300
    lineHeight: 1.65
  body:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: DM Sans
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.18em"
rounded:
  xs: 2px
  sm: 8px
  md: 12px
  lg: 18px
  xl: 24px
  pill: 999px
spacing:
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 48px
  2xl: 80px
  section: 120px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 16px 34px
  button-primary-hover:
    backgroundColor: "{colors.charcoal}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 16px 34px
  button-accent:
    backgroundColor: "{colors.accent-soft}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 16px 34px
  button-ghost:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 16px 34px
  card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.body-text}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-accent:
    backgroundColor: "{colors.accent-soft}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-accent-hover:
    backgroundColor: "{colors.accent-deep}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-sand:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-sand-soft:
    backgroundColor: "{colors.sand-soft}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  band-accent-deep:
    backgroundColor: "{colors.accent-deep}"
    textColor: "{colors.neutral}"
    typography: "{typography.label}"
    padding: 10px 18px
  eyebrow:
    backgroundColor: "{colors.sand-soft}"
    textColor: "{colors.accent-ink}"
    typography: "{typography.label}"
  chip:
    backgroundColor: "{colors.white}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 7px 16px
  link-on-light:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.accent-ink}"
    typography: "{typography.body}"
  text-muted:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.secondary}"
    typography: "{typography.body}"
  price-value:
    backgroundColor: "{colors.white}"
    textColor: "{colors.primary}"
    typography: "{typography.heading-serif}"
  nav-on-dark:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
  divider:
    backgroundColor: "{colors.line}"
    height: 1px
  section-on-page:
    backgroundColor: "{colors.page}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  underline-accent:
    backgroundColor: "{colors.accent}"
    height: 2px
  toggle-taupe:
    backgroundColor: "{colors.taupe}"
    textColor: "{colors.charcoal}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 6px 14px
  button-rose:
    backgroundColor: "{colors.rose}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 16px 34px
  card-rose:
    backgroundColor: "{colors.rose-soft}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  link-rose:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.rose-ink}"
    typography: "{typography.body}"
  section-on-white:
    backgroundColor: "{colors.surface-0}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  section-on-cream:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  section-on-paper:
    backgroundColor: "{colors.surface-3}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  section-on-sand:
    backgroundColor: "{colors.surface-5}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  section-on-cream-sand:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  card-on-sand-soft:
    backgroundColor: "{colors.surface-4}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-on-sand:
    backgroundColor: "{colors.surface-0}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  card-on-white:
    backgroundColor: "{colors.surface-5}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  band-sand-deep:
    backgroundColor: "{colors.surface-6}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    padding: 10px 18px
  hero-dawn:
    backgroundColor: "{colors.dawn}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  section-glow:
    backgroundColor: "{colors.glow}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  section-sky:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  button-gold:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 16px 34px
  card-gold:
    backgroundColor: "{colors.gold-soft}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 32px
  link-gold:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.gold-ink}"
    typography: "{typography.body}"
  footer-light:
    backgroundColor: "{colors.surface-5}"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
  footer-dark:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
---

## Overview

Divine Light Journey es la marca con la que Zuzel acompaña procesos de conciencia: comunidad, meditaciones y
programas de 40 días. La web no vende urgencia, vende **calma sostenida**. Por eso el sistema es cálido y
silencioso: papel cálido, tinta azul marino y un **calipso apagado** que solo aparece donde hay que mirar.

El principio es el de la luz sobre papel: el fondo de página es un papel cálido (`#F6F1EB`), las secciones
suben a crema (`#FFFCF6`) y las tarjetas al blanco; el texto se apoya en una tinta azul marino profunda
(`#36374B`), no en negro. Esa distancia corta entre los claros es lo que hace que la página respire sin verse
vacía: el contraste no viene del color, viene del grosor del texto y del espacio.

El calipso es el gesto de color principal y tiene una regla dura: **`#70A3B2` es relleno, no texto pequeño**. Sobre
crema da 2.71:1. Para texto sobre fondo claro se usa su tinta `#43616A` (6.50:1); para fondo de tarjeta o botón
secundario se usa el calipso claro `#B9D2D8`, que deja el texto marino en 7.35:1.

El **rosa empolvado `#DAA79F`** es la segunda nota, aportada por Héctor el 29-oct: la calidez de la marca cuando
el calipso no basta (tarjetas de programa, cabeceras, detalles). También es relleno, pero admite texto marino
encima (5.55:1); con texto crema o blanco no cumple (2.05:1).

Los valores de este documento están medidos sobre `https://lorieladd.com/40-days` (la guía de color que fijó
Héctor el 29-oct-2026): tokens leídos de su CSS, fondos de sección y acentos localizados uno a uno. Son
normativos: si algo no está aquí, no es marca. Son **independientes de la propuesta de diseño** pendiente de
aprobación: si la propuesta cambia, estos colores no.

## Colors

- **Primary `#36374B` (azul marino):** titulares, texto corrido de peso alto, botón primario, fondo de las
  secciones oscuras. Es la voz de la marca y sustituye al negro.
- **Accent `#70A3B2` (calipso):** el acento de la guía. Filetes, subrayados, degradados, iconos y fondos
  decorativos. **Nunca texto sobre fondo claro** (2.71:1 sobre crema). Sobre marino sí vale como texto grande:
  4.19:1, uso reservado a ≥24px.
- **Accent soft `#B9D2D8`:** el calipso para relleno que lleva texto encima. Fondo de la tarjeta destacada y del
  botón secundario, con texto marino (7.35:1).
- **Accent ink `#43616A`:** el calipso cuando es texto sobre fondo claro. 6.50:1 sobre crema, 5.92:1 sobre el
  papel de página y 5.00:1 sobre arena. Es el color de enlaces, antetítulos y precios cuando no van en tinta.
- **Accent deep `#4E727C`:** el extremo del degradado del calipso y el fondo oscuro que lleva texto crema
  (5.10:1). Es el hover de la tarjeta destacada.
- **Rose `#DAA79F` (rosa empolvado):** la segunda nota de color. Fondo de tarjeta de programa, cabecera con
  degradado, botón secundario cálido y detalles. Admite texto marino encima (5.55:1) pero **nunca texto crema o
  blanco** (2.05:1). Sobre fondo claro no se usa como texto.
- **Rose soft `#E6C5C0`:** el rosa aclarado para bloques grandes que llevan texto marino (7.26:1).
- **Rose ink `#775B57`:** el rosa cuando es texto sobre fondo claro. 6.00:1 sobre crema, 5.47:1 sobre el papel de
  página y 4.61:1 sobre arena.
- **Gold `#D9B26B` (dorado de luz):** el dorado que pidió Zuzel el 30-oct — «un tono dorado que tenga que ver
  con la luz». Filetes, iconos, subrayados y el extremo cálido del degradado de amanecer. **Solo relleno**
  (1.95:1 sobre crema); con texto marino encima da 5.83:1.
- **Gold soft `#EFD9B4`:** el dorado pálido para superficies grandes que llevan texto (marino 8.45:1).
- **Gold ink `#7A5C26`:** el dorado cuando es texto sobre fondo claro. 6.06:1 sobre crema, 5.52:1 sobre papel y
  4.66:1 sobre arena.
- **Sky `#CFE4EC`, Glow `#F7E3C4`, Dawn `#FBEFDD`:** los tres stops del cielo de amanecer. `sky` arriba (azul
  claro), `glow` en el horizonte (dorado pálido) y `dawn` abajo (crema rosada). Texto marino en los tres:
  8.84:1, 9.27:1 y 10.25:1.
- **Taupe `#AB9D8B`:** estados, interruptores y detalles apagados, medido en la guía. **Solo relleno**: 2.59:1
  sobre crema; con texto lleva carbón `#353535` (4.63:1), no marino.
- **Page `#F6F1EB`:** fondo de página — es el `background-color` del body en la guía. El crema puro **no** es el
  fondo de página; es la capa de sección.
- **Neutral `#FFFCF6` (crema de papel):** secciones y superficies elevadas; también el texto sobre marino.
- **Sand `#E6DED5` y sand-soft `#F2EDE5`:** arena de la guía y su versión al 50% sobre crema (capas
  intermedias, tarjetas informativas).
- **Line `#CEC4B7`:** todos los bordes de 1px. Sobre crema separa sin dibujar caja; 1.68:1 es un borde, no
  información.
- **Secondary `#6A5C49` (marrón cálido):** texto secundario, metadatos, pies. 6.33:1 sobre crema, 5.77:1 sobre
  el papel de página.
- **Charcoal `#353535`:** color del texto corrido en la guía y hover del botón primario. Es el único gris neutro
  del sistema; no introduce familia nueva.
- **Fuera del sistema:** el violeta de la barra de cookies de la guía (`#5A5090`, componente de terceros),
  cualquier rosa que no sea `#DAA79F` y cualquier dorado que no sea `#D9B26B`.

**Superficies — la escala de fondo.** El fondo no es un solo beige: hay una rampa de siete pasos que va del
blanco puro a la arena profunda, y cada paso se usa con un papel concreto. Los pasos intermedios están
calculados mezclando blanco con la arena de la guía (`#E6DED5`), no elegidos a ojo.

| token | valor | papel | marino encima |
|---|---|---|---|
| `surface-0` | `#FFFFFF` | tarjetas, superficies elevadas, secciones de respiración | 11.63:1 |
| `surface-1` | `#FFFCF6` | crema de la guía: sección clara por defecto | 11.36:1 |
| `surface-2` | `#F9F4EE` | crema-arena: sección alterna suave | 10.64:1 |
| `surface-3` | `#F6F1EB` | papel de página (el `body` de la guía) | 10.36:1 |
| `surface-4` | `#F2EDE5` | arena suave: tarjetas informativas, chips | 9.98:1 |
| `surface-5` | `#E6DED5` | arena de la guía: bandas y bloques destacados | 8.74:1 |
| `surface-6` | `#DED5CA` | arena profunda: pie, avisos, cierre | 7.96:1 |

**Cómo se alternan.** Blanco y crema se mezclan sin miedo: una página puede empezar en blanco, seguir en crema y
cerrar en arena. La regla es la del salto de luz: entre dos capas con **menos de 1.15:1** de diferencia (papel
`#F6F1EB` contra crema `#FFFCF6` = 1.10:1; papel contra blanco = 1.12:1) hace falta un **filete de 1px** o la
división no se ve; a partir de **1.30:1** (crema contra arena) la capa se lee sola y el filete es opcional
(decorativo, no estructural).

**No** se apilan tres claros seguidos sin filete, ni se pone una tarjeta blanca sobre crema sin borde. Sí se
puede: tarjeta blanca sobre arena, tarjeta arena sobre blanco, sección crema entre dos blancas, banda de arena
profunda al cierre.

**Luz, no oscuridad.** El proyecto trata de luz, y el diseño tiene que parecerlo: **no hay secciones de página
oscuras**. Donde antes había un hero o un cierre en carbón o marino, ahora hay un **cielo de amanecer**:

```
linear-gradient(180deg, #CFE4EC 0%, #E7E4D8 38%, #F7E3C4 68%, #FBEFDD 100%)
```

Azul claro arriba, dorado pálido en el horizonte, crema rosada abajo. El texto va siempre en tinta `#36374B`
(8.84:1 arriba, 10.25:1 abajo). Los únicos fondos oscuros que quedan son **de componente, no de página**: el marco
del reproductor de vídeo, el velo de una foto y la **variante oscura del pie**.

**El pie tiene dos versiones** (decisión de Héctor, 30-oct). `footer-light` — arena `#E6DED5` con texto marino y
monograma en dorado tinta — es la **de por defecto**: es la que responde a lo que pidió la clienta. `footer-dark` —
marino `#36374B` con texto crema y monograma en dorado `#D9B26B` (5.83:1) — se ofrece como alternativa para
cierres que necesiten contraste duro. Mismo contenido, misma rejilla, mismo monograma: solo cambia la capa.

**Accesibilidad — lo que manda.** Todo par texto/fondo está medido:

| Combinación | Ratio | Uso |
|---|---|---|
| `#FFFCF6` sobre `#36374B` | 11.36:1 | texto sobre marino (nav y botón primario) |
| `#FFFFFF` sobre `#36374B` | 11.63:1 | tarjetas sobre marino |
| `#36374B` sobre `#FFFCF6` | 11.36:1 | titulares y cuerpo sobre sección |
| `#36374B` sobre `#F6F1EB` | 10.36:1 | cuerpo sobre el papel de página |
| `#36374B` sobre `#F2EDE5` | 9.98:1 | cuerpo sobre arena suave |
| `#36374B` sobre `#E6DED5` | 8.74:1 | cuerpo sobre arena |
| `#36374B` sobre `#B9D2D8` | 7.35:1 | texto del botón y la tarjeta destacada |
| `#36374B` sobre `#E6C5C0` | 7.26:1 | texto sobre tarjeta rosa grande |
| `#6A5C49` sobre `#FFFCF6` | 6.33:1 | texto secundario |
| `#43616A` sobre `#FFFCF6` | 6.50:1 | enlaces y antetítulos |
| `#775B57` sobre `#FFFCF6` | 6.00:1 | rosa cuando es texto |
| `#36374B` sobre `#DAA79F` | 5.55:1 | texto marino sobre rosa |
| `#FFFCF6` sobre `#4E727C` | 5.10:1 | texto sobre el calipso profundo |
| `#70A3B2` sobre `#36374B` | 4.19:1 | calipso como texto grande (≥24px) sobre marino |
| `#70A3B2` sobre `#FFFCF6` | 2.71:1 | **solo relleno** — nunca texto |
| `#FFFCF6` sobre `#DAA79F` | 2.05:1 | **prohibido**: ni crema ni blanco sobre rosa |
| `#36374B` sobre `#D9B26B` | 5.83:1 | texto del botón dorado |
| `#7A5C26` sobre `#FFFCF6` | 6.06:1 | dorado cuando es texto |
| `#36374B` sobre `#CFE4EC` | 8.84:1 | texto sobre el cielo (arriba) |
| `#36374B` sobre `#F7E3C4` | 9.27:1 | texto sobre el horizonte |
| `#D9B26B` sobre `#FFFCF6` | 1.95:1 | **solo relleno** |
| `#AB9D8B` sobre `#FFFCF6` | 2.59:1 | **solo relleno** |

Reglas duras: **nunca texto blanco o crema sobre calipso ni sobre rosa** (2.77:1 y 2.05:1), ni calipso `#70A3B2`
como texto sobre crema (2.71:1). Cuando el fondo es calipso y lleva texto, el fondo es `#B9D2D8` (texto marino) o
`#4E727C` (texto crema); cuando es rosa, o va `#DAA79F` con texto marino, o `#E6C5C0` con marino.

## Typography

Dos familias con reparto estricto.

- **Serif de titular (propuesta: Piazzolla; alternativa: Fraunces).** Titulares y precios. Peso **400**,
  interletra ligeramente negativa y altura de línea apretada (1.02-1.1). **Pendiente de aprobación de Héctor**:
  la guía no declara serif en su CSS (usa DM Sans y las cabeceras serif van dentro de imágenes), así que la
  familia es una propuesta, no un valor medido.
- **DM Sans — todo el texto corrido.** Medido en la referencia (única familia declarada). Cuerpo 16px/1.7;
  entradillas 18px en peso 300 (finas, nunca 400); etiquetas 11px en mayúsculas con interletra 0.18em.
- La **cursiva** está reservada a la segunda voz del titular y a los subtítulos de sección. No se usa para
  énfasis dentro del cuerpo.

## Layout

- **Contenedor: 1200px**, con 32px de relleno lateral en móvil y 48px en escritorio. Más estrecho que una web
  de producto: la lectura es de texto, no de panel.
- **Ritmo vertical: 120px** entre secciones (96px en móvil). Las secciones de respiración (meditación, texto
  largo) van a 160px.
- **Medida de lectura: 62-68ch** en cuerpo y 22-26ch en titulares. Ningún párrafo ocupa todo el ancho.
- Rejillas de tarjetas: 3 columnas en escritorio, 1 en móvil, `gap` de 24px. Las tarjetas de programa llevan
  cabecera con inicial en serif translúcida sobre degradado calipso.
- Escala de espaciado: 8, 12, 16, 24, 48, 80, 120.

## Elevation & Depth

La profundidad es **cálida y mínima**. Casi todo se separa con borde de 1px (`#CEC4B7`) o con un cambio de
capa de la rampa de superficies (blanco → crema → papel → arena). La sombra solo aparece cuando algo flota de
verdad.

- Tarjetas en reposo: `0 10px 30px rgba(54,55,75,0.06)`.
- Tarjetas elevadas / hover: `0 18px 44px rgba(54,55,75,0.10)`.
- Nada de sombras negras: siempre teñidas con la tinta `#36374B`.
- El hover sube 3px (`translateY(-3px)`), transición de 0.25s. Es el único movimiento de elevación.
- Los degradados son **lineales y suaves**, de calipso a calipso profundo o de arena a crema, nunca de dos
  acentos distintos.

## Shapes

- **Radios:** tarjetas 18px; bloques grandes 24px; botones y chips **píldora completa** (999px); imágenes 8px;
  2px solo para filetes.
- **Sin caja en las secciones a sangre:** las bandas de color van de borde a borde y sin radio.
- **Filetes de 1px** en `#CEC4B7` como separador por defecto; sobre calipso profundo, filete crema al 30%.
- **Grafismo propio:** la inicial grande en serif translúcida (marca de agua) en la cabecera de cada tarjeta de
  programa; el filete corto de 40px antes del antetítulo; el arco suave (blob) de fondo al 6% detrás de las
  secciones de texto largo.

## Components

- **`button-primary`** — marino `#36374B`, texto crema, píldora, 16×34. Uno por pantalla. Es el CTA de compra.
- **`button-primary-hover`** — el mismo botón en `#353535`.
- **`button-accent`** — calipso claro `#B9D2D8` con texto marino: el CTA secundario («Empezar ahora»,
  «Avísame»). Nunca con texto blanco ni sobre el calipso base.
- **`button-ghost`** — crema con texto marino, para acompañar al primario sin competir.
- **`card`** — blanca, radio 18px, relleno 32px, borde `#CEC4B7`. La tarjeta por defecto.
- **`card-accent` / `card-accent-hover`** — la tarjeta destacada (programa en vivo): calipso claro con texto
  marino, y calipso profundo con texto crema al pasar el ratón.
- **`card-rose`** — la variante cálida de la misma tarjeta: `#E6C5C0` con texto marino. Convive con la calipso;
  no compiten en la misma rejilla.
- **`button-rose`** — rosa `#DAA79F` con texto marino (5.55:1). El CTA cálido; nunca con texto blanco.
- **`link-rose`** — rosa como texto sobre claro, en `#775B57`.
- **`card-sand` / `card-sand-soft`** — las variantes informativas, en arena y arena suave.
- **`eyebrow`** — etiqueta de sección en mayúsculas sobre arena suave, en calipso tinta `#43616A` porque es
  texto sobre claro. Encabeza cada sección.
- **`price-value`** — precio en serif 54px sobre blanco, con la letra de la moneda al 60% del tamaño.
- **`chip`** — píldora blanca con borde y etiqueta en mayúsculas («PROGRAMA EN VIVO», «GRATIS»).
- **`nav-on-dark`** — barra superior sobre marino con texto crema; el enlace activo se subraya con un filete
  calipso de 2px.
- **`band-accent-deep`** — banda de aviso en calipso profundo con etiqueta crema.
- **`divider`** — 1px `#CEC4B7`; en las tarjetas de precio separa la descripción del importe.

## Do's and Don'ts

**Do**

- Fija el fondo de página en `#F6F1EB` y alterna secciones en blanco `#FFFFFF`, crema `#FFFCF6` y arena
  `#E6DED5`; el blanco no es solo de tarjeta, también es una capa de sección válida.
- Baja de capa con la rampa de superficies (0 → 6) en vez de inventar un beige nuevo.
- Sustituye cualquier banda oscura por el degradado de amanecer (`sky → glow → dawn`).
- Usa el dorado `#D9B26B` como filete, icono o extremo cálido del degradado; `#7A5C26` si el dorado es texto.
- Usa el calipso como relleno y baja a `#43616A` cuando necesites calipso en texto.
- Usa el rosa `#DAA79F` como relleno cálido con texto marino, o `#775B57` cuando el rosa es texto.
- Escribe los titulares en serif peso 400, con la segunda voz en cursiva.
- Deja 120px entre secciones y 62-68ch de medida de lectura.
- Separa con filete de 1px antes que con sombra.
- Calcula el contraste de cualquier par nuevo antes de pintarlo.

**Don't**

- No pongas texto blanco sobre calipso (2.77:1), ni crema o blanco sobre rosa `#DAA79F` (2.05:1), ni calipso
  `#70A3B2` como texto sobre crema (2.71:1).
- No introduzcas rosas fuera de `#DAA79F`, dorados fuera de `#D9B26B` ni el violeta de la barra de cookies.
- No vuelvas a poner secciones de página oscuras: ni hero negro, ni banda marino entera. El pie oscuro solo
  existe como variante explícita (`footer-dark`), nunca por defecto.
- No introduzcas negro puro: la tinta es `#36374B` y el gris es `#353535`.
- No mezcles degradados de dos acentos ni degradados fríos.
- No uses negritas en los titulares serif: el peso 400 es la firma.
- No redondees las secciones a sangre ni pongas sombras negras.
- No cambies la paleta por página: la web, la landing de Reconecta y la plataforma consumen estos tokens.

## Pendientes

1. **Tipografía serif definitiva** — Piazzolla (propuesta) frente a Fraunces. Decide Héctor; afecta al
   `@font-face` y a la licencia.
2. **Logotipo** — el sistema usa inicial en serif como marca provisional (issue `MLAB-473`).
3. **Calipso y rosa exactos** — calipso `#70A3B2` leído del CSS de la guía; rosa `#DAA79F` aportado por Héctor el
   29-oct. Si Zuzel tiene los hex de su manual, se sustituyen y se recalculan los contrastes.
4. **Aplicar a los consumidores** — la web (Weave Engine) y la plataforma (tema `warm-sand`) siguen con los
   valores anteriores; hay que reemplazarlos por estos tokens.
