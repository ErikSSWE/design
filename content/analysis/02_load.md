---
Title: Load
Description: loading time
Template: kmom
---

Loading time
=======================

urval
---------

Jag har valt dessa tre följande ssidor att testas: Eslövs kommun, mff shopen och ikea. Tanken bakom valet är ganska simpelt, min kreativitet och kunna välj är inte så stor och detta var tre hemsidor jag enkelt kunnde komma på bara så och som endån är ganska olika.

verktyg
---------

De verktyg jag använde var konsollen och google page speed.

Rådatan
--------

<a href="https://docs.google.com/spreadsheets/d/1FwLa-S92qDSV6yiOmjOvreYzlXc6hpCBGrosT-HMQMM/edit?usp=sharing">Google spread sheet</a>

Denna länk är till mitt Spread sheet för testerna utförda där man kan hitta alla individuella mätningar och inte bara medelvärdet.

<br>

###Eslövs kommun

![Eslövs kommun](%assets_url%/img/eslovskommun1.png)

<br>
<a href="https://eslov.se/">Eslövs kommun</a>

så på google Pagespeed fick Eslövs kommun ett poäng av: 78 för desktop och för mobil fick den 50 vilket inte är så bra.
Sen har vi mätningarna från devtools som jag själv utfört och där fick Eslöv på resurser: 59, laddningstid:5,86s och på total storlek: 3,72(MB)
när jag kollar på google Pagespeed test så rekommenderar att ta bort oanvänd css kod men även js kod.

<br>

###Mff shopen
![Mff-shopen](%assets_url%/img/mff-shopen1.png)

<a href="https://www.mffshopen.se/">Mff shoppen</a>

mff shopen fick av google Pagespeed test 42 för desktop och för mobil fick den 18 vilket är dåligt i min mening och enligt google pagespeed.
Mina egna mätningar av hemsidan fick jag resurser: 115, laddningstid: 21,55s och total storlek:10,62(MB). När jag kollar ser jag direkt att en av deras stora roblem är deras bilder och bildformat vilket hade ökat sidans hastighet och poäng märkvärdigt.

<br>

###Ikea
![Ikea](%assets_url%/img/ikea.jpg)

<a href="https://www.ikea.com/se/sv/">Ikea</a>

Ikea fick av google Pagespeed test ett resultat av 80 på desktop och på mobil fick Ikea 25. I mitt test av hemsidan fick jag värdena resurser:123, laddningstid: 5,14s och total storlek: 3,87(MB) Förslag på förbättring är att ta bort oanvänd css kod men även att ta bort resurser som blockerar renderingen.

<br>

analys
--------
Det vanligaste förbättringsförslagt verkar vara att ta bort oanvänd kod i både css ocj js. Sen också fixa bildformaten. Med detta gjort skulle vissa hemsidor minskat i laddningstid vilket hade resulterat i trevligare upplevelse för användaren. Hur man ska ta bort oanvänd kod är jag inte rikigt bra på men med bilderna borde man tänka på vilket format man använder.

<br>

Vinnare
--------

Vinnaren av detta test är Ikeas hemsida då jag använder min egna mätningar och bestämmde igenom medelvärdet på laddningstiden av varje sida där det var en väldigt jämn fight mellan ikea och Eslövs kommun men där ikea vann tillslut, så 1:Ikea 2:Eslövs kommun 3:Mff. Mff shopen ko tyvär väldigt långt efter i detta race men inte en dålig sida bara för det måste jag påpeka.


gränser
-------
Min personliga smak i detta med laddningstid är att det måste vara under 15s för att katogoriseras som en snabb sida enligt mig vilket alla inte gjort i detta lilla testet. Men det gick endån halvsabbt för mff shopen. Eslövs kommun och ikea är båda enligt mig väldigt snabba hemsidor. Om man kollar på alla tre hemsidor så märker man också att mff är lite bakom de andra två, det kanske kan kännas så bara för att jag sett tiden och kan ha en bättre uppfattning än den vanliga använder som kanske inte hade märkt någon skillnad men som sagt jag känner att det finns en skillnad när jag laddar om sidorna.

Test utförda av
----------------------
Erik Svensson