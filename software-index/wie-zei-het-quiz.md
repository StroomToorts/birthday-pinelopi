---
id: birthday-pinelopi/wie-zei-het-quiz
naam: Quiz "wie zei dit?" met citaten, twee antwoordknoppen, score, voortgangsbalk en eindoordeel
soort: software
bestanden: [index.html]
afgeleid_van:
---
## Wat ze doet
Een kleine quiz in de browser: per vraag verschijnt een citaat met een korte uitleg, en de speler kiest wie van twee personen het zei. Na het antwoord kleurt de juiste knop groen, een fout gekozen knop rood, en verschijnt een knop naar de volgende vraag; bovenaan staan het vraagnummer, de score en een voortgangsbalk. Op het einde volgt een uitslag met emoji en boodschap volgens de score, en een knop om opnieuw te beginnen. De vragen staan als een lijst gegevens (citaat, antwoord, uitleg) bovenaan het script, dus nieuwe inhoud vraagt geen codewerk. Gewone HTML, CSS en JavaScript, geen pakketten of diensten. Het bewaart geen scores, schudt de vragen niet en ondersteunt alleen vaste antwoordnamen, geen meerkeuze per vraag.
## Varianten
## Inbouwen
Kopieer uit `index.html` de `#quiz-section`-HTML, de CSS van `#quiz-section` tot en met `.quiz-btn.dimmed` (plus `.progress-bar`, `.progress-fill`, `.next-btn` en `.plates-btn` voor de opnieuw-knop) en de JavaScript onder `// ─── QUIZ ───`. Vervang de lijst `quizQuestions` door je eigen citaten en de twee namen in `renderQuestion()` door je eigen keuzes; die namen moeten exact gelijk zijn aan het veld `answer`. Pas de drempels en teksten in `showQuizResult()` aan, en de Nederlandse knopteksten als je pagina een andere taal heeft.
