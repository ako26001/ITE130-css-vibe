# ITE130 - css, bootstrap och vibe coding
Under veckan har vi i kursen ITE130 blivit introducerade till css, cascading style sheets, bootstrap och vibe coding. Jag tänkte därför visa en del av vad jag har lärt mig. 

## Css - Cascading style sheets
Kortfattat kan man säga att det betyder att senast pålagda mall gäller. Det fungerar på samma sätt som det gör när du målar en vägg. Den senast målade färgen på väggen är den som kommer synas.

### Syftet
Att påverka browser default style. Dvs se till att lägga på lager av style för att webbsidan ska få en egen stil och inte ska visas i browswerns default style.

### Tre metoder för css
* **Inline style** - innebär att man lägger till style på raden, i ```<body>```, för det som ska ha den stilen, likt exemplet nedan. 

```
<body>
 <p style="color: red; font-size: 18px;">This is a paragraph.</p>
</body>
```
* **Embedded style** - innebär att man i ```<head>``` lägger till style och beskriver stilen man vill ha på olika element. Se exempel nedan.
```
<head>
  <style>
    h1{color:pink}
    p{color: dark-green}
  </style>
</head>
```
* **Linked style** - innebär att man i ```<head>``` länkar till ett css-dokument, alltså ett stylesheet som beskriver den exakta stilen. Se exempel nedan.
```
<head>
  <link rel=stylesheet href: https://exempel.css>
</head>
```

## Bootstrap 









## Vibe Coding
Att använda sig av AI för att skriva kod kallas Vibe coding. Alltså ber man AI att till exempel skapa en ruta med text och bild i. AI tar då av redan skriven kod som någon annan har gjort eller kombinerar olika befintliga koder för att uppnå det du bett den göra. 


### Fördelar:
* Är snabbt och effektivt
* Man behöver inte ha speciellt mycket kunskap om kodning själv

### Nackdelar:
* Blir inte alltid det resultat man önskar
* Ibland kan man själv behöva gå in i koden och redigera

### Tre metoder för Vibe Coding
1. Förutseende - Här skriver du själv koden men AI ger förslag på vad du kan komma att vilja skriva här näst baserat på statistik. Detta sker då inline.
2. Interaktiv - Går ut på att man steg för steg arbetar med AI:n för att skapa projektet. Oftast ger man AI:n ett uppdrag och den skriver koden som du sedan går in i och redigerar. 
3. Autopilot - Här ger du AI ramar att arbeta inom och sedan låter du den skapa projektet utifrån det. 

