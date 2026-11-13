# TP5 · Brandbook interactivo (Spot · Post · Stop)

> Este archivo es la memoria compartida del equipo. Claude Code lo lee al abrir la carpeta.
> **Regla:** cada vez que se tome una decisión nueva, anotala acá (sección 11, "Registro de decisiones") antes de hacer Commit + Push.

## Cómo trabajamos (leer primero)

- **Link de la página (para todo el equipo):** https://mateocuenya-create.github.io/spot-brandbook/ — es GitHub Pages: se actualiza solo 1 o 2 minutos después de cada *Push*.
- **Repo:** https://github.com/mateocuenya-create/spot-brandbook (público). Se trabaja con **GitHub Desktop**.
- **Antes de empezar:** en GitHub Desktop, **Fetch origin** y, si aparece, **Pull origin**. Nunca trabajar dos personas a la vez.
- **Al terminar:** **Commit to main** y **Push origin**.
- **Instrucciones para Claude** (el equipo es nuevo en GitHub; hablarles simple):
  1. Al terminar cualquier cambio en el repo, **decir siempre qué hacer en GitHub Desktop**: el texto exacto para poner en *Summary* (corto, en español, ej. `Agrego KM 4 Tipografías`), y después **Commit to main** y **Push origin**.
  2. Después del Push, **pasar siempre el link** de la página (el de arriba) para ver el cambio.
  3. Anotar en "Registro de decisiones" lo que se decidió.
  4. Respetar la sección "Lo aprendido": no inventar, el Figma es el modelo, cada marca usa solo sus misceláneas.
  5. Para probar en la compu: abrir `index.html` con doble clic (no moverlo de la carpeta, necesita `assets/`).
  6. **Todo lo nuevo se hace también para el celular.** La página tiene versión mobile: hasta 760 px de ancho se diseña a 480 px y va en una columna (ver "Versión mobile" en el Registro de decisiones).
     - Cada sección nueva o cambio va con sus estilos mobile en el bloque "VERSIÓN MOBILE" del CSS (reglas con `html.movil`), en el mismo cambio.
     - Las interacciones se mantienen siempre que se pueda; lo que en compu es hover, en el celular es tocar.
     - Antes de dar el link, probarlo en los dos tamaños: compu y celular (375 px de ancho).

**Entrega: el viernes (fecha exacta a confirmar por el equipo).** Presentación oral el mismo día en clase.
Idioma de todo el proyecto: español rioplatense (Buenos Aires). Contexto: tesis grupal de Multimedia (UADE), tema deportes. Equipo de 4 personas, cada una con su propia cuenta de Claude. **No trabajan al mismo tiempo**: antes de empezar, hacer *Fetch/Pull* en GitHub Desktop; al terminar, *Commit* + *Push*.

---

## 1. Qué hay que hacer

Una **página web con interacción** que funcione como **sistema de diseño / brandbook** y explique cómo funcionan los diseños de la tesis. Arranca por la marca principal **Spot** y sus dos derivadas **Post** y **Stop**. Las tres marcas tienen que estar en la página. Unifica el contenido de los informes de TP2, TP3 y TP4.

Mapeo:
- **TP2 = Spot** (app, marca principal)
- **TP3 = Post**
- **TP4 = Stop** (evento)

**Todo se hace en HTML, no en Figma.** El Figma es referencia visual y de contenido. (Excepción: la escala tipográfica, ya hecha en Figma; ver sección 7.)

### Entregables (consigna completa en `docs/Consigna TP5.pdf`)
1. El sistema de diseño interactivo navegable (la página).
2. Exposición oral de **máx. 8 minutos** de todo el equipo, navegando el sistema y justificando decisiones de diseño. Público: posibles inversores y profesionales del diseño. Lenguaje técnico. Sin actings, sin participación del público, **sin soporte visual extra**: solo se muestra y navega la pieza. No hace falta explicar la navegación, sino la identidad.
3. Un **video .mp4** con la navegación completa y todas las interacciones (se valoran locución, audio y edición).

Todos los integrantes entregan los mismos archivos en la tarea "TP5" de Teams. Nombres obligatorios:
- `"Nombre de Proyecto" - "Apellido" - Sistema de diseño`
- `"Nombre de Proyecto" - "Apellido" - Video.mp4`

Cada sección debe tener **introducción** (objetivo), **desarrollo** y una **breve conclusión** que analice funcionalidad y consistencia.

**⚠️ Links a documentos:** según la consigna, si la página enlaza archivos para revisar, **tienen que estar alojados en Microsoft Teams**. No se consideran Google Drive ni otros servicios. Los links de Drive de abajo sirven como fuente, pero en la página final hay que reemplazarlos por links de Teams.

Contenido que pide la consigna: nombre del proyecto y claim, voz y tono, signos identificadores primarios y secundarios (usos, aplicaciones, convivencia con otros signos), códigos de color, familias tipográficas, iconografía, ilustraciones, fotografía, video y otros recursos visuales (impresos y digitales), componentes interactivos y UI kit, **piezas de comunicación** (papelería, firmas de mail, favicon e íconos de app, avatares de redes, slides de presentación, merchandising) y **UX** (navegación, interacción, descarga de archivos, elección de piezas, situaciones reales).

---

## 2. Fuentes de contenido

### 2.1 Figma "Spot para Claude" (fuente principal)
- URL: https://www.figma.com/design/TMlNvCfuRHQ5VcK0YFF82J/Spot-para-Claude
- fileKey: `TMlNvCfuRHQ5VcK0YFF82J`
- Para leerlo, tu Claude tiene que estar conectado a Figma y vos tenés que tener acceso al archivo (pedíselo a Mateo).
- Acceso verificado el 06/11/2026: todas las páginas, textos, links y prototipo se leen bien.

| Página | ID | Qué contiene | Links |
|---|---|---|---|
| Spot | `0:1` | 19 elementos sueltos: sistema de íconos, componentes, insignias (grupo, consistencia, participación social, lugares, lugar asociado, lugar repetido), láminas de documentación (paleta cromática, familias tipográficas, "SISTEMA DE DISEÑO") | 1 (Phosphor Icons) |
| Pantallas app Spot | `1:2882` | 49 pantallas: Crear equipo (pasos 1–4 y éxito), Registrar entrenamiento (en proceso, pausa, cargando, finalizado, logros), Buscar equipo (mapa, filtros, perfil, confirmación), Canjear locker (beneficios, QR, canje exitoso, mapa), Login, Splash, Inicio, Welcome Home, Equipos (Mis equipos / Descubrir) | 0 |
| POST | `1:18433` | 138 elementos (TP3) | 21 (ver 2.3) |
| Evento STOP | `1:27208` | 159 elementos (TP4) | 20 (ver 2.4) |
| Brand guidelines TP5 | `4:9125` | **Primera página. Diseño de la página web del TP5: es el modelo a seguir** (ver sección 4) | 0 |
| Escala tipográfica | `9:2603` | Escala tipográfica (ver sección 7) | 0 |
| Sistema de íconos | `77:159` | Página nueva (10/11): 65 íconos de la app, con variante Outline/Fill y solo outline | 0 |

Nota: "Brand guidelines TP5" NO es un brand guidelines de Spot: es el diseño de la home de la página del TP5.

### 2.2 Figma Slides de los informes originales (apoyo)
URLs: `https://www.figma.com/slides/<fileKey>/`
- TP2 (Spot): `Myt83wOiBIA7PuxkkPTeUR` · 208 slides · 10 links
- TP3 (Post): `wh4Qfp6r3i3wYAxCGItyuM` · 172 slides · 72 links
- TP4 (Stop): `t4aX9pOrlg0MG6p04FaugH` · 222 slides · 42 links

Links de Drive de los informes (fuente; en la página final van por Teams):
- Carpeta "POST ENTREGA": https://drive.google.com/drive/folders/1P3OWB-jIM64xL2g7gsh9bMG6bz0nViK0
- Doc "UX testing – Guion y resultados": https://docs.google.com/document/d/1g3UchIzlsiWPJGU6ggCy1I5NWh5iD5Uem1D-sq5eBnY
- Carpeta "Scouting STOP": https://drive.google.com/drive/folders/14YwL3C2o1haFPcKiBN30SHzPEDU-wrh3
- Video demo POST: https://drive.google.com/file/d/1vOfNjafTr_FcnJ2jNNCvhPz8BEj5X5zI/view

### 2.3 Links en la página POST del Figma (21)
- Vistas exterior: https://drive.google.com/drive/folders/1ZJO6nUyX1oAlbv-zsnk3-qg18gVQe2w0
- Vistas interior: https://drive.google.com/drive/folders/1NGNZ14GXM6byTsJXMqhk0Q1SCPckCrLd
- Video demo: https://drive.google.com/file/d/1vOfNjafTr_FcnJ2jNNCvhPz8BEj5X5zI/view
- Sitio de notitas (dedicatorias de POST): https://estefigarrido.github.io/dedicatorias-post/
- Instagram socialrunning.ar: https://www.instagram.com/socialrunning.ar/
- 16 links "producto similar" de MercadoLibre (pantallas LED, Novastar VX1000, Logitech C920, Kinect, gabinete gamer, dicroica RGB, PC gamer, lámpara sunset, piso goma EVA, mat de yoga, cortina blackout, truss 30x30, vela sombra). Son referencias de presupuesto, no contenido de marca.

### 2.4 Links en la página Evento STOP del Figma (20)
- Landing: https://camilarodriguezturri.github.io/stop-landing/
- Cápsula del tiempo: https://camilarodriguezturri.github.io/stop-evento/
- Artifact de notitas: https://claude.ai/artifact/WD4hEhmkbJkXDoFaYvfkrx
- Recorrido en Google Maps: https://www.google.com/maps/d/u/0/viewer?mid=1sm8SFMhU2ks3nwu8IOlcxLDph92mjVE
- Instagram @socialrunning.ar y @sanitariosvip (baños químicos)
- Prensa: Athletech News y GearJunkie (Strava 2024), Fortune (Strava IPO / run clubs Gen Z), Infobae (Maratón BA 2025; clubes de running para solteros), Perfil (21k BA), Time Out (social running club), Nike After Dark Tour (about.nike.com y Marathon Handbook), Minuto Uno (21k BA récord de inscriptos).

### 2.5 Sitio STOP "cápsula del tiempo" (para reutilizar animaciones)
- https://camilarodriguezturri.github.io/stop-evento/
- Estático: `styles.css`, `app.js`, `piezas.js`, `config.js`, `qrcode.js`. Fuentes: Sora, Reddit Sans, JetBrains Mono. `theme-color` #7aa1ff. 29 `@keyframes`.
- Pendiente: elegir qué animaciones reusar.

---

## 3. Referencia de estilo: Dropbox (la única)

**https://brand.dropbox.com**: brandbook inmersivo, animado, de scroll continuo, con componentes interactivos en lugar de páginas estáticas. Imitar el espíritu, no copiar.
- Cada capítulo es una pieza autónoma con su propia interacción (sliders de tipografía, selectores de paleta, "tragamonedas" de íconos, etc.).
- Ritmo de "picos y pausas": momentos de alto impacto alternados con secciones calmas.
- No buscar más referencias.

---

## 4. La página "Brand guidelines TP5" (`4:9125`) — ES EL MODELO A SEGUIR

Releída el 10/11/2026. Es la primera página del Figma. El equipo la diseñó como la página web: **construir lo que está ahí, sin inventar.** Cada lámina es una pantalla (1920 de ancho; las altas son pantallas con scroll).

### Pantallas
| Lámina | ID | Qué es | Estado |
|---|---|---|---|
| "1" | `4:9456` | Portada amarilla con el logo SPOT! animado | Lista |
| Slide 2 | `4:9521` | Home: video de ciclistas, mapa-circuito con **10 puntos** de colores, menú, logo SPOT! y logos de **post.** y **STOP** arriba a la derecha | Lista |
| Slide 3 | `4:9537` | Menú lateral (578 px), con ítems que se abren/cierran (componente "Item menú": Abierto/Cerrado) | Lista |
| Slide 4 | `4:9550` | **KM 1 · Acerca de SPOT!** (7617 px): Brand Spirit, Misión y visión, frase "Comienzos en Compañía, Comunidad & Comodidad" sobre foto, Submarcas (post. con fotos de la instalación y STOP, con botones "Conocé más"), "Siguiente parada: KM 2", "Volver arriba", footer © 2026 | Completa con textos reales |
| Slide 5 | `4:9575` | **KM 2 · Manual de Voz y Tono** (12025 px): pilares (Comienzos, Compañía, Comunidad, Comodidad, con "Así suena"), La voz, "Si Spot fuera una persona…" (8 rasgos), enfoque (4 cards), El tono (4 momentos), perfil de tono (4 dimensiones de Nielsen Norman Group), "Somos… pero no…" (8 pares), Guía de estilo (Así sí / Así no) | Completa con textos reales |
| Slide 6 | `198:425` | **KM 3 · Logotipos** (15085 px): Logos Spot, Construcción (tira de 3852 px que se sale del cuadro), Variantes de color, Tamaños, Espacios seguros, Ubicación, Malas prácticas, footer | Completa (el subtítulo y los links del hero siguen siendo copia del KM 2) |
| Slide 7 | `281:746` | **KM 4 · Uso de Tipografías** (6710 px): Sora y Reddit Sans, "dos familias parecidas" con carrusel de pantallas de la app (ventana de 951 px), Títulos Display, footer | Completa (tag dice "KM 2" y subtítulo/links son copia del KM 2) |
| Slide 8 | `281:1181` | **KM 5 · Colores de la marca** (10171 px): componente "Colores por marca" (click en cada logo), Crema/Negro Spot con %, ejemplo de filtros 1 y 2, Tipografía y color, Vectores y color | Completa, pero sin footer en el Figma |
| Slide 9 | `282:9418` | **KM 6 · Elementos gráficos** (12623 px, el cuadro mide 5200 de ancho por los carruseles): Puntos y estrellas por marca, Signos Display, Fotografías Spot/Post/Stop (carruseles "Carrusel fotos"), Usos indebidos, footer | Completa |

