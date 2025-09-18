# Labyrinth: Echo of the Shards 🧩✨

Ein atmosphärisches Fantasy‑Labyrinth‑Spiel, in dem du mystische Scherben sammelst, Fallen entgehst und dich listigen Gegnern stellst. Finde den Weg durch prozedural angehauchte Areale, löse leichte Rätsel und setze gesammelte Artefakte taktisch ein, um das Herz des Labyrinths zu erreichen.

## 🎯 Kurzüberblick
- Genre: Fantasy / Adventure / Puzzle‑Action
- Ziel: Scherben sammeln, Portale aktivieren, Bossräume freischalten
- Herausforderungen: Fallen (Spikes, Pendel, Druckplatten), Gegner (Wächter, Jäger), begrenzte Ressourcen
- Loop: Erkunden → Scherben → Upgrades/Artefakte → Tiefer ins Labyrinth → Boss

## 🔥 Hauptfeatures
- Dynamische Labyrinth‑Layouts mit wiederverwendbaren Raum‑Modulen
- Taktische Scherben‑Artefakte (Dash, Zeitlupe, Schutzkuppel) mit Abklingzeiten
- Gegner‑KI mit Patrouille, Geräusch‑ und Sichtkegel‑Erkennung
- Umweltgefahren: Fallen, Geheimtüren, versteckte Schalter
- Leichte Rätselmechaniken (Muster, Druckplatten, Farbcodes)
- Minimalistische UI/HUD, Controller‑ und Tastatur‑Support
- Checkpoints, sammelbare Lore‑Fragmente und Fortschrittsspeicherung

## 🖼️ Screenshots & GIFs
Füge hier Medien ein, um Gameplay und Stimmung zu zeigen.
- `media/screenshot-01.png`
- `media/screenshot-02.png`
- `media/echo-run.gif`

Tipp: Lege einen Ordner `media/` im Projekt an und verlinke Dateien relativ:

```markdown
![Eingangshalle](media/screenshot-01.png)
![Kampf im Korridor](media/screenshot-02.png)
![Echo‑Dash](media/echo-run.gif)
```

## ⚡ Quickstart (Unity 6)
Voraussetzungen: Unity 6 (2025.x LTS empfohlen), Git, optional Rider/VS Code.

1) Repository klonen oder herunterladen
2) In Unity Hub öffnen (Version: Unity 6)
3) Build Target prüfen (PC/Mac/Linux Standalone)
4) Startszene laden (z. B. `Scenes/MainMenu` oder `Scenes/Labyrinth_Test`)
5) Play drücken ▶

Optional:
- Quality auf „High“ stellen, VSync aus, um Performance zu testen
- Input testen: WASD/Left‑Stick, Maus/Right‑Stick, Space/Face‑Button zum Dash

## 🛠️ Tech‑Stack
- Engine: Unity 6, C#
- Patterns: ScriptableObjects (Config/Items), Event‑Kanäle, State Machines
- Tools: Cinemachine, ProBuilder/ProGrids, TextMeshPro
- Build: Addressables (optional), URP (leichtgewichtig)

## 🗺️ Roadmap
- [ ] Koop‑Modus (2‑Spieler lokal/online)
- [ ] Shop‑/Upgrade‑System für Artefakte
- [ ] Boss‑Encounter Phase 2 (mehr Muster, Telegraphiert)
- [ ] Optional: Rogue‑lite Progression zwischen Runs
- [ ] Accessibility: Farbblinde‑Profile, skalierbare UI
- [ ] Lokalisierung (DE/EN)
- [ ] Steam‑Seite und Demo‑Build

## 📜 Lizenz
Dieses Projekt steht unter der MIT‑Lizenz. Details siehe `LICENSE`.

---

Fragen oder Feedback? Erstelle ein Issue oder melde dich gerne via LinkedIn/E‑Mail aus meinem Profil‑README. 👋
