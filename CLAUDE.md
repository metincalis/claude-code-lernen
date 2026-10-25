# CLAUDE.md

Regeln für Claude Code in diesem Repo. Claude liest diese Datei zu Beginn jeder Sitzung.

## Worum es geht

Lernprojekt: Ich lerne Schritt für Schritt Webentwicklung (HTML, CSS, später JavaScript und GSAP) und das Arbeiten mit Claude Code, Git und GitHub.

## Mein Stand

- HTML/CSS: solide, aber nicht perfekt
- JavaScript: Anfänger
- GSAP: kenne ich, wende es noch nicht an
- Rechner: Intel-iMac

## Wie du mit mir arbeitest

- Antworte auf Deutsch, locker, aber präzise – Antwort zuerst, kurz und strukturiert.
- Erkläre mit Analogien, Alltagsbeispielen und Ursache-Wirkung, Schritt für Schritt.
- Fachbegriffe beim ersten Auftreten kurz erklären.
- Code immer kommentieren: nicht nur *was* eine Zeile tut, sondern *warum*.
- Bei größeren Aufgaben erst Ziel und Umfang klären, dann umsetzen.
- Ehrlich widersprechen, wenn ich falschliege, und Risiken offen nennen.

## Projektaufbau

- `uebungen/` – eine Datei pro Lektion, Namensschema `lektion-<nummer>.html`
- `css/style.css` – gemeinsames Stylesheet; jede Übung bindet es mit `<link rel="stylesheet" href="../css/style.css">` ein, statt eigenes `<style>` zu schreiben
- `README.md` – Überblick und Lernfortschritt; nach jeder neuen Lektion die Checkliste ergänzen

## Konventionen

- Reines HTML/CSS ohne Build-Tools, Frameworks oder Server – jede Datei muss per Doppelklick im Browser funktionieren.
- HTML-Dateien: `<!doctype html>`, `lang="de"`, `charset="utf-8"`, `viewport`-Meta, `<title>`.
- Dateinamen ohne Umlaute und Leerzeichen (z. B. `uebungen`, nicht `Übungen`).
- Commit-Nachrichten auf Deutsch, kurz und beschreibend.
