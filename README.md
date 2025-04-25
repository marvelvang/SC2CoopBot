# SC2CoopBot

Ein unterstützender Bot für **Starcraft 2**, der gemeinsam mit einem menschlichen Spieler die Steuerung übernimmt.  
Das Ziel ist eine semi-automatische Koordination von Einheiten, Gebäuden und allgemeinen Spielabläufen — durch Chat-Kommandos steuerbar.

---

## Vision
- Der Bot unterstützt den Spieler, übernimmt aber **keine vollständige Kontrolle**.
- Aufgabenverteilung zwischen Mensch und Bot ("Kooperatives Spielen").
- Der Bot lernt langfristig durch Beobachtung und Verbesserungsvorschläge.

---

## Git Workflow Konventionen

### Branching Modell
- Wir verwenden **GitHub Flow**.
- Neue Features oder Fixes entstehen immer in eigenen Branches:
  - `feature/<beschreibung>`
  - `bugfix/<beschreibung>`
  - `docs/<beschreibung>`
  - `chore/<beschreibung>`
  - `refactor/<beschreibung>`

### Merge Strategie
- **Nur Merge-Commits ("Create a merge commit")** beim Mergen in `main`.
- **Keine** Fast-Forward-Merges (`--no-ff`).
- Jeder Merge soll einen klaren, nachvollziehbaren Abschluss eines Themas zeigen.

### Commit Stil
- Kurze, präzise Commit-Nachrichten (im Präsens).
- Beispiel: `Add basic chat command parsing`
- Feature-Branches sollten aufgeräumt sein (lokale Rebase-Squashs bei Bedarf erlaubt).

### Pull Requests
- Jeder Merge in `main` erfolgt über einen Pull Request.
- PRs müssen überprüft werden (Selbstcheck oder Review durch andere).

---

## Setup Hinweise

- Projekt-Sprache: **C#**
- IDE-Empfehlung: Visual Studio Code, Rider oder Visual Studio 2022+
- Versionierung: Git, GitHub Flow
- Coding Style: `.editorconfig` ist vorhanden und sollte respektiert werden.

---

## Dateien im Projekt

| Datei/Ordner         | Beschreibung                               |
|:---------------------|:------------------------------------------|
| `.editorconfig`       | Standardisierte Code-Style Regeln         |
| `.gitattributes`      | Definiert Line-Endings und Textbehandlungen |
| `docs/roadmap.md`     | Geplante Features und Projektmeilensteine |

---

## Lizenz

(Platzhalter — später ergänzen)