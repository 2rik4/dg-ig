<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Hausarztpraxis erfasst Arzneimittelallergien ihrer Patientinnen und Patienten. Die Daten werden von einer Notfallstation gelesen und müssen dort zuverlässig ausgewertet werden können, damit bei einer Behandlung keine unverträglichen Medikamente verabreicht werden.

### Scope

Dieses IG deckt ausschliesslich Allergien gegen Arzneimittel ab (AllergyIntolerance, Parent: CH Core). Andere Allergietypen, etwa gegen Lebensmittel oder Umweltstoffe, sind bewusst nicht Teil dieses IG.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Profil für Arzneimittelallergien mit Pflichtangaben zu klinischem Status, Code und Kritikalität sowie der Invariante `dg-allergy-1` (eine bestätigte Allergie braucht mindestens eine Reaktion).
* [Penicillin-Allergie von Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten Penicillin-Allergie mit hoher Kritikalität und Urtikaria als Reaktion.


<!-- TODO_Name ist der Name hinter "Instance:" in beispiele.fsh,
     z. B. AllergyIntolerance-PenicillinAllergieAnna.html -->

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Thurika Rajkumar

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
