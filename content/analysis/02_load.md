---
Title: Load
Description: This is our Loading page.
Template: analysis-content

---

Uppgiften handlar om att analysera ett antal webbplatser genom att testa och mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag valde att utvärdera <a href="https://www.rituals.com/sv-se/home" target="_blank">Rituals</a> webbplats eftersom jag letade efter en hemsida med mycket innehåll, som information, bilder, videor och animationer. Det kändes som en bra sida att testa för att se hur snabbt den laddar och hur den presterar.

För att få en kontrast till en kommersiell webbplats valde jag att titta på en myndighetssida, nämligen <a href="https://www.csn.se/" target="_blank">CSN</a>. Jag valde den eftersom den förväntas vara enkel, tydligt uppbyggd och ha bra laddningstider, vilket passar bra för en hemsida med fokus på att förmedla information.

Slutligen valde jag att granska <a href="https://www.svt.se/" target="_blank">SVT Nyheter</a>, eftersom den är en kombination av en kommersiell och en informationssida. Den innehåller mycket material, som bilder och videor, men behöver samtidigt vara snabb och lättillgänglig för att kunna leverera nyheter och information till alla på ett effektivt sätt.


Metod
-----------------------

Efter att jag hade valt webbplatserna undersökte jag tre sidor från varje webbplats. Jag använde <a href="https://pagespeed.web.dev/" target="_blank">PageSpeed Insights</a> för att testa varje sida och noterade resultaten i ett Google Kalkylark. PSI bedömde prestanda, tillgänglighet, sökmotoroptimering (SEO) och hur väl "bästa praxis" hade följts vid utformningen för både mobild och dator. Samtidigt använde jag webbläsarens inspektörverktyg, specifikt fliken "Network", för att analysera laddningstider, antalet laddade resurser och sidans totala storlek. Laddningstiderna mättes genom att ta genomsnittet från tre försök per sida.

<iframe class="chart" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRQfcTWkCQFcWb7IHbNLUTrpf2s0pVS9NMaW0QZ2NOt4rJ1Q0hL_XPgJXWN-r42TyWVDN4eNAGMStyp/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

Resultat
-----------------------

### Rituals

<img src="../image/Rituals.JPG" alt="museumNL" class="analysis-mobile">

Rituals är ett företag som säljer skönhetsprodukter, hemartiklar och dofter inspirerade av asiatiska traditioner. Deras hemsida används som en plattform för att sälja produkter och förmedla företagets fokus på välbefinnande.

Hemsidan har låg prestanda enligt tester från PageSpeed Insights, särskilt på mobila enheter. Startsidan har en laddningstid på cirka 899 millisekunder, men den låga prestandapoängen (21 på mobil och 26 på desktop) indikerar att det finns problem som påverkar användarupplevelsen. Sidan för skönhetsprodukter är långsammare med en genomsnittlig laddningstid på 4,46 sekunder och mycket låga poäng (5 på mobil och 23 på desktop). Kollektionssidan för Alchemy presterar något bättre med laddningstider på 860 millisekunder och poäng på 32 (mobil) respektive 36 (desktop). Den största orsaken till de låga poängen är stora filstorlekar och mängden resurser som laddas.

För att förbättra hemsidans prestanda kan Rituals använda lösningar som att komprimera bilder, minska storleken på JavaScript och CSS-filer. Trots prestandaproblemen är hemsidan attraktiv och visar varumärkets identitet samt att den erbjuda en inspirerande kundupplevelse.


### CSN

<img src="../image/CSN.JPG" alt="beyondaero" class="analysis-mobile">

CSN hemsida är en plattform för studenter och andra användare som behöver hantera studiestöd. Den är uppbyggd med fokus på tydlighet och funktion för att göra det möjligt för besökare att hitta information och använda tjänster som att ansöka om studiemedel eller betala tillbaka lån.

Generellt sett fungerar hemsidan mycket bra på desktop. Startsidan, som är den mest besökta, har en hög prestandapoäng på 83 och snabba laddningstider, med ett genomsnitt på 583 millisekunder. På mobil är prestandan något sämre (52 poäng), men sidan laddar fortfarande relativt snabbt. Betalningssidan har dock lägre prestanda, särskilt på mobil där poängen bara är 27 och laddningstiden längre. Det beror troligtvis på större filstorlekar och fler resurser som behöver laddas in. Beslutssidan presterar bäst av alla tre sidor och är särskilt effektiv på desktop med en hög prestandapoäng på 96 och snabb laddningstid på 631 millisekunder. På mobil är resultatet något lägre men fortfarande bättre än betalningssidan.

