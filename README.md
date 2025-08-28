# Bootcamp FMW2025 - 🧱 Grundläggande HTML-formulär

Inför veckans bootcamp ska vi lära oss bygga formulär i HTML. Formulär är nåt vädigt grundläggande som du finner på så gott som varenda sida på webben. Man kan forma och utforska dem i all oändlighet men vi börjar med en enkel introduktion.

## 📋 Formuläret ska innehålla

Formulärets layout är valfri. Ni får använda fieldsets, styling etc. så länge elementen listade nedan är med.

- En text input med valfritt namn
- En email input med valfritt namn
- En range input som heter "amount"
- En output som heter "result" vars ursprungliga värde är "amount"s min-värde
- En submit-knapp

## 💻 Förväntat resultat

- När man trycker på submit-knappen ska ett objekt med tre keys och tre värden loggas i konsollen i DevTools.
- När man ändrar värdet på range inputen ska det nya värdet renderas i gränssnittet.

## 👨‍💻 Gör alla ändringar i `index.html`

Det finns redan en html-fil med `<form>`-taggar där ni lägger all inputs och andra element.

```html
<!DOCTYPE html>
<html lang="sv">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Jättefint formulär</title>
    <script defer src="main.js"></script>
  </head>
  <body>
    <form id="basicForm">// alla element läggs här inom</form>
  </body>
</html>
```

## 🎁 Bonusuppgifter

Fält där användaren anger text eller siffror

- Ge dem placeholders
- Gör dem required
- Förifyll dem med värden
- Skapa en select input med minst 3 options
