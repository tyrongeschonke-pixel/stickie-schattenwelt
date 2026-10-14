# Stickie durch die Schattenwelt

[**Spiel öffnen**](https://tyrongeschonke-pixel.github.io/stickie-schattenwelt/)

Kostenloses 2D-Abenteuer im Querformat: 50 Level, fünf große Bosse, Nahkampf und Fernkampf, Lichtdorf, Waffenladen, zusätzliche Lebenspunkte und deutsche Boss-Dialoge.

## Auf dem iPhone

1. Öffne den Spiel-Link in Safari.
2. Drehe das iPhone ins Querformat und tippe auf **Spiel starten**.
3. Über **Teilen → Zum Home-Bildschirm** kannst du ein App-Symbol hinzufügen.

Auf Android funktioniert derselbe Link in Chrome; dort kannst du das Spiel ebenfalls zum Startbildschirm hinzufügen. Es gibt keine Werbung und keine echten Geldkäufe.

## Spielstände

Fortschritt, Coins, Waffen und Zusatzleben werden in diesem Browser auf diesem Gerät gespeichert. Benutze keinen privaten Browsermodus. Das Löschen der Websitedaten entfernt auch den Spielstand. Spielstände werden nicht zwischen Geräten synchronisiert.

## Updates

`stickie-web.zip.b64` enthält die fertige Web-App als Textkodierung. Der Workflow wandelt sie in die ZIP-Datei zurück und veröffentlicht das Spiel. Wird das Paket auf `main` ersetzt, erscheint die neue Version automatisch unter **demselben Link**. Ein normaler Upload als `stickie-web.zip` wird ebenfalls unterstützt und hat Vorrang. Keine neue App-Installation nötig. Der Godot-Export erzeugt für jeden Build einen neuen Cache-Stand. Verfügbare Updates werden über **Update bereit · neu laden** angeboten; ein bereits laufendes Spiel wird dabei nicht ungefragt neu gestartet.

Die Web-App wurde mit Godot 4.7.2 aus dem vorhandenen Spielprojekt exportiert. Sie verwendet **keine Threads**, sodass keine speziellen COOP/COEP-Header erforderlich sind. Das bearbeitbare Quellprojekt wird lokal aufbewahrt und gehört nicht zum öffentlichen Repository.

## Veröffentlichung

GitHub Pages verwendet **GitHub Actions** als Quelle. Der Workflow entpackt die geprüfte Web-App und veröffentlicht sie. Das Hosting des öffentlichen Repositorys über GitHub Pages ist im kostenlosen GitHub-Tarif enthalten.

Die erste Version wurde im Desktop-Browser geprüft. Ein Test auf einem echten iPhone bleibt notwendig, besonders für Touch-Steuerung, Bildschirmtastatur und Leistung.
