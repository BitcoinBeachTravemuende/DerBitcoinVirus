# DER BITCOIN VIRUS

Gratis Buch zum Thema Bitcoin von @KahnsisDeVillain

## Lesen

Online Version: https://bitcoinbeachtravemuende.github.io/DerBitcoinVirus/

<center>

[![Book Cover](src/assets/cover-front.png)](https://bitcoinbeachtravemuende.github.io/DerBitcoinVirus/)

</center>

## Buch auf Deinem Rechner erstellen

### Voraussetzung 

Voraussetzung ist eine Installation von `Rust` und `Cargo` auf Deinem Rechner. Folge dazu der offiziellen [Rust Installationsanleitung](https://www.rust-lang.org/tools/install) (in Englisch). 

Das Buch wurde mit [`mdbook`](https://github.com/rust-lang/mdBook) erstellt, welches Du mit folgendem Befehl installieren kannst. 

```bash
cargo install mdbook
```

### Erstellen des Buches

Um das Buch lokal zu erstellen, führe folgenden Befehl aus:

```
mdbook build
```

Die erstellten Dateien befinden sich im Verzeichnis `book/`.

### Entwicklung

Um das Buch beim Entwickeln zu betrachten, führe folgenden Befehl aus:

```bash
mdbook serve
```

Damit wird ein lokaler Webserver gestartet, der das Buch ausliefert. Das Buch kann im Browser unter `localhost:3000` betrachtet werden. Während der Webserver läuft, wird das Buch automatisch neu gerendert, sobald sich die Dateien des Buches ändern.

## Nix

Alternativ zu den oberen Schritten kann das Buch auch mit `Nix` erstellt werden. 

Voraussetzungen: 

1. [Nix installieren](https://zero-to-flakes.com/install) (engl.)
1. [`direnv` einrichten](https://zero-to-flakes.com/direnv) (engl.)

Mit `cd` in das Rootverzeichnis, um in die `nix develop` Shell zu gelangen. Gebe einamlig `direnv allow` ein. Danach führe die `mdbook` Befehle aus wie oben beschrieben.


## Online veröffentlichen

Sobald ein Pull Request in den `main` Branch gemerged wird, wird das Buch per [GitHub Action](.github/workflows/publish.yml) automatisch neu erstellt und wird ca. 2-3 Minuten später auf https://bitcoinbeachtravemuende.github.io/DerBitcoinVirus/ veröffentlicht.

## Verbesserungen

Vorschläge für Verbesserungen oder Korrekturen sind immer willkommen. Erstelle dazu ein Issue oder einen Pull Request.

## Lizenz

MIT Lizenz (siehe [LICENSE](LICENSE) or http://opensource.org/licenses/MIT)
