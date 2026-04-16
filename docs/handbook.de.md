# Handbuch (DE) – Alby Hub Home Assistant Add-on & Integration

## Zielversion und Kompatibilität

- Minimale unterstützte Home-Assistant-Version (2026.x): **2026.1**
- Gilt für Add-on und geplante HACS-Integration im MVP.

<a id="support-matrix-de"></a>
## Support-Matrix (MVP)

| Installationsart | Support-Status | Einschränkungen |
|---|---|---|
| Home Assistant OS | Unterstützt | Voller Supervisor-/Add-on-Flow empfohlen |
| Home Assistant Supervised | Unterstützt | Add-on-Funktion abhängig von sauberem Supervisor-Setup auf dem Host |
| Home Assistant Container | Unterstützt (eingeschränkt) | Kein nativer Add-on-Store/Supervisor; Nutzung primär über HACS-Integration und externe Dienste |

<a id="setup-tests-de"></a>
## Setup-Tests im Wizard

### Pflichttests
- Verbindungscheck (Hub/NWC erreichbar)
- Scope-Check (erforderliche Berechtigungen vorhanden)

### Optionaler Test
- 1-sat Live-Testzahlung (optional sichtbar, nicht verpflichtend)
- Immer mit kurzer Risiko-/Kosten-Erklärung

## Verhalten bei Testfehlern

- MVP-Regel: **Mit Warnung fortfahren** ist erlaubt.
- Fehler in optionalen Schritten blockieren den Abschluss nicht.
- Pflichttest-Fehler werden klar angezeigt; Nutzer kann trotzdem mit Warnhinweis abschließen.

## UX-Texte im Setup

- Inline-Erklärungen im Kurzmodus (1–2 Sätze)
- Pro Schritt ein „Mehr erfahren“-Link auf den passenden Handbuch-Abschnitt

## Sprache im MVP

- Verbindlich: **DE + EN** für Config-/Options-Flow
- Weitere Sprachen (z. B. FR, ES) folgen in späteren Releases

## HACS-Release-Policy

- Start bei Version **0.0.0**
- Versionsschema: **x.y.z**
  - `z` = pre-release
  - `y` = release
  - `x` = major release
- Jede Veröffentlichung mit Release Notes und Kompatibilitätshinweis
