# Kort presentation av examinationsuppgiften som skapats i FIGMA 


(Länk https://www.figma.com/file/jzRU6FsIG21tfoEjZMmPDy/NINA-NORBY-GRAFIK-FEND23?type=design&node-id=0%3A1&mode=design&t=kjAseqeafdKA99jr-1)


# WEBBPLATSEN:

Hemsidan följer en enkel struktur baserad på bootstraps column-klasser (12-kolumnsystem) , men man kan självklart frångå bootstrap om man hellre vill skapa sin hemsida från grunden. Trots att den kan utvecklas med "mobil first" principen, presenteras prototypen endast i desktop-format.

Produktkortet kan skapas från grunden med vanlig HTML och CSS, men den nuvarande versionen liknar Bootstrap's produktkort (https://getbootstrap.com/docs/5.0/components/card/). En separat knapp behöver dock läggas till för att ta bort artiklar från kundkorgen.

Färgerna avviker från Bootstraps signaturfärger och är specificerade i Figma-filen. Dessa färger återfinns både på designbordet och som variabler, angivna i HSL-färger. 
Observera att det finns överflödiga färger från ett tidigare försök med Color System-applikationen, vilka inte används men har ej tagits bort. För klarhet rekommenderas att referera till Figma-filen för exakta färgspecifikationer.




# FILFORMAT - BILDER :


Logga: PNG används för loggan på grund av stöd för genomskinlighet och förlustfri komprimering. Som jag har uppfattat det som är den särskilt lämpligt för logotyper.

Produktbild + bakgrundsbild: 
Bilderna sparas som AVIF och JPG. AVIF prioriteras, men JPG används som backup på grund av webbläsarkompatibilitet. Övervägningar kring AVIFs krav på enhetskraft /prestanda görs, men förväntas inte märkbart påverka användarupplevelsen. JPG kan aktiveras utan betydande påverkan på användarupplevelsen hoppas jag på , trots att bildprestanda inte är primärt fokus på webbplatsen då det är kläder som säljs.









CDN för bootsrap om man önskar att anväda detta, självklart kan man ju installera botstrap(npm)
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
