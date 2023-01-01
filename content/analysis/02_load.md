Laddningstider av 3 svenska tidningars webbplatser.
=======================

Målet med denna analys är att synliggöra skillnaden på laddningstid och dataförbrukning på webben och att analysera förbättringspotential.

Urval
-----------------------

1. https://www.dn.se/ (härefter kallat DN)
2. https://www.aftonbladet.se/ (härefter kallat Aftonbladet)
3. https://www.svd.se/ (härefter kallat SVD)

De tre webbplatserna har valts ut för att de är Sveriges tre största enskilda morgon/dags-tidningar [[1]](#ref1). Kvälsstidningen Expressen har valts bort då deras sålda exemplar är räknade på tre olika tidningar: Expressen, GT och Kvälssposten.
Tanken bakom att välja tre webbplatser för nyhetsmedia är att de borde vara ungefär lika mån om att spara på dataförbrukning och laddningstid samt att de borde ha liknande resurser att lägga på detta område. Både ekonomiskt och kunskapsmässigt.

Metod
-----------------------

Testerna är gjorda i Brave browser i privat flik med Brave Shields down.
Värdena på Resources, Transfered Data och Load Time är tagna efter en minut då alla tre sidor fortsatte att skicka requests i flera minuter efter att det mesta var färdigladdat. Eventuell helsides pop-up reklam stängdes direkt den dök up då vissa element inte laddades förän den var stängd och inget scrollande gjordes.

Resultat
-----------------------
<a href= https://docs.google.com/spreadsheets/d/e/2PACX-1vTMkZfsMiM1RZpOgHZHhlsUMmUdXLEx-aJjTDSRfMu9nbTQ5XykqjoUFFKeGtD3qz1QuRAPV6k0QH0D/pubhtml>Länk till hela dokumentet här.</a>
<div class=embed-xlsx>
    <iframe class=loading-sheet src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTMkZfsMiM1RZpOgHZHhlsUMmUdXLEx-aJjTDSRfMu9nbTQ5XykqjoUFFKeGtD3qz1QuRAPV6k0QH0D/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

</br>

###Aftonbladet:  

![Screenshot av aftonbladets hemsida](../image/aftonbladet_loading.png?width=25%)
*Screenshot av aftonbladet.se*

| [aftonbladet.se]    | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 18          | 96            | 83             | 100 |
| Desktop             | 46          | 98            | 83             | 100 |


| [aftonbladet.se/kultur] | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 22          | 98            | 92             | 86  |
| Desktop             | 53          | 98            | 92             | 83  |


| [aftonbladet.se/ledare]  | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 27          | 98            | 92             | 86  |
| Desktop             | 58          | 98            | 92             | 83  |


</br>

###Dagens Nyheter:  

![Screenshot av dagens nyheters hemsida](../image/dn_loading.png?width=25%)
*Screenshot av dn.se*

| [dn.se]             | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 41          | 83            | 100             | 92 |
| Desktop             | 92          | 78            | 100             | 92 |


| [dn.se/kultur]      | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 56          | 97            | 100            | 99  |
| Desktop             | 90          | 91            | 100            | 100 |


| [dn.se/ledare]      | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 63          | 97            | 100            | 99  |
| Desktop             | 85          | 91            | 100            | 100 |

</br>


###Sveriges Dagblad:  

![Screenshot av svenska dagbladets hemsida](../image/svd_loading.png?width=25%)
*Screenshot av svd.se*


| [svd.se]            | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 46          | 83            | 100            | 92  |
| Desktop             | 85          | 78            | 100            | 92  |


| [svd.se/kultur]     | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 26          | 86            | 92             | 93  |
| Desktop             | 90          | 91            | 92             | 92  |


| [svd.se/ledare]     | Performance | Accessibility | Best Practices | SEO |
|---------------------|------------:|--------------:|---------------:|----:|
| Mobil               | 30          | 86            | 92             | 93  |
| Desktop             | 89          | 91            | 92             | 92  |



Rangordnat medelvärde på varje webplats tre sidor i alla fyra ketegorier, mobil och desktop sammanslaget:
1. Dagens Nyheter 89,41666667
2. Sveriges Dagblad 83,45833333
3. Aftonbladet 78,41666667

Genomsnittlig laddningstid sätter de tre webbplatserna i samma ordning:
1. Dagens Nyheter 2,076666667s
2. Sveriges Dagblad 2,565555556s
3. Aftonbladet 2,988888889s 

Rangordning för överförd data, lägst är bäst, ändrar dock ordningen till följande:
1. Sveriges Dagblad 1,877777778 Mb
2. Dagens Nyheter 2,522222222 Mb
3. Aftonbladet 2,977777778 Mb


Analys
-----------------------
Alla tre webbplatsers tre sidor klarar sig relativt bra på Accessibility, Best Practices och SEO.
Performance på mobila enheter tar ner medelvärdet på alla webbplatser rejält.
En teori till förklaring på det är att den stora majoriteten som besöker dessa webbplatser på mobila enheter gör detta i respektive app. Att lägga resurser på de få besökarna som använder sig av en browser i telefonen är nog inte prioriterat. En uppföljande undersökning skulle kunna vara att kolla hur mycket trafik som kommer till dessa webbplatser via mobil respektive via desktop och förhållandet till hur mycket de designerade apparna används.
När det kommer till överförd data i denna undersökning så kunde det variera väldigt mycket beroende på vad som fanns "above the fold" i just den laddningen. Artiklar med stora fotografier eller en reklam-textbanner gör en väldigt stor skillnad och därför avråds att använda överförd data som en lämpligt betyg i denna undersökning. Ett förbättringspotential för en mer relevant statistik för detta skulle vara att hitta en annan mätmetod för detta värde. Möjligtvis hur mycket data som överförts efter att ha skrollat hela vägen ner till footern. Eller helt enkelt låta mer sofistikerade verktyg såsom Google PageSpeed Insights ta hand om det.

De återkommande punkterna på alla tre webbplatsernas sida med sämst Performance poäng är följande
(ordning har ingen betydelse):
*Reduce unused JavaScript
*Serve static assets with an efficient cache policy
*Reduce JavaScript execution time
*Avoid chaining critical requests
*Keep request counts low and transfer sizes small
*Avoid large layout shifts
*Avoid long main-thread tasks
Att minska oanvänd JavaScript verkar vara den enskilt absolut största vinsten för att få ner laddningstiden. Den punkten motsvarar mellan 0.18 och 0.44 sekunder på de tre webbplatserna.
Att ändra format, storlek eller laddningssätt av bilder kommer på andra plats.

Med hänsyn till laddningstid och resultaten från Google PageSpeed Insights rangordnas webbplatserna i följande ordning (först är bäst):
1. Dagens Nyheter
2. Sveriges Dagblad
3. Aftonbladet

En personlig gräns av vad som känns som en rimlig laddningstid är under tre sekunder.
De flesta av webbplatsernas sidor klarar den gränsen och dessutom så laddas bilder och text in tidigt så man kan skrolla ner och börja läsa innan allt är färdigladdat. 

Referenser
-----------------------
<a name="ref1"></a>
https://sv.wikipedia.org/wiki/Svenska_dagstidningar#De_st%C3%B6rsta_svenska_dagstidningarna

Övrigt
-----------------------

Artikelförfattare: Max Behrendt.

[aftonbladet.se]: https://www.aftonbladet.se/
[dn.se]: www.dn.se
[svd.se]: www.svd.se
[aftonbladet.se/kultur]: https://www.aftonbladet.se//kultur
[dn.se/kultur]: www.dn.se/kultur
[svd.se/kultur]: www.svd.se/kultur
[aftonbladet.se/ledare]: https://www.aftonbladet.se//ledare
[dn.se/ledare]: www.dn.se/ledare
[svd.se/ledare]: www.svd.se/ledare