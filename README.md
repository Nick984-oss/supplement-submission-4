# Online-Supplement: Reifegradmodell für digitale Souveränität in föderierten Bildungsökosystemen

Version 1.0 - September 2026

Dieses Repository enthält das anonymisierte ergänzende Material zur Herleitung und konzeptionellen Ex-ante-Evaluation des im Beitrag beschriebenen Reifegradmodells. Das Supplement erweitert die im Haupttext notwendigerweise komprimierte Darstellung, ersetzt den Haupttext jedoch nicht.

## Primäre Dateien

- `supplement/Supplementary_Material.pdf` - gesetzte, zitierfähige Gesamtfassung.
- `supplement/Supplementary_Material.tex` - vollständig editierbare LaTeX-Quelle.
- `supplement/references.bib` - Literaturdatenbank für die LaTeX-Fassung.
- `supplement/S1_Coding_Item_Traceability.csv` - maschinenlesbare Traceability-Tabelle.

Die zusätzlichen Markdown-Dateien enthalten dieselben fachlichen Inhalte in einer leicht prüfbaren Textdarstellung.

## Inhalt

- **S1 - Codierleitfaden und Item-Traceability:** Dokumentation des final konsolidierten Codesystems sowie der Rückverfolgbarkeit von Literaturankern über Dimensionen und Kriterien bis zu den 18 Self-Assessment-Items.
- **S2 - Protokoll der Taxonomieentwicklung:** Rekonstruktion der erhaltenen Entwicklungsstände, Konsolidierungsentscheidungen und Qualitätsprüfung der Taxonomie.
- **S3 - Erweiterte Ex-ante-Evaluation:** Ausführliche Traceability-Prüfung der sechs Designanforderungen gegen die Komponenten des Artefakts.

## Methodischer Status

Das Supplement dokumentiert die **konzeptionelle Herleitung und interne Traceability** des Artefakts. Es stellt weder eine empirische Evaluation realer Bildungsorganisationen noch einen psychometrischen Validitätsnachweis dar. Ein vollständiges historisches Recherche- und Screeningprotokoll ist nicht Bestandteil des Supplements; es werden keine nachträglich geschätzten Screeningzahlen ausgewiesen.

## Reproduzierbarer PDF-Build

Voraussetzung ist eine LaTeX-Installation mit LuaLaTeX, `latexmk`, `biber`, `tabularray`, `tcolorbox` und `biblatex`.

```bash
cd supplement
latexmk -lualatex -interaction=nonstopmode -halt-on-error Supplementary_Material.tex
```

Alternativ:

```bash
make pdf
```

Die PDF enthält keine eingebetteten Rasterbilder; sämtliche Tabellen und Gestaltungselemente sind nativ in LaTeX gesetzt.

## Zitierhinweis im Manuskript

Im Manuskript kann auf die einzelnen Bestandteile mit „Online-Supplement, S1“, „Online-Supplement, S2“ und „Online-Supplement, S3“ verwiesen werden. Der durch Anonymous GitHub erzeugte Link ist an den vorgesehenen Stellen im Haupttext einzusetzen.
