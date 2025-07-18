
# 🦖 Math Dino: Ein digitales therapeutisches Action-Rennspiel

**Math Dino** ist ein digitales Lernspiel für Kinder im Alter von 6 bis 12 Jahren mit **Rechenschwäche (Dyskalkulie)**.  
Die Spieler schlüpfen in die Rolle des neugierigen 10-jährigen **San Kang**, der aus einem Dinosaurierlabor entkommen muss, indem er spannende, in die Geschichte eingebettete Mathematikrätsel löst.

---

## 🎯 Projektübersicht

- **Engine**: Unity 6000.1.9f1  
- **Sprache**: C#  
- **Sprachunterstützung**: 🇰🇷 Koreanisch, 🇺🇸 Englisch, 🇩🇪 Deutsch  
- **Zielgruppe**: Grundschüler (6–12 Jahre)  
- **Therapeutischer Fokus**: Kinder mit Dyskalkulie

---

## 🧠 Was ist Dyskalkulie?

Dyskalkulie ist eine spezifische Lernstörung, die das Verstehen von Zahlen, Symbolen und Rechenoperationen erschwert – unabhängig von Intelligenz oder Bildung.

**Math Dino** berücksichtigt drei Haupttypen:

1. **Lexikalische Dyskalkulie** – Schwierigkeiten beim Erkennen von Zahlwörtern  
2. **Praktische Dyskalkulie** – Schwierigkeiten beim Abschätzen von Mengen oder Größen  
3. **Arithmetische Dyskalkulie** – Schwierigkeiten bei Grundrechenarten

---

## 🧩 Spielgeschichte

San Kang, ein neugieriger Junge, verirrt sich bei einem Museumsbesuch in ein geheimes Dinosaurierlabor.  
Durch einen Unfall brechen die Dinosaurier aus!  
Zusammen mit seiner freundlichen Lehrerin **Frau Jane** muss er entkommen – mithilfe von kleinen Matheaufgaben.

---

## 🧪 Spiel-Features

- **Action-Rennspiel mit Quiz-Mechanik**  
- **+10 Sekunden** bei richtiger Antwort, **–5 Sekunden und Vibration** bei falscher Antwort  
- Aufgaben basieren auf dem **Typ der Dyskalkulie**  
- Lokalisierter Quiz-Import via `quiz_xx.txt`  
- **Wiederholung, visuelles Feedback** und spielerisches Lernen

---

## 📁 Projektstruktur

```
Assets/
├── Scripts/
├── StreamingAssets/
│   ├── quiz_ko.txt
│   ├── quiz_en.txt
│   ├── quiz_de.txt
```

---

## ⚙️ Wichtige Skripte

| Skript | Beschreibung |
|--------|--------------|
| `QuizManager.cs` | Steuert Quiz-Aktivierung, Bewertung und Übergänge |
| `QuizLoader.cs` | Lädt Quizdaten abhängig von der Sprache |
| `QuizOptionCollider.cs` | Erkennt Kollision mit Quiz-Antwortfeldern |
| `TimeManager.cs` | Verwalten der Spielzeit & Anzeige |
| `PlayerController.cs` | Bewegung des Spielers nach vorne |
| `GameManager.cs` | Spielende-Logik & Animation |
| `BGMManager.cs` | Szenenabhängige Hintergrundmusik |
| `CameraFollow.cs` | Kamera folgt dem Spieler |
| `MainMenuManager.cs` | Menüfunktionen und Szenenwechsel |
| `OptionsController.cs` | Einstellungen für Sprache & Audio |
| `PauseManager.cs` | Pause & Neustart-Funktion |
| `QuizData.cs` | Datenstruktur für Quizfragen & Antworten |

---

## 📊 Geplante Erweiterungen

- Statistiken nach Fragetyp & Schwierigkeitsgrad  
- Adaptive Schwierigkeitsanpassung  
- O/X-Feedback bei richtigen/falschen Antworten  
- Lernbericht nach Spielende

---

## 💡 Zielsetzung

Math Dino ist mehr als ein Lernspiel –  
es soll als **digitales therapeutisches Werkzeug** Kindern mit Dyskalkulie helfen,  
durch visuelles, wiederholtes Training Ängste abzubauen und mathematisches Selbstbewusstsein zu entwickeln.

## 👤 Entwickler

- Taehwan Koo, Bachelor-Student im Fachbereich Künstliche Intelligenz, Fakultät für Informatik
- Interessensgebiete: Künstliche Intelligenz, Computer Vision, Medizin, autonomes Fahren, Anwendungen
