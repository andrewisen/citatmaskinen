# Citatmaskinen 2.0
Citatmaskinen är en en dryckeslek för oss som hängt på internet och gillar fuktiga mejmejs.<br/>
Det är en hemsida med slumpmässiga citat från populära internetvideos.<br/><br/>
Hemsidan går ut på att gissa ursprunget till citaten - Kul va!

## Komma igång
Det är bara att klona och köra i valfri webbläsare.<br/>
Du kan även göra enkla ändringar för att göra sidan till din egen.<br/>

OBS: Sökvägen till textfilen är "./files/data.txt".<br/>
Det kan uppstå problem om du kör direkt i OSX eller Linux.

### Frutsättningar
Grundläggande webkunksaper rekomenderas.

```
Ett webbhotell att ladda upp innehållet till.
```

### Installera

Börja med att klona projektet.
Är du osäker? [Läs hur man klonar projekt här!](https://help.github.com/articles/cloning-a-repository/)

```console
git clone https://github.com/andrewisen/citatmaskinen.git
```

Gör dina egna redigeringar i valfritt program.<br/>
Förslagsvis i data-filen.

```
"./files/data.txt".
```

Den är uppbyggd som en CSV-fil enligt följande konvektion:

```
CITAT ;  KÄLLA ; LÄNK TILL CITAT 
```

Exempelvis:

```
Vem vare som kasta?;Skogsturken;https://youtu.be/bzUiA9tjn6E?t=30s
Ha det så kult på restaurangen!;Pistolhota unge;https://youtu.be/qCSfy670df4?t=27s
...
```

Ladda sedan innehållet till ditt webbhotell med valfri FTP-klient.

## Skapad med

* [jQuery](https://jquery.com) - Framework
* [Javascript](https://sv.wikipedia.org/wiki/Javascript) - Script
* [Bootstrap](https://getbootstrap.com) - Design


## Upphovsman

* **André Wisén** - *Initial work* - [André "MG" Wisén](https://github.com/andrewisen)

## Tack till

* [Arvid Viderberg](https://github.com/Aweponken)
