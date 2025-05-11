### Lesen Sie diese Readme in einer anderen Sprache:

-   [Englisch](README.md)
-   [Französisch](README.fr.md)
-   [Deutsch](README.de.md)
-   [Spanisch](README.es.md)

# Übersetzungsdateien für Chillbot

Dieses Repository hostet die Übersetzungsdateien für den Discord Bot**Chillbot**. Diese Dateien ermöglichen es Chillbot, seine Funktionen in mehreren Sprachen anzubieten und der Community zur Verbesserung der Übersetzungen beizutragen.

## Dateistruktur

Übersetzungsdateien sind in**JSON**Format und organisiert nach Sprachcode (z. B.,,`en-US.json`,`fr-FR.json`).
Jede Datei spiegelt die Hierarchie der Module, Befehle und Nachrichten des Bots wider.

**Beispielstruktur:**

```json
{
  "pro": {
    "ftnl": {
      "chillbot": {
        "core": {
          "utility": {
            "commands": {
              "list": {
                "slash": {
                  "publics": {
                    "music": {
                      "PlayCmd": {
                        "action": {
                          "success": "🎵 %s, Successfully joined %s.",
                          "noPrime": "You can get 24/7 playback by voting for the bot here."
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }
      }
    }
  }
}
```

-   **Schlüssel**Reflektieren Sie die Struktur der Merkmale des Bots.
-   **Werte**sind die Saiten übersetzt, die manchmal Variablen enthalten (`%s`,`%d`, usw.).

## Wie man beiträgt

1.  **Wählen oder erstellen Sie die Sprachdatei:**Wenn die Datei für Ihre Sprache nicht vorhanden ist, kopieren Sie eine vorhandene Datei (z. B..`en-US.json`) und benennen es mit dem entsprechenden Sprachcode um (z. B.,,`fr-FR.json`).
2.  **Übersetzen Sie die Saiten:**Ersetzen Sie jeden Wert durch die richtige Übersetzung. Achten Sie darauf, Variablen zu behalten (`%s`,`%d`, etc.) in their original positions.
3.  **Behalten Sie die Struktur bei:**Ändern Sie die Schlüsselstruktur nicht. Fehlende oder umbenannte Schlüssel können während der Integration Fehler verursachen.
4.  **Validieren Sie die Syntax:**Verwenden Sie einen JSON -Validator, um Formatierungsfehler zu vermeiden.

## Best Practices

-   **Dynamische Variablen:**Variablen sicherstellen (`%s`,`%d`usw.) an der richtigen Stelle innerhalb des Satzes bleiben.
-   **Emojis und Links:**Halten Sie die in den Nachrichten vorhandenen Emojis, Links oder Discord -Erwähnungen.
-   **Klarheit und Zuversicht:**Verwenden Sie klare und natürliche Übersetzungen für Ihre Sprache.

## Übersetzung einreichen

1.  **Gabel**Dieses Repository.
2.  **Erstellen Sie einen Zweig**Für Ihren Beitrag.
3.  **Bearbeiten oder hinzufügen**Die relevante Übersetzungsdatei.
4.  **Öffnen Sie eine Pull -Anfrage**mit einer klaren Beschreibung Ihrer Änderungen.

## Beispielnachrichten zur Übersetzung

-   Erfolgs- oder Fehlermeldungen:`"success": "🎵 %s, Successfully joined %s."`
-   Befehlsbeschreibungen:`"description": "Starts playing music in voice channel"`
-   Taste -Etiketten:`"supportButtonLabel": "Support"`

## Kontakt \\ & Support

Bei Fragen oder Vorschlägen treten Sie dem Support Discord Server des Bots oder öffnen Sie in diesem Repository ein Problem.

* * *

Vielen Dank, dass Sie Chillbot für alle zugänglich gemacht haben!
