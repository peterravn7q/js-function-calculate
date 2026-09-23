# JavaScript – Functions Calculate

## Hjemmeopgave

I denne hjemmeopgave arbejder du videre med **JavaScript functions, parameters og function calls**.

Du skal arbejde med to funktioner, der henholdsvis beregner en sum og en forskel mellem to tal.

Du arbejder selvstændigt med projektet og følger kommentarerne i filerne trin for trin.

---

# Fremgangsmåde – sådan kommer du i gang med projektet

I denne hjemmeopgave skal du bruge **GitHub Template-metoden**.

Du skal derfor **ikke downloade projektet som ZIP og ikke bruge Fork**.

Følg denne rækkefølge:

```text
GitHub Template
↓
Dit eget repository på GitHub.com
↓
GitHub Desktop
↓
Visual Studio Code
↓
Arbejd med hjemmeopgaven
↓
Commit
↓
Push
```

> Følg punkterne **ét ad gangen og i den viste rækkefølge**.

---

## 1. Opret dit eget repository på GitHub.com

Åbn det udleverede **template-repository** på GitHub.com.

Du skal være logget ind på din egen GitHub-konto.

Klik på:

**Use this template**

Vælg derefter:

**Create a new repository**

Vælg din egen GitHub-konto som ejer, og brug det repository-navn, som din underviser har angivet.

Klik derefter på:

**Create repository**

Vent et øjeblik, mens GitHub opretter dit nye repository.

### Kontrollér, at du er i dit eget repository

Når repositoryet er oprettet, skal du kontrollere navnet øverst på siden.

Det skal være **dit eget GitHub-brugernavn**, der står foran repositoryets navn.

Det kan fx se sådan ud:

```text
dit-brugernavn/js-functions-calculate
```

> **Stop her og kontrollér dette, før du går videre.**

---

## 2. Hent dit repository ned på din computer

Nu ligger projektet på **GitHub.com**, men du skal også have det ned på din egen computer.

Åbn **GitHub Desktop**.

Vælg:

**File → Clone repository...**

Vælg fanebladet **GitHub.com**, og find det repository, du netop har oprettet.

Hvis repositoryet ikke vises, kan du i stedet vælge fanebladet **URL** og indsætte adressen til dit repository fra GitHub.com.

### Vælg, hvor projektet skal gemmes

I feltet **Local path** vælger du, hvor projektet skal ligge på din computer.

> **Local path** betyder den mappe på din computer, hvor projektets filer bliver gemt.

Klik derefter på:

**Clone**

Vent, mens GitHub Desktop henter projektet ned på din computer.

---

## 3. Åbn projektet i Visual Studio Code

Når projektet er klonet, vælg:

**Open in Visual Studio Code**

Du skal arbejde direkte i den projektmappe, som GitHub Desktop har klonet.

Kontrollér, at projektet har denne struktur:

```text
js-functions-calculate/
│
├── index.html
├── js/
│   └── script.js
└── README.md
```

---

# Hjemmeopgaven

Du skal arbejde med disse filer:

- `index.html`
- `js/script.js`

Læs kommentarerne i koden grundigt, inden du begynder at skrive din løsning.

---

## 4. Forbind JavaScript-filen med HTML-filen

Åbn:

```text
index.html
```

I filen finder du denne kommentar:

```html
<!-- Skriv scriptet, der linker til js/script.js, herunder -->
```

Din første opgave er at forbinde JavaScript-filen med HTML-dokumentet.

JavaScript-filen ligger i mappen:

```text
js/
```

og hedder:

```text
script.js
```

> **Vær opmærksom på filstien:** `script.js` ligger ikke i samme mappe som `index.html`, men i undermappen `js`.

Skriv selv det korrekte `<script>`-element på det angivne sted.

Gem derefter filen.

---

## 5. Åbn `js/script.js`

Start med at skrive:

```js
"use strict";
```

I filen finder du allerede funktionen:

```js
beregnSum(number1, number2)
```

