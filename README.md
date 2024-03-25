
# Rapport

Jag började med att ändra namnet på appen under Java -> res -> values -> strings.xml till
"MyAmazingApp". Detta kan ses i koden nedanför.

<string name="app_name">MyAmazingApp</string>

Nästa steg var att ändra texten i mitten av skärmen. Jag skapade en ny stringvariabel "Text_Info" i
strings.xml där jag skrev "This is my amazing app". Detta kan ses i koden nedanför.

<string name="Text_Info">This is my amazing app</string>

Därefter gick jag in i res -> layout -> activity_main.xml och under "TextView" skrev jag in 
"Text_info". Detta kan ses i koden nedanför.

android:text="@string/Text_Info"

Jag verifierade att allt såg ut som planerat och tog en skärmdump som är bifogad i projektet.


## Följande grundsyn gäller dugga-svar:

- Ett kortfattat svar är att föredra. Svar som är längre än en sida text (skärmdumpar och programkod exkluderat) är onödigt långt.
- Svaret skall ha minst en snutt programkod.
- Svaret skall inkludera en kort övergripande förklarande text som redogör för vad respektive snutt programkod gör eller som svarar på annan teorifråga.
- Svaret skall ha minst en skärmdump. Skärmdumpar skall illustrera exekvering av relevant programkod. Eventuell text i skärmdumpar måste vara läsbar.
- I de fall detta efterfrågas, dela upp delar av ditt svar i för- och nackdelar. Dina för- respektive nackdelar skall vara i form av punktlistor med kortare stycken (3-4 meningar).

Programkod ska se ut som exemplet nedan. Koden måste vara korrekt indenterad då den blir lättare att läsa vilket gör det lättare att hitta syntaktiska fel.

```
function errorCallback(error) {
    switch(error.code) {
        case error.PERMISSION_DENIED:
            // Geolocation API stöds inte, gör något
            break;
        case error.POSITION_UNAVAILABLE:
            // Misslyckat positionsanrop, gör något
            break;
        case error.UNKNOWN_ERROR:
            // Okänt fel, gör något
            break;
    }
}
```

Bilder läggs i samma mapp som markdown-filen.

![](android.png)

