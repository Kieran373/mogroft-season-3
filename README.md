# mogroft-season-3
Dieses Repository gilt als Sammelstelle der Dokumentation und Datapacks für Mogroft Season 3.

## Datapacks
Nutze gerne die Vorlage unter `Datapacks\sample-pack`, um nicht mehr die Dateistruktur für ein neues Datapack anlegen zu müssen.
Hier eine kleine Anleitung:
1. Kopiere den Ordner `sample-pack` in deinen `datapacks`-Ordner.
2. Benenne ihn um z. B. in `neues-pack`.
  - Ändere außerdem `sample-pack\data\sample` in z. B. `neues-pack\data\neu`.
3. Passe die `load.json` an (achte auf dein neu vergebenes Kürzel `neu`):
  ```mc
  {
    "values": [
      "neu:load"
    ]
  }
  ```
4. Passe die `tick.json` an (achte auf dein neu vergebenes Kürzel `neu`):
  ```mc
  {
    "values": [
      "neu:tick"
    ]
  }
  ```
5. Entwickele dein Datapack.
6. Lege es in diesem Repository unter `Datapacks\neues-pack` ab.
7. Beschreibe in einer kleinen Dokumentations-Markdown-Datei, was dein Datapack macht und lege diese anschließend bspw. unter `Documentation\Datapacks\neues-pack.md` ab.