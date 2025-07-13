# KIDSCRIPT – Zählen lernen für Kinder

## Einführung
KIDSCRIPT ist eine einfache, kindgerechte Programmierumgebung, die Kindern das Zählen auf spielerische Weise beibringt. Mit einer vereinfachten Syntax und visuellen Feedback können Kinder erste Programmierkonzepte erlernen.

## Hauptfunktionen

- 🎨 **Kindgerechte Oberfläche** mit bunten Farben und großer Schrift
- 🔢 **Zahlen als Emojis** für visuelles Lernen
- 🔊 **Sprachausgabe** (Text-to-Speech) für auditives Lernen
- ⏱️ **Zeitverzögerungen** für besseres Verständnis des Ablaufs
- 📝 **Einfache Syntax** mit deutschen Schlüsselwörtern:
  - `zeige` - Gibt Text aus
  - `zähle von X bis Y` - Schleife von X bis Y
  - `warte X sekunde(n)` - Pause im Programm
  - `ende` - Beendet einen Block

## Verwendung

1. Öffnen Sie die HTML-Datei in einem modernen Browser
2. Bearbeiten Sie den Code im Textfeld (oder lassen Sie den Beispielcode)
3. Klicken Sie auf "▶️ Start" um das Programm auszuführen
4. Sehen Sie die Ausgabe im schwarzen Ausgabebereich
5. Beobachten Sie die Emoji-Zahlenanzeige

## Beispielcode

```kidscript
zeige "Lass uns zählen!"

zähle von 1 bis 5
    zeige "Das ist die Zahl " + i
    warte 1 sekunde
ende

zeige "Super gemacht!"
```

## Technische Details

### Implementierung
- **Transpiler**: Wandelt KIDSCRIPT-Code in JavaScript um
- **SpeechSynthesis API**: Für die Sprachausgabe
- **Reine Client-seitige Lösung**: Kein Server benötigt

### Unterstützte Befehle
| Befehl | Beschreibung | Beispiel |
|--------|--------------|----------|
| `zeige` | Zeigt Text an | `zeige "Hallo"` |
| `zähle von X bis Y` | Schleife von X bis Y | `zähle von 1 bis 10` |
| `warte X sekunde(n)` | Pausiert das Programm | `warte 2 sekunden` |
| `ende` | Beendet Block | `ende` (nach Schleife) |

## Systemvoraussetzungen
- Moderner Browser (Chrome, Firefox, Edge)
- Optional: Lautsprecher/Headset für Sprachausgabe

## Lizenz
MIT-Lizenz - Freie Verwendung für Bildungszwecke

## Erweiterungsmöglichkeiten
- Weitere Befehle hinzufügen (z.B. wenn-dann)
- Farbige Ausgabe implementieren
- Mehr Interaktionsmöglichkeiten
- Speichern/Laden von Programmen
