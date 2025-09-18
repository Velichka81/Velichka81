# CONTRIBUTING

Danke, dass du dieses Projekt unterstützen möchtest! Diese kurze Anleitung erklärt Schritt für Schritt, wie du Issues erstellst, Branches benennst, nach Conventional Commits committest und Pull Requests stellst.

---

## 1) Issues erstellen
Nutze bitte die vorhandenen Issue-Vorlagen (Bug Report oder Feature Request):
- Gehe zu „Issues” → „New issue” → wähle eine Vorlage.
- Fülle die Abschnitte kurz und präzise aus:
  - Beschreibung (Was ist das Problem/der Wunsch?)
  - Schritte zur Reproduktion (bei Bugs)
  - Erwartetes Ergebnis
  - Screenshots/Anhänge (falls hilfreich)
  - Umgebung (OS, Version/Commit, Browser/Laufzeit)
- Prüfe vorher, ob es schon ein ähnliches Issue gibt (Duplikate vermeiden).
- Optional: Schlage passende Labels vor (z. B. bug, enhancement).

Tipp: Ein kleines, reproduzierbares Beispiel oder klare Akzeptanzkriterien helfen enorm.

---

## 2) Branches benennen
Erstelle für jede Änderung einen neuen Branch. Nutze die folgende Konvention (kebab-case):
- feat/<kurze-beschreibung>
- fix/<kurze-beschreibung>
- docs/<kurze-beschreibung>
- chore/<kurze-beschreibung>
- refactor/<kurze-beschreibung>
- test/<kurze-beschreibung>

Wenn es ein zugehöriges Issue gibt, füge die Nummer hinzu:
- feat/123-kurze-beschreibung

Beispiele:
- feat/landing-page-cta
- fix/null-pointer-on-login
- docs/update-readme-contributing

---

## 3) Commits nach Conventional Commits
Nutze klare Commit-Nachrichten im Format:

<type>(optional-scope)!: kurze, prägnante Beschreibung

Gängige Typen:
- feat: neue Funktion oder Erweiterung
- fix: Bugfix
- docs: nur Dokumentation
- chore: Wartung, Build, Konfiguration
- refactor: Code-Umstrukturierung ohne Feature-/Bug-Verhalten zu ändern
- test: Tests hinzufügen/ändern
- style: Formatierung, Linting ohne Logikänderung
- perf: Performance-Verbesserungen
- build/ci: Build-/CI-Anpassungen
- revert: eine Änderung zurücknehmen

Beispiele:
- feat(auth): passwortloses Login hinzufügen
- fix(api): 500-Fehler bei leerem Token beheben
- docs: README um Installationshinweise ergänzt

Optionaler Body (Warum/Wie) und Footer (z. B. Closes #123) sind willkommen:
- Body: Hintergrund, Trade-offs, Breaking Changes kurz erklären
- Footer: Closes #123, Relates to #456

---

## 4) Pull Requests stellen
Wenn deine Änderungen bereit sind:
1. Push deinen Branch und öffne einen Pull Request (PR).
2. Nutze die PR-Vorlage (kurze Beschreibung, verknüpfte Issues).
3. Checkliste durchgehen:
   - Tests erfolgreich (lokal/CI)
   - Dokumentation aktualisiert (README/Kommentare)
   - Keine Breaking Changes – oder klar dokumentiert
4. Verknüpfe das Issue im PR (z. B. „Closes #123”).
5. Halte PRs klein und fokussiert. Große PRs gerne in Teilstücke aufteilen.
6. Markiere als Draft, wenn du frühes Feedback möchtest.

Tipp: PR-Titel kann dem Conventional-Commit-Stil folgen, z. B. „feat: …”.

---

## 5) Typischer Workflow (Kurz)
1. Issue auswählen/erstellen
2. Branch anlegen: `feat/<beschreibung>` oder `fix/<beschreibung>`
3. Änderungen umsetzen, Commits im Conventional-Format
4. PR öffnen, Vorlage ausfüllen, Checks beachten
5. Review anfordern, Feedback einarbeiten, mergen

---

Fragen? Erstelle ein Issue mit dem Label „question” oder starte eine Diskussion – wir helfen gern weiter.
