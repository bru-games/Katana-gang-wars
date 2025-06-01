# Katana: Gang Wars – Unity-Projekt

## 🔧 Voraussetzungen
- Unity Hub installiert
- Unity Version: **2022.3 LTS** oder **2023.x**
- Android Build Support aktiviert (inkl. Android SDK, NDK, OpenJDK)

## 📂 Projektstruktur
- `Assets/Scripts/` → C#-Skripte für Spielmechanik
- `Assets/Scenes/` → Unity-Szenen (Intro, Charakterauswahl, Level1–10, Victory)
- `Assets/Sprites/` → Platzhalter für Charaktere, Gegner und Katana
- `Assets/UI/` → UI-Elemente wie Buttons und HUD

## ▶️ Szenenübersicht
1. **IntroScene** – zeigt @bruno Games und den Titel
2. **CharacterSelect** – Auswahl: Männlich oder Weiblich
3. **Level1 – Level10** – Gegnerwellen, Level-Aufstieg
4. **Victory** – Abschlussbildschirm

## 🕹️ Steuerung
- Touch-Buttons (links/rechts, Faust, Tritt)
- Katana wird automatisch aufgesammelt bei Berührung
- Intro kann durch Tippen übersprungen werden

## 🧱 Installation in Unity
1. Projekt entpacken und in Unity Hub importieren
2. Szenenpfad: `Assets/Scenes/IntroScene.unity`
3. Öffne `File → Build Settings`
4. Wähle „Android“, klicke „Switch Platform“
5. Füge alle relevanten Szenen in korrekter Reihenfolge hinzu:
   - IntroScene
   - CharacterSelect
   - Level1 bis Level10
   - Victory

## 📦 APK erstellen
1. Im Build Settings-Fenster:
   - Platform: Android
   - Target Device: ARMv7 + ARM64
   - Build System: Gradle
   - Scripting Backend: IL2CPP
2. Klicke auf `Build`, wähle Zielordner
3. Unity erstellt die Datei `Katana_Gang_Wars.apk`
4. Auf Android-Gerät kopieren und installieren

## 🧾 Hinweis
Alle Sprites in `Assets/Sprites/` sind Platzhalter.
Du kannst deine eigenen PNG-Dateien mit gleichem Namen ersetzen.

## 🧑‍🎨 Freie Asset-Quellen (empfohlen)
- https://kenney.nl/assets
- https://opengameart.org
- https://itch.io/game-assets/free

Viel Erfolg!