Cada KM tiene su color de fondo arriba: KM 1 amarillo, KM 2 naranja, KM 3 rosa, Tipografías violeta, Colores azul, Elementos gráficos amarillo. Todos llevan el tag "KM n", el título con borde crema, una carita sticker, misceláneas flotando y links internos.

Texto suelto con la voz y tono resumida: `19:9775`. Lista de contenidos del equipo: `4:9615` (incluye además "sistema de marca", "Ubicación" en logos y "Arquigrafía").

### Notas de implementación que dejó el equipo (sección "Componentes web" `4:9590`)
- **Navegación general:** puntos del mapa de KM y menú índice; se usan en todas las secciones.
- **KM 1:** Misión y visión con hover.
- **KM 2:** Pilares de la marca (hover: la tarjeta pasa al color del pilar) y frases destacadas de La voz y El tono (hover: la frase se marca en naranja, como la misión del KM 1).
- **Logos:** SPOT · post. · STOP y animación del logo SPOT (hover).

### Componentes con estados (en "Componentes web")
Puntos mapa (Default/Hover) · Logo SPOT (2 variantes) · Component 2 (contorno del mapa ↔ logo) · Logo Post (2 capas) · Component 3 y Component 5 · Pilar de marca (4 pilares × Default/Hover) · Frase destacada KM2 (La voz / El tono × Default/Hover) · Card enfoque (Azul/Rosa/Verde/Violeta × Default/Hover) · Card tono (4 momentos × Default/Hover) · Toggle y Fila "Somos / Pero no" (4 colores × Somos/Pero no) · Logo Spot/Post/Stop · Variantes de color y "Nav fondos logo" (5 fondos) · Item menú (Abierto/Cerrado).

### Interacciones del prototipo (220 en total)
- Portada → Home: a los 2,4 s, Dissolve 0,1 s.
- Hover: Smart Animate de 0,1 s (puntos del mapa), 0,2 s, 0,3 s (contorno del mapa y otros) y 0,4 s (Card tono).
- Click en punto del mapa → KM: Move in desde la derecha, 0,3 s ease-out. "Volver al Inicio": Move out hacia la izquierda, 0,3 s.
- Menú: overlay Move in, 0,2 s ease-out.
- Click que cambia de estado (toggles "Somos / Pero no", ítems del menú): Smart Animate 0,35 s ease-in-out.
- 132 clics que cambian una variable (botones de fondo "Blanco Crema", "Color", etc. en Variantes de color de logos).
- Detalles exactos: leer `node.reactions` con `use_figma`.

## 5. Estructura de contenido de la página

1. **Brand Spirit**: misión y visión; submarcas (Post y Stop)
2. **Voz y tono**
3. **Logos**: variantes de color de cada uno; espacios seguros; tamaños; usos correctos e incorrectos; ejemplos de uso
4. **Tipografías**: Tipo 1, Tipo 2; *sin escala tipográfica*; **incluir link para descargar**
5. **Colores**: Spot, Post, Stop; combinaciones que no van
6. **Elementos gráficos**: misceláneas, variantes, ejemplos de aplicación; imágenes (usos correctos/incorrectos); ilustraciones (caritas, puntitos = siluetas y logros)
7. **Design System**
8. **Animaciones**: principios; puntos flotando; Post
9. **Iconos**

(Falta ubicar las piezas de comunicación y la UX que exige la consigna; ver sección 8.)

---

## 6. Decisiones vigentes

- Un solo `index.html` (HTML + CSS + JS adentro) y la carpeta `assets/` con los gráficos exportados de Figma (`assets/svg/`) y el video (`assets/video/`). Sin frameworks ni pasos de compilación: se abre directo en el navegador o en GitHub Pages.
- Scroll continuo con animaciones; recorrido tipo carrera (KM por capítulo); respetar la home del Figma (portada amarilla → mapa con puntos → capítulos, menú lateral).
- Tono de presentación para inversores y diseñadores.
- Supuestos sin confirmar: Spot, Post y Stop con capítulo propio y misma estructura; UX como capítulo propio al final.
- Ir de a poco: no construir una sección nueva sin el OK del equipo.

---

## 7. Tipografía (resuelta en Figma)

Familias de la **app Spot**: **Sora** (títulos, números, métricas; Regular, SemiBold, Bold, ExtraBold) y **Reddit Sans** (texto, etiquetas, botones; Regular, Italic, Medium, SemiBold, Bold).
Descartadas: SF Pro (barra de estado iOS) y Bitcount Prop Single (solo logo). JetBrains Mono, Plus Jakarta Sans e Inter aparecen en láminas de documentación, no en la app.

Página **"Escala tipográfica"** (`9:2603`):
- Frame **app** `9:2604`: escala 1,125 base 16 px (11, 13, 14, 16, 18, 20, 23, 26, 29, 32, 36, 41, 46, 52, 58, 66 px) + inventario de 52 variantes reales (23 Sora + 29 Reddit Sans).
- Frame **desktop** `11:2603`: base 18 px, razón 1,125, de −4 a +16: 11, 13, 14, 16, 18, 20, 23, 26, 29, 32, 36, 41, 46, 52, 58, 66, 74, 83, 94, 105, 119 px. 14 estilos: Display XL (Sora Bold +16), Display (+13), H1 (+10), H2 (+8), H3 (+6), H4 (+4), H5 (Sora SemiBold +2), Cuerpo L (Reddit Sans Regular +1), Cuerpo (0), Cuerpo destacado (Bold), Cuerpo S (−1), Etiqueta (SemiBold MAYÚS −2), Caption (−3), Overline (SemiBold MAYÚS −4).
- Todos los tamaños redondeados a enteros.
- Ojo: la app real no sigue estrictamente 1,125 (coinciden 31 de 52 variantes). Interlineados, tracking y roles del frame desktop son propuesta, no vienen de la app.
- En la web: Sora + Reddit Sans (Google Fonts) + **link de descarga** de ambas.

**Colores: todavía NO extraídos.** Visualmente: amarillo (portada y KM 1), naranja (KM 2), crema, negro/gris oscuro (`#252525`). Leer los códigos exactos de Spot, Post y Stop en la lámina "Paleta Cromática" / "COLOR · PALETA PRINCIPAL" de la página "Spot" antes de construir.

---

## 7b. Tips técnicos para el Figma desde Claude Code
- MCP de Figma: `create_session` con el fileKey primero y reusar el `sessionId`; `get_metadata` (sin nodeId lista páginas), `get_screenshot`, `get_design_context`, `use_figma` (cargar antes el skill figma-use).
- En `use_figma`: cambiar de página con `await figma.setCurrentPageAsync(page)`, una vez por llamada; hipervínculos con `getStyledTextSegments(['hyperlink'])`; prototipo con `node.reactions`.
- Los Slides de TP2/3/4 son archivos Slides: leer con `use_figma` en modo solo lectura.

---

## 8. Pendientes y preguntas abiertas

1. ¿Post y Stop repiten la estructura de capítulos de Spot, o cada sección (logos, colores, tipografías) muestra las tres marcas juntas?
2. Piezas de comunicación y UX (las exige la consigna): ¿se suman al final?
3. En "Animaciones" aparece "Post": ¿es una animación propia de la marca Post?
4. Leer del Figma: códigos de color, logos (variantes, espacios seguros, usos incorrectos), ilustraciones (caritas, puntitos) y fotos de cada marca. Sacar de los Slides TP2/3/4: Brand Spirit, misión/visión, voz y tono, claim y nombres.
5. Elegir qué animaciones del sitio STOP reutilizar.
6. Subir a Teams los archivos que se enlacen (hoy están en Drive).
7. Aparte de la página: video .mp4 y guion de la exposición de 8 minutos.
8. Primer paso de construcción: home (portada, mapa, menú y KM 1–2), siguiendo el Figma como modelo.

---

## 9. Preferencias del equipo
- Ir de a poco y confirmar antes de avanzar.
- Lo más importante: **las animaciones** y que la experiencia sea tipo Dropbox.
- Números redondeados, sin decimales.
- Ser directo y no sobrecargar con referencias.
- Plazo justo: priorizar una versión funcional y mejorar después.

---

## 10. Lo aprendido (se empezó de cero el 10/11/2026)

El 10/11/2026 se borró todo lo construido y se empezó de nuevo. Respaldo de la versión anterior (página, propuesta y gráficos exportados del Figma) en la compu de Mateo: `Downloads/spot-brandbook-respaldo-2026-11-10/`. **No reusar ese código sin que el equipo lo pida.**

### Reglas que dejó el feedback del equipo
- **No inventar.** Ni textos, ni piezas, ni elementos gráficos. Todo sale del Figma.
- **El Figma es referencia y también modelo a seguir** (la home es la página "Brand guidelines TP5").
- **No sobrecargar.** Les gusta que todo sea interactivo, pero con medida: una propuesta con muchas animaciones inventadas se rechazó por "demasiado".
- **Cada marca usa SOLO sus misceláneas.** Nunca mezclar (ej.: la estrella de STOP no va en SPOT!).

### Datos confirmados del Figma
- Colores oficiales (estilos del Figma): Amarillo #FDCE42, Naranja #FF7640, Rosa #F79EE1, Violeta #AB8AE5, Azul #7AA1FF, Negro #252525, Blanco Crema #EDE8DB (+ Negro 80/60/20 y Crema 60 como transparencias). Verde de post.: #49B867.
- Portada (Slide 1): animación del Figma de 2,4 s: 58 puntitos del logo que parpadean (0–42 %), borde que se dibuja (16,7–55,6 %, curva cubic-bezier(.6,0,.6,1)), relleno crema y puntos que se desvanecen (75–91,7 %). El contorno que queda **es** el recorrido del mapa de la Home.
- Fondo de la Home (Slide 2): es un **video** (ciclistas). Figma no deja exportarlo por API; hace falta el archivo original. Encima lleva velo negro 40 % y desenfoque de 10 px.
- Hover de los puntos del mapa: el punto sube 7 px con sombra y aparece arriba una pastilla "KM n · nombre".
- Lenguaje de movimiento de la app Spot (prototipo de "Pantallas app Spot"): casi todo Smart Animate de 0,1 a 0,3 s ease-out; cambios de estado de "Registrar" en 1 s con curva Gentle; overlays que suben desde abajo en 0,2 s; celebraciones de logro con insignia central, puntitos y formas de colores, franja diagonal con líneas onduladas, stickers inclinados ("¡Canje exitoso!") y "+30 p.".
- Texto real de **voz y tono** cargado por el equipo en "Brand guidelines TP5" (nodo 19:9775).

### Misceláneas de cada marca
- **SPOT!:** insignias (cada familia con su forma y color), puntitos del logo, línea ondulada de "Logros conectados", círculos de colores, estallido naranja e insignia azul (lámina 24:9844).
- **post.:** "formas marcarias": estrella ondulada de 12 puntas con contorno (verde o crema), forma de 7 puntas verde, círculos con contorno crema, puntos verdes y ondas crema a los costados (lámina 24:9862; también página POST, "Interfaz de la pantalla principal"). Comportamiento definido en el Figma: "si se acercan a la silueta de la persona, puede empujarlas al moverse".
- **STOP:** "garabatos": estrella azul, estrella de contorno, cruz de puntos, destello de puntos, círculo punteado, puntos rosa/azul, franjas diagonales y líneas de puntos, en crema, rosa o azul según el fondo (lámina 24:9888; también página Evento STOP, "Objetos y garabatos").
- **Caritas:** las 9 caritas de línea ("Cara 1"–"Cara 9", página "Brand guidelines TP5", nodos 24:9978–24:9986) son de las tres marcas; cambia el color del círculo. Formato (lámina de SPOT!): círculo del color, borde crema 3 px, sombra 0 3px 3px 25 %, carita al 90 %, inclinada ±15°. Colores: SPOT! violeta o naranja · post. verde · STOP rosa o crema (STOP además tiene "vec-cara-canchera", "vec-cara-sonadora", "vec-cara-dormida").

### Tips técnicos
- Figma no deja exportar videos por API.
- Para probar la página en la compu: abrir `index.html` con doble clic.
- Logos de post. ("Logo post.", página POST 1:21442) y STOP ("logo_stop", página Evento STOP 1:37225) se pueden exportar como SVG.

## 11. Registro de decisiones
(Anotar acá cada decisión nueva: fecha · quién · qué se decidió.)

- 10/11/2026 · Mateo · Se empieza de cero. Historial de Git limpio.
- 11/11/2026 · Mateo · **Video de fondo de la Home resuelto.** Archivo original: `0_Running_People_1920x1080.mp4` (22 s, 16,5 MB, link de Drive que pasó Mateo). Achicado con `avconvert` (Preset960x540) a `assets/home/home.mp4` (960×540, 11 MB): alcanza porque va desenfocado y con velo negro 40 %. En loop, sin sonido, con `home-fondo.jpg` como imagen mientras carga. Ya no está pendiente.
- 10/11/2026 · Mateo · **Títulos de los KM idénticos al Figma.** El borde crema hecho con `-webkit-text-stroke` dejaba picos en las esquinas (la A, la e). En el Figma es: Sora SemiBold 128, borde crema 23 px por FUERA con uniones REDONDAS, sombra 0 4 4 25 % sobre todo. Ahora se dibujan en SVG (`armarTitulos`, `.titulo-km text`: stroke 46 + `paint-order: stroke fill` + `stroke-linejoin: round`). Regla: cualquier texto con borde, hacerlo así, nunca con `-webkit-text-stroke`.
- 10/11/2026 · Mateo · **Misceláneas jugables tomadas de truus.co** (sus stickers se empujan al pasar el mouse). Analizado en su código: función "Momentum-based Cards Hover" con GSAP + InertiaPlugin. Al entrar el mouse a una pieza: velocidad del mouse × 30 (máx. ±1080) para empujarla, giro = torque (según desde dónde pega) × 20 (máx. ±60°), y vuelve sola a su lugar con resistencia 200. Solo con mouse (en celular no).
  - Aplicado en `index.html` (`iniciarStickers`): todas las misceláneas de los heros de KM 1, 2 y 3 (puntos, estrellas, insignia y carita) y las de post. y STOP en el KM 1. La insignia (estrella + dibujo) se mueve como una sola pieza. GSAP 3.13.0 + InertiaPlugin desde jsDelivr.
