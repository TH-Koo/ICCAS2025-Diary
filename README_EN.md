
# 🦖 Math Dino: A Digital Therapeutic Running-Action Game

**Math Dino** is a digital therapeutic game designed for children aged 6 to 12 who experience **developmental dyscalculia**.  
Players take on the role of a curious 10-year-old boy named **San Kang**, who must escape from a dinosaur-infested lab by solving gentle, story-based math quizzes.

---

## 🎯 Project Overview

- **Engine**: Unity 6000.1.9f1  
- **Language**: C#  
- **Localization**: 🇰🇷 Korean, 🇺🇸 English (US/UK), 🇩🇪 German  
- **Target Age**: Elementary students (6–12 years)  
- **Therapeutic Focus**: Children with Dyscalculia

---

## 🧠 What is Dyscalculia?

Dyscalculia is a specific learning disorder that makes it difficult to understand numbers, symbols, and basic arithmetic, regardless of intelligence or schooling.  
Math Dino addresses the following three types of dyscalculia:

1. **Lexical Dyscalculia** – Difficulty recognizing number-related words  
2. **Practical Dyscalculia** – Difficulty estimating quantities or comparing sizes  
3. **Arithmetic Dyscalculia** – Difficulty performing basic arithmetic operations

---

## 🧩 Game Story

San Kang, a curious 10-year-old, gets lost during a field trip to a dinosaur museum.  
He accidentally enters a mysterious elevator and ends up in a secret research facility full of machines and dinosaur tanks.  
Suddenly, an explosion sets the dinosaurs free!  
San and his kind teacher **Ms. Jane** must escape before they get caught — solving math-themed puzzles along the way.

---

## 🧪 Game Features

- Temple-run style **running action gameplay** + math quiz mechanics  
- **+10 seconds for correct answers**, **–5 seconds and vibration for wrong answers**  
- Questions are categorized based on **type of dyscalculia**  
- Language-specific quiz loading via `quiz_xx.txt`  
- Reinforcement through **repetition and visual interaction**  
- Future support for **answer tracking and learning analytics**

---

## 📁 Project Folder Structure

```
Assets/
├── Scripts/
│   ├── QuizManager.cs
│   ├── QuizLoader.cs
│   ├── QuizOptionCollider.cs
│   ├── TimeManager.cs
│   ├── PlayerController.cs
│   ├── GameManager.cs
│   └── ...
├── StreamingAssets/
│   ├── quiz_ko.txt
│   ├── quiz_en.txt
│   ├── quiz_de.txt
```

---

## ⚙️ Key Scripts Overview

| Script | Description |
|--------|-------------|
| `QuizManager.cs` | Manages quiz activation, judgment, and transitions |
| `QuizLoader.cs` | Loads quiz data based on selected language |
| `QuizOptionCollider.cs` | Detects player collision with quiz options |
| `TimeManager.cs` | Manages game time and updates localized timer UI |
| `PlayerController.cs` | Controls automatic forward movement of the player |
| `GameManager.cs` | Handles game-over state and animation |
| `BGMManager.cs` | Plays background music based on current scene |
| `CameraFollow.cs` | Keeps camera following the player |
| `MainMenuManager.cs` | Handles main menu, options, and exit actions |
| `OptionsController.cs` | Manages sound/language settings and options UI |
| `PauseManager.cs` | Toggles pause and restart functions |
| `QuizData.cs` | Structure for storing quiz question, options, and correct answer |

---

## 📊 Future Extensions

- Track accuracy by quiz type and difficulty  
- Adaptive difficulty adjustment  
- Add O/X popup UI for correct/wrong feedback  
- End-of-game report screen for learning analytics

---

## 💡 Purpose

Math Dino is not just an educational game — it’s designed as a potential **digital therapeutic tool**.  
It provides math exposure through playful exploration, reduces math anxiety through repetition and friendly visuals,  
and helps children build confidence and focus through gradual success.

---

## 👤 Developer

- Taehwan Koo, undergraduate AI major  
- Interested in game-based cognitive training and medical AI applications
