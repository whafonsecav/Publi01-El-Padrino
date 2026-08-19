# El Padrino · Kay Adams

Presentación HTML en formato **16:9** para el ejercicio de análisis de personaje de
*El Padrino* (1972), tomando como personaje a **Kay Adams**.

**Politécnico Grancolombiano** — Institución Universitaria
**Asignatura:** Publicidad 2 · Tercer semestre
**Modalidad:** Presencial · Viernes nocturno

**Integrantes:** Mariana Pinzón · Mariana Silva · William Fonseca

---

## Ver la presentación

Abrir `index.html` en cualquier navegador moderno, o visitarla publicada con GitHub Pages:

> `https://whafonsecav.github.io/Publi01-El-Padrino/`

### Controles

| Acción | Tecla / gesto |
| --- | --- |
| Lámina siguiente | `→` · `Espacio` · `PageDown` · rueda abajo · swipe izquierda |
| Lámina anterior | `←` · `PageUp` · rueda arriba · swipe derecha |
| Primera / última | `Inicio` / `Fin` |
| Pantalla completa | `F` |
| Imprimir o exportar a PDF | `P` |

La barra de navegación inferior se oculta sola a los 2,6 s para que la lámina quede
limpia al proyectar; reaparece con cualquier movimiento del mouse o del teclado.

Para exportar a PDF: `P` → destino *Guardar como PDF* → orientación horizontal,
márgenes *Ninguno* y activar *Gráficos de fondo*.

---

## Estructura (6 láminas, según el Excel)

| # | Lámina | Contenido |
| --- | --- | --- |
| 01 | **Portada** | Título, personaje, institución, asignatura, modalidad e integrantes |
| 02 | **Trama** | Línea de tiempo Intro · Nudo · Desenlace con las tres imágenes del personaje |
| 03 | **Personaje** | Demográficos (sexo, edad, NSE, estudios) + Actitudes/Opiniones + Intereses + Intenciones |
| 04 | **Escenario** | Cuándo (1945 – 1955) y dónde (New York → New Hampshire) |
| 05 | **Motivación** | Emociones · Sentimientos · Conflicto/Situación (tipo existencial) |
| 06 | **Gracias** | Cierre con los datos del curso y los integrantes |

Los textos son los del archivo `Ejercicio El Padrino.xlsx`, incluido en el repositorio.
En la lámina 05 se respeta la separación por color del Excel: **Emociones** (3) y
**Sentimientos** (5) son dos grupos distintos.

---

## Paleta

Derivada del póster de la película:

| Color | Hex | Uso |
| --- | --- | --- |
| Negro cálido | `#050403` | Fondo |
| Sepia | `#4a3418` | Rellenos de panel |
| Bronce | `#7c5c2e` | Degradados y reglas |
| Oro antiguo | `#c9a24a` | Acento principal |
| Oro claro | `#e0be71` · `#fbf3dd` | Titulares metálicos |
| Crema | `#f4ecda` | Texto destacado |
| Rojo sangre | `#c4502f` | Acento único (la rosa del póster) |

**Tipografías:** Cinzel (titulares), Cormorant Garamond (texto), Inter (etiquetas).

---

## Estructura de archivos

```
index.html                 Presentación completa (CSS + JS + iconos SVG en línea)
assets/img/                Retratos del personaje, recortados y virados a la paleta (WebP)
assets/logo/               Logo del Politécnico Grancolombiano
Ejercicio El Padrino.xlsx  Fuente del contenido
```

Sin dependencias externas más allá de Google Fonts: los iconos son SVG en línea y
las imágenes se optimizaron de 7,5 MB (PNG) a ~275 KB (WebP) con un viraje sepia-oro
y viñeta para que se integren con la paleta.
