# KITSCH – Abschiedsseite

Eine einzelne, statische Seite, mit der sich das Restaurant KITSCH (Zürs) nach zwei Saisons von seinen Gästen verabschiedet.

## Dateien

| Datei                     | Zweck                                                        |
| ------------------------- | ------------------------------------------------------------ |
| `index.html`              | Seite (semantisches HTML, Sprache `de`)                      |
| `style.css`               | Gesamte Gestaltung, keine externen Ressourcen                |
| `assets/kitsch-logo.png`  | **Benötigte lokale Logodatei** – Original-Logo, siehe unten  |

Kein Framework, keine Bibliotheken, kein JavaScript, kein Build-Schritt, keine externen Schriften oder Dienste.

## Logo

`assets/kitsch-logo.png` ist das unveränderte Original-Logo der bisherigen Website
(kitsch.cc → www.kitsch-zuers.com): transparentes PNG, 1400 × 1400 px, Originalfarben
(Schwarz, Magenta `#e6007e`, Cyan `#009fe3`, Weiß). Eine Vektorfassung (SVG/PDF) war auf
der alten Website nicht abrufbar; sollte eine vorliegen, kann sie unter demselben Pfad
abgelegt und in `index.html` referenziert werden.

Die Datei wird außerdem als Favicon verwendet.

## Veröffentlichen

Den Inhalt dieses Verzeichnisses (`index.html`, `style.css`, `assets/`) unverändert in das
Web-Root eines beliebigen Webservers legen. Es sind keine weiteren Schritte nötig.

## Instagram-Post

Im Ordner `social/` liegt ein passender Feed-Post in derselben Gestaltung:

- `instagram-post.png` – fertiges Bild, 1080 × 1350 px (4:5)
- `instagram-caption.txt` – Begleittext und Alt-Text zum Einfügen
- `instagram-post.html` – Vorlage; bei Änderungen in einem Browserfenster von exakt
  1080 × 1350 px öffnen und als Screenshot exportieren

## Rechtliches

Die Links am unteren Seitenrand zeigen auf die bestehenden, geprüften Seiten der bisherigen Website:

- Impressum: https://www.kitsch-zuers.com/impressum/
- Datenschutzerklärung: https://www.kitsch-zuers.com/datenschutzrichtlinie/

Sollte die alte Website abgeschaltet werden, müssen diese beiden Ziele angepasst werden.
