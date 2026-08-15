# Evetev — Activos de marca

Repositorio público de logos, isotipos, favicon, mascota y tokens de color de **Evetev S.A.S.** Se sirve como CDN vía jsDelivr: cualquier proyecto apunta por URL, sin copiar archivos.

> Fuente de verdad visual: **Manual de imagen corporativa v2.0**. Este repo solo distribuye; las reglas de uso viven en el manual.

---

## Uso rápido

\<\!-- Isotipo \--\>

\<img src="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-azul-noche.svg"

     alt="Evetev" height="32"\>

\<\!-- Lockup completo \--\>

\<img src="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-horizontal-negro.svg"

     alt="Evetev" height="40"\>

\<\!-- Favicon \--\>

\<link rel="icon" href="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/favicon.svg" type="image/svg+xml"\>

\<link rel="apple-touch-icon" href="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/apple-touch-icon.png"\>

\<meta name="theme-color" content="\#0A2540"\>

\<\!-- Tokens de color \--\>

\<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/tokens/colores.css"\>

/\* Con los tokens importados \*/

.boton-primario{ background:var(--eve-coral); border-radius:var(--eve-radio-pill); }

.boton-primario:hover{ background:var(--eve-coral-hover); }

**Patrón de URL:** `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@VERSION/RUTA`

---

## Catálogo

### `isotipos/` — el símbolo (dos rombos entrelazados)

| Archivo | Cuándo usarlo | URL |
| :---- | :---- | :---- |
| `isotipo-azul-noche.svg` | Fondos claros. **Uso por defecto.** | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-azul-noche.svg` |
| `isotipo-blanco.svg` | **Fondos oscuros o fotografía** — la única que asegura contraste ahí (T2) | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-blanco.svg` |
| `isotipo-cian.svg` | Sobre azul noche | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-cian.svg` |
| `isotipo-teal.svg` | Color heredado del original | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-teal.svg` |
| `isotipo-gradiente-corporativo.svg` | Hero, portadas, piezas expresivas | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-gradiente-corporativo.svg` |
| `isotipo-gradiente-ia.svg` | Piezas de Eve Intelligence | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-gradiente-ia.svg` |
| `isotipo-gradiente-azul-cian.svg` | Degradado corto, usos pequeños | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/isotipos/isotipo-gradiente-azul-cian.svg` |

### `unidades/` — media unidad, ícono de línea de producto

Identifican líneas de producto (EvePay, Eve Intelligence, Tienda). **Nunca sustituyen al isotipo completo en la marca principal.**

Cada variante existe en `izquierda` y `derecha`; el trazo es idéntico en todas.

| Variante | Cuándo usarla | URL (sustituye `LADO` por `izquierda` o `derecha`) |
| :---- | :---- | :---- |
| `-negro` | **Ícono de producto en interfaz.** Se tiñe con `mask` en CSS, así un solo archivo sirve para todos los colores | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-negro.svg` |
| `-blanco` | **Obligatoria sobre fondo oscuro** (T2) | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-blanco.svg` |
| `-degradado` | Corporativa, pieza expresiva | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-degradado.svg` |
| `-coral` | Pieza expresiva | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-coral.svg` |
| `-cian` | Pieza expresiva | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-cian.svg` |
| `-electrico` | Pieza expresiva | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-electrico.svg` |
| `-violeta` | Pieza expresiva | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-violeta.svg` |
| `-ambar` | Pieza expresiva. **El ámbar no es color de marca**: es el complementario del eléctrico | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/unidades/unidad-LADO-ambar.svg` |

Las de color degradan **contra azul noche**, así que **son para fondo claro**: sobre oscuro pierden ese extremo y la figura se parte.

### `logotipos/` — la palabra "Evetev" (Baloo 2 en contornos)

| Archivo | Cuándo usarlo | URL |
| :---- | :---- | :---- |
| `logotipo-bicolor.svg` | **Por defecto.** Eve azul noche + tev eléctrico | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-bicolor.svg` |
| `logotipo-azul-noche.svg` | Una sola tinta, fondo claro | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-azul-noche.svg` |
| `logotipo-blanco.svg` | Fondo oscuro (T2) | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-blanco.svg` |
| `logotipo-teal.svg` | Color heredado | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-teal.svg` |
| `logotipo-negro-minuscula.svg` | Variante "evetev" en minúsculas | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-negro-minuscula.svg` |

**Con razón social** — dicen `Evetev S.A.S.` Para documentación oficial; en producto y marketing va el logotipo normal.

