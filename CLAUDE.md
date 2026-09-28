# Home Assistant

Dieses Repository dient ausschließlich der Arbeit an meinem Home Assistant (Automationen, Helfer,
Skripte, Dashboards, Geräte). Es hat nichts mit anderen Projekten zu tun – bitte keine anderen
Repos oder Themen hier vermischen.

## Grundregeln

- Vor groesseren Aenderungen immer zuerst kurz sagen, was geplant ist, und um Bestaetigung bitten,
  bevor etwas in Home Assistant tatsaechlich geaendert wird.
- Vor dem Erstellen von Automationen oder Helfern immer zuerst den ha-mcp Best-Practices-Skill
  laden.
- Wo moeglich native HA-Konstrukte nutzen (Trigger, Bedingungen, Helfer) statt Jinja2-Templates.
- Kurz zeigen, was geplant ist, bevor es umgesetzt wird.

## Mein System

- Home Assistant OS 2026.5.1, Nabu Casa.
- Sprache: Deutsch. Alle Entities und Automationen sind auf Deutsch benannt.
- Friendly Names sollen sinnvoll und leicht verstaendlich formuliert sein. Entity-IDs stimmen mit
  dem Friendly Name ueberein, Umlaute werden dabei ersetzt (ä→ae, ö→oe, ü→ue, ß→ss).

## Ordnung im System

- Neue Automationen und Entitaeten immer passenden Bereichen und Kategorien zuweisen. Falls noch
  keine passenden existieren, welche anlegen. Ein uebersichtliches, sortiertes System ist mir sehr
  wichtig.
- Passende Icons bei Automationen, Kategorien und Helfern setzen.
- Nutzt eine geaenderte Sache (z. B. eine Entity-ID) noch an anderen Stellen, das konsistent
  mitanpassen oder mich ueber noetige weitere Aenderungen informieren.
- In Automationen, Skripten usw. immer Entitaets-IDs verwenden (nicht device_id), damit die
  Steuerung auch nach einem Re-Pairing problemlos weiterfunktioniert.