Skillnaderna i prestanda mellan sidorna beror främst på faktorer som filstorlek och mängden resurser. Startsidan är relativt liten med 5,2 MB och 54 resurser, vilket bidrar till dess snabbhet. Betalningssidan är betydligt större, med en total storlek på 12 MB och 160 resurser, vilket påverkar laddningstiden negativt. Beslutssidan är minst och effektivast, med en filstorlek på 3,6 MB och bara 50 resurser, vilket gör den snabbast att ladda.

För att förbättra användarupplevelsen, särskilt på mobila enheter, kan CSN optimera hemsidan ytterligare. Att minska filstorlekar, optimera bilder och minska antalet resurser som laddas skulle kunna förbättra prestandan.

### SVT

<img src="../image/SVT.JPG" alt="filmstaden" class="analysis-mobile">

SVT Nyheter är en plattform för att dela dagliga utrikes och inrikes nyheter inom tex ekonomi, kultur, sport och underhållning med en bred publik. Den är byggd för att vara enkel att använda och ger snabb åtkomst till aktuella program och information.

Resultaten från tester visar att hemsidan fungerar bra, särskilt på datorer. Startsidan har en prestandapoäng på 80 på desktop och laddar snabbt med en genomsnittlig tid på 328 millisekunder och en filstorlek på 2 MB. Kultursidan presterar ännu bättre med en desktop-poäng på 89 och en mycket snabb laddningstid på 241 millisekunder. På mobil är prestandan något lägre, med poäng mellan 38 och 54, vilket visar att hemsidan kan optimeras mer för mobila enheter. Sport-sidan är lite långsammare än de andra med en laddningstid på 496 millisekunder och en filstorlek på 2,1 MB, vilket påverkar prestandan negativt på mobiler.

Sammanfattningsvis är SVT Nyheter snabb och användarvänlig, särskilt för datoranvändare. För att förbättra upplevelsen på mobila enheter kan SVT arbeta med att minska filstorlekar och optimera resursanvändningen. Trots dessa mindre förbättringsområden är hemsidan bra uppbyggd och visar innehållet smidigt och effektivt till sina användare.

Analys
-----------------------

Efter att ha analyserat de tre webbplatserna Rituals, CSN och SVT kan man se tydliga skillnader i hur snabbt de laddar och hur bra de presterar. Rituals har den sämsta prestandan, särskilt på mobiler, vilket beror på stora filer och många resurser som måste laddas. CSN fungerar bättre, särskilt på datorer, där sidorna laddar snabbt. På mobiler presterar CSN sämre, särskilt för sidor med mycket innehåll som betalningssidan. SVT är den webbplats som fungerar bäst, med korta laddningstider och hög prestanda, speciellt på datorer. Mobilprestandan kan dock förbättras något, särskilt för sport-sidan.

De vanligaste sakerna som behöver förbättras handlar om att minska stora filer och antalet resurser som laddas på sidorna. Rituals och CSN kan exempelvis komprimera bilder, minska storleken på CSS-filer och animationer och använda tekniker som lazy loading (Google Developers) för att förbättra snabbheten.

Baserat på resultaten rangordnar jag webbplatserna så här:

1. SVT: Den fungerar snabbast och mest effektivt, särskilt på datorer.
2. CSN: Mycket bra på datorer, men den kan förbättras för mobiler.
3. Rituals: Långsam laddning och låg prestanda, särskilt på mobiler.

Gränsvärde och snabbhet
Jag tycker att en laddningstid på under 1 sekund känns snabb, medan över 3 sekunder känns långsam. CSN och SVT klarar detta på flera sidor, särskilt på datorer. Rituals däremot, särskilt deras skönhetssida, laddar mycket långsamt och tar över 4 sekunder.

Referenser
-----------------------

Google Developers. (n.d.). Why speed matters. Retrieved December 5, 2024, from https://web.dev/learn/performance/why-speed-matters/

Övrigt
-----------------------

© Nikki Krause