| Archivo | URL |
| :---- | :---- |
| `logotipo-sas-bicolor.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-sas-bicolor.svg` |
| `logotipo-sas-azul-noche.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-sas-azul-noche.svg` |
| `logotipo-sas-blanco.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-sas-blanco.svg` |
| `logotipo-sas-teal.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-sas-teal.svg` |
| `logotipo-sas-negro-minuscula.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/logotipos/logotipo-sas-negro-minuscula.svg` |

### `lockups/` — isotipo \+ logotipo juntos

**Horizontal** para encabezados, membretes y firmas de correo. **Vertical** para portadas, redes y splash.

| Archivo | Cuándo usarlo | URL |
| :---- | :---- | :---- |
| `lockup-horizontal-corporativo.svg` | **Encabezado por defecto** | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-horizontal-corporativo.svg` |
| `lockup-horizontal-negro.svg` | Impresión a una tinta | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-horizontal-negro.svg` |
| `lockup-vertical-corporativo.svg` | **Portada por defecto** | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-vertical-corporativo.svg` |
| `lockup-vertical-negro.svg` | Impresión a una tinta | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-vertical-negro.svg` |
| `lockup-vertical-teal.svg` | Color heredado | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-vertical-teal.svg` |

**Con razón social** — dicen `Evetev S.A.S.`, para contratos, facturas y papelería registral:

| Archivo | URL |
| :---- | :---- |
| `lockup-horizontal-sas-corporativo.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-horizontal-sas-corporativo.svg` |
| `lockup-horizontal-sas-negro.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-horizontal-sas-negro.svg` |
| `lockup-vertical-sas-corporativo.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-vertical-sas-corporativo.svg` |
| `lockup-vertical-sas-negro.svg` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/lockups/lockup-vertical-sas-negro.svg` |

### `favicon/`

| Archivo | Para qué | URL |
| :---- | :---- | :---- |
| `favicon.svg` | Pestaña, por defecto | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/favicon.svg` |
| `favicon-32.png` | Respaldo sin SVG | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/favicon-32.png` |
| `apple-touch-icon.png` | Pantalla de inicio de iOS (180 px, opaco) | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/apple-touch-icon.png` |
| `icon-512.png` | Buscadores y `webmanifest` | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/icon-512.png` |
| `mask-icon.svg` | Pestaña fijada de Safari | `https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/mask-icon.svg` |

Juego completo para el `<head>`:

    <link rel="icon" href="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/favicon.svg" type="image/svg+xml">
    <link rel="icon" href="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/favicon-32.png" sizes="32x32" type="image/png">
    <link rel="apple-touch-icon" href="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/apple-touch-icon.png">
    <link rel="mask-icon" href="https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/favicon/mask-icon.svg" color="#0A2540">
    <meta name="theme-color" content="#0A2540">

### `mascota/`

`mascota.webp` (512×512, fondo transparente) — Eve. Asistente digital, onboarding, estados vacíos. **No usar** en documentos legales, facturas ni en el flujo de pago de EvePay.

`https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/mascota/mascota.webp`

`mascota-saludando.png` (1024×1024, transparente) — el que usa la web corporativa.

`https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/mascota/mascota-saludando.png`

#### El repertorio completo (`.webp`, 1024×1024, transparente)

Las 22 poses de Eve, publicadas de una vez. Antes vivían solo en el monorepo y
se subían de una en una: eso dejaba a quien maquetaba —y al agente de EveStudio,
que lee este repositorio— eligiendo entre dos imágenes o citando URLs de
archivos que no existían.

| Pose | Archivo | Cuándo |
|---|---|---|
| Saludando | `mascota-saludando.webp` | bienvenida, portada |
| Neutral | `mascota-neutral.webp`, `mascota-neutral-2.webp` | acompañar sin protagonismo |
| Sonrisa suave | `mascota-sonrisa-suave.webp` | confirmaciones discretas |
| Sonrisa emocionada | `mascota-sonrisa-emocionada.webp` | éxito, meta cumplida |
| Riendo | `mascota-riendo.webp` | celebración |
| Cantando | `mascota-cantando.webp` | anuncios, novedades |
| Pensativa | `mascota-pensativa.webp` | procesando, «lo estamos revisando» |
| Curiosa | `mascota-curiosa.webp` | descubrimiento, ayuda contextual |
| Sorprendida | `mascota-sorprendida.webp` | avisos, algo inesperado |
| Frotando el ojo | `mascota-frotando-ojo.webp` | estado vacío, «aquí no hay nada todavía» |
| Estudio | `mascota-estudio.webp` | documentación, aprendizaje |
| Sentada | `mascota-sentada.webp` | espera, pantallas en calma |
| Caminando | `mascota-caminando.webp` | progreso, pasos de un flujo |
| Saltando | `mascota-saltando.webp` | logro, gamificación |
| Perfil izquierdo / derecho | `mascota-perfil-izquierdo.webp`, `mascota-perfil-derecho.webp` | mirando hacia el contenido de al lado |
| Primer plano | `mascota-primer-plano.webp`, `mascota-primer-plano-2.webp`, `mascota-primer-plano-3.webp` | avatares, iconos grandes |
| Arriba | `arriba.webp` (1376×768) | cabeceras apaisadas |
| Original | `mascota-original.webp` (1408×1117) | referencia del diseño inicial |

