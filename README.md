# 📦 Interaktives & Responsives CSS Box-Modell Tutorial

Ein modernes "Learning-by-Doing"-Projekt für Web-Development-Einsteiger. Dieses interaktive Schaubild macht das theoretische CSS Box-Modell visuell greifbar – direkt im Browser und optimiert für alle Endgeräte (PC, Tablet und Smartphone).

> 💻 **Tipp für das beste Lernergebnis:**
> Obwohl dieses Tutorial komplett responsiv ist und auf dem Smartphone sauber angezeigt wird, solltest du es **am besten am PC oder Laptop nutzen**. Nur so kannst du den Code nebenbei in einem Editor öffnen, Werte verändern und die Experimente aktiv ausprobieren!

---

## 🚀 Das Konzept: Verschachtelung verstehen

Anstatt das Box-Modell nur theoretisch zu erklären, schachtelt dieses Tutorial die HTML-Elemente farblich exakt so ineinander, wie es auch die offiziellen **Browser-Entwicklertools (F12)** tun. 

* 🟦 **Content (Blau):** Der innerste Kern mit dem Text.
* 🟩 **Padding (Grün):** Der schützende Innenabstand um den Text herum.
* ⬛ **Border (Dunkelgrau):** Die harte, sichtbare Schale (Rahmen) der Box.
* 🟨 **Margin (Gelb/Orange):** Der äußere Sicherheitsabstand zur Umgebung.

---

## 📱 Features dieser Version

* **100% Responsiv:** Dank CSS Flexbox und intelligenten Media Queries schrumpfen die Schichten auf Smartphones automatisch zusammen. Kein seitliches Herausrutschen des Layouts!
* **Min-Height Flexibilität:** Wird der Bildschirm kleiner und bricht der Text um, wächst der blaue Content-Bereich dynamisch nach unten mit.
* **Sauberes Best-Practice CSS:** Verwendet den Industriestandard `box-sizing: border-box`, um unvorhersehbare Box-Vergrößerungen zu verhindern.

---

## 🛠️ So nutzt du dieses Tutorial zum Lernen

1. **Repository klonen oder herunterladen:** Klicke oben rechts auf den grünen `Code`-Button und lade die ZIP-Datei herunter.
2. **Datei starten:** Öffne die `index.html` mit einem Doppelklick in deinem bevorzugten Browser.
3. **Im Editor experimentieren:** Öffne dieselbe Datei in einem Texteditor (z. B. VS Code) und verändere im `<style>`-Bereich die Werte für `padding` oder `margin`.

### 🧪 Experimente für dich:
* Verkleinere dein Browserfenster, um zu sehen, wie das `@media`-Skript im CSS die Abstände auf Handys automatisch verringert.
* Lösche im CSS testweise ganz oben die Zeilen 8–12 (den `*`-Reset). Schau dir an, wie sich das Layout ohne `border-box` verändert!

---

## 🌐 Live-Demo

Du kannst das Tutorial sofort ausprobieren, ohne Code herunterzuladen:
👉 <a href="https://m-wiecha.github.io/css-box-modell-tutorial/" target="_blank" rel="noopener noreferrer">Hier geht's zur Live-Demo</a> 🚀

---

## 📝 Lizenz

Frei verwendbar für Bildungs- und Lernzwecke (MIT Lizenz). Viel Spaß beim Coden!
