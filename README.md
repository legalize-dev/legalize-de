# Legalize — Deutschland

> **Early stage** — This repository is under active development. File structure, commit history, and content may undergo significant changes, including full regeneration. Do not build tooling against the current layout without expecting breaking changes.
>
> **Frühphase** — Dieses Repository befindet sich in aktiver Entwicklung. Dateistruktur, Commit-Verlauf und Inhalte können sich erheblich ändern, einschließlich vollständiger Neugenerierung. Bauen Sie keine Tools auf der aktuellen Struktur auf, ohne mit grundlegenden Änderungen zu rechnen.

Konsolidierte deutsche Bundesgesetzgebung in Markdown, versioniert mit Git.

Jedes Gesetz ist eine Datei. Jede Änderung ist ein Commit.

Teil des Projekts [Legalize](https://github.com/legalize-dev/legalize) · [legalize.dev](https://legalize.dev)

## Struktur

```
de/
  GG.md                      — Grundgesetz
  BGB.md                     — Bürgerliches Gesetzbuch
  STGB.md                    — Strafgesetzbuch
  HGB.md                     — Handelsgesetzbuch
  ...
```

Der normative Rang (Grundgesetz, Bundesgesetz, Rechtsverordnung, Bekanntmachung) steht im YAML-Frontmatter jeder Datei, nicht in der Verzeichnisstruktur.

## Quelle

Daten von [gesetze-im-internet.de](https://www.gesetze-im-internet.de/), bereitgestellt durch das BMJ (Bundesministerium der Justiz) über juris GmbH. Öffentlich zugänglich, keine Registrierung erforderlich.

## Format

Jede Datei enthält:

- **YAML-Frontmatter**: Metadaten (Titel, Kennung, Datum, Rechtsstatus, BGBl-Referenz)
- **Markdown-Inhalt**: konsolidierter Text mit hierarchischer Gliederung

## Lizenz

Die Gesetzestexte sind gemeinfrei. Die Strukturierung und Formatierung stehen unter der [MIT](LICENSE)-Lizenz.

---

Erstellt von [Enrique Lopez](https://enriquelopez.eu) · [legalize.dev](https://legalize.dev)
