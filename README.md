# Enciclopedia Fader

Enciclopedia al estilo Wikipedia con los conceptos culturales que Luis Fader usa en sus clases de idiomas. Cada artículo se puede leer en **español, ruso, italiano e inglés**.

Los contenidos están basados en los manuales *Ciao, amore!* (italiano), *Aquella vez* (español) y *Outsiders* (inglés), y en las novelas *La città triste*, *El impostor* y *Los Sueños y la Bestia*.

## Cómo verla

Abre `index.html` en el navegador. Es una sola página, sin dependencias: solo carga las fuentes de Google Fonts.

Para publicarla en internet, activa **GitHub Pages** en *Settings → Pages* (rama `main`, carpeta raíz). Quedará en `https://luisfader.github.io/fader/`.

Cada artículo tiene su propio enlace, por ejemplo `index.html#hispanoamerica` o `index.html#museo-fader`.

## Artículos

| Categoría | Artículos |
|---|---|
| Lengua | Hispanoamérica · Español neutro · Vosotros y ustedes · La zeta y el seseo · Coche, carro, auto |
| Lugares | Museo Fader · Mendoza · La ciudad de estilo español · Venecia |
| Costumbres | Horarios de comidas · El mate · Uscire · Estereotipos |
| Historia | Italianos en el mundo · ¿Por qué Inglaterra es tan rica? · Londres antes y ahora |
| Ideas de las novelas | Ministerio de los Sentimientos · Ley de la Felicidad · La revolución de la risa · La aplicación Destino · Prohibido enamorarse · Las Cupidronas · El Extractor · Un acuerdo con uno mismo · El falso experto |
| Universo Fader | Sinea y los personajes |

## Cómo añadir un artículo

Los artículos están en el array `A` dentro del `<script>` de `index.html`. Cada uno tiene:

- `id`: el identificador que aparece en el enlace (`#mi-concepto`).
- `cat`: `lengua`, `lugares`, `costumbres`, `historia`, `ideas` o `universo`.
- `cult`: `es` (hispánica), `it` (italiana), `en` (anglófona) o `novela`.
- `src`: el manual y la unidad de donde sale.
- `see`: lista de `id` relacionados.
- `box`: los datos del cuadro lateral, en los cuatro idiomas.
- `t`: título (`h`), resumen (`l`) y texto en HTML (`b`) para `es`, `ru`, `it` y `en`.
