---
Title: Load
Description: This is my load page.
Template: areas
---

Laddningstid och användbarhet i webbdesign
=======================
Laddningstid och användbarhet är centrala för en webbsidas användarupplevelse och funktionalitet. I denna analysuppgift har tre webbplatser valts ut för att analysera deras laddningstider, samt hur de kan förbättras med avseende laddningstid och användbarhet.

Urval
-----------------------
För att mäta webbplatsers laddningstid och identifiera förbättringsområden för laddningstid och användbarhet valdes trewebbplatser ut. Urvalet begränsades till personliga webbplatser, det vill säga webbplatser som representerar en enskild individ, för att möjliggöra att återanvända webbplatserna för fortsatta analysuppgifter.

Sökningar genomfördes på sökmotorn Google, där sökfraser som "art director portfolio", "författare hemsida" och "personlig blogg" användes. Urvalet baserades på de översta resultaten, där tre webbplatser av olika karaktär valdes ut.

De valda webbplatserna är:
1. En finsk grafisk designers portfolio: https://www.lottanieminen.com.
2. En svensk författares hemsida: https://camillalackberg.se.
3. En svensk blogg: https://underbaraclaras.se.

Metod
-----------------------
För att bedöma användarupplevelsen på webbsidorna användes Google Pagespeed Insights. Detta verktyg analyserar webbsidans webbadress och genererar en rapport som innehåller poäng för prestanda, tillgänglighet, bästa metoder och SEO, både för mobila enheter och datorer. Rapporten innehåller även rekommendationer för hur respektive område kan förbättras.

Information om webbsidornas laddningstider samlades in genom att öppna dem i webbläsaren Firefox och använda verktyget "Inspektera". Från fliken "Nätverk" i utvecklarverktyget hämtades data om sidans laddningstid, antal laddade resurser och den totala laddningstiden. Mätningar genomfördes tre gånger för varje webbsida, och ett genomsnitt av värdena beräknades för att ge ett mer tillförlitligt resultat.

Resultat
-----------------------
### Lotta Nieminen
![Lotta Nieminens portfolio](%base_url%/image/lotta.jpg  "Lotta Nieminens portfolio") {.image}

Den finska grafiska designern Lotta Nieminens hemsida fick 71 poäng för prestanda och 75 poäng för tillgänglighet i Google Pagespeed Insights för dator, medan den fick 55 poäng för prestanda och 73 poäng för tillgänglighet för mobil.

För att förbättra prestandan föreslog rapporten att införa en effektiv cachepolicy för statiska resurser samt att säkerställa att all text förblir synlig medan webbteckensnitten läses in.

För att förbättra tillgängligheten rekommenderades bland annat följande åtgärder: använda beskrivande namn på länkar, öka kontrasten mellan bakgrunds- och förgrundsfärg, säkerställa att tryckområden är tillräckligt stora med tillräckliga avstånd, samt att rubrikelement ordnas hierarkiskt i fallande ordning. Vidare föreslogs att alla bildelement förses med alt-attribut och att knappar har namn som är åtkomliga för hjälpmedel.

Portfoliohemsidan hade en genomsnittlig laddningstid på 8,12 sekunder, baserat på tre mätningar. Genomsnittligt antal laddade resurser uppgick till 11,67, och den genomsnittliga sidstorleken var 211,20 kilobyte, varav 217,35 kilobyte data överfördes.

<div class="embed-calc"><iframe title="Mätvärden laddnibgstid för Lotta Nieminens portfolio" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSeIxyAgVf39mbflDpfHHJI-CPtpwKECgD5jCgDre-MrZy4SL7O5j03qwklyBG2NWMxcfYZv87nWqJj/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe></div>

### Camilla Läckberg
![Camilla Läckbergs hemsida](%base_url%/image/camilla.jpg  "Camilla Läckbergs hemsida") {.image}

Den svenska författaren Camilla Läckbergs hemsida fick 87 poäng för prestanda och 82 poäng för tillgänglighet i Google PageSpeed Insights för dator, medan den fick 63 poäng för prestanda och 90 poäng för tillgänglighet för mobil.

För att förbättra prestandan föreslog rapporten att bredd och höjd ska anges för bildelement, att en effektiv cachepolicy för statiska resurser ska införas samt att all text förblir synlig medan webbteckensnitten läses in. Vidare rekommenderades att enorm nätverksbelastning undviks, att bilder förladdas för snabbare rendering av innehåll, att bilder kodas mer effektivt och att oanvänt JavaScript reduceras.

För att förbättra tillgängligheten föreslogs att kontrasten mellan bakgrunds- och förgrundsfärger ska vara tillräcklig, att tryckområden görs tillräckligt stora och har goda avstånd samt att attribut används korrekt i förhållande till elementens roller. Dessutom påpekades att länkar bör ha tydliga och igenkännliga namn.

Hemsidan hade en genomsnittlig laddningstid på 3,92 sekunder, baserat på tre mätningar. Totalt laddades 23 resurser, och den genomsnittliga sidstorleken uppgick till 24,42 megabyte, varav 23,94 megabyte data överfördes.

<div class="embed-calc"><iframe title="Mätvärden laddnibgstid för Camilla Läckbergs hemsida" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTYCs56a7qBb2cieO0kW2z9AS42Upxm-m_4huGpEY2iGS5CQivG3re9wGdgbclboskWbiJHFMA2NHsn/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe></div>

### Underbara Clara
![Underbara Claras blogg](%base_url%/image/clara.jpg "Underbara Claras blogg") {.image}

