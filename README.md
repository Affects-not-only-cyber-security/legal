# legal

Rechtstexte der **Anocs KG** (FN 604478 p, Handelsgericht Wien), wie sie auf ihren Websites
veröffentlicht sind, mit nachvollziehbarer Versionsgeschichte.

Stand: 2. November 2026 · noch keine Fassung veröffentlicht

## Welche Fassung gilt

Maßgeblich ist die Fassung auf der jeweiligen Website. Dieses Repository belegt, welche
Fassung wann galt und was sich geändert hat:

- `main` enthält nur freigegebene Fassungen.
- Jede Veröffentlichung bekommt einen Tag `vJJJJ.MM.N` (zum Beispiel `v2026.11.0`), ein
  Release und einen Eintrag in [CHANGELOG.md](CHANGELOG.md).
- Ein Link auf einen Tag zeigt dauerhaft genau diese Fassung, zum Beispiel
  `…/legal/blob/v2026.11.0/anocs.at/datenschutz.md`.

## Aufbau

Unternehmensweite Texte liegen im Wurzelverzeichnis, Texte für eine Website in einem Ordner
mit deren Namen:

| Datei | Inhalt |
|---|---|
| `agb.md` | Allgemeine Geschäftsbedingungen |
| `anocs.at/impressum.md` | Impressum und Offenlegung für www.anocs.at |
| `anocs.at/datenschutz.md` | Datenschutzerklärung für www.anocs.at |

Jede Datei beginnt mit den Angaben zur Fassung, die auch die Website anzeigt:

```yaml
---
titel: Datenschutzerklärung
stand: JJJJ-MM-TT         # letzte inhaltliche Änderung
gueltig_ab: JJJJ-MM-TT    # ab wann diese Fassung gilt
url: https://www.anocs.at/datenschutz/
---
```

## Nutzungsrechte

Einsicht ist ausdrücklich erwünscht. Eine Erlaubnis zur Weiterverwendung ist damit nicht
verbunden; alle Rechte bleiben bei der Anocs KG beziehungsweise bei den Rechteinhabern der
verwendeten Muster.

## Hinweise und Fehler

Bitte per E-Mail an impressum@mail.anocs.at.