```
https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/mascota/mascota-pensativa.webp
```

**Por qué `.webp` y no los PNG del monorepo:** los originales pesan entre 390 KB
y 1,1 MB cada uno. En web eso no es aceptable para una imagen decorativa, así
que aquí se publican convertidos a WebP con calidad 85 y transparencia intacta —
las mismas 22 imágenes pasan de 16,2 MB a 1,5 MB, un 9 %. Los PNG maestros
siguen en el monorepo (`packages/brand/assets/mascota/`), que es donde deben
estar: este repositorio distribuye lo optimizado para web.

`mascota-saludando.png` se mantiene además en PNG porque `evetev.com/nosotros`
ya lo enlaza así, y la regla 2 de abajo dice que lo publicado no se retira.

### `ilustraciones/`

Escenas de producto, no marca. A diferencia de logos y mascota, **no representan
a Evetev**: ilustran el contexto de una vertical. Por eso no las rigen las reglas
de contraste T1/T2 — pero sí la regla de que el texto encima tenga que leerse.

**`conjunto-residencial-color.svg`** (viewBox 1344×768) — conjunto residencial en
trazo técnico `#1E6FEB`, con **dos elementos rellenos de color**: la torre de la
izquierda en `#144A96` y el árbol de la derecha en `#16A34A`, y **halo** en las
líneas. Para **EveConecta**, la vertical de propiedad horizontal.

`https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/ilustraciones/conjunto-residencial-color.svg`

**`flujo-de-pago.svg`** (viewBox 1344×768) — la tarjeta del cliente, el datáfono
del comercio y la caja donde cae el dinero, unidos por dos flechas. Para
**EvePay**, la pasarela de pagos. Color en el cuerpo de la tarjeta (`#144A96`) y
en la rueda de la caja (`#16A34A`), y halo.

`https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/ilustraciones/flujo-de-pago.svg`

Las dos son **las buenas** de su producto, y son hermanas a propósito: misma
dirección de fuga, mismo lienzo, mismas cotas de color y de halo. Puestas una al
lado de otra tienen que parecer la misma mano.

**Misma mano, no mismo asunto.** Es la distinción que costó una versión: la
primera escena de EvePay fue una calle de comercios, construida copiando la de
EveConecta —prismas con rejilla de ventanas—, y esas rejillas ganan la lectura.
La portada de una pasarela de pagos acababa ilustrando ladrillo. Lo que se
comparte es el **estilo**; el **tema** lo pone cada producto.

`comercio.svg` es esa primera escena. **Superada**, pero se mantiene publicada
porque la regla 2 dice que lo publicado no se retira. No la uses: para EvePay
está `flujo-de-pago.svg`, y para una escena de edificios está la de EveConecta.

### El halo

Las dos llevan el «glow controlado» que pide el prompt (§4). En un raster el
modelo lo resuelve solo; en SVG son **dos capas**: la escena desenfocada debajo,
sin rellenos, y la nítida encima. Sin quitarle los rellenos a la capa de abajo
el desenfoque da una nube gris alrededor de cada volumen en vez de un halo en
las líneas, y además tapa el halo de lo que tiene detrás.

`stdDeviation="5"` sobre un lienzo de 1344, elegido mirando: a 2,2 no se ve
—estas escenas se muestran a menos de la mitad de su tamaño y el desenfoque se
encoge con ellas— y a 7 se mete dentro de las caras blancas y el dibujo pierde
el filo de plano. **Es relativo al viewBox**, así que si algún día cambia el
ancho del lienzo hay que volver a mirarlo.

Cuesta unos 6 KB por archivo, que es el precio de duplicar la geometría.

