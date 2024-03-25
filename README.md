
# Rapport

Jag började med att ändra namnet på appen under Java -> res -> values -> strings.xml till
"MyAmazingApp". Detta kan ses i koden nedanför.
```
<string name="app_name">MyAmazingApp</string>
```
Nästa steg var att ändra texten i mitten av skärmen. Jag skapade en ny stringvariabel "Text_Info" i
strings.xml där jag skrev "This is my amazing app". Detta kan ses i koden nedanför.
```
<string name="Text_Info">This is my amazing app</string>
```
Därefter gick jag in i res -> layout -> activity_main.xml och under "TextView" skrev jag in 
"Text_info". Detta kan ses i koden nedanför.
```
android:text="@string/Text_Info"
```
Jag verifierade att allt såg ut som planerat och tog en skärmdump som är bifogad i projektet.


![](android.png)

