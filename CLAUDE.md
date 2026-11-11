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
