---
Title: Colors
---


Analys av färgval på webplatser
=======================

Denna analys har som mål att undersöka färgkompositionen på tre olika webplatser. De grundläggande frågorna att besvara är:
Vilka färger används och vad har de för relation med varandra?
Speglar färgerna websidans innehåll och budskap?

Urval
-----------------------
Webplats 1:
https://www.pole-emploi.fr/accueil/ (Härefter kallad "Pôle Emploi").

Webplats 2:
https://www.lepotagerdesante.com/ (Härefter kallad "Le Potager de Santé").

Webplats 3:
https://www.dn.se/ (Härefter kallad "Dagens Nyheter").

De tre webplatserna är valda från artikelförfattarens personliga webhistorik.
De enda kriteria som ställdes var att välja webplatser med någorlunda skilda funktioner och målgrupper.
Frågor som lämnats obesvarade men skulle kunna tänkas ha en påverkan på analysen är bland annat:
Har artikelförfattaren en medveten eller omedveten dragning till webplatser med särskilda färger?
Har webplatserna nåtts via riktad reklam och i så fall hur påverkas utbudet av webplatser av artikelförfattarens kön, ålder, intressen, jobb och annat som ligger till grund för annonsörers riktade reklam?
Hur påverkar den använda skärmens färgåtergivning uppfattningen av färgerna med det mänskliga ögat?
Lider artikelförfattaren av en omedveten synpåverkan?

Metod
-----------------------

