---
id: birthday-pinelopi/welkomstscherm-met-muziek
naam: Welkomstscherm met binnenknop dat achtergrondmuziek start, ook op een gsm die autoplay blokkeert
soort: software
bestanden: [index.html]
afgeleid_van:
---
## Wat ze doet
Een schermvullende laag die bij het openen van een webpagina over de inhoud ligt, met vallende sterretjes, een titel die na een korte pauze inzoomt en een knop die daarna verschijnt. De pagina probeert meteen muziek af te spelen; lukt dat niet (gsm-browsers blokkeren autoplay), dan start de muziek bij de eerste tik of klik op de laag. Bij de binnenknop vervaagt de laag en dooft de muziek in anderhalve seconde uit, waarna de laag helemaal verdwijnt. Handig voor elke cadeau-, uitnodigings- of presentatiepagina die met geluid wil openen. Het is gewone HTML, CSS en JavaScript zonder pakketten of diensten; je hebt alleen een mp3-bestand nodig. Het onthoudt niets tussen bezoeken en heeft geen dempknop.
## Varianten
## Inbouwen
Kopieer uit `index.html` het `<audio id="party-audio">`-element en het `#overlay`-blok, de CSS onder `/* ─── OVERLAY ─── */` (inclusief `.star-particle` en `@keyframes starFall`) en de JavaScript onder `// ─── OVERLAY ───` tot en met de functie `enterParty()`. Pas de teksten in `#overlay-text`, de kleuren en het muziekbestand (`party.mp3`) aan. De knop roept `enterParty()` aan via `onclick`; de rest van de pagina hangt er niet van af.