Den personliga bloggen Underbara Clara fick 82 poäng för prestanda och 81 poäng för tillgänglighet för datorversionen enligt Google PageSpeed Insights. För mobilversionen uppnåddes 56 poäng för prestanda och 77 poäng för tillgänglighet.

För att förbättra prestandan föreslog rapporten att implementera en effektiv cachepolicy för statiska resurser, säkerställa att text förblir synlig medan webbteckensnitt laddas, och använda passiva lyssnare för att förbättra scrollningsprestanda. Dessutom rekommenderades att använda bilder med rätt storlek, undvika att skicka äldre JavaScript till moderna webbläsare, samt att ange bredd och höjd för bildelement. Rapporten betonade också vikten av att skjuta upp inläsningen av bilder som inte syns på skärmen, minska nätverksbelastningen, förladda bilder för att optimera innehållets första rendering, minifiera JavaScript och ta bort oanvänt JavaScript. Vidare påpekades att ett onödigt stort DOM-träd bör undvikas.

För att förbättra tillgängligheten föreslogs att alla bildelement ska ha alt-attribut och att länkar bör ha igenkännliga namn. Det rekommenderades också att länkar som används för att hoppa över innehåll ska vara fokuserbara och att kontrasten mellan bakgrundsfärger och förgrundsfärger ska vara tillräcklig. Vidare föreslogs att länkar får olika färger för att bli enklare att särskilja, att tryckytor görs tillräckligt stora och har tillräckliga avstånd, samt att rubrikelement organiseras hierarkiskt i fallande ordning.

Enligt mätningarna hade Underbara Claras blogg en genomsnittlig laddningstid på 1,72 sekunder, baserat på tre tester. Totalt laddades i genomsnitt 22,67 resurser, och den totala sidstorleken var 628,41 kilobyte, varav 572,79 kilobyte överfördes.

<div class="embed-calc"><iframe title="Mätvärden laddnibgstid för Underbara Claras blogg" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vStW0kJTWWIWxPCsdwdVhrDCsRpguzszc9-T29-xvMvDnkeXQOkO2R4Ict0jk5nxrMC9gAMi57BrEd0/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe></div>

Analys
-----------------------
Laddningstid och prestanda är viktiga faktorer för en positiv användarupplevelse på webben. För att säkerställa både funktionalitet och nöjda användare är det viktigt att dessa delar optimeras för att bli så bra som möjligt. I denna analys utvärderas tre webbplatser baserat på deras laddningstider och användarupplevelse.

### Förbättringsförslag för prestanda
Samtliga analyserade webbplatser har liknande förbättringsområden. För alla webbsidor rekomenderas att använda en cachelagringspolicy för statiska resurser, för att öka prestandan. Detta innebär att sidor kan laddas snabbare vid återbesök genom att konfigurera Cache-Control-headern i HTTP-svar (Chrome for Developers, 2019).

Dessutom föreslås att använda CSS-egenskapen font-display för att säkerställa att texten är synlig medan anpassade webbtypsnitt laddas. Genom font-display kan exempelvis systemtypsnitt användas temporärt, vilket förbättrar användarupplevelsen (Chrome for Developers, 2024).

För två av webbplatserna föreslås även:
- Reducering av storleken på nätverksbelastningen till under 1600 kB.
- Förinläsning av bilder för snabbare rendering av innehåll.
- Eliminering av oanvänt JavaScript för att minska sidans totala vikt.

### Förbättringsförslag för tillgänglighet
För att förbättra tillgängligheten identifierades tre generella områden:
- Igenkännliga länknamn: Skärmläsare gynnas av tydliga, unika och fokuserbara länknamn samt alternativa texter för länkade bilder.
- Tillräcklig kontrast: Bristande kontrast mellan text och bakgrund kan göra innehållet svårläst, särskilt för personer med nedsatt syn.
- Användarvänliga tryckområden: Större och mer välplacerade tryckytor underlättar interaktion, särskilt för personer som har svårt att använda små kontroller.

### Jämförelse och rankning
De tre webbplatserna rankas enligt resultaten från analysen:
1. Underbara Claras blogg får högsta betyg tack vare den snabbaste laddningstiden i förhållande till dess resursstorlek, trots låga poäng på mobila enheter enligt PageSpeed Insights.
2. Camilla Läckbergs webbplats visar god prestanda och laddningstider i förhållande till resursanvändning, men dess totala storlek (cirka 100 gånger större än de andra sidorna) utgör en belastning för både användare och miljö.
3. Lotta Nieminens portfolio placeras sist på grund av den högsta laddningstiden, trots liten total sidstorlek. Fler förbättringar behövs i hur innehållet laddas.

### Slutsats
Subjektivt sett har samtliga webbplatser acceptabla laddningstider, även om Lotta Nieminens sida upplevs ligga på gränsen till långsam. En riktlinje kan vara att hålla laddningstiden under 10 sekunder för att bibehålla en god användarupplevelse. Denna analys visar att optimering av både prestanda och tillgänglighet är viktiga delar för en förbättrad användarvänlighet.

Referenser
-----------------------
Chrome for Developers. (2019, Maj 2). <em>Serve static assets with an efficient cache policy.</em> http://bit.ly/4iU9N7C

Chrome for Developers. (2024, April 2). <em>Ensure text remains visible during webfont load.</em> https://bit.ly/3PcCUVT

Övrigt
-----------------------
Av Jenny Karlsson