# Kort presentation av examinationsuppgiften som skapats i FIGMA 


[Länk till min figma ]( https://www.figma.com/file/jzRU6FsIG21tfoEjZMmPDy/NINA-NORBY-GRAFIK-FEND23?type=design&node-id=118%3A479&mode=design&t=txVQvHZ0DhOLUfPl-1)


## WEBBPLATSEN

Hemsidan följer en enkel struktur baserad på bootstraps column-klasser (12-kolumnsystem) , men man kan självklart frångå bootstrap om man hellre vill skapa sin hemsida från grunden. Trots att den kan utvecklas med "mobil first" principen, presenteras prototypen endast i desktop-format.
Webbsidan är responsiv och kan därför visa vyn 

Produktkortet kan skapas från grunden med  HTML och CSS, men den nuvarande versionen liknar Bootstraps produktkort ["card" ](https://getbootstrap.com/docs/5.0/components/card/). En separat knapp behöver  läggas till för att skapa funktionen där man kan ta bort artiklar från kundkorgen.

Färgerna avviker från Bootstraps signaturfärger och är specificerade i Figma-filen. Dessa färger återfinns både på designbordet och som variabler, angivna i HSL-färger. 
Observera att det finns överflödiga färger från Color System-applikationen, vilkt  inte används men har ej tagits bort. För klarhet rekommenderas att se vilka variabler som satts i Figma-filen vid uppskapande av webbsidoprototypen. 



## FILFORMAT - BILDER 


**Logga**: PNG används för loggan på grund av stöd för genomskinlighet och förlustfri komprimering. Som jag har uppfattat det som är den särskilt lämpligt för logotyper.

**Produktbild + bakgrundsbild**: 
Bilderna sparas som AVIF och JPG. AVIF prioriteras, men JPG används som backup på grund av webbläsarkompatibilitet. Övervägningar kring AVIFs krav på enhetskraft /prestanda görs, men förväntas inte märkbart påverka användarupplevelsen. JPG kan aktiveras utan betydande påverkan på användarupplevelsen hoppas jag på , trots att bildprestanda inte är primärt fokus på webbplatsen då det är kläder som säljs.



[Länk till bootstarp om man ej kopierar nedanstående link och script ](https://getbootstrap.com/docs/5.3/getting-started/download/#npm)

CDN för bootsrap om man önskar att anväda detta, men det går såklart att ladda ner bootstrap.
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">

```

```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
```