- 10/11/2026 · Mateo · **Movimiento al scrollear tomado de houseofyellow.nl** (pedido del equipo: que no sea brusco). Analizado en su código: usan Lenis (duración 1,2 s, curva expo-out `t => Math.min(1, 1.001 - 2^(-10t))`, rueda suavizada, touch nativo) + GSAP ScrollTrigger con entradas de 0,45 s que suben ~24 px al llegar al 90 % de la pantalla, escalonadas de a 0,15 s, una sola vez.
  - Aplicado en `index.html`: Lenis 1.1.13 desde jsDelivr, una instancia por página KM (son las que scrollean); todos los saltos internos (links del hero, menú, flecha, "Volver arriba") usan el mismo scroll suave.
  - Entradas: lista `ENTRAN` en el script (secciones, pilares, stickers, cards, filas, fotos, botones…). El hero de cada KM no se anima (ya está a la vista).
  - Sin la librería o con "reducir movimiento", queda el scroll normal y todo visible.
- 10/11/2026 · Mateo · **Se construyó todo lo diseñado** en `index.html`: portada, home (10 puntos), menú desplegable, KM 1, KM 2 y KM 3. Sin contenido inventado: textos, gráficos y fotos exportados del Figma (`assets/home`, `assets/km1`, `assets/km2`, `assets/km3`, `assets/logos`, `assets/img/caritas`).
  - Cómo está hecho: cada pantalla está maquetada a 1920 px como el Figma y se escala con `zoom` (variables `--z`, `--zs`, `--zm`). Pensado para compu; en celular se ve chico.
  - Animaciones del prototipo respetadas: portada 2,4 s → Home con Dissolve 0,1 s; hover de puntos 0,1 s; contorno → logo 0,3 s; KM entra desde la derecha 0,3 s; "Volver al Inicio" sale a la izquierda 0,3 s; menú entra 0,2 s; ítems del menú abren/cierran 0,35 s ease-in-out; toggles "Somos / Pero no" 0,35 s ease-in-out; hovers de pilares (0,3 s), cards de enfoque (0,3 s), cards de tono (0,4 s), misión/visión (0,2 s) y glosario (Dissolve 0,1 s); botones de fondo en variantes de color (instantáneo).
  - El corredor del mapa y los stickers de la versión anterior NO están (no son del Figma).
  - Lo que falta o está incompleto en el Figma (avisar al equipo): video de ciclistas (no está en el Drive; se usa un cuadro fijo); ejemplos "pero no" de 7 de las 8 filas (solo existe el de "Ridículos"; la página muestra "Falta el ejemplo…"); en KM 3 el subtítulo y los links del hero eran copia del KM 2 y no se usaron; "Espacios seguros" del KM 3 tiene el mismo texto e imagen que "Tamaños"; los dos botones "Siguiente parada" del KM 1 van al KM 2 (el de la izquierda parece que debería ser "anterior"); los botones "Conocé más sobre POST/STOP" llevan a la Home como en el prototipo; KM 2 no tiene "Siguiente parada"; puntos 4 a 10 y Tipografías, Colores y Elementos gráficos todavía sin pantalla.
- 10/11/2026 · Mateo · Se releyó el Figma después de los cambios del equipo (sección 4 actualizada): KM 1 y KM 2 completos, KM 3 casi completo, Tipografías/Colores/Elementos gráficos en borrador, Home con 10 puntos, página nueva "Sistema de íconos".
- 11/11/2026 · Mateo · **Figma actualizado → se construyeron KM 4, KM 5 y KM 6, y lo nuevo de KM 3** (Espacios seguros real, Ubicación, Malas prácticas). Todos los KM 2–6 llevan el componente "Footer · Paradas" (anterior/siguiente según el prototipo). Los puntos 4, 5 y 6 del mapa y el menú ya llevan a sus KM. Recursos nuevos en `assets/km3b`, `assets/km4`, `assets/km5`, `assets/km6` (exportados del Figma).
  - **Deslizables de costado** (lo que en el Figma se sale del cuadro): se arrastran con mouse o dedo, con trackpad horizontal o Shift + rueda, con inercia y rebote suave en los bordes (función `deslizable`). Quieto se ve igual al Figma.
    - KM 3 · tira de construcción: libre, las cotas (9/24/124 px) se mueven con la tira; la primera vez que aparece se corre un poco y vuelve, para mostrar que se puede mover.
    - KM 6 · carruseles de fotos: flechas como el prototipo (Smart animate 0,5 s, de la última vuelve a la primera) + arrastre que encastra en cada foto; la foto se corre un poco dentro de su marco (paralaje).
    - KM 4 · carrusel de pantallas de la app: arrastre + los 3 puntitos de abajo; la pantalla 1 queda donde está en el Figma y las otras se centran.
  - **Interacciones que respetan el diseño:** KM 4: los íconos de alineación cambian la alineación de la frase; pasar el mouse por Light/Semi Bold/Regular/Bold (o por el "Aa") cambia el peso del "Aa" (por eso las fuentes se cargan como variables). KM 5: "Colores por marca" igual al prototipo (Dissolve 0,3 s; logo activo al 100 %, otros al 50 %; colores ajenos a la marca al 15 %); click en un color copia su HEX y muestra "¡Copiado!"; los tonos de % se ensanchan al pasar el mouse. KM 6: las piezas de cada marca y los puntos sobre el texto de introducción son stickers jugables (como truus.co); banner de Fotografías con paralaje. KM 3: las malas prácticas "niegan" con un vaivén al pasar el mouse.
  - Huecos del Figma (avisar al equipo): en KM 4 y KM 5 el subtítulo es copia del KM 2 ("¿Cómo le hablamos…?") y no se usó; los links de los heros de KM 4, 5 y 6 eran "La voz / El tono / Guía de estilo" y se reemplazaron por los nombres de las secciones de cada página; el tag de KM 4–6 dice "KM 2" (se puso el número correcto); KM 5 no tiene footer en el Figma (se agregó el mismo componente: anterior KM 4, siguiente KM 6); en KM 6 el texto de Stop en "Puntos y estrellas" es copia del de Post, y el de "Fotografías Post" es copia del de Spot; la siguiente parada de KM 6 es "Design System · KM 7", que no existe todavía (no lleva a ningún lado); "Usos indebidos de fotografías" son cajas vacías con una cruz (así están en el Figma).

- 11/11/2026 · Mateo · **Más juego (pedido con capturas):**
  - KM 1 · fotos de post.: ahora son un **mazo como truus.co** (`iniciarMazo`): la de adelante se arrastra y se tira a un costado; las de atrás se levantan al pasar el mouse y pasan adelante con un click. Los 3 lugares son los del Figma (centro, izquierda −4,31°, derecha 4,43°), con rebote (back.out, 0,75 s). Alrededor hay **misceláneas de post.** (las mismas piezas del KM 1, `DECOS.postfotos`) que se mecen suave y se pueden empujar.
  - KM 2 · rasgos ("Optimista", "Transparente"…): se **agarran y se tiran** con inercia y se inclinan según la velocidad (`iniciarRasgos`). Doble click: vuelven a su lugar.
  - Heros de todos los KM: las misceláneas **flotan** lento (10–26 px/s) en una dirección al azar, salen por un borde y entran por el otro (`iniciarFlotar`). Se siguen pudiendo empujar.
  - KM 3 · tira de construcción: **ya no se arrastra**; queda fija en pantalla y se corre sola de costado mientras scrolleás (1500 px de scroll para recorrerla), después sigue el scroll normal (`iniciarTira`, `.pin-tira` con `position: sticky`).
  - KM 3 · variantes de color: al cambiar de fondo, **el fondo nuevo crece como un punto** desde donde hiciste click (flecha, punto de la paleta o el menú de fondos) y el logo entra girando con rebote; los puntos de la paleta aparecen de a uno.
- 11/11/2026 · Mateo · **Títulos sin agujeritos en el borde crema.** Con el trazo de 23 px quedaban huecos chiquitos de fondo donde dos letras o palabras están apenas separadas (la "y" de "Voz y Tono") o en el centro de las "o" ("Logotipos"). Ahora el borde se dibuja en un canvas y se rellenan solo los huecos cerrados (lo que el fondo no alcanza desde afuera); el contorno exterior queda idéntico (`bordesSinHuecos`). Se taparon huecos en KM 2, KM 3 y KM 5; los otros títulos no tenían.
- 11/11/2026 · Mateo · **Misceláneas de los heros con física** (reemplaza el "salen por un borde y entran por el otro"). Reglas del equipo: no pasan por arriba del título (chocan contra él, medido con la tinta real de las letras + el borde crema), rebotan entre ellas y contra los bordes del cuadro (no se van), y nunca se quedan quietas (12–24 px/s). También chocan con el tag "KM n" y el logo grande del KM 1. El mouse las empuja con velocidad y giro, y después vuelven de a poco a su ritmo (`iniciarFlotar`; las del hero ya no usan el empuje de GSAP de `iniciarStickers`).
- 11/11/2026 · Mateo · **Misceláneas de los heros, versión suave** (reemplaza la anterior). Movimiento lento (10–22 px/s) y choques blandos: un "colchón" de 22 px las desvía de a poco del título (y del tag y el logo del KM 1), y entre ellas también; nunca quedan encima del título ni encimadas. Los bordes de la pantalla ya no las frenan: salen del cuadro y cada 3–6 s entra una nueva por la izquierda o la derecha (máximo: las del Figma + 4). La carita y la insignia son únicas: si salen, vuelven a entrar por un costado. El mouse las empuja suave (tope 320 px/s) y el giro es leve.
  - Piezas que pueden entrar (`PIEZAS_SPOT`): solo de SPOT!, la marca de estas páginas según el Figma (componente "Punto": paleta Amarillo, Naranja, Rosa, Violeta, Azul, siempre con borde crema; formas círculo, estrella 7 y estrella 12). Nunca del mismo color que el fondo del hero (regla de "Vectores y color" del KM 5). Como en los heros del Figma, 3 de cada 4 son puntos y 1 es estrella. post. y STOP no aparecen acá porque estas páginas son de SPOT!.
- 11/11/2026 · Mateo · **Caritas e insignias entre las misceláneas que entran por los costados.** Mezcla: 50 % puntos, 18 % caritas, 17 % insignias, 15 % estrellas (`MEZCLA`).
  - Caritas: las 9 de "Brand guidelines TP5" (Cara 1–9, `assets/miscelaneas/cara-N.png`, imágenes originales transparentes) dentro de un círculo de un color de SPOT! (nunca el del fondo), borde crema y una inclinación al azar. La carita del Figma de cada hero, cuando sale y vuelve a entrar, cambia de cara y de color.
  - Insignias: las 7 de logros de la app (página "Spot": grupo, consistencia, asistencia perfecta, nuevo integrante, lugares, lugar asociado, lugar repetido), en `assets/miscelaneas/insignia-*.svg`, sin el número de hito. Tampoco entran si son del color del fondo.
  - Tip técnico: las exportaciones de Figma por MCP traen un fondo #373737 (y a veces el de la ficha: #1E1E1E, #252525 y un borde blanco). En SVG se puede borrar ese `<rect>`; en PNG no, así que para imágenes sueltas usar las "raw images" originales.
- 11/11/2026 · Mateo · **KM 5 · logo activo bien encendido.** Los SVG de post. y STOP se habían exportado de la variante "Spot", con la transparencia del 50 % (estado apagado) ya incluida. Ahora se usan los logos de cada variante activa (349:2782, 349:2898, 349:3019), limpiando el fondo de la sección que trae la exportación. Activo 100 %, los demás 50 % (CSS).
- 11/11/2026 · Mateo · **Cada KM arranca con sus propias misceláneas** (`variarHero`). Mismas posiciones y tamaños del Figma, pero en KM 2–6 cambian los colores de los puntos (solo SPOT!, nunca el del fondo), la estrella grande, la insignia (KM 2 grupo, KM 3 consistencia, KM 4 asistencia perfecta, KM 5 lugar repetido, KM 6 lugar asociado) y la carita (KM 2 cara 1 violeta, KM 3 cara 7 amarilla, KM 4 cara 2 rosa, KM 5 cara 9 naranja, KM 6 cara 3 azul). KM 1 queda igual al Figma.
- 11/11/2026 · Mateo · **Ajustes varios:**
  - Home: la pastilla del punto 1 dice "KM 1 · SPOT!" como en el Figma (variante Hover de "Puntos mapa"). Los otros puntos siguen con el nombre de su KM porque el Figma solo tiene ese texto de ejemplo.
  - **Transición portada → Home** (reemplaza el Dissolve de 0,1 s): el contorno del logo es el recorrido del mapa, así que el amarillo se desvanece (1,3 s), el contorno pasa de negro a crema y se afina hasta coincidir con el mapa; después aparecen los 10 puntos uno por uno con rebote, y por último menú, logo y submarcas. El video arranca con un leve zoom que se asienta.
  - Misceláneas fijas (post. y STOP del KM 1, las de alrededor de las fotos y las de la intro del KM 6): ya no quedan encimadas; si dos se tocaban se corren lo mínimo (`separarDecos`).
  - KM 5: el logo SPOT! había desaparecido al limpiar el SVG (se borró el recorte `clipPath` que lo hace visible). Recuperado. Ojo al limpiar SVG: el `<rect fill="white">` dentro de `<clipPath>` no se toca.
  - KM 6: la fila de arriba de STOP ya no es una sola imagen; son 6 piezas sueltas (`stop-f1`…`stop-f6`) que se empujan cada una por separado.
