# Weekopdracht-Opdracht-frontend-Requests

<h4>1:
Doel: Zet een employee in de database</h2>

<p>maak een formulier in HTML waar je een naam en salaris meegeeft
en via javascript een post naar de backend maakt.</p>
<p>Zet vervolgens 2+ employees in de database via het formulier </p>

<h4>2:
Doel:
Zien van alle employees in de database. Wat is hun id, naam en salaris</h4>

<p>Maak een div met een id</p>
<p>Maak een functie die met een GET alle employees uit de database haalt</p>

<p>Loop door de employees uit de response heen en toon de gegevens op de website
(dit is nog niet behandelt in de les)</p>
<p>Je maakt een var employeestring aan in javascript en laat deze leeg. </p>
<p>Via de loop voeg je voor elke employee een stukje aan deze string. </p>
<p>De gehele string stuur je door naar de innerhtml van  je id in de html.</p>

Zorg dat de functie wordt aangeroepen bij het laden van de pagina.

<h4>3:
Doel:
Verander het salaris van 1 medewerker aan de hand van zijn id</h4>

<p>Maak een formulier in HTML waar je de id en het nieuwe salaris van de medewerker kan invoeren</p>
<p>Verstuur de gegevens via een Put methode</p>
<p>Zorg ervoor dat de naam niet wordt veranderd</p>

<h4>4:
Doel:
Verwijder een Employee</h4>

<p>Maak een formulier in HTML waar je een id kan invoeren</p>
<p>Roep een DELETE endpoint aan en verwijder de medewerker in de database.</p>

<h4>5:
Doel:
Maak een telefoon aan en koppel employee aan een telefoon.</h4>

<p>Maak in de backend een telefoon met een klasse (id en telefoonnummer), service, repository en een endpoint.</p>
<p>Maak een one to one relatie</p>
<p>Maak een formulier in de front end voor het aanmaken van een telefoon</p>
<p>Maak een formulier voor het koppelen van de employee aan de telefoon</p>
<p>Verander de get all employees zodat ook het telefoonnummer wordt getoond bij alle employees</p>
