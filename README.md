# Produkt Feeds

Dieses Repository stellt Produkt-Feeds als **CSV-Dateien** zur Verfügung.  
Die Dateien werden automatisch durch das Repository [`feed-engine`](https://github.com/labiosthetique/feed-engine) generiert und über **GitHub Pages** bereitgestellt.  

## Zugriff auf die Feeds

Alle Dateien aus diesem Repository sind öffentlich über die folgende Basis-URL erreichbar:

```
https://static.labiosthetique-ws.com/
```

Die Feeds selbst liegen im Unterordner `feed/`.  
Beispiel-URL für eine Feed-Datei:

```
https://static.labiosthetique-ws.com/feed/produkt-feed.csv
```

*(Dateiname entsprechend anpassen, je nach Feed.)*

## Struktur

- **`feed/`** – Enthält die generierten CSV-Feeds  
- **GitHub Pages** – Stellt die Dateien statisch unter der o. g. Domain zur Verfügung  
- **feed-engine** – Externes Repo, das für die Generierung der Feeds verantwortlich ist  

## Verwendung

1. Wähle den gewünschten Feed im Ordner [`feed/`](./feed/).
2. Baue die URL auf, indem du den Dateinamen an die Basis-URL anhängst:
   ```
   https://static.labiosthetique-ws.com/feed/DATEINAME.csv
   ```
3. Lade die CSV-Datei herunter oder binde sie in dein System ein.

## Hinweise

- Die Feeds werden regelmäßig aktualisiert.  
- Änderungen an Struktur oder Inhalt erfolgen über das [feed-engine](https://github.com/labiosthetique/feed-engine)-Repository.  
- Dieses Repository dient ausschließlich als **statischer Bereitstellungsort**.  

---

