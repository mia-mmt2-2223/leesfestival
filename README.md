# leesfestival data

Als je in deze repo op **festival.json** klikt, en vervolgens rechts op de button **Raw**, krijg je de ruwe data te zien in je browser. De URL daarbij is: `https://raw.githubusercontent.com/mia-mmt2-2223/leesfestival/main/festival.json`. Dit is tevens de URL die je dient te gebruiken in je p5js project:


```
let data;

function preload(){
    data = loadJSON("https://raw.githubusercontent.com/mia-mmt2-2223/leesfestival/main/festival.json");
}

function setup(){
    console.log(data.description); //controleren of de data correct is ingeladen
}
``` 

We hebben zoveel mogelijk de gegevens van de Dropbox Paper overgenomen. Je ziet echter ook `durationMinutes`, `maxSeats` en `availableSeats` staan. Die fictieve gegevens hebben we zelf eraan toegevoegd zodat er wat meer te visualiseren is :)
`datetime` staat voor de datum+tijdstip voor de aanvang van de activiteit. Zie de [lesstof in GitBook](https://cmd-viscom.gitbook.io/1-2-mmt2/lesprogramma/6-data/data-and-apis/de-data-uit-een-api-toepassen/een-datum-gebruiken-in-je-data) hoe je met deze grote getallen moet omgaan.

