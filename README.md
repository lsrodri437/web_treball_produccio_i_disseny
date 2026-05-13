# Festa Major El Vendrell 2025

## Tema i motivació
L'objectiu d'aquesta pàgina web és centralitzar tota la informació rellevant sobre la Festa Major del Vendrell 2025. La web està dirigida tant als veïns de la vila com als visitants que vulguin conèixer la programació, la història i les tradicions locals. La motivació principal és oferir una eina digital moderna i accessible que faciliti la participació ciutadana i la descoberta del ric patrimoni cultural i festiu del Vendrell, amb un especial èmfasi en el bestiari de foc i la cartografia dels esdeveniments.

## Dades
Per a la realització d'aquest projecte s'han utilitzat les següents fonts i recursos:
* **Continguts textuals:** Informació històrica i descriptiva sobre els actes i les entitats de foc del Vendrell.
* **Multimèdia:** Fotografies, un vídeo promocional en format MP4, la banda sonora original en MP3...
* **Eines de desenvolupament:** HTML5 i CSS3 per a l'estructura i el disseny.
* **Recursos externs:** Integració de Google Calendar per a l'agenda d'actes i Google Forms per al formulari de voluntariat.
* **Cartografia:** Dades geogràfiques processades i exportades amb QGIS.

## Estructura de la web
La web es divideix en set seccions principals:
* **Inici (`index.html`):** Benvinguda visual amb una secció Hero, reproductor del videoclip de la banda sonora i vídeo promocional.
* **Informació (`informacio.html`):** Recorregut per la història de la festa utilitzant un efecte visual de Parallax.
* **Multimèdia (`multimedia.html`):** Galeria fotogràfica organitzada per carpetes (dies de la festa) amb un disseny de collage "Masonry" i visualització "Lightbox".
* **Programa (`programa.html`):** Calendari interactiu dels esdeveniments i opció de descàrrega del programa oficial en PDF.
* **Grups de Foc (`grups_de_foc.html`):** Fitxes informatives i visuals de les 10 bèsties de foc que formen el seguici.
* **Contacte (`contacte.html`):** Secció amb dades de contacte oficials i formulari d'inscripció per a voluntaris.
* **Mapes (`mapes.html`):** Visor cartogràfic amb selectors per consultar rutes i punts d'interès.

## Disseny web responsiu
El disseny s'ha treballat mitjançant **CSS Grid** i **Flexbox** per garantir que la web sigui utilitzable en qualsevol dispositiu:
* **Adaptabilitat:** S'han definit *media queries* per a mòbil, tauleta i escriptori.
* **Menú Hamburguesa:** En dispositius mòbils, la navegació es comprimeix en un menú desplegable tipus "hamburguesa" per optimitzar l'espai.
* **Imatges:** S'utilitza la propietat `object-fit: cover` i amplades percentuals per assegurar que les fotografies no es deformin i s'ajustin a les graelles.

## Cartografia
Els mapes s'han integrat mitjançant l'eina **QGIS2Web**. S'ha realitzat una tasca prèvia de digitalització i simbolització de les rutes de la rua, els escenaris de concerts i els punts d'encesa del correfoc. Aquests mapes s'insereixen a la web a través de `iframes` dins d'un visor estilitzat que permet a l'usuari alternar entre diferents capes d'informació geogràfica de forma intuïtiva.

## Dificultats/millores
Una de les principals dificultats ha estat la implementació de funcionalitats interactives (com els filtres de la galeria o el lightbox) sense recórrer a JavaScript, la qual cosa ha requerit una arquitectura CSS molt "complexa", que ha sigut possible gràcies al suport de Gemini. Com a millores futures, moltes, principalment corregir el problema de la galeria d'imatges, la qual no troba centrada les seves tres columnes; a més la d'afegir una targeta per a cada bèstia de foc en fer clic en el seu quadrat, la qual mostraria més informació d'aquesta...
