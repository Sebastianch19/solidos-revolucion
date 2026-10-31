# Torno Virtual de Revolución

Simulador de sólidos de revolución por los métodos de discos y arandelas, para el proyecto de Cálculo Integral. Gira una región alrededor del eje x, del eje y o de las rectas y = k y x = k, y calcula el volumen en tiempo real.

**App en línea:** https://sebastianch19.github.io/solidos-revolucion/

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La aplicación completa (HTML + CSS + JavaScript en un solo archivo). |
| `informe.pdf` | El informe para entregar: planteamiento, modelo matemático, capturas, validación, enlace y código (anexo A). |
| `informe.html` | La fuente editable del informe. |
| `capturas/` | Capturas de la app que usa el informe. |

## Abrir la app

Abre `index.html` con doble clic en Chrome, Edge, Firefox o Safari. Necesita internet para cargar Three.js, math.js y KaTeX.

Para abrir un caso concreto se le puede agregar un estado al enlace, por ejemplo:

- `index.html#caso=torre&theta=240&n=12`
- `index.html#caso=arandela&eje=y`
- `index.html#caso=toro&eje=yk&k=-3`

Casos disponibles: `tanque`, `torre`, `libre`, `cono`, `esfera`, `arandela`, `copa`, `parabola`, `toro`. Ejes: `x`, `y`, `yk`, `xk`.

## Publicar en GitHub Pages (enlace público)

1. Crea un repositorio público en GitHub, por ejemplo `solidos-revolucion`.
2. Sube `index.html` (y si quieres el resto de archivos).
3. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)` → **Save**.
4. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/solidos-revolucion/`.

Otra opción sin cuenta de GitHub: arrastra la carpeta a https://app.netlify.com/drop.

## Antes de entregar el informe

En `informe.html` hay campos resaltados en amarillo que debe completar el equipo:

- Universidad, docente e integrantes (portada).
- Enlace público de la app (portada y sección 5).
- Revisión del apartado de uso de IA (sección 6).
- Fuente del factor de emisión de CO₂ del concreto (sección 2.6 y referencias).

Para regenerar el PDF después de editar: abre `informe.html` en Chrome, espera a que se vean las fórmulas, pulsa **Imprimir → Guardar como PDF**, márgenes predeterminados y sin encabezados ni pies de página. La carpeta `capturas/` debe estar junto al archivo.