Funktionen har to parametre:

- `number1`
- `number2`

Din opgave er at færdiggøre funktionen, så den:

1. beregner summen af de to tal
2. udskriver resultatet i browserens **Console**

Brug kommentaren i `script.js` som vejledning.

---

## 6. Skriv funktionen `beregnDifference()`

Under funktionen `beregnSum()` finder du en kommentar, der beskriver den næste del af opgaven.

Du skal selv skrive en ny funktion med navnet:

```js
beregnDifference(number1, number2)
```

Funktionen skal:

1. tage imod to parametre: `number1` og `number2`
2. beregne forskellen mellem de to tal
3. udskrive resultatet i browserens **Console**

> Brug strukturen fra `beregnSum()` som inspiration, men skriv selv funktionen.

---

## 7. Kald begge funktioner

Når begge funktioner er skrevet, skal du kalde dem nederst i `script.js`.

Brug **to selvvalgte tal**, så du kan kontrollere, om funktionerne virker.

Du skal altså lave et funktionskald til:

```text
beregnSum()
```

og et funktionskald til:

```text
beregnDifference()
```

> Husk, at de værdier, du skriver i funktionskaldet, bliver sendt ind i funktionens parametre.

---

## 8. Kontrollér resultatet i browseren

Åbn `index.html` med **Live Server**.

Åbn derefter browserens Developer Tools og gå til:

```text
Inspect → Console
```

Kontrollér, at begge funktioner giver det forventede resultat.

Hvis noget ikke virker:

1. Læs eventuelle fejlmeddelelser i Console.
2. Kontrollér syntaksen.
3. Kontrollér parenteser `{ }` og `( )`.
4. Kontrollér, at funktionernes navne er skrevet korrekt.
5. Kontrollér, at du sender to værdier med i hvert funktionskald.
6. Gem filerne og test igen.

---

## 9. Arbejd progressivt med commits

Du skal ikke vente med at committe, til hele hjemmeopgaven er færdig.

Lav commits løbende, når du har afsluttet en tydelig del af arbejdet.

Du kan eksempelvis lave commits efter:

```text
Forbundet JavaScript med index.html
```

```text
Tilføjet use strict
```

```text
Færdiggjort beregnSum-funktionen
```

```text
Tilføjet beregnDifference-funktionen
```

```text
Testet begge funktioner
```

Skriv selv korte og meningsfulde commit-beskeder, der beskriver, hvad du har ændret.

> Formålet er, at din Git-historik viser, hvordan du har arbejdet med hjemmeopgaven trin for trin.

---

## 10. Push til GitHub.com

Når du har lavet et commit i GitHub Desktop, skal du huske at klikke på:

**Push origin**

På den måde bliver dine ændringer sendt fra din computer til dit repository på GitHub.com.

Gå gerne ind på GitHub.com bagefter og kontrollér, at dine seneste commits kan ses.

---

# Når hjemmeopgaven er færdig

Kontrollér følgende:

- [ ] Jeg har oprettet mit eget repository med **Use this template**
- [ ] Jeg arbejder i mit eget repository
- [ ] Jeg har klonet projektet med GitHub Desktop
- [ ] Projektet er åbnet i Visual Studio Code
- [ ] `js/script.js` er forbundet korrekt med `index.html`
- [ ] Jeg har skrevet `"use strict";`
- [ ] Jeg har færdiggjort funktionen `beregnSum()`
- [ ] Jeg har skrevet funktionen `beregnDifference()`
- [ ] Begge funktioner har parametrene `number1` og `number2`
- [ ] Jeg har kaldt begge funktioner med selvvalgte tal
- [ ] Jeg har testet koden i browserens Console
- [ ] Jeg har lavet løbende commits
- [ ] Jeg har pushet mine commits til GitHub.com

> **Husk:** Formålet er både at træne **JavaScript functions, parameters og function calls** og at øve workflowet mellem **GitHub.com → GitHub Desktop → Visual Studio Code → Commit → Push**.