- 11/11/2026 · Mateo · **Home: la pastilla de los puntos no mostraba "KM n".** El `<span class="km">` heredaba el estilo de las páginas `.km` (que arrancan con `visibility:hidden`). Se renombró a `pkm`. Regla: no usar la clase `km` para nada que no sea un `article.km`.
- 11/11/2026 · Mateo · **KM 3 · Tamaños pequeños de uso interactivo** (`iniciarTamano`). Quieto se ve como el Figma. Los extremos de la regla (los triangulitos) se arrastran: la regla y el logo se achican o agrandan juntos y el número se actualiza (px en Digital, mm en Impresión). Por debajo del mínimo (70 px / 25 mm) el número pasa a naranja, aparece "Mínimo recomendado: …" y el logo se desenfoca de a poco (se "empasta", como dice el texto). La primera vez que aparece se achica y vuelve sola para mostrar que se puede tocar. También con flechas del teclado.
- 11/11/2026 · Mateo · **KM 6 · las misceláneas de la intro viajan a la card de SPOT! al scrollear** (`iniciarViajeKM6`). El recorrido está atado al scroll: arranca cuando dejás atrás la intro y termina cuando la card queda centrada; volviendo hacia arriba se desarma. Entran 8 (3 estrellas a 85 % y 5 puntos) ubicadas alrededor del logo sin taparlo; las amarillas no entran porque la card es amarilla (regla de "Vectores y color"), y las que sobran se achican y desaparecen en la primera parte del recorrido. Se siguen pudiendo empujar con el mouse.
- 11/11/2026 · Mateo · **Cursores de la marca** (idea tomada de bitwip.fr, que usa cursores propios en imagen con un halo claro: flecha por defecto, manito en lo clickeable y "grab" en lo que se arrastra). Adaptado a SPOT!, en `assets/cursor/`: `flecha.svg` (la flechita que pasó Mateo, con interior crema y halo crema) por defecto; `estrella.svg` (estrella de 7 puntas naranja de SPOT!, borde crema y contorno negro) en todo lo que se puede clickear; `mano.svg` (la mano que pasó Mateo, con interior crema) en todo lo que se arrastra. Solo con mouse (`@media (hover:hover) and (pointer:fine)`); el bloque de CSS está al final de los estilos.
- 11/11/2026 · Mateo · KM 3 · la demo de **tamaños** se repite cada vez que vuelve a aparecer en pantalla (también al subir), salvo que la tengas agarrada. KM 5 · **"¡Copiado!"** ahora es una pastilla grande (Sora 34) que aparece con un rebote en el medio del color. KM 4 · pasar el mouse por **Light / Semi Bold / Regular / Bold** cambia también el peso de la frase del recuadro de color de esa tipografía (celeste para Sora, amarillo para Reddit Sans).
- 11/11/2026 · Mateo · **Cursor propio (reemplaza los cursores en imagen)** (`iniciarCursor`). Como los cursores del sistema no pueden hacer transiciones, se esconde el del sistema y se dibuja uno en la página (`#cursor`), solo con mouse.
  - `flecha.svg` (la flecha nueva que pasó Mateo, interior crema) por defecto; `clic.svg` (la flecha con rayitos) sobre lo clickeable; `mano.svg` sobre lo que se arrastra. Pasan de una a otra con un fundido y un rebotecito; al apretar se achica un poco.
  - Una estrellita de SPOT! (`estrella.svg`, 16 px) persigue al cursor con retraso y gira según la velocidad.
  - **Pastilla explicativa** (idea de bitwip.fr, la del texto que corre): negra con borde crema, la estrella de SPOT! girando y un texto en mayúsculas que corre. Aparece sobre lo interactivo (`PISTAS`: "Agarralos y tiralos", "Tirala a un costado", "Arrastrá para ver más", "Achicá el logo", "Copiá el color", "Cambiá de marca", "Cambiá el fondo", etc.), cada mensaje como mucho 3 veces por visita. Mientras se ve, la estrellita se esconde (pasa a ser la de la pastilla).
  - Las reglas `cursor:` con los SVG quedan de respaldo si falla el JavaScript.
- 11/11/2026 · Mateo · **Estrellita del cursor, más tierna.** Ahora es la estrella de 8 puntas rosa de SPOT! (`assets/km2/6b150.svg`, 22 px), va abajo a la derecha de la flecha sin taparla, llega despacio (como una mascota que te sigue), flota apenas arriba y abajo y **no gira**. La pastilla explicativa usa la misma estrella.
- 11/11/2026 · Mateo · **Favicon animado** del Figma (componente "Favicon animado" `320:1134`, en Brand guidelines TP5): 12 cuadros (`assets/favicon/f01.svg`…`f12.svg`: el logo SPOT!, el punto de post. y la estrella de STOP en distintos colores), cada uno 0,625 s, corte seco y en loop, igual que el prototipo (`iniciarFavicon`). Funciona en Chrome y Firefox; Safari muestra el primer cuadro fijo.
- 11/11/2026 · Mateo · **Se sacó la pastilla explicativa** del cursor (no quedó bien). **Estrellita del cursor:** ahora es la estrella de 12 puntas azul de SPOT! (`assets/km2/319f2.svg`, 20 px) y se mueve más sutil: se acomoda en unos 0,16 s, a la misma velocidad sin importar los cuadros por segundo, y nunca queda a más de 46 px de su lugar (sin tirones ni saltos); flota apenas y no gira.
- 11/11/2026 · Mateo · **KM 2 · "Somos… pero no…" completo.** Los ejemplos de "pero no" sí estaban en el Figma: cada instancia de "Fila Somos / Pero no" guarda sus textos en las propiedades "Ejemplo sí" y "Ejemplo no" (por eso en el prototipo andaba). Se cargaron las 8 filas en `SOMOS`. Ya no aparece "Falta el ejemplo…". Tip: para leer textos de instancias, mirar `componentProperties`, no solo las capas de texto visibles.
- 11/11/2026 · Mateo · **Sincronización con el Figma actualizado (2.ª ronda).**
  - Inicio: "Última actualización Nov 2026" abajo a la derecha (Sora Light, crema 60 %).
  - Menú y mapa: KM 7 Design System, KM 8 Animaciones, KM 9 Íconos, KM 10 Arquigrafía. Todavía sin página, así que no son links (KM 10 y KM 7 ya tienen página desde el 12/11).
  - KM 1: la parada anterior es KM10 · Arquigrafía (ahora es link, desde el 12/11).
  - Subtítulos de los heros: KM 3 "Nuestra firma en todo lugar" (con links a Construcción / Variantes / Malas prácticas), KM 4 "Incluso el texto lleva nuestra impronta", KM 5 "La clave de nuestra expresión visual", KM 6 "Nuestra expresión visual potenciada".
  - KM 5 · Tipografía y color: queda un solo párrafo, como en el Figma.
  - KM 6 · Usos indebidos: texto nuevo y 9 fotos reales en 3 filas (`assets/km6/indebido-1..9.jpg`), con la cruz de 1 px; al pasar el mouse la foto hace "que no".
  - KM 6 · Secciones nuevas: Ilustraciones, Caritas (set de 10 con nombre y color, `assets/miscelaneas/carita-*.png`, se pueden empujar), Efecto puntos (tarjeta de logro `insignia-card.svg`; en el Figma no tiene fondo) y Puntos en siluetas (botón a meshic.app).
  - Las caritas que aparecen flotando en los heros ahora son las 10 oficiales.
  - No se construyó: la sección "Tipografía y color" duplicada en el Figma del KM 5, ni la grilla de caritas repetida dentro de "Efecto puntos".
  - Typos del Figma copiados tal cual: "hehcas", "fromado".
  - El fondo de "Puntos en siluetas" es un cuadro fijo del video halftone (`siluetas-halftone.jpg`) hasta que tengamos el archivo de video.
- 11/11/2026 · Mateo · **Volver a la Home repite la animación principal** (`repetirPortada`). Cada vez que se vuelve a la Home desde un KM (menú "Volver al Inicio", logo, atrás del navegador), la portada amarilla entra con un fundido de 0,25 s. Después se ve otra vez la animación de los puntitos del logo (2,4 s) y la transición al mapa. Con un click se saltea, igual que al entrar.
- 11/11/2026 · Mateo · **KM 5 · puntos de color en Crema/Negro Spot** (Figma `455:2521` y `455:2520`). Son 7 puntos de 36 px abajo de cada bloque: amarillo, naranja, rosa, violeta, azul, verde, y negro (en el bloque crema) o crema (en el bloque negro). Al tocar uno, el fondo que está detrás de los tonos 80–10 % pasa a ese color en 0,5 s, para entender cómo se ven las opacidades sobre cada color. El punto elegido queda un poco más grande. El bloque de cada color mide 950 px, como en el Figma. Tocar los puntos no copia el HEX.
- 11/11/2026 · Mateo · **Botón del menú siempre visible en los KM** (`iniciarBotonMenu`). Arriba de todo queda igual al Figma. Cuando bajás más de 140 px, queda fijo en su lugar, se achica un poco y lleva un círculo detrás. El círculo cambia de color según lo que tiene abajo para que siempre se vea: crema con las rayitas negras sobre fondos oscuros y sobre fotos, y negro con las rayitas crema sobre fondos claros. En la Home no cambia nada.
- 11/11/2026 · Mateo · **KM 6 · Signos Display: rastro de misceláneas** (idea de extrafazant.nl, `iniciarRastro`). Al mover el mouse en el espacio vacío a la izquierda de cada pieza, se van dejando misceláneas de esa marca: al lado de post. solo las de post., al lado de STOP solo las de STOP. Nunca se mezclan, porque las marcas no conviven.
  - Tamaños de 48 a 178 px. Aparecen con un rebote, se van solas a los 2,6 s y como máximo hay 14 a la vez.
  - Solo se usan las piezas que se ven sobre crema: post. `post-p1/p3/p4/p5`; STOP `stop-f1/f2/f4/f5/f6` y `stop-estrella`. Las de contorno crema no se ven sobre ese fondo.
  - Solo funciona con mouse.
- 11/11/2026 · Mateo · **Botón del menú: sin círculo** (pedido del equipo, reemplaza lo anterior). Queda fijo; arriba de todo tiene el tamaño del Figma y al bajar más de 140 px se achica al 60 % y se corre un poco hacia la esquina (0,35 s). Además cambia de color según el fondo: negro sobre fondos claros, crema sobre fondos oscuros y fotos (fundido de 0,3 s).
- 11/11/2026 · Mateo · **KM 2 · "Nuestro perfil de tono" rehecho como en el Figma nuevo** (`180:258`).
  - Fondo negro y textos crema. Cada dimensión tiene una barra de 1000 px de su color al 35 % (Divertido/Serio amarillo, Casual/Formal violeta, Irreverente/Respetuoso rosa, Entusiasta/Práctico naranja).
  - Sobre cada barra, un tramo lleno que va del centro hasta donde está Spot, y una marca de 13 × 45 px. Posiciones sobre 1000: 300, 200, 650 y 400.
  - El extremo donde está Spot va en crema y el otro al 40 %. Ya no se usan las imágenes de las barras y se sacaron los divisores de alrededor.
  - **Animación al llegar scrolleando** (`iniciarPerfil`): cada barra se dibuja de izquierda a derecha. La marca nace en el centro y se desliza con un rebotecito hasta donde está Spot, y el tramo de color la acompaña. El extremo elegido se enciende y la frase sube.
  - Va de a una fila (0,16 s entre filas) y se repite cada vez que la sección vuelve a entrar en pantalla. No se puede mover a mano.
- 11/11/2026 · Mateo · **KM 6 · "Puntos y estrellas" también deja el rastro de misceláneas** (misma función que Signos Display, `rastroEn`). Al mover el mouse en el espacio vacío a la izquierda de cada tarjeta, se dejan piezas de esa marca: al lado de SPOT! sus puntos y estrellas (las 16 piezas de la intro, `intro-1..16`), al lado de post. las de post. y al lado de STOP las de STOP. Nunca se mezclan. El máximo de 14 piezas a la vez es por sección.
- 11/11/2026 · Mateo · **KM 6 · Signos Display: el rastro deja signos display**, como cuenta el texto ("las estrellas de Post y Stop pueden usarse en tamaños mucho más grandes"). Ya no se dejan misceláneas chicas: ahora son las estrellas de cada marca en tamaño grande (150 a 340 px) y en línea fina.
  - Las piezas son `assets/km6/display-post-1/2.svg`, las estrellas de post. en verde, y `display-stop-1/2.svg`, las de STOP en azul y rosa. Tienen la misma forma que las piezas originales, solo el contorno, con un trazo que no engorda al agrandarse.
  - post. al lado de post. y STOP al lado de STOP. Como máximo 6 a la vez.
- 11/11/2026 · Mateo · **KM 6 · carruseles de fotos (Spot, Post y Stop) se deslizan con el scroll** (reemplaza el arrastre, `iniciarCarruseles`). Funciona como la tira de construcción del KM 3.
  - Al llegar, el carrusel queda fijo en el medio de la pantalla y las fotos pasan de costado mientras scrolleás: 700 px de scroll por foto.
  - Cada foto se queda quieta un momento antes de dar paso a la siguiente. Cuando termina, la página sigue normal, y volviendo hacia arriba se recorre al revés.
  - Las flechas del prototipo siguen andando: llevan el scroll hasta la foto anterior o la siguiente, y de la última vuelven a la primera. El paralaje de la foto dentro del marco se mantiene.
- 11/11/2026 · Mateo · **KM 6 · "Elementos sobre fotografías"** (Figma `483:9862`, después de Usos indebidos y sin divisor, como en el Figma). Se hizo lo que pide el comentario de Franco en el Figma.
  - Son 2 fotos de 1400 × 788 (`assets/km6/sobre-foto-1.jpg` y `sobre-foto-2.jpg`). Al pasar el mouse, cada una cambia a su versión de la derecha del Figma.
  - Foto 1: capa negra al 30 %, la frase "En compañía es mejor." y el logo SPOT!.
  - Foto 2: degradado negro de 0 a 80 % (hasta el 87 % de la altura), el título "Encontrá tu team" en naranja y su texto.
  - Además aparece el cartel del selector de color de Figma (`panel-color.png` y `panel-degradado.png`, las capturas que puso el equipo al lado de cada foto), con un rebote.
  - Con teclado también funciona (al hacer foco), y en pantallas táctiles se alterna tocando.
  - Typos del Figma copiados tal cual: "usar colocar", "princincipiantes".
