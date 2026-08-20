# Copilot Instructions

Be ruthless in creative quality standards and editorial feedback. Ziel: den bestmöglichen Roman schreiben, in allen Rollen gemäß `00 - General/Plan.md`. Änderungen an bestehendem Manuskript-/Referenztext immer erst als Vorschlag zur Freigabe, dann ausführen.

## Projektkontext
Buchprojekt **„Terms of Residence"** — Urban Fantasy mit schwarzer Komödie und Slice-of-Life; Ensemble ohne Auserwählten; Progression = Erkenntnis. Das Manuskript wird auf **Englisch** verfasst.

## Sprache & Prioritäten
1. **Manuskripttext immer auf Englisch (US-Rechtschreibung, Oxford-Komma; s. Writing Rule 50).**
2. **Meta-Kommunikation (Feedback, Fragen, Diskussion) auf Deutsch**, außer bei expliziter Bitte um Englisch.
3. Bei Regel-Widerspruch gilt: **Writing Rules > Style DNA > alle anderen Dateien.**

## Kanonische Architektur

`.github/instructions/Core/`
enthält global geltende Writing Rules und Style DNA.

`.github/instructions/Characters/`
enthält je Figur genau eine vollständige kanonische Character-Datei.
Wenn eine Figur relevant ist, konsultiere ihre vollständige Datei.

`.github/instructions/Story/`
enthält Premise, System, Story Principles, Folklore, Timeline, projektspezifische Schreibregeln sowie Master- und Part-Outlines.
Konsultiere die für die aktuelle Aufgabe relevanten Story-Dateien.

### Trennung von Wahrheit / Wissen / Leserwissen (nie vermischen)
- **Objektive Wahrheit** über das System → `Story/system.instructions.md`.
- **Was eine Figur weiß/glaubt** → die jeweilige `Characters/…`-Datei.
- **Was der Leser wann erfährt** → die jeweilige `Story/part-*.instructions.md`.

## Autoritäts-Hierarchie (Source of Truth)
1. Aktuelle kanonische Repository-Instruction/-Datei.
2. Explizite aktuelle Nutzer-Anweisung.
3. Aktueller Planungsstand / offene Entscheidungen.
4. Session-Memory.

**Repository-Inhalt schlägt veralteten erinnerten Session-Kontext.** Wenn sich eine Information während der Session geändert haben könnte, die aktuelle Repository-Datei **neu lesen** — nicht auf eine früher erinnerte Version verlassen. Keine versteckten Doppel-Versionen pflegen.

## Kernprinzipien
- Sofern die Stilregeln nichts anderes sagen: **Melodrama, Sentimentalität, Übertreibung vermeiden.**
- **Invisible Writing (Writing Rules P11–P12) ist oberste Schreib-Priorität:** Die Architektur darf man im Text nicht fühlen („Kunst, die nicht gemacht wirkt").

## Output-Länge
Die Szene trägt die Länge, die sie braucht, um ihre Funktion zu erfüllen. Es gibt keine Mindest- oder Höchstlänge pro Szene.

## Formatierung
Verwende Markdown-Formatierung.

## Arbeitsweise
- Bei bestehendem Manuskript-/Referenztext: **Änderungen erst vorschlagen, nach Bestätigung ausführen.** Neue Kapitel eigenständig schreiben, sofern alle benötigten Informationen vorliegen.
- Nach dem Schreiben eines Kapitels/einer Szene: gegen **Writing Rules** und **Style DNA** prüfen, bevor du sie zur Überprüfung vorlegst.
- Bei Unsicherheit: **nachfragen statt raten.**
- UTF-8 annehmen (teils mit BOM, meist ohne).
- Falls eine benötigte kanonische Datei nicht existiert oder leer ist, gemeinsam mit mir erstellen — vorher nach Details fragen.
- Neue Informationen, die du während der Arbeit entdeckst, in die **passende kanonische Instruction-Datei** einpflegen (Figur → Character-Datei; objektive Mechanik → `system`; Struktur → `master-outline`/`part-*`). Bei Unsicherheit über den Ort: nachfragen.
- `00 - General/Plan.md` (Rollen, Phasen, Workflow) bleibt als **Prozess-Referenz** erhalten; die Story-Kanon-Inhalte liegen ausschließlich in `.github/instructions/`.