Es una escena densa: va de fondo, atenuada y desvanecida, nunca a plena opacidad
detrás de un texto.

**El color va a los lados, y eso no es composición: es un requisito.** La landing
de EveConecta la usa de fondo abriéndole un hueco radial en el centro, para que
las líneas no crucen el titular. Cualquier elemento con color puesto al medio cae
dentro de ese hueco y no se ve — comprobado en el navegador con una versión que
tenía la torre y el árbol centrados: no aparecían ni subiendo la opacidad.

Pesa 6,7 KB. Se probó antes una versión raster de la misma escena y pesaba
202 KB, de los cuales 106 KB eran solo el canal alfa —imprescindible, porque con
`contain` sobra ancho a los lados y un blanco opaco dibujaría el rectángulo de la
imagen recortado contra el degradado—. En SVG la transparencia es gratis. Por eso
el manual dice que estas escenas se dibujen en SVG siempre que se pueda.

`conjunto-residencial.svg` (viewBox 1344×768) es la versión de una sola tinta,
sin color. Sigue publicada; úsala donde el color de los dos elementos no aporte.

**Ningún SVG de esta carpeta se edita a mano.** Cada escena tiene su script en
`packages/brand/ilustraciones/` del monorepo —`conjunto-residencial.py`,
`flujo-de-pago.py` y el superado `comercio.py`—, y todos comprueban al generar
que no queden trazos a menos de 24 unidades, la regla que más cuesta cumplir a
ojo. Toca el script y regenera.

Los dos aceptan `--sin-color` y `--sin-glow`. `--sin-glow` no es un capricho:
existe para poder reproducir `conjunto-residencial.svg` **byte a byte** tal como
está publicado, y esa comprobación es la que demuestra que un cambio nuevo no
movió la escena.

`conjunto-residencial.webp` (1344×768) es la primera versión generada.
**Superada**, pero se mantiene publicada porque la regla 2 dice que lo publicado
no se retira. No la uses en algo nuevo: tiene trazos violeta que se salen de la
paleta.

**Las ilustraciones se generan con un prompt fijo**, para que parezcan una
familia y no un muestrario: está en `evetev_brand_styles.md` §4, «Ilustraciones
de apoyo». Ahí también está qué hacer antes de publicar una nueva, incluido
**etiquetar** — sin etiqueta `@1` no la sirve.

### `tokens/`

`colores.css` (variables CSS listas) · `colores.json` (para Tailwind, Figma o scripts).

---

## Reglas de operación

1. **Siempre con versión.** Usa `@1` en producción. Nunca `@latest` ni una URL sin etiqueta: jsDelivr cachea de forma inmutable las versiones etiquetadas.  
2. **Los archivos publicados no se sobreescriben.** Si un logo cambia, se publica una versión nueva (`@2`) y las páginas viejas siguen funcionando.  
3. **Cambios por PR.** Igual que el resto del código: rama corta, PR, una aprobación. Un logo mal cambiado se replica en todos los proyectos al instante.  
4. **SVG externo no se recolorea con CSS** (`fill: currentColor` no cruza la frontera de `<img>`). Por eso existen las variantes de color pre-hechas; si necesitas un color nuevo, se agrega al repo.  
5. **Accesibilidad:** logo informativo → `alt="Evetev"`. Logo decorativo junto a texto que ya dice la marca → `alt=""`.

---

## Para las apps del monorepo `evetev/`

Las aplicaciones internas **no** usan el CDN: importan los SVG como componentes desde `packages/ui` (cero petición de red, tipados, tree-shaking). El CDN es para sitios externos, correos, documentos, prototipos y terceros.

// dentro del monorepo

import { IsotipoEvetev } from '@evetev/ui';

---

## Publicar una versión nueva

git add .

git commit \-m "feat(brand): agrega variante X"

git tag v1.1.0 && git push \--tags

La URL `@1` toma automáticamente la última `1.x`. Para congelar exacto: `@1.1.0`.

---

## Migrar a dominio propio (cuando exista)

Estructura pensada para migrar sin reescribir rutas: publica este repo en `assets.evetev.com` (GitHub Pages o proyecto estático en Vercel) y reemplaza el prefijo:

https://cdn.jsdelivr.net/gh/Evetev-Dev/brand@1/...  →  https://assets.evetev.com/...

---

## Licencia

Marcas y logos © Evetev S.A.S. Todos los derechos reservados. Repo público por conveniencia técnica de distribución; **no** implica licencia de uso a terceros.  