- 11/11/2026 · Mateo · **KM 6 · "Efecto puntos" pasó a llamarse "Insignias"** (Figma `448:2449`), con el texto nuevo. Typo del Figma copiado tal cual: "caritaa." y "utilizamos" en minúscula. La grilla de caritas repetida ya no está en el Figma.
- 11/11/2026 · Mateo · **Elementos sobre fotografías: el cartel ya no es la captura de Figma** (pedido del equipo; se borraron `panel-color.png` y `panel-degradado.png`). Ahora es un cartel propio con la gráfica de la marca: negro, borde crema, Sora y Reddit Sans, y el porcentaje en naranja.
  - Foto 1, "Capa sobre la foto": muestra #000000 y el porcentaje. Tiene una regla con el rango recomendado 20–30 % marcado con línea punteada naranja. Al mover el control (de 0 a 60 %) cambia la capa de la foto de verdad.
  - Foto 2, "Degradado lineal": muestra #000000 al 80 % y dónde está cada parada (0 % arriba, 80 % al 87 % de la altura). Al mover el control cambia lo oscuro del final del degradado.
  - El cartel aparece con el hover y se puede usar sin que se cierre.
- 11/11/2026 · Mateo · **Rastro de misceláneas también al scrollear con el mouse quieto** (Puntos y estrellas y Signos Display). La página que pasa debajo del cursor cuenta como recorrido: si el cursor está al lado de una tarjeta, se van dejando piezas de esa marca, y cambian de marca cuando pasás de una tarjeta a la otra.
- 11/11/2026 · Mateo · **KM 6 · Insignias rehecha con el Figma nuevo** (`448:2449`) y los comentarios de Estefanía:
  - **Unir los puntos** (Group 81): están los puntos y los números del 1 al 29 que forman SPOT, sin las líneas. Al pasar por encima, el cursor pasa a ser el lápiz de Phosphor del Figma (`assets/cursor/lapiz.svg`). Se arrastra de punto a punto, o se toca uno y después otro, y queda la línea violeta (#AB8AE5, 3,7 px). Doble click borra todo (`iniciarUnirPuntos`).
  - **Cinta de íconos de puntos**: los 10 íconos del Figma (tulipán, rayo, llama, gota, rama, mariposa, reloj, candado, café, cubiertos; `assets/km6/icono-*.svg`) pasan solos en loop a velocidad media (55 s la vuelta; antes 75 s, se aceleró el 11/11 a pedido del equipo). Se pausan con el mouse encima, y la grilla rosa de 15 px solo aparece sobre el ícono que tiene el mouse (`iniciarCintaIconos`).
  - **"Descargar plantilla"** descarga `assets/km6/plantilla-insignia.svg`. Es la grilla de 15 px de 405 × 405 del frame "Insignia · Plantilla", rosa al 35 %, armada a mano porque la grilla del Figma es de diseño y no se exporta.
  - **¿Cómo crear una insignia?**: el texto tiene las partes en violeta del Figma. La receta (mariposa + círculo violeta con borde crema + sombra paralela = insignia Noobie) gana opacidad paso a paso mientras scrolleás hasta ahí (`iniciarReceta`).
  - La captura del panel "Drop shadow" de Figma se cambió por una tarjeta propia de la marca con los mismos valores: X 0, Y 4, desenfoque 4, expansión 0, #000000 al 25 %.
  - La insignia Noobie se exportó del Figma (`insignia-noobie.svg`). Se borró `insignia-card.svg` porque la tarjeta de consistencia ya no está en el Figma.
- 11/11/2026 · Mateo · **Insignias · "unir los puntos" ahora es guiado** (pedido del equipo: dibujar a mano era poco intuitivo; reemplaza el lápiz libre).
  - Mientras scrolleás por la sección, un lapicito une solo los puntos en orden con la línea violeta y se forma SPOT: S 1–10, P 11–17, O 18–25 y vuelve al 18, T 26–28 y 27–29.
  - Los puntos y los números se ponen violetas cuando el lápiz pasa por ellos.
  - Arranca cuando el dibujo asoma abajo y termina cuando su centro llega a la mitad de la pantalla. Volviendo hacia arriba se borra al revés.
  - El cursor ya no cambia a lápiz: `lapiz.svg` se usa ahora para el lapicito que dibuja.
- 11/11/2026 · Equipo · **KM 3 · Botón "Descargar Logos"** (Figma `544:11222`, debajo del título "Logos Spot"): mismo estilo que "Descargar plantilla" (pastilla negra, Reddit Sans SemiBold 20, crema), 207 × 54 px, 109 px debajo del título; acompaña al título mientras se scrollea (sticky). Descarga `assets/descargas/Logos_Spot.zip` (SPOT!, post. y STOP en color y negro, PNG y SVG). Los archivos para descargar van en `assets/descargas/`. Ojo: en el KM 3 del Figma hay otro "Descargar plantilla" (`498:2076`, plantilla de lockup) que todavía no está en la página.
- 11/11/2026 · Equipo · **KM 3 · tira de construcción: cotas fijas y logos hasta el borde** (pedido con capturas). En el Figma las franjas naranja/rosa, la línea punteada, las flechas y los textos 9/24/124 px están sueltos en la lámina (x 377–1404), no dentro de la tira; por eso ahora quedan quietos y los tres logos pasan por debajo para compararlos. La tira ocupa los 1920 px (ya no se corta en el margen de 120 px); arranca y termina en el margen como antes. Arreglado de paso: las flechas verticales de las cotas no se veían (una regla las estiraba).
- 11/11/2026 · Equipo · **KM 6 · La cinta de íconos de puntos va más rápido**: 55 s por vuelta en vez de 75 s (`.pista-iconos`, animación `cinta`). Se sigue pausando con el mouse encima.
- 12/11/2026 · Mateo · **KM 3 · sección Favicon** (Figma `549:2362`, entre Variantes de color y Tamaños pequeños, con divisor antes y después).
  - Tiene el texto con "O de cada logo" y "colores de su marca" en azul y negrita, como en el Figma.
  - Variables: los 12 favicons del favicon general.
  - Animaciones: General (12 cuadros), Spot (15), Post (4) y Stop (4), cada una en tamaño mediano (240) y miniatura (32). Las secuencias son las de los componentes "Favicon animado · … · mediano + miniatura", a 0,625 s cada cuadro.
  - Según el comentario de Estefanía, **cada animación solo corre mientras el mouse está encima**. Al sacar el mouse vuelve al primer cuadro. Con teclado funciona al hacer foco.
  - Los cuadros se arman en el momento con las formas de `assets/favicon/f01` (O de SPOT!), `f05` (O de post.) y `f09` (estrella de STOP), cambiando los colores (`iniciarFaviconSec`).
- 12/11/2026 · Mateo · **KM 3 · sección Colaboraciones** (Figma `495:2064`, entre Ubicación y Malas prácticas, con divisor antes y después).
  - Tiene el encabezado y 4 bloques con las pautas a la izquierda y la muestra a la derecha:
    - **Composición del lockup**: Spot × Café Martínez, sobre negro.
    - **Jerarquía visual**: Spot × Íntegra, sobre negro.
    - **A pedido de la marca**: Spot × Hyper Night 10K y Spot × adidas, sobre negro.
    - **Plantilla**: el logo, el signo ×, el recuadro para el logo aliado y las guías.
  - Los lockups y la plantilla se exportaron del Figma: `assets/km3/lockup-*.svg` y `plantilla-colaboracion.svg`.
  - El botón **"Descargar plantilla"** baja `plantilla-colaboracion.svg`.
  - Cada lockup aparece de izquierda a derecha, como si se armara, la primera vez que entra en pantalla (`iniciarColab`).
  - Typo del Figma copiado tal cual: "esta la única excepción" (sin tilde y sin "es").
- 12/11/2026 · Mateo · **KM 5 · sección Proporción** (Figma `372:1525`, después de las hojas de filtros y antes de Tipografía y color, con divisor después).
  - Tiene el texto del Figma y una barra por marca de borde a borde (1920 × 240), con los anchos exactos del Figma:
    - **Spot:** crema 20 % (con borde negro), amarillo, naranja, rosa, violeta y azul 15 % cada uno, negro 5 %.
    - **post.:** negro 50 %, verde 25 %, crema 15 %, violeta 10 %.
    - **Stop:** negro 45 %, rosa 25 %, azul 15 %, crema 15 %.
  - El logo de cada marca va en el primer tramo (`assets/km5/prop-logo-*.svg`, exportados del Figma).
  - Al entrar en pantalla, cada barra se llena color por color de izquierda a derecha. Al pasar el mouse por un color, ese tramo se ensancha (`iniciarProporcion`).
- 12/11/2026 · Mateo · **Movimientos con scroll más sutiles** (pedido del equipo): la tira de construcción del KM 3 y los carruseles de fotos del KM 6.
  - Ya no saltan al lugar que marca el scroll: lo siguen con suavidad, en unos 0,45 s (`seguirSuave`).
  - **Tira:** necesita más scroll para recorrerse, 2400 px en vez de 1500.
  - **Carruseles:** 1000 px de scroll por foto en vez de 700, cada foto se queda quieta más tiempo y el paralaje dentro del marco es más leve (30 px en vez de 50).
- 12/11/2026 · Mateo · **Colaboraciones con animación de armado** (pedido del equipo; reemplaza el barrido de izquierda a derecha).
  - Cada lockup y la plantilla se parten en tres: SPOT!, el × y el logo aliado (o el recuadro). Los cortes van en el medio de los espacios, según el Figma (`CORTES_LOCKUP`).
  - Al entrar en pantalla se arman: SPOT! llega desde la izquierda, el logo aliado desde la derecha y el × aparece girando con un rebote. En "A pedido de la marca" el segundo lockup se arma un poco después.
  - Al salir del todo de la pantalla se desarman, así se vuelve a ver la animación al pasar otra vez.
  - Al pasar el mouse por un ejemplo, los dos logos se separan un poco y el × gira, para mostrar que el espacio a cada lado del × es el mismo.
- 12/11/2026 · Mateo · **KM 3 · Favicon con animación de entrada** (pedido del equipo, `entradaFavicon`).
  - Al llegar scrolleando, los 12 favicons de Variables saltan de a uno, de izquierda a derecha, girando con un rebote (0,06 s entre cada uno).
  - Después aparecen las 4 animaciones, una tras otra: el favicon mediano crece girando con rebote, la miniatura cae a su lugar y suben el título y el texto.
  - Se repite cada vez que la sección vuelve a entrar en pantalla. El hover sigue igual: la animación de cada favicon solo corre con el mouse encima.
- 12/11/2026 · Mateo · **KM 3 · animaciones de entrada en Logos Spot, Construcción, Espacios seguros y Ubicación** (pedido del equipo, `iniciarKM3Entradas`). Se repiten cada vez que la parte vuelve a entrar en pantalla.
  - **Logos Spot:** cada logo entra con el carácter que describe el texto. SPOT! se marca de izquierda a derecha, como un recorrido. post. aparece calmo, con un desenfoque que se aclara. STOP explota con un rebote. El hover de SPOT! sigue igual.
  - **Diagramas** (Construcción, Espacios seguros y Ubicación): se dibujan solos. Primero aparecen los logos, después se trazan las guías (las líneas azules de la altura de x, las cajas de espacio seguro, los márgenes) y al final aparecen las líneas punteadas.
  - Para poder animar sus partes, esos SVG ahora se cargan dentro de la página en lugar de como `<img>`. Quietos se ven igual que antes. Los archivos de `assets/km3/` y `assets/km3b/` no cambiaron.
- 12/11/2026 · Mateo · **Arreglo: el logo SPOT! de "Logos Spot" no aparecía.** La caja estaba recortada del todo mientras esperaba, y el navegador no avisaba que había entrado en pantalla. Ahora el recorrido de izquierda a derecha recorta las imágenes de adentro, no la caja.
  - Además, las entradas del KM 3 (logos y diagramas) ya no usan IntersectionObserver: miran el scroll de cada KM (`entradaRepetida`).
  - Regla: no ocultar con `clip-path` el mismo elemento que se usa para detectar si entró en pantalla.
- 12/11/2026 · Mateo · **Versión mobile (responsive)**, pedido del equipo: que se mantengan todas las animaciones e interacciones que se puedan.
  - **Cómo funciona.** Si la pantalla mide hasta 760 px de ancho, un script en el `<head>` pone la clase `movil` en `<html>`. Entonces los KM se diseñan a **480 px** en vez de 1920 (`--z` = ancho / 480). Todo va en una columna con márgenes de 24 px. Si se cruza el corte (girar el celular, achicar la ventana), la página se recarga.
    - Los estilos están todos juntos al final del CSS, en el bloque "VERSIÓN MOBILE", con `html.movil`.
    - En JS, las constantes `MOVIL`, `ANCHO` y `ALTO_HERO`.
    - La versión de compu no cambió.
    - Las tablets (más de 760 px) siguen viendo la versión de compu.
  - **Portada y Home.** Se ve la franja central del escenario, con el mapa entero y todo el alto de la pantalla. El menú, el logo, post./STOP y "Última actualización" se reubican arriba y abajo. La pastilla de los puntos no aparece: tocar un punto lleva directo al KM.
  - **Heros.**
    - Tag, título, bajada y links van uno debajo del otro.
    - Los títulos largos se parten en dos renglones (`renglones()`) y se achican para entrar en 432 px. El borde crema sin huecos también funciona con dos renglones.
    - Las misceláneas con física siguen andando, en un cuadro de 480 × 1000. Esquivan el título, la bajada y los links, y entra 1 nueva como máximo.
  - **Lo que se reacomoda en columna:**
    - zona de submarcas del KM 1: el mazo de fotos va en su propia caja debajo del botón de post., con sus misceláneas;
    - pilares, cards, perfil de tono y "Somos… pero no…" del KM 2;
    - variantes, favicon, tamaños, diagramas, colaboraciones y malas prácticas del KM 3;
    - todo el KM 4: los bloques de Sora y Reddit Sans, las frases, los pesos y "xan";
    - paleta (2 columnas), crema/negro, filtros, proporción y tipografía/vectores (2 columnas) del KM 5;
    - intro, cards, piezas, fotos, sobre fotos, caritas (3 columnas), insignias y siluetas del KM 6;
    - el footer.
  - **Lo que se achica entero** (es muy visual y no se puede reacomodar): la tira de construcción (zoom 0,4, se sigue recorriendo con el scroll), el carrusel de la app del KM 4, los lockups, unir los puntos, la cinta de íconos y la receta de la insignia (en dos renglones).
  - **Interacciones en el celular:**
    - Se mantienen: animaciones de entrada, misceláneas de los heros, viaje de las misceláneas a la card de SPOT!, perfil de tono, tira y carruseles con el scroll, mazo de fotos (se tira con el dedo), rasgos (se arrastran), tamaños (se arrastran los extremos), variantes de color, copiar HEX, fondos de los tonos, proporción, lockups que se arman, favicon y unir los puntos.
    - Lo que en compu es hover pasa a ser **tocar**: pilares, misión/visión, cards de enfoque y de tono, favicon y sobre fotos.
    - En "Elementos sobre fotografías" el cartel con el control se ve siempre debajo de la foto. Moverlo enciende la foto.
    - Tocar una miscelánea (fuera de los heros) la hace saltar y girar (`iniciarToques`), en lugar del empuje con el mouse.
  - **No van en el celular:** el cursor propio, el rastro de misceláneas de Puntos y estrellas / Signos Display y el empuje con el mouse (necesitan mouse). Tampoco el fondo halftone de "Puntos en siluetas" ni la silueta de "Si Spot fuera una persona" (no entran en la columna).
- 12/11/2026 · Mateo · **Correcciones de la versión mobile** (pedido del equipo).
  - **Pixelado y "rastro" en el celular.** Lo más probable es que viniera de la propiedad `zoom`, que Safari (iPhone) dibuja mal en lo que se mueve.
    - En mobile ya no se usa `zoom`: el lienzo de cada KM se escala con `transform` dentro de `.escala-km`, que guarda el alto real.
    - La portada y la Home también se escalan así.
    - Las partes achicadas (tira, carrusel de la app, perfil, lockups, unir los puntos, cinta, receta, caritas, logos del KM 5, fotos con cartel, favicon y títulos) usan `achicarMovil()`: `scale` + una caja `.achicado` del tamaño real.
    - El botón del menú queda fuera de lo escalado, fijo arriba.
    - Como `position: sticky` no funciona dentro de un `transform`, en mobile la tira y los carruseles se mantienen fijos con JS (`fijarMovil`).
    - Regla: en mobile no usar `zoom`; para achicar algo, sumarlo a `ACHICAR_MOVIL`.
  - **Misceláneas más chicas y ubicadas con criterio.**
    - Heros: piezas al 60 %, en lugares elegidos a mano alrededor del texto (`HERO_MOVIL`). La carita mide 70 px.
    - Las que entran por los costados también son más chicas.
    - Esquivan también el botón del menú.
    - Submarcas y fotos de post.: al 60 %. Intro del KM 6: al 65 %.
  - **Lo que era hover ahora pasa al scrollear** (`iniciarActivoScroll`): cuando una pieza cruza la franja del medio de la pantalla se activa.
    - Pilares, misión/visión, cards de enfoque y de tono, logo SPOT!, malas prácticas, usos indebidos, signos display, filtros, tipografía/vectores, lockups, "xan" y pantallas de la app.
    - Las animaciones del favicon arrancan solas.
    - Las fotos de "Elementos sobre fotografías" se encienden.
    - Tocar sigue funcionando.
  - **KM 4 · Light / Semi Bold / Regular / Bold:** ahora se tocan. El peso elegido queda puesto en el "Aa" y en la frase (en naranja el elegido), y se saca tocándolo de nuevo. En compu sigue el hover.
- 12/11/2026 · Mateo · **KM 10 · Arquigrafía y señalética** (Figma "Slide 16:9 - 10 · Arquigrafía y señalética", `577:2572`, en Brand guidelines TP5). Textos, orden y medidas iguales al Figma.
  - Secciones: Wayfinding (6 principios), Tipos de señales (direccionales, locativas, orientativas, complementarias), Iconografía, Medidas y alturas, Arquigrafía (un solo frente, lo existente con identidad, hitos a gran escala, la pantalla también es arquitectura). Footer: anterior KM 9 · Íconos (sin link, no existe todavía), siguiente "Volver al inicio".
  - Ahora es link en el menú (con sus 5 subsecciones), en el mapa de la Home y en la "parada anterior" del KM 1.
  - **Hueco del Figma (avisar al equipo):** el hero de esta página dice "KM 9" y "Parada anterior: Animaciones · KM8", pero el menú del Figma (y la página) la tienen como **KM 10** (KM 9 es Íconos). Se usó KM 10 para que coincida con el menú y el mapa.
  - Archivos en `assets/km10/`: los esquemas son SVG exportados del Figma (`direccionales`, `locativas`, `orientativas`, `complementarias`, `iconos`, `medidas`); fotos `parada.jpg`, `inflables.jpg`, `parada-foto.jpg`; `stand.png` (imagen del Figma). Las pantallas de post. son videos: ver la entrada de abajo.
  - Hero naranja con las misceláneas de los otros KM (insignia "consistencia", carita violeta en el lugar del Figma, fuera del título).
  - **Animaciones** (se repiten cada vez que se vuelve a pasar):
    - Principios: la línea de arriba de cada uno se dibuja y aparece el texto, de a uno.
    - Señales: los SVG se pasan a la página la primera vez que se abre el KM (`iniciarKM10`, pesan). Las líneas de la regla se dibujan, las cotas aparecen de 0 m a 3 m, la persona entra caminando y cada señal "se instala": lo que apoya en el piso crece desde el suelo y lo que va colgado baja a su lugar, de izquierda a derecha.
    - Íconos: cada familia se da vuelta como un cartel de partidas, ícono por ícono. Con el mouse encima, el ícono salta.
    - Medidas: un nivel naranja sube por la regla al scrollear (0,75 → 1,50–1,70 → 2,25 → 3 m) y marca esa altura en el texto. Con el mouse (o tocando) sobre una altura, el nivel va a esa.
    - Un solo frente: los tres módulos del stand llegan separados e inclinados y se juntan en una sola fachada a medida que se scrollea.
    - Lo existente, con identidad: una franja rosa (como la de la parada) cruza la foto y la descubre.
    - Hitos: las dos fotos "se inflan" (de redondas y chicas a su tamaño, con rebote). Con el mouse encima (en el celular, al pasar por el medio) respiran.
    - Pantallas de post.: las tres pantallas se prenden una por una, con parpadeo.
  - Regla técnica: a una pieza de SVG del Figma que ya trae `transform` (rotada o movida) no se le anima el transform directo, porque lo pisa: se la mete en un `<g>` y se anima ese.
  - **Mobile:** una columna; los esquemas van de borde a borde achicados con transform (`ACHICAR_MOVIL`), las alturas en 2 × 2, las fotos a todo el ancho. El nivel de alturas avanza al scrollear igual que en compu; los íconos y los hitos se activan al pasar por el medio de la pantalla.
- 12/11/2026 · Mateo · **KM 10 · lupa sobre las señales.** En "Tipos de señales" y en "Medidas y alturas", al pasar el mouse sobre una señal aparece agrandada encima del esquema (sale desde donde está, con rebote, y el resto del esquema se apaga un poco), para verla y leerla mejor. Muestra solo esa señal con la regla de alturas detrás. Se cierra al sacar el mouse o con Escape (`armarLupa`).
  - Mobile: se toca la señal para agrandarla; se cierra tocándola de nuevo, tocando afuera o scrolleando lejos.
- 12/11/2026 · Mateo · **KM 10 · Las pantallas de post. son videos** (en lugar de la imagen del Figma). Los 3 MP4 del Drive, uno por pantalla y en este orden: arriba "animación respirar (pantalla entrada)", en el medio "Animación running (pantalla frente)" y abajo "animación insignia (Pantalla atras)". Cada uno va con su proporción original (no se recortan).
  - Comprimidos con `avconvert` de la Mac: `assets/km10/post-respirar.mp4` (960 px de ancho, 24 MB: dura 60 s y no se repite, así que no se recortó), `post-running.mp4` y `post-insignia.mp4` (1280 px, unos 5 MB).
  - Se cargan recién al acercarse y solo se reproducen mientras se ven (sin sonido, en loop); al entrar se "prenden" con el parpadeo de antes.
  - Los originales están en la carpeta `videos stop/`, que **no se sube** (está en `.gitignore`) porque pesan mucho.
- 12/11/2026 · Mateo · **KM 10 · Juego con las misceláneas de post.** en la columna libre al lado de las pantallas de post. (debajo del texto "La pantalla también es arquitectura"). Son las de "Puntos y estrellas" del KM 6 (`PIEZAS.post`: punto verde, aro crema, aro verde y estrellas de 7 y 12 puntas redondeadas), varias de cada una en distintos tamaños, sobre fondo Negro Spot porque el sistema de post. está pensado para fondo oscuro. Caen al llegar, rebotan y se apilan; se agarran y se tiran con el mouse o el dedo, y tocándolas saltan. Al volver a pasar por la sección caen de nuevo. Arriba dice "Agarrá un punto o una estrella y tiralo" y desaparece al jugar (`iniciarJuegoInsignias`). Primero se probó con insignias y con misceláneas de SPOT!, pero va con las de post. porque la sección habla de post.
  - Mobile: la caja va entre el texto y los videos, a todo el ancho, de 360 px de alto, con la mitad de las piezas (10).
- 12/11/2026 · Equipo · **KM 1 · fotos de STOP** (Figma "Group 111" `708:12461`), debajo del botón "Conocé más sobre STOP", igual que las de post.: mismo mazo (la de adelante se tira a un costado, las de atrás pasan adelante con un click) y mismos lugares, 2217 px más abajo, como en el Figma. Fotos: `assets/km1/foto-stop-centro.jpg` (fiesta en la terraza), `foto-stop-1.jpg` (largada, izquierda) y `foto-stop-2.jpg` (tótem, derecha), recortadas como en los marcos del Figma. Las paradas, "Volver arriba" y el copyright bajaron 906 px y la zona mide 4685 px. `iniciarMazo` arma un mazo por marca (`data-mazo="post"` / `"stop"`, función `armarMazo`); en el celular cada mazo va debajo de su botón.
  - **Misceláneas de STOP alrededor de sus fotos** (pedido del equipo, 13/11), como las de post.: 10 piezas en los mismos lugares que las de post. (2217 px más abajo), pero solo con piezas de STOP (las del logo de STOP en el KM 1: punto azul, estrella azul de contorno, cruz de puntos, aros crema, puntos rosa y azul). Se mecen suave y se pueden empujar (`DECOS.stopfotos`). En el celular van alrededor del mazo de STOP, al 60 %.
  - **Arreglo de paso:** el stand de "Un solo frente" (KM 8) y la foto de adelante del mazo usaban la misma clase `.frente`, y el estilo del stand corría la foto de STOP 627 px. Ahora el del stand es `div.frente`.
- 12/11/2026 · Equipo · **Arquigrafía pasa a ser KM 8 y se actualizó con el Figma nuevo** (`577:2572`). Ahora son 8 secciones y Arquigrafía es la última.
  - **Numeración:** el tag dice "KM 8"; el footer del KM 7 lleva a "KM8 · Arquigrafía"; la parada anterior del KM 1 dice KM8; el footer de Arquigrafía: anterior KM 7 · Design System, siguiente Volver al inicio. **La Home (mapa de 10 puntos) y el menú NO se cambiaron todavía** (pedido del equipo): el menú sigue mostrando Animaciones e Íconos y numera Arquigrafía como 10. El id interno de la página sigue siendo `km10` (y la carpeta `assets/km10/`), para no romper links ni código.
  - **Hero rosa** (antes naranja); las misceláneas ya no usan rosa.
  - **Wayfinding:** se sacaron los 6 principios (ya no están en el Figma); queda el texto, con "Post" en vez de "post.".
  - **Textos nuevos:** Direccionales ("…postes autoportantes clavados en la tierra. Adentro, sobre la pared…"), Locativas sin "¿Llegué?", Orientativas ("El directorio de cada piso. Número, nombre y la lista…"), y en 1,50–1,70 m se suma "Para tener en cuenta, la altura promedio de una persona es de 1,75 cm." (typo del Figma copiado tal cual: "1,75 cm").
  - **Iconografía sobre fondo Negro Spot** con textos crema, sin divisores arriba y abajo. El gráfico de íconos es el mismo (ya era la versión oscura).
  - **Arquigrafía:** "Lo existente, con identidad" ahora se llama "Nuestra identidad sobre lo existente" y "Hitos a gran escala", "Hitos inflables y a gran escala". Las imágenes van a la derecha como en el Figma (1113 × 616, x 567); los dos hitos van uno debajo del otro. Debajo de las pantallas de post. se sumó la foto de la fachada (`assets/km10/fachada-post.jpg`, 1110 × 370).
  - **Huecos del Figma (avisar al equipo):** el hero y el footer del Figma dicen "Parada anterior: Animaciones · KM8" (se usó KM 7 · Design System, porque Arquigrafía es la 8); el bloque de las pantallas de post. tiene en el Figma el título y el texto copiados de "Nuestra identidad sobre lo existente" (se dejó "La pantalla también es arquitectura" con su texto); en el Figma las pantallas son una imagen fija, acá siguen los videos.
- 12/11/2026 · Equipo · **KM 6 · intro: las misceláneas se corren para leer el texto.** Con el mouse sobre el texto ("La marca de Spot y sus sumbarcas…"), las 16 piezas se van a la zona libre de la derecha (x 1400–1880), en el mismo orden en que estaban y separadas para no encimarse; sale primero la de más a la derecha (25 ms entre cada una, 0,7 s con rebote). Al sacar el mouse vuelven a su lugar. Si ya arrancó el viaje a la card de SPOT! con el scroll, no se corren (el viaje sigue igual). Se siguen pudiendo empujar. Solo con mouse; en el celular ya van debajo del texto (`iniciarViajeKM6`, usa el `transform` del `.deco`).
- 12/11/2026 · Equipo · **KM 6 · carruseles de fotos: scroll normal y fotos con flechas** (reemplaza "se deslizan con el scroll"). Ya no hay que scrollear todas las fotos de una marca para pasar a la siguiente: la página scrollea de corrido y cada fila se recorre solo con las flechas, como el prototipo (0,5 s, ease-in-out; de la última vuelve a la primera y al revés). Se mantiene el paralaje leve de la foto dentro del marco mientras se mueve. Igual en el celular. Se borraron `.pin-carrusel` y su versión mobile.
- 12/11/2026 · Equipo · **KM 7 · Design System, primera parte** (Figma "Slide 16:9 - 9", `517:10185`). Se construyó solo hasta el botón amarillo; lo que sigue en el Figma (Botones, Elementos de interfaz, Nomenclatura) espera indicaciones del equipo.
  - **Hero** naranja con tag KM 7, "Design System", bajada "Spot en soportes digitales" y links a "De átomos a botones" y "Átomos". Misceláneas como los otros KM: insignia "nuevo integrante" (`insignia-integrante.svg`) y carita 5 rosa en el lugar del Figma (1552, 414).
  - **Átomos**: textos del Figma (`523:10562`), con "átomos", "botones", "diseño atómico" y "decisiones que ya tomamos" en naranja.
  - **De átomos a botones** (`iniciarEscenaDS`): la escena queda fija en el medio de la pantalla durante 1500 px de scroll (1100 en el celular), un tercio por paso, y cada paso se anima solo (CSS según `data-paso`). Volviendo hacia arriba se desarma al revés.
    1. Los dos puntos aparecen con un rebote y después la frase "Todo nuestro sistema se basa en los puntos.".
    2. Desde los dos puntos se despliega el botón: los puntos toman borde, el contorno punteado y el relleno se abren desde el centro, "SOY UN BOTÓN" se escribe letra por letra con el cursor de texto (que después titila), aparecen la caja de selección con la flecha, el balde con la barrita amarilla y la sombra que baja; al final entran las 5 etiquetas (Curvas, Tipografía, Efectos, Íconos, Color).
    3. El balde se vuelca y el amarillo se derrama sobre el botón desde ahí; se va la guía (puntos, contorno, caja, etiquetas), el texto y la flecha pasan a negro, la sombra pasa a ser la sombra paralela del botón (0 8 5, 25 %) y el botón hace un saltito.
  - Archivos del Figma en `assets/km7/`: `circulo.svg`, `circulo-borde.svg`, `linea-cursor.svg`, `flecha-gris.svg`, `flecha.svg`, `balde.svg`.
  - Ahora es link en el mapa (punto 7), en el menú (Átomos y De átomos a botones) y en la "siguiente parada" del KM 6. Footer: anterior KM 6, siguiente KM 8 · Animaciones (sin link, no existe todavía).
  - Mobile: la escena se arma en un cuadro de 1080 × 940 achicado a 0,4 (`ACHICAR_MOVIL`), con el botón al medio, Curvas y Color arriba, y Tipografía, Efectos e Íconos abajo, con letra más grande; se mantiene fija con `fijarMovil`.
  - **Huecos del Figma (avisar al equipo):** el hero del Figma trae parada anterior/siguiente adentro (componente "Hero · Sección"); no se puso para que quede igual a los otros KM de la página. El link "Botones ↗" del hero todavía no está porque esa sección no se construyó.
- 12/11/2026 · Mateo · **Transición de la portada a la Home, más prolija.** Antes el contorno del logo (con los piquitos donde se juntan las letras) quedaba grueso y encima de los puntos del mapa mientras aparecían, y se veía doble con la línea del mapa. Ahora el contorno pasa a crema y se afina a 4 px, se funde con la línea del mapa (uno desaparece mientras el otro aparece) y los puntos de los KM salen recién cuando el contorno ya se fue, así quedan siempre encima de la línea (`salirDePortada`).
- 12/11/2026 · Mateo · **KM 2 · Guía de estilo: "Así sí / Así no" animado.** Al scrollear, cada fila de las tablas entra de a una: primero aparece el "Así sí", que asiente (baja y rebota), y después el "Así no", que niega (se sacude de costado). La línea punteada de cada fila se dibuja de izquierda a derecha, y el encabezado hace lo mismo con sus íconos. Si entran varias filas juntas, van una después de la otra, y se rearman al salir del todo de la pantalla (`iniciarGuia`). Igual en el celular.
- 12/11/2026 · Mateo · **KM 3 · Construcción: lo de arriba sigue a la vista durante el swipe.** Antes solo la tira quedaba fija y centrada, y el título "Construcción" con los tres logos se iban. Ahora el título, el texto, los tres logos sobre la misma altura de x y la tira quedan fijos juntos arriba de la pantalla mientras la tira se desliza (todo va dentro de `.pin-sticky`; la imagen de los tres logos tiene la clase `.constr-logos`). En pantallas bajas sube lo justo para que la tira se vea entera. En el celular arranca debajo del botón del menú.
- 12/11/2026 · Mateo · **KM 4 · Dos familias: resaltar la tipografía** (comentario del Figma en las tres pantallas de ejemplo: "si hace hover sobre algo que esté en Sora, lo que está en Reddit Sans pasa a 50 % de opacidad, y lo mismo viceversa"). Con el mouse sobre un texto de cualquiera de las tres pantallas, queda prendido todo lo que usa esa familia (vuelve con un fundido) y lo demás baja al 50 %. Arriba del texto aparece un cartelito con la familia (escrita en esa misma letra), el peso y el tamaño, por ejemplo "Sora SemiBold · 20 px". Cada texto se marca solo, según su fuente real (`iniciarFuentesUI`). Se apaga al sacar el mouse, al arrastrar o al cambiar de pantalla. En el celular se toca el texto, y se apaga tocándolo de nuevo o tocando afuera.
  - Para poder separar las familias, la tarjeta "Abasto Run" dejó de ser una imagen (`ui-grupo.png`) y se armó en HTML con los textos y estilos del Figma (nodo `307:1577`; ícono `assets/km4/ui-users.svg`).
- 12/11/2026 · Mateo · **KM 4 · Títulos Display: laboratorio del sticker** en el espacio de la izquierda (debajo del título, fijo mientras se scrollea). El "Team Peaks" de la pantalla de equipo, en grande (Sora Bold, relleno Negro Spot y contorno blanco crema sobre violeta), con tres controles que explican el texto de la sección: **Contorno** (grosor de 0 a 16 px, arranca en 10), **Puntas** (redondeadas o rectas: con rectas se ven las esquinas filosas) y **Sombra paralela** (prendida o apagada). Abajo una línea explica lo que se está viendo. Al llegar, el contorno "se pega" con un rebote, y cada cambio hace un saltito (`iniciarSticker`). En el celular va arriba del texto, a todo el ancho.
- 12/11/2026 · Mateo · **KM 4 · Laboratorio del sticker, cambios:** se puede escribir cualquier título (hasta 24 letras; si no entra en la tarjeta, se achica solo), se puede cambiar el fondo con los 5 colores de SPOT! (amarillo, naranja, rosa, violeta y azul; arranca en violeta) y se sacó la opción de puntas rectas (el contorno siempre va con puntas redondeadas). Quedan: Texto, Fondo, Contorno y Sombra paralela.
- 12/11/2026 · Mateo · **KM 4 · Pantallas de la app con esquinas de iPhone.** Las tres capturas de "Títulos Display" (inicio, registrar y equipo) llevan las esquinas redondeadas como un iPhone (42 px, ≈14 % del ancho; 19 px en el celular) y una sombra suave.
- 12/11/2026 · Mateo · **KM 5 · Filtros: comparador deslizable** (buen y mal uso de los porcentajes del negro). Las dos hojas de filtros van una encima de la otra con una barra en el medio: a la izquierda de la barra se ve la 1 (bien) y a la derecha la 2 (mal). La barra se arrastra con el mouse o el dedo (o con las flechas del teclado). Al llegar se mueve sola de punta a punta para mostrar las dos, y se repite al volver a pasar. A los costados están el número, el veredicto ("Así sí" / "Así no") y la explicación del texto de arriba; el lado que menos se ve se apaga (`iniciarComparador`). En el celular, el comparador va a todo el ancho y los dos textos abajo. Antes se probó una animación de "la mirada" que recorría cada pantalla, pero no gustó.- 12/11/2026 · Mateo · **KM 7 · Design System, segunda parte: Botones, Grillas, Íconos y Nomenclatura** (Figma `517:10185`, debajo de "De átomos a botones"). Textos y medidas del Figma (`iniciarKM7Secciones`).
  - **Botones** (`563:11469`): muestrario con Botones, Botones de ícono y Tags seleccionables, con las notas de cada variante; el selector "Fondo" (crema, azul, verde, violeta, rosa) cambia el fondo del muestrario. A la derecha, el celular (mockup del Figma) con la **hoja de filtros de la app armada en HTML** (Figma "Hoja filtros", `1:4734`) que funciona como la app, según el comentario del Figma ("solo entre el formulario sin seleccionar y seleccionado"): los tags se seleccionan (Disciplina y Momento en amarillo, Nivel en azul y de a uno), los días en naranja, "Ver equipos" se habilita cuando hay algo elegido y "Limpiar" vuelve todo a cero. Un círculo naranja late sobre RUNNING hasta que se toca algo. **Entrada:** los botones del muestrario aparecen de a uno con rebote y el celular sube girando.
  - **Grillas** (`646:2647`): grilla desktop de 12 columnas y mobile de 4, con las cotas (20 px, 120 px, 20 px, 16 px). Al llegar, las columnas crecen desde abajo una por una y después aparecen las cotas. En el celular, las dos grillas una abajo de la otra y sin cotas.
  - **Íconos** (`682:10952`): en el cuadrante redondeado del Figma, seis íconos de la app (Figma "Sistema de íconos", `77:159`, solo outline, en `assets/km7/iconos/`). Idea tomada de la iconografía de Dropbox: al pasar el mouse por un ícono (en el celular, tocándolo) se mezcla con otro con un giro y aparece un punto de color de SPOT! detrás. Al llegar se mezclan solos una vez, de izquierda a derecha. En el celular se ven tres.
  - **Nomenclatura** (`586:2648`): la fórmula se arma pieza por pieza (los puntos y guiones bajos aparecen con un rebote, en naranja); las seis reglas entran como los principios del KM 10; las filas de "Códigos de cada parte" se dibujan de a una. Pasando el mouse (o tocando) una parte de la fórmula se marca su fila en los códigos, y al revés. En "Así se ve una carpeta ordenada", los archivos llegan desordenados y se acomodan en su carpeta.
  - Hero: se sumaron los links "Botones ↗" y "Nomenclatura ↗"; en el menú, las cuatro secciones nuevas.
  - **Huecos del Figma:** el texto de Botones dice "Pensando l la interfaz"; se corrigió a "Pensando la interfaz". La imagen de referencia de Dropbox (`682:10950`) no va en la página.
  - Archivos nuevos: `assets/km7/ds/` (íconos de los botones y de la hoja de filtros, `mockup-iphone.png`, `pantalla-filtros.png` para la parte de arriba de la pantalla) y `assets/km7/iconos/` (41 íconos).
- 12/11/2026 · Mateo · **KM 7 · ajustes de Íconos y Nomenclatura.**
  - Íconos: el cambio de ícono es más rápido y sutil (sale en 0,12 s y entra en 0,3 s, con un giro chico). Ahora se mezcla al entrar con el mouse **y mientras el mouse se mueve encima** (cada 0,3 s), así alcanza con pasarlo por arriba. La pista dice "Pasá el mouse por los íconos para mezclarlos" (en el celular, "Tocá los íconos para mezclarlos"), con el ícono de flechas girando; hasta que alguien la usa, cada 2,5 s un ícono hace un saltito para invitar.
  - El unicornio que se vio sobre un ícono no es de la página (no está en el código ni en los archivos): viene de algo del navegador de quien lo vio, por ejemplo una extensión.
  - Nomenclatura: "Así se ve una carpeta ordenada" va dentro del contorno de una carpeta de macOS (pestaña arriba a la izquierda, borde Negro Spot), con las tres carpetas adentro. Entra con un leve crecimiento antes de que se acomoden los archivos.
- 12/11/2026 · Mateo · **Página de post.** (`<article id="post">`, link `#post`). Se abre desde el logo de post. de la Home (arriba a la derecha, crece con un brillo verde al pasar el mouse) y desde el botón "Conocé más sobre POST" del KM 1. No está en el menú ni en el mapa porque no es un KM. Footer: anterior KM 1 · Acerca de SPOT!, siguiente "Volver al inicio".
  - **Contenido**: todo sale de la página POST del Figma (`1:18433`, el informe del TP3), sin textos inventados. Los títulos son los de las láminas.
  - **Estilo gráfico de post.**, distinto al de SPOT!: fondo Negro Spot, verde #49B867, crema y violeta de acento. Las bajadas van en **JetBrains Mono** (se sumó a Google Fonts) y el texto en Reddit Sans. Solo se usan misceláneas de post.: puntos verdes, aros crema y verdes, y estrellas de 7 y 12 puntas.
  - **Secciones y animaciones:**
    - **Hero**: el logo de post. con el círculo de respiración de dos capas detrás (inhala 4 s, exhala 6 s, con "Inhalá / Exhalá"). Las misceláneas flotan y se corren al paso del mouse o del dedo, como dice el Figma ("si se acercan a la silueta de la persona, puede empujarlas al moverse").
    - **01 Introducción**: el bloque amarillo de Spot con la pregunta "¿qué pasa cuando ya cruzamos esa primer línea de meta?", que se arma palabra por palabra. Una línea de meta a cuadros cruza la pantalla y abajo, en negro, "Así es como nació post.".
    - **02 ¿De dónde viene la idea?**: TP1 (eje, tema, subtema), los tres motivos, 4 fotos tipo polaroid que caen y se enderezan con el mouse, y las encuestas con contadores.
    - **03 ¿Qué es Post?**: ficha (medidas, 16 personas, 20 minutos, cuándo) y los 3 videos de las pantallas de afuera (los mismos del KM 10).
    - **04 Dinámica del interior**: **juego de la pose**, una silueta de puntos que se mueve con el mouse o el dedo (arriba y abajo los brazos, a los costados se inclina). Hay que acercarla a la pose en contorno verde. Tiene el círculo de precisión con el %, la barra de tiempo que se vacía en 10 s y las pastillas (¡Genial!, ¡Seguí así!, ¡WOW!, #zentotal). Son 3 poses; sin nadie, se mueve sola. Al lado está la referencia de Hole in the Wall.
    - **05 Recorrido en pantalla**: los 8 pasos. La pantalla queda fija y muestra cada paso al scrollear: bienvenida, círculo que se completa, calibración, respiración, barra y pastilla, tres pantallas que se unen y cierre. Las capturas son las del Figma.
    - **06 Dedicatorias**: "¿A quién le dedicás esta carrera?", las 4 capturas de TikTok y la **fachada en vivo**. Las notas del Figma (nacho, cami, sofi, el grupo del parque, profe caro) aparecen y desaparecen. Se puede escribir una dedicatoria propia ("para:" y mensaje), que entra a la pantalla. La nota se agranda según el largo del mensaje (S, M, L, XL), con el borde rasgado arriba y el color al 80 %.
    - **07 Contexto**: render junto al Obelisco (se acerca al scrollear) y las dos carreras (Gran Fondo Argentina y Hoka Run · Club de Corredores) con sus sponsors.
    - **08 Prototipo**: TouchDesigner + MediaPipe, las 4 iteraciones (silueta, tiempo, respiración, recorrido), cada una con su mini animación, y el círculo de precisión que cuenta hasta 86 % con las pastillas.
  - Las animaciones de entrada se repiten al volver a pasar (`entradaRepetida`). Los videos se cargan al acercarse y solo corren mientras se ven (`iniciarPost`).
  - **Archivos**: imágenes del Figma en `assets/post/`, pasadas a JPG y achicadas con `sips`; misceláneas `assets/post/fig-*.svg` y `nota-borde-1.svg`.
  - **Mobile**: una columna. El juego de la pose se usa arrastrando el dedo. La pantalla del recorrido queda arriba con JS, porque `sticky` no anda dentro del transform. Las fotos van en 2 columnas.
  - **No se hizo todavía**: accesibilidad, reflexiones finales ni UI kit completo del Figma. La página de STOP va después.
- 13/11/2026 · Mateo · **Sincronización con el Figma (3.ª ronda) y corrección de errores de tipeo.**
  - **El recorrido pasa a tener 8 KM** (Figma: Home con 8 puntos y menú sin Animaciones ni Íconos). El mapa tiene los 8 puntos en sus lugares y colores nuevos (amarillo, naranja, rosa, violeta, azul, amarillo, naranja, rosa), y el menú tiene 8 ítems.
  - **Arquigrafía es ahora el KM 8**: hero rosa, tag "KM 8", parada anterior KM 7 · Design System. La "siguiente parada" del KM 7 y la "parada anterior" del KM 1 llevan a Arquigrafía (KM8). El id interno sigue siendo `km10` (y la carpeta `assets/km10/`) para no romper enlaces.
  - **Hueco del Figma (avisar):** el hero de Arquigrafía dice "Parada anterior: Animaciones · KM8"; se puso Design System · KM7 porque Animaciones ya no existe. El KM 1 del Figma todavía dice "KM10" en la parada anterior; se usó KM8.
  - **KM 8 · Wayfinding:** se sacó la grilla de 6 principios, porque en el Figma quedó afuera de la lámina. Queda solo el texto.
  - **KM 8 · Arquigrafía:**
    - Títulos nuevos: "Nuestra identidad sobre lo existente" e "Hitos inflables y a gran escala".
    - La parada y los hitos miden 1113 px, como en el Figma. Las dos fotos de los hitos van una debajo de la otra.
    - Debajo de los videos de post. se sumó el render de la cabina por fuera (`assets/km10/fachada-render.jpg`).
    - En el Figma ese bloque repite el título y el texto de "Nuestra identidad sobre lo existente" (copia por error). Se dejó "La pantalla también es arquitectura" con su texto.
  - **KM 8 · textos que cambiaron:**
    - Orientativas: "El directorio de cada piso. Número, nombre y la lista…".
    - 1,50–1,70 m: se sumó "Para tener en cuenta, la altura promedio de una persona es de 1,75 m". En el Figma dice "1,75 cm"; se corrigió.
  - **KM 7 · De átomos a botones:** frase nueva debajo del botón amarillo (Figma `682:10959`), "Todo comienza con pequeños elementos. Estos pequeños elementos van a formar cosas más grandes.". Aparece cuando el botón termina de armarse.
  - **KM 1 · fotos de STOP** (Figma Group 111): mazo de 3 fotos igual al de post., que se tira y se reordena. Son la largada con el portal, la terraza del after y las cápsulas (`assets/km1/foto-stop-1..3.jpg`). La zona de submarcas creció a 4863 px y las paradas bajaron. `iniciarMazo` arma los dos mazos (`armarMazo`). En el celular cada mazo va en su caja, debajo de su botón.
  - **Arreglo:** la foto de adelante del mazo usa la clase `frente`, que chocaba con `.frente` del KM 8 y la ponía en `position: relative`. Ahora `.submarcas-zona .foto-rot` fuerza `position: absolute`.
  - **Errores de tipeo corregidos en la página** (antes estaban copiados tal cual del Figma; en el Figma siguen):
    - Ortografía: hehcas → hechas, aun → aún, fromado → formado, areglarlo → arreglarlo, princincipiantes → principiantes, sumbarcas → submarcas, Despúes → Después, subtitulos → subtítulos, especifica → específica, iconos → íconos.
    - Tildes en preguntas indirectas: "como dialogan" → "cómo dialogan", "simbolizar como" → "simbolizar cómo".
    - Gramática: "esta la única excepción" → "esta es la única excepción", "usar colocar" → "colocar", "Los variantes" → "Las variantes", "se tratan de" → "se trata de" (dos veces).
    - Puntuación: "caritaa. utilizamos" → "caritas. Utilizamos", "entrada. guiamos" → "entrada: guiamos", "principales. el hogar" → "principales: el hogar".
    - Números con la unidad separada, como pide la Guía de estilo: 18km → 18 km, 4km → 4 km.
    - En la página de post.: "primer línea de meta" → "primera línea de meta", serian → serían, kilometro → kilómetro.
- 13/11/2026 · Mateo · **Se borró la página de post.** (pedido del equipo). Se sacaron:
  - el `<article id="post">`, sus estilos (también los de mobile) y `iniciarPost`;
  - `post` de `KMS`;
  - JetBrains Mono de Google Fonts;
  - la carpeta `assets/post/`.
  - El botón "Conocé más sobre POST" del KM 1 vuelve a llevar a la Home, como en el prototipo. La entrada del 12/11 sobre esa página queda solo como historial.
- 13/11/2026 · Mateo · **Home sin los logos de post. y STOP** arriba a la derecha (pedido del equipo). Se borró el bloque `.submarcas` de la Home, con sus estilos y su animación de entrada.
- 13/11/2026 · Mateo · **Menú y mapa con 8 paradas**, revisados contra el Figma. Los números del menú ahora tienen el color de su punto en el mapa, como en el Figma: amarillo, naranja, rosa, violeta, azul, amarillo, naranja y rosa. Antes eran todos amarillos. Los toman de `PUNTOS_MAPA`.
- 13/11/2026 · Equipo · **Dos conflictos de Git resueltos** (Pull con cambios de Mateo). Se combinaron las dos versiones:
  - De Mateo: fotos de STOP con sus archivos (`foto-stop-1..3.jpg`), render de la fachada de post. (`fachada-render.jpg`), "1,75 m", paradas del KM 1 en 4415 px, página de post. borrada (el botón "Conocé más sobre POST" vuelve a la Home), menú y mapa con 8 paradas y números de colores.
  - Nuestro: misceláneas de STOP alrededor de sus fotos (`data-mazo`, `DECOS.stopfotos`), textos de Arquigrafía iguales al Figma ("Post", Orientativas sin "¿Qué hay acá?"), hitos y parada a la derecha a 1113 px, headers con flechas y menú que lleva al header (ver abajo).
  - Se borraron las fotos repetidas `assets/km1/foto-stop-centro.jpg` y `assets/km10/fachada-post.jpg`.
  - **Regla:** antes de trabajar, siempre *Fetch* y *Pull*, y al terminar *Commit* + *Push* enseguida. Si GitHub Desktop avisa de conflictos, resolverlos antes de seguir editando.
- 13/11/2026 · Equipo · **Headers con flechas a la parada anterior y la siguiente** (componente "Hero · Sección" del Figma, `512:2066`), en todos los KM (`armarNavHero`).
  - Abajo a la izquierda: flecha + "Parada anterior", nombre y KM. Abajo a la derecha: "Siguiente parada", nombre, KM y flecha (Reddit Sans SemiBold 16, Sora SemiBold 24, Negro 80, línea de 2 px, chip con borde de 1 px; flechas en `assets/hero/`). Usan las mismas paradas que el footer de cada KM (el KM 1, las de sus paradas). Al pasar el mouse, el círculo se oscurece un poco y la flecha se corre 4 px.
  - Como pide el componente, el índice y las flechas comparten la línea de base (178 px del borde de abajo) y la bajada queda 50 px arriba del índice: la bajada y el índice se ubican solos según cuántos links tenga cada KM. Entre links hay 18 px, como en el Figma.
  - Las misceláneas del hero esquivan las flechas.
  - Celular: una fila abajo del hero con solo la flecha y el KM de cada lado (los nombres no entran).
- 13/11/2026 · Equipo · **Menú: tocar el nombre de una sección lleva a su header** (antes solo abría o cerraba las subsecciones). Las subsecciones se abren y cierran con la flechita de al lado del nombre o con el número. Si ya estás en esa sección, sube al header.
- 13/11/2026 · Equipo · **Arreglos después del merge:**
  - Las flechas de los headers no se veían porque se había borrado `assets/hero/` (`flecha-izq.svg` y `flecha-der.svg`, exportadas del Figma). Se recuperaron. Ojo: es una carpeta nueva, hay que subirla en el Commit.
  - Las fotos de STOP del KM 1 quedaban abajo de todo, fuera de la zona negra: al combinar quedaron sumados dos veces los 2217 px (`armarMazo`). Ahora se suman una sola vez.
  - Se borraron otra vez las fotos repetidas que volvieron con el merge (`foto-stop-centro.jpg`, `fachada-post.jpg`).
- 13/11/2026 · Equipo · **Ícono del menú invisible al abrir `index.html` con doble clic.** El botón de los KM dibuja el ícono con una máscara CSS (para cambiarle el color según el fondo) y la máscara cargaba `assets/km2/21764.svg`; con `file://` Chrome bloquea las máscaras que vienen de archivos, así que el botón andaba pero no se veía. Ahora el mismo SVG va escrito dentro del CSS (`--bm-icono`, data URI). **Regla:** para `mask` o `mask-image`, usar el SVG escrito en el CSS, nunca `url(assets/...)`.
  - Se exportó la página a Descargas: "Spot - Sistema de diseño (13-11-2026) v2" (`index.html` + `assets/`).
- 13/11/2026 · Equipo · **Favicons y mezclador de íconos vacíos al abrir `index.html` con doble clic.** Leían sus SVG con `fetch`, que Chrome bloquea con `file://` (publicada sí andaba).
  - KM 3 · Favicon: las tres formas (`assets/favicon/f01`, `f05`, `f09`) van escritas en `FAV_BASE` y los cuadros se arman con `favCuadro`. El favicon animado de la pestaña también usa eso (los mismos 12 cuadros de "General").
  - KM 7 · Íconos: los 33 SVG de `ICONOS_DS` van escritos en `ICONOS_SVG` (si falta alguno, prueba con `fetch`).
  - Si se cambia un SVG de esas carpetas, hay que actualizarlo también dentro de `index.html`.
  - Siguen usando `fetch`, pero si falla queda la imagen quieta: los diagramas del KM 3 y los esquemas del KM 8 (con doble clic se ven, sin la animación de dibujarse).
  - **Regla:** nada que tenga que verse puede depender de `fetch`; si hace falta el texto de un SVG, escribirlo en el HTML.
  - Exportado a Descargas: "Spot - Sistema de diseño (13-11-2026) v3".
- 13/11/2026 · Mateo · **KM 1: se sacaron los botones "Conocé más sobre POST" y "Conocé más sobre STOP"** (pedido del equipo). En el celular, cada mazo de fotos va ahora debajo del texto de su marca.
- 13/11/2026 · Mateo · **KM 3 · Colaboraciones: la plantilla ya no se parte en tres** (pedido del equipo, la animación se veía rara).
  - Antes, al cortarla en SPOT! / × / recuadro, las líneas de las guías quedaban cortadas y se separaban.
  - Ahora entra entera, con un fundido suave, y no se mueve con el mouse.
  - Los cuatro lockups de ejemplo siguen armándose como antes (`CORTES_LOCKUP` ya no incluye la plantilla).
