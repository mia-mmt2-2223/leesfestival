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

We hebben zoveel mogelijk de gegevens van de Dropbox Paper overgenomen. Je ziet echter ook `durationMinutes` en `maxSeats` staan. Die fictieve gegevens hebben we zelf eraan toegevoegd zodat er wat meer te visualiseren is :)

