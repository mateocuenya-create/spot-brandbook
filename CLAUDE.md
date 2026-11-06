# TP5 · Brandbook interactivo (Spot · Post · Stop)

> Este archivo es la memoria compartida del equipo. Claude Code lo lee al abrir la carpeta.
> **Regla:** cada vez que se tome una decisión nueva, anotala acá (sección 10, "Registro de decisiones") antes de hacer Commit + Push.

**Entrega: martes 10/11/2026, 18:30.** Presentación oral el mismo día en clase.
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
| Brand guidelines TP5 | `4:9125` | **Diseño imaginado de la home de esta página** (ver sección 4) | 0 |
| Escala tipográfica | `9:2603` | Escala tipográfica (ver sección 7) | 0 |

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

## 4. Home del TP5 (Figma, página "Brand guidelines TP5", `4:9125`)

Lo más importante para el equipo: **las animaciones de esta página**. Se reconstruyen a mano en HTML/CSS/JS.

Idea: el brandbook es **una carrera**. Los capítulos son "kilómetros" (KM) y la home es un mapa de recorrido con puntos.

### Pantallas
- `4:9456` **Slide 1 · Portada** (1920×1080): fondo amarillo, logo SPOT! centrado.
- `4:9521` **Slide 2 · Home/mapa** (1920×1080): foto de ciclistas desenfocada de fondo, logo SPOT! arriba, botones "post." y "STOP", contorno de recorrido tipo mapa con 6 puntos de colores (`4:9524`–`4:9529`), ícono de lista (menú) arriba a la izquierda.
- `4:9537` **Slide 3 · Menú lateral** (overlay 525×1080, oscuro): cerrar, "Volver al Inicio", índice: Acerca de Spot (Brand Spirit, Post, Stop…), Manual de voz y tono, Logotipos (construcción, variantes de color, espacios seguros, usos correctos e incorrectos, tamaños, ejemplos), Tipografías, Colores (usos correctos e incorrectos), Elementos gráficos (misceláneas, fotografías…).
- `4:9550` **Slide 4 · KM 1 "Acerca de SPOT!"** (1920×**2343**, más alta): amarillo, tag "KM 1", título con logo, tagline **"Una marca en constante movimiento"**, links internos (Brand Spirit ↗, Misión y visión ↗, Submarcas ↗), flecha hacia abajo; debajo, bloque crema con "Brand Spirit" + texto (hoy lorem ipsum) y un tag.
- `4:9575` **Slide 5 · KM 2 "Manual de Voz y Tono"** (1920×1080): naranja, tag "KM 2", pregunta **"¿Cómo le hablamos a nuestro público?"**, mismos links internos (placeholder), flecha.

### Interacciones del prototipo (datos exactos leídos del Figma)
1. **Portada → Home:** automático a los **2,4 s**, Smart Animate 0,3 s ease-out (probable morph del logo).
2. **Contorno del mapa** ("Component 2" `4:9523`, variantes `4:9659` Vector → `4:9656` Component 1): hover → cambia de forma, Smart Animate 0,3 s ease-out.
3. **Puntos del mapa** (set `4:9591`, Default `4:9598` → Hover `4:9592`): hover, Smart Animate 0,1 s ease-out.
4. **Click en punto:** `4:9524` → KM 1; `4:9525` → KM 2. Move In desde la izquierda, 0,3 s ease-out. Los otros 4 puntos todavía sin destino.
5. **KM 1 → KM 2:** click en KM 1, Move In desde la izquierda, 0,3 s ease-out.
6. **Menú:** ícono lista (en Home, KM 1 y KM 2) → overlay entra desde la derecha, 0,2 s ease-out; "close" lo cierra.
7. **"Volver al Inicio"** (`4:9547`) → Home, Move Out hacia la izquierda, 0,3 s ease-out.

### Componentes web (sección `4:9590`)
"Puntos mapa" (Default/Hover), "Logo SPOT" (Default y Variant2, `4:9618`), "Component 2" (contorno del mapa, `4:9655`), botón "SPOT" (`4:9616`), un tag, un ícono de mapa.

Fidelidad: **exacta** en disparadores, destinos, duraciones y easing; **aproximada** en los morph de formas (recrear con SVG mirando los dos estados de cada componente).

---

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

- Todo en **un único archivo .html autocontenido** (el equipo no trabaja en simultáneo, así que no hace falta dividirlo).
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
8. Primer paso de construcción: home (portada, mapa, menú y KM 1–2) para ver las animaciones antes de seguir.

---

## 9. Preferencias del equipo
- Ir de a poco y confirmar antes de avanzar.
- Lo más importante: **las animaciones** y que la experiencia sea tipo Dropbox.
- Números redondeados, sin decimales.
- Ser directo y no sobrecargar con referencias.
- Plazo justo: priorizar una versión funcional y mejorar después.

---

## 10. Registro de decisiones
(Anotar acá cada decisión nueva: fecha · quién · qué se decidió.)

- 06/11/2026 · Mateo · Se crea el repo y este CLAUDE.md. Un solo archivo .html. Confirmado del Figma: demora de la portada 2,4 s; links en Teams (no Drive) según la consigna.
