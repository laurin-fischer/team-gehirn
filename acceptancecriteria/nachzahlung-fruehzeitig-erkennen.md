---
typ: feature-fortschritt
id: "nachzahlung-fruehzeitig-erkennen"
feature: "Nachzahlung frühzeitig erkennen"
figma_page: "Feature: Nachzahlung frühzeitig erkennen"
fortschritt_ki: 69
kriterien_erfuellt: "2 von 5"
freigabe: ausstehend
quelle: theydo-simulation/features.json
erzeugt_von: fortschritt-workflow
bewertung_von: ki
zuletzt_geaendert: 2026-11-11
---

# Nachzahlung frühzeitig erkennen

> **Ziel:** Kund:innen erkennen früh, dass eine Nachzahlung droht, verstehen den Grund und können direkt gegensteuern.

**Fortschritt laut KI:** `███████░░░` **69 %** · 2 von 5 Kriterien erfüllt

**Freigabe:** [Freigabe für 50 % bei UX angefragt](https://github.com/laurin-fischer/team-gehirn/pulls?q=is%3Apr+head%3Afreigabe%2Fnachzahlung-fruehzeitig-erkennen%2F50%2F7c117116)

Die Nachzahlungswarnung und die Erklärung sind sichtbar umgesetzt, die Abschlagsanpassung ist nur teilweise belegt, und Erinnerungen fehlen in den Screens.

> **Datenvertrag:** Der Status je Kriterium ist eine KI-Bewertung der aktuellen Screens (Hypothese).
> Verbindlich fertig ist ein Feature erst nach Freigabe durch UX per Pull Request.

## Kriterien

| ID | Kriterium | Gewicht | Status | Begründung | Screens |
|---|---|---|---|---|---|
| AC1 | Auf der Übersicht erscheint ein gut sichtbarer Hinweis, wenn die Prognose eine Nachzahlung erwarten lässt. | 2 | ✅ erfüllt | Auf der Übersicht ist ein klarer, gut sichtbarer Hinweis zur drohenden Nachzahlung vorhanden: „Voraussichtlich ca. 96 € Nachzahlung“ plus erklärender Warntext. Das ist direkt auf dem Übersichts-Screen platziert. | [NZ-01 – Übersicht mit Nachzahlungs-Hinweis](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-01-uebersicht-mit-nachzahlungs-hinweis.md) |
| AC2 | Ein Detailscreen zeigt die erwartete Nachzahlung als Betrag und erklärt den Grund (z. B. gestiegener Verbrauch). | 2 | ✅ erfüllt | Der Detailscreen zeigt die erwartete Nachzahlung als Betrag („96 €“) und nennt den Grund („Seit Juni verbrauchst du rund 12 % mehr Strom als im Vorjahr“). Damit sind Betrag und Erklärung sichtbar umgesetzt. | [NZ-02 – Nachzahlung erklärt](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-02-nachzahlung-erklaert.md) |
| AC3 | Von dort führt ein direkter Weg zur Abschlagsanpassung, inklusive eines konkret empfohlenen neuen Abschlags. | 2 | ⚠️ teilweise | Es gibt einen direkten Weg zur Abschlagsanpassung über den Button „Abschlag anpassen“ und den Hinweis „Anpassen“ auf der Übersicht. Ein konkret empfohlener neuer Abschlag wird in den Screens aber nicht angezeigt. | [NZ-01 – Übersicht mit Nachzahlungs-Hinweis](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-01-uebersicht-mit-nachzahlungs-hinweis.md), [NZ-02 – Nachzahlung erklärt](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-02-nachzahlung-erklaert.md) |
| AC4 | Nutzer:innen können eine Erinnerung oder Benachrichtigung für künftige Nachzahlungs-Warnungen einstellen. | 1 | ❌ offen | In den gelieferten Screens ist keine Einstellung, Option oder Navigation für eine Erinnerung bzw. Benachrichtigung zu künftigen Nachzahlungs-Warnungen zu sehen. | [NZ-01 – Übersicht mit Nachzahlungs-Hinweis](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-01-uebersicht-mit-nachzahlungs-hinweis.md), [NZ-02 – Nachzahlung erklärt](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-02-nachzahlung-erklaert.md) |
| AC5 | Alle Texte sind ohne Fachbegriffe verständlich (kein Energie- oder Buchhaltungsjargon). | 1 | ⚠️ teilweise | Die Texte wirken überwiegend verständlich und sachlich. Ob wirklich kein Fachjargon verwendet wird, lässt sich aber nicht sicher bestätigen, weil Begriffe wie „Prognose“, „Saldo“ und „Abschlag“ vorkommen und keine Tonalitätsrichtlinie vorliegt. | [NZ-01 – Übersicht mit Nachzahlungs-Hinweis](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-01-uebersicht-mit-nachzahlungs-hinweis.md), [NZ-02 – Nachzahlung erklärt](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-02-nachzahlung-erklaert.md) |

Gewichtung: erfüllt zählt voll, teilweise halb, offen gar nicht.

## Bitte selbst prüfen

- Prüfen, ob der Button „Abschlag anpassen“ tatsächlich zu einer Anpassungsfunktion führt und ob dort ein konkret empfohlener neuer Abschlag vorgeschlagen wird.
- Prüfen, ob es in der App eine Stelle für Erinnerungen/Benachrichtigungen zu Nachzahlungs-Warnungen gibt, die in den Screens nicht sichtbar ist.
- Prüfen, ob die Begriffe „Prognose“, „Saldo“ und „Abschlag“ für die Zielgruppe ausreichend verständlich sind oder vereinfacht werden sollten.

## Screens im Flow „Feature: Nachzahlung frühzeitig erkennen“

- [NZ-01 – Übersicht mit Nachzahlungs-Hinweis](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-01-uebersicht-mit-nachzahlungs-hinweis.md)
- [NZ-02 – Nachzahlung erklärt](../screens/feature-nachzahlung-fruehzeitig-erkennen/nz-02-nachzahlung-erklaert.md)
