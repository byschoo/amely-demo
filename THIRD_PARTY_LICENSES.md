# Licencias de terceros

Todo el código de terceros incluido en la web usa licencias permisivas (MIT o BSD). La tipografía usa la
SIL Open Font License 1.1 y las imágenes, licencias que permiten el uso comercial gratuito (Licencia
Unsplash y CC BY-SA 4.0). Las fotos de Unsplash son gratuitas: ninguna es de Unsplash+. Comprobación automática de las dependencias de producción: `npm run licenses`.

## Dependencias de ejecución (npm)

| Paquete | Licencia | Uso |
| --- | --- | --- |
| react, react-dom, scheduler | MIT | Interfaz |
| react-router | MIT | Rutas (aislado en `src/components/app-link.tsx`) |
| motion (framer-motion, motion-dom, motion-utils) | MIT | Animaciones |
| clsx, tailwind-merge | MIT | Utilidad `cn()` |
| @tabler/icons-react | MIT | Iconos |
| tslib | 0BSD (familia BSD) | Dependencia transitiva de motion |
| rough-notation | MIT | Subrayado a mano del titular (Highlighter de Magic UI) |
| @fontsource-variable/fraunces | OFL-1.1 (fuente) | Logotipo y titulares, autoalojada |
| @fontsource-variable/nunito-sans | OFL-1.1 (fuente) | Texto, autoalojada |

Herramientas de desarrollo (no se distribuyen en el sitio): vite, @vitejs/plugin-react, tailwindcss,
@tailwindcss/vite y typescript. Todas usan licencias MIT o Apache-2.0.

Respecto a la plantilla se ha retirado `svg-dotted-map`, que Amely no usa.

## Componentes de Magic UI (licencia MIT)

Basados en <https://magicui.design> (licencia MIT: <https://github.com/magicuidesign/magicui/blob/main/LICENSE.md>),
consultados con el servidor MCP de Magic UI. El archivo lleva su cabecera.

| Componente | Archivo | Uso en Amely |
| --- | --- | --- |
| Highlighter | `src/components/ui/highlighter.tsx` | Subrayado a mano de «fresca» en el titular (respeta «reducir movimiento») |

En el rediseño del 19 de noviembre de 2026 se retiraron Marquee, Number Ticker, Dot Pattern, Border Beam,
Animated Shiny Text y el brillo del botón de pedido (idea de Shiny Button): ya no hay código suyo en la web.

```
MIT License

Copyright (c) Magic UI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Imágenes

Las licencias se comprobaron en la página de origen de cada imagen. Los datos están en
`src/config/media.ts` y en `public/media/credits.json`; el crédito se muestra junto a cada imagen y en el
Aviso Legal. **Las fotos de tartas son ilustrativas: ninguna muestra productos de Amely** y deben
sustituirse por fotografías reales antes de abrir la tienda.

| Imagen | Autor u obra | Fuente | Licencia | ¿Exige atribución? |
| --- | --- | --- | --- | --- |
| [Cookies con pepitas de chocolate](https://unsplash.com/photos/4Mh3AjljekQ) | Girl with red hat | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Brownies apilados](https://unsplash.com/photos/S2KGqxh-10E) | Larissa Uemura | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Bizcocho de limón glaseado](https://unsplash.com/photos/-Qe0rpF2ThY) | Alexandra Golovac | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Magdalenas de arándanos](https://unsplash.com/photos/5RQffqRkmWQ) | Joshua Flores | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Tarta de queso con fresas](https://unsplash.com/photos/hXqbSgOPjSI) | Alexandra Khudyntseva | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Tarta de mousse de chocolate](https://unsplash.com/photos/hcEDfkiVmMI) | kaouther djouada | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Tarta de nata y frutos rojos](https://unsplash.com/photos/7ourhaJ2sJc) | Summer Time | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Porciones de tarta de fresa y nata](https://unsplash.com/photos/-qQlfYB7pqM) | Vicky Ng | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Tarta de fresas](https://unsplash.com/photos/FhB0rr4T2z4) | Laurene Gicquel | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Tarta de limón](https://unsplash.com/photos/_iyYsTa7qo8) | David B Townsend | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Tarta de manzana](https://unsplash.com/photos/0lqRhBh0I40) | Diliara Garifullina | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Tarta de almendras](https://unsplash.com/photos/9YveTrGjt7s) | Michael Navarro | Unsplash | [Licencia Unsplash](https://unsplash.com/es/licencia) | No (se acredita igualmente) |
| [Plaza Mayor de Torrejón de Ardoz](https://commons.wikimedia.org/wiki/File:Torrej%C3%B3n_de_Ardoz,_plaza_Mayor.jpg) | Rodelar | Wikimedia Commons | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | **Sí**: el crédito aparece sobre la foto y en el Aviso Legal |

Todas son gratuitas (ninguna es de Unsplash+). No se ha modificado ninguna imagen: los recortes se hacen al
mostrarlas (CSS).

## Marca

El logotipo (nombre en Fraunces con la cereza por punto, `src/components/brand/logo.tsx`) es original de este
proyecto. El icono de la tarta que gira, con su marco de blonda (`src/components/brand/turntable-cake.tsx`), es
una ilustración SVG dibujada para este proyecto, sin fotos ni recursos de terceros; `public/favicon.png` y
`public/apple-touch-icon.png` son esa misma ilustración exportada a PNG.

## Referencias de diseño

- **21st.dev (sólo como referencia de patrones, sin copiar código):** el abanico de tartas del hero sigue la idea
  de «Hero Section with Cards» (@scrollxui); en móvil, el abanico giratorio, la de «Card Fan Carousel»
  (@aayush-duhan, sin su GSAP); y la carta, la de «Shop by Category Grid» (@ziegfiroyt) y «Menu Item
  Card» (@ravikatiyar162); el menú móvil, la de «Immersive Full Screen Navigation» (@hyperiux: apertura con
  clip-path y enlaces que aparecen escalonados) y «Liquid Morph Floating Menu» (@aayush-duhan: botón que se
  transforma). Todo se ha escrito desde cero para Amely con Tailwind y Motion. La barra fija ya no
  adapta «Morphing Scroll Navbar»: ahora es estática.
- **Stitch:** sistema de diseño «Amely Pastel» (acción frambuesa #C72C5C, formas redondeadas). La imagen
  generada por Stitch no se usa: es una tarta creada por IA y no un producto de Amely.
- **Selecta (`Selecta_Design_00`):** referencia de composición del hero (serif editorial, insignia,
  efectos de Magic UI). No se ha copiado su texto.

Todos los textos son originales y salen del plan de negocio de Amely.