Webläsartillägget ColorZilla användes för att extrahera färgerna från alla tre webplatser. På Pôle Emploi fungerade ColorZillas verktyg "webpage color analyser" som automatiskt extraherar färgerna på webplatsen. På de andra två webplatserna fungerade det verktyget inte och färgerna extraherades därför manuelt med color picker-verktyget. Detta kan ha påverkat urvalet av färger som valts ut från webplatserna.
För att få en bättre överblick av de återkommande färgerna på webplatserna så användes funktionen att inte ladda bilder växelvis i webläseren.
Färgerna sattes sen in i Adobe Color Wheel (https://color.adobe.com/create/color-wheel) för att analysera deras relation med varandra.
Färgernas betydelse analyserades med artikelförfattarens begränsade kunskap i modern och traditionell färgteori och slutsatserna är därför högst personliga.

Resultat
-----------------------

Gemensamt för de tre webplatserna är att alla använde sig av vitt-#FFFFFF och svart-#000000 med flertalet gråtoner där emellan. De har utelämnats ur resultaten nedan för att fokusera mer på grundfärgerna RGB eller YMC beroende på vilken lära man utgår ifrån.
</br>
###Pôle Emploi:
Detta är Frankrikes motsvarighet till arbetsförmedlingen. Deras målgrupp är framförallt arbetslösa, arbetsgivare och personer som vill vidareutbilda sig eller byta yrke.
De mest använda färgerna är blått, vitt och rött. Men inslag av grönt och lila är också återkommande.

Typsnitten använda på sidan: </br>
All text är sans serif med typsnitten: Roboto,Helvetica,Arial,sans-serif
På några få ställen kunde jag hitta Helvetica Neue istället för Roboto som förstahandsval. Några texter är i bildformat och har ett rundare typsnitt men fortfarande sans-serif.

| *Screenshot av webplatsen* |
|:--:|
| ![Pôle Emploi website](../assets/img/poleemploi.png) |

<table style="border-spacing: 4px; border-collapse: separate">
    <caption><em>De mest använda färgerna.</em></caption>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #934C94">
        <td style="height: 50px; width: 50px; background-color: #1B2B66">
        <td style="height: 50px; width: 50px; background-color: #223D5B">
        <td style="height: 50px; width: 50px; background-color: #1C3F55">
        <td style="height: 50px; width: 50px; background-color: #289DBD">
        <td style="height: 50px; width: 50px; background-color: #4EB6AF">
        <td style="height: 50px; width: 50px; background-color: #599D78">
        <td style="height: 50px; width: 50px; background-color: #F5C83C">
        <td style="height: 50px; width: 50px; background-color: #E8A53D">
        <td style="height: 50px; width: 50px; background-color: #FF5950">
    </tr>
</table>

| *Färgschema* |
|:--:|
| ![Pôle Emploi color scheme](../assets/img/poleemploi_scheme.png) |

Webplatsens färgschema tycks inte passa in perfekt i något precist schema. Men med lite små justeringar kan det beskrivas som ett split complementary-schema, ett double split complementary-schema eller ett triad-schema. Nyanserna av grönt och rött är varandras motsatser på färgghjulet även om den röda är mer mättad än den gröna. Detta bidrar till argumentationen för att det är ett complementary-schema. Den blå färgen däremot har ingen complementary-färg om man inte räknar in vitt men ligger 120 grader från den röda färgen och skulle därför kunna passa in på ett triad-schema med en altererad grön och lila som accent-färg.

I överlag tycker jag att typsnitt och färgval speglar profilen jag tror de strävar efter, seriöst men inte auktoritärt och avskräckande.
</br>
###Le Potager de Santé:
Detta är en webplats för ett företag som säljer ekologiska frön och erbjuder utbildning i ekologisk odling. Dess målgrupp kan förväntas vara alla som är intresserade av odling eller är oroliga över klimatförändringarna.
Webplatsen går framför allt i gröntoner och orange men tar man de många bilderna i beaktning så är det en färgrann webplats.

Typsnitten använda på sidan:</br>
- Cairo, sans-serif.
- Savoyeplain.

Denna webplats följer inte riktigt riktlinjerna för semantisk html och alla element är i princip div eller span. Jag hittar ett h3 element i footern och h5 används som klass i några span-element. Cairo, sans-serif är använt överallt förutom i menyn och logotypen där det är skrivstils-typsnittet savoyeplain som är angivet utan backuptypsnitt.

| *Screenshot av webplatsen* |
|:--:|
| ![Le potager de santé website](../assets/img/lepotagerdesante.png) |


<table style="border-spacing: 4px; border-collapse: separate">
    <caption><em>De mest använda färgerna.</em></caption>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #528951">
        <td style="height: 50px; width: 50px; background-color: #F0AA4E">
        <td style="height: 50px; width: 50px; background-color: #136244">
        <td style="height: 50px; width: 50px; background-color: #04C4E9">
        <td style="height: 50px; width: 50px; background-color: #7EB536">
        <td style="height: 50px; width: 50px; background-color: #00B04E">
        <td style="height: 50px; width: 50px; background-color: #88B121">
        <td style="height: 50px; width: 50px; background-color: #518C32">
    </tr>
</table>

| *Färgschema* |
|:--:|
| ![Le potager de santé color scheme](../assets/img/lepotagerdesante_scheme.png) |

Färgschemat på Le Potager de Santé passar bra in på beskrivningen av ett analogt schema. Nästan alla färger är en nyans av grönt och orange används som accentfärg. Den blåa färgen används endast i logotypen på webplatsen.

De återkommande gröna färgerna speglar mycket väl deras profil och typsnittet savoyeplein är välkomnande samtidigt som det balanseras helt ok med det mer neutrala Cairo.

</br>
###Dagens Nyheter:
Detta är webplatsen för en av Sveriges största tidningar. Dagens nyheter är oberoende socialdemokratisk så därför kan den förväntade målgruppen vara omvärldsintresserade vuxna eller unga svensktalande med värderingar som ligger på mitten och vänster av den politiska skalan.

Typsnitten använda på sidan är följande:
- h1: PublicoBanner,Times,Georgia,serif
- h2: PublicoText,Georgia,Times New Roman,Times,serif
- p: Georgia,Times New Roman,Times,serif

h3-h6 används inte och alla headers och brödtext i main är av typen serif. Alla länkar och text i footern samt h1 i aside är i olika typer av sans-serif.

| *Screenshot av webplatsen* |
|:--:|
![Dagens Nyheter website](../assets/img/dn.png)

<table style="border-spacing: 4px; border-collapse: separate">
    <caption><em>De mest använda färgerna.</em></caption>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #DA000D">
        <td style="height: 50px; width: 50px; background-color: #60BCA0">
        <td style="height: 50px; width: 50px; background-color: #568BBE">
        <td style="height: 50px; width: 50px; background-color: #F58E04">
        <td style="height: 50px; width: 50px; background-color: #2A7157">
        <td style="height: 50px; width: 50px; background-color: #FFEABE">
    </tr>
</table>

| *Färgschema* |
|:--:|
| ![Dagens Nyheter color scheme](../assets/img/dn_scheme.png)|

Färgschemat på Dagens Nyheter påminner närmast om ett "split complementary"-schema med blå som accentfärg. Nyanserna av orange och rött ligger perfekt till för att beskrivas som split complementary-färger till den mörkare nyansen av grön.

Typsnitten och färgerna på Dagens Nyheter tycker jag passar deras profil som mediabolag med lång historia bakom sig.


Analys
-----------------------

###Pôle Emploi:
Då de officiella franska färgerna är blå, vitt och rött så är det inte så svårt att lista ut varför just dessa färger används på hemsidan. Det är en officiell myndighet och i många (artikelförfattarens personliga uppfattning) franska myndigheter använder sig av dessa färger på deras webplatser.
Det är dock inte de exakta färgerna utan något mindre mättade. En anledning till dett är att de ger ett mindre auktoritärt intryck.
Den gröna färgen på webplatsen är en komplementärfärg till den röda och följer därmed principerna inom färgteori.
Något att notera är att sidorna för arbetssökande går i rött medan sidorna för arbetsgivare går i grönt. Rött skulle kunna knytas till arbetarrörelsen och kan därför vara passande. Grönt kan har en historisk mening av stabilitet och genoristet men också oerfarenhet/naivitet (inexperience) {1, 2} vilket är lite motsägelsefullt.
I överlag utstrålar webplatsen proffesionalitet, seriöshet och byråkrati, vilket måste sägas passa den eftersökta profilen väl.
Orange är använt endast på ett ställe och det är en varning för bedrägeri så det följer idéen om att orange är en varningsfärg.

De officiella färgerna enligt https://www.schemecolor.com/france-flag-colors.php:</br>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #0055A4"></span>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #EF4135"></span>
</br>
Färgerna använda på Pôle Emplois webplats:
</br>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #FF5950"></span>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #1B2B66"></span>

###Le Potager de Santé:
Denna webplatsen är kanske inte så välbyggd och är helt klart rörig ibland men med tanke på att det handlar om en webplats för försäljning av ekologiska frön från ett par franska bohemer så måste man väl säga att den är ganska passande ändå. Typsnittet i skrivstil känns lite förlegat och gör att headern inte riktigt passar in med resten av sidan som ändå känns någorlunda modern. Min gissning är att de inte velat ändra på sin logotyp och ville använda sig av det typsnittet även när sidan byggdes/fräschades upp för att bli mer modern. Det ger inte riktigt ett enhetligt intryck men ger en känsla av mänsklighet och tradition. Utan skrivstilen kanske det skulle blivit lite för sterilt för att passa in i deras profil.
Det är grönt för hela slanten och nyansen av orange som används är en bra accentfärg som också kan tolkas som naturlig en höstfärg. Den blåa färgen som endast finns i deras logga känns malplacerad. </br>
De använda nyanserna av orange och blått:</br>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #FDA004"></span>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #04C4E9"></span>
</br>
Kanske skulle en mer direkt komplementärfärg med mindre grönt i sig fungerat bättre:
</br>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #FDA004"></span>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #6FB4FD"></span></br>
Eller:</br>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #FDA004"></span>
<span style="display: inline-block; height: 50px; width: 50px; background-color: #0055B0"></span>

###Dagens Nyheter:
Dagens Nyheters webplats känns snygg, modern och professionell samtidigt som Serif typsnittet Publicotext och Publicobanner känns traditionellt och anrikt. Med tanke på att det är en av de största tidningarna men samtidigt har nästan 160 på nacken så måste det sägas att det är helt i riktning med deras profil.
Färgen röd speglar deras länk till arbetarrörelsen som oberoende socialdemokratisk och den gröna färgen är en en passande accentfärg på nästan motsatt sida av färghjulet.
Värt att notera är att sidorna Ekonomi, Kultur och Sport går i grönt, blått och orange istället för rött. Valen av dessa färger skulle vara intressant att veta mer om då de traditionellt kanske inte speglar motsvarande profiler. Grönt som kan tolkas som inexperience {1,2} är kanske inte det man vill förknippa med ekonomi men i samma traditionella tankesätt kan det också förknippas med stabilitet och genorsitet {1,2} och det är ju desto mer passande. Värt att notera är att Dagens Nyheters gröna färg under ekonomisidorna är snarlik den som används på Pôle Emplois sidor för arbetsgivare. Någon slags auktoritet kanske kan förknippas med det gröna ändå.
Den blå färgen på Dagens Nyheters Kultursidor känns lite borgerlig i ett europeiskt perspektiv och är kanske därför inte helt passande då kulturen och borgerligheten sällan går hand i hand.
Orange för att representera sport hittar jag inget belägg för i de traditionella sätten att analysera färgers mening men personligen tänker jag på nederländerna och fotboll. Jag skulle också säga att det är en ganska vibrant livlig orange nyans de använder så det kanske är passande ändå.

Referenser
-----------------------
{1} https://www.mediacaterer.com/2022/02/color-meaning-and-symbolism.html </br>
{2} http://www.webdesignref.com/chapters/13/ch13-17.htm


Övrigt
-----------------------

Artikelförfattare: Max Behrendt