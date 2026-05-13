Aquest projecte consisteix en la creació d'una plataforma web informativa completa dedicada a la **Festa Major del Vendrell 2025**. L'objectiu principal és oferir als ciutadans i visitants un espai centralitzat on consultar el programa d'actes, la història de la vila, les entitats participants i mapes interactius de la celebració.

## 🚀 Sobre el Projecte

La web ha estat dissenyada seguint principis de **disseny responsive** i **bones pràctiques de desenvolupament**, assegurant una experiència d'usuari fluida tant en escriptoris com en dispositius mòbils. El lloc web consta de 7 pàgines amb layouts diferenciats i estructurats mitjançant un sistema de graella propi.

### Característiques Principals:
- **Disseny Adaptatiu (Responsive):** 3 punts de ruptura (breakpoints) per a mòbils, tauletes i escriptoris.
- **Efecte Parallax:** Presentació de la història amb fons fixos que es revelen en fer scroll.
- **Galeria "Masonry" i Lightbox:** Collage d'imatges organitzat per dies (carpetes) amb ampliació de fotos sense necessitat de JavaScript.
- **Mapes Interactius:** Visor cartogràfic professional que integra mapes elaborats amb **QGIS2Web**.
- **Multimèdia:** Reproductor de la banda sonora oficial (MP3) i vídeo promocional de la festa.
- **Integració d'Eines:** Google Calendar per al programa d'actes i Google Forms per al voluntariat.

## 🛠️ Tecnologies Utilitzades

Per aquest projecte s'ha prioritzat el desenvolupament "vanilla" per demostrar el domini de les tecnologies base, **evitant l'ús de frameworks CSS** com Bootstrap o W3.CSS:

- **HTML5:** Estructura semàntica del contingut.
- **CSS3:** - **Grid View:** Layouts complexos i organitzats.
  - **Flexbox:** Alineació d'elements i sistema de "Sticky Footer".
  - **Media Queries:** Adaptabilitat total segons la mida de pantalla.
  - **CSS Hacks (Checkbox/Target):** Per a funcionalitats interactives (tabs, lightbox, selector de mapes) sense JS.
- **QGIS2Web:** Per a la generació de la cartografia interactiva.
- **Markdown:** Per a la documentació del projecte.

## 📂 Estructura del Projecte

El repositori segueix una organització neta de fitxers:

```text
├── index.html           # Pàgina principal
├── informacio.html      # Història amb efecte Parallax
├── multimedia.html      # Galeria de fotos (Collage i Lightbox)
├── programa.html        # Programa d'actes i descàrrega de PDF
├── grups_de_foc.html    # Fitxes de les 10 bèsties de foc
├── contacte.html        # Dades de contacte i formulari de voluntariat
├── mapes.html           # Visor de mapa interactiu
├── css/
│   └── styles.css       # Full d'estils principal (únic i documentat)
├── images/              # Carpeta d'imatges i iconografia
├── documents/           # Programa oficial en PDF
├── musica/              # Arxius MP3 de la banda sonora
├── videos/              # Videos utilitzats en la pàgina web
├── res/                 # Archius generats a partir de QGIS
└── maps/                # Exportacions de QGIS2Web
