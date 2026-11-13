# MU Media Cockpit · AT CH SI

Klickbarer Prototyp eines Media-Monitoring-Cockpits für die Management Unit
Österreich, Schweiz, Slowenien. Gebaut für eine Live-Präsentation:
**alle Werte sind Dummy-Daten** (Indexwerte und Prozent, keine Euro).

## Live stellen (GitHub Pages)

1. Neues Repository anlegen (z. B. `mu-media-cockpit`), `index.html` und diese README hochladen.
2. Im Repository: **Settings → Pages → Branch: `main`, Ordner: `/ (root)` → Save**.
3. Nach etwa einer Minute läuft die Seite unter `https://<benutzername>.github.io/mu-media-cockpit/`.

Tipp fürs Gespräch: Die Datei läuft auch **ohne Internet**, einfach `index.html`
per Doppelklick lokal im Browser öffnen. GitHub Pages als Zweitweg, lokal als Erstweg.

## Bedienung in der Präsentation

| Aktion | Taste / Klick |
| --- | --- |
| Ansichten Überblick · Messen · Verbessern · Scorecard | `1` `2` `3` `4` |
| Markt durchschalten (MU → AT → CH → SI) | `M` oder Klick oben |
| Budget umschichten | Regler in Ansicht 3, Summe bleibt 100 % |
| Simulation zurücksetzen | „Zurücksetzen“ in Ansicht 3 |
| Meilensteine | Klick auf die Punkte in Ansicht 4 |

Empfohlener Klickpfad (ca. 6 Min.): Überblick MU → Frage ans Panel „Welchen Markt
sehen wir uns an?“ → Markt wechseln → `2` Messen (Kampagne zeigen, Blase hovern)
→ `3` Verbessern (10 Punkte von TV zu Online-Video schieben, Reichweite steigt)
→ `4` Scorecard (Tag 90, dann Monat 12) → Schlusssatz auf der Scorecard.

## Technik

- Eine einzige `index.html`, kein Framework, keine externen Abhängigkeiten, keine Fonts von Drittservern.
- Chartfarben CVD-geprüft (Farbfehlsichtigkeit); jede Grafik hat Tooltip **und** „Werte als Tabelle“.
- Animationen respektieren `prefers-reduced-motion`; Bedienung komplett per Tastatur möglich.
- Responsiv bis Smartphone-Breite.

Prototyp, privat erstellt von Christoph Glöckel. Keine offiziellen Marken-Assets,
kein Logo; die Akzentfarbe ist dem öffentlichen Markenauftritt nachempfunden.
