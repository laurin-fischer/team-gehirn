---
typ: feature-fortschritt
id: "zaehlerstand-abgeben"
feature: "Zählerstand abgeben"
figma_page: "Feature: Zählerstand abgeben"
fortschritt_ki: 100
kriterien_erfuellt: "5 von 5"
freigabe: ausstehend
quelle: theydo-simulation/features.json
erzeugt_von: fortschritt-workflow
bewertung_von: ki
zuletzt_geaendert: 2026-11-11
---

# Zählerstand abgeben

> **Ziel:** Kund:innen geben ihren Zählerstand einfach und fehlerfrei in der App ab (Kern-Feature der App).

**Fortschritt laut KI:** `██████████` **100 %** · 5 von 5 Kriterien erfüllt

**Freigabe:** [Freigabe für 100 % bei UX angefragt](https://github.com/laurin-fischer/team-gehirn/pulls?q=is%3Apr+head%3Afreigabe%2Fzaehlerstand-abgeben%2F100%2F04b736d8)

Das Feature ist auf dem gezeigten Screen weitgehend vollständig umgesetzt, alle fünf Acceptance Criteria sind sichtbar abgedeckt.

> **Datenvertrag:** Der Status je Kriterium ist eine KI-Bewertung der aktuellen Screens (Hypothese).
> Verbindlich fertig ist ein Feature erst nach Freigabe durch UX per Pull Request.

## Kriterien

| ID | Kriterium | Gewicht | Status | Begründung | Screens |
|---|---|---|---|---|---|
| AC1 | Der Zähler wird mit Zählernummer und letzter Ablesung angezeigt. | 1 | ✅ erfüllt | Der Screen zeigt den Zähler mit Zählernummer sowie die letzte Ablesung inklusive Datum und letztem Zählerstand. Damit ist das Kriterium klar abgedeckt. | [ZS-01 – Zählerstand erfassen](../screens/feature-zaehlerstand-abgeben/zs-01-zaehlerstand-erfassen.md) |
| AC2 | Der Zählerstand kann per Kamera gescannt werden. | 2 | ✅ erfüllt | Es gibt die Aktion „Zähler scannen“ und den Text, dass die Kamera den Zählerstand automatisch erkennt. Das belegt die Scan-Funktion per Kamera. | [ZS-01 – Zählerstand erfassen](../screens/feature-zaehlerstand-abgeben/zs-01-zaehlerstand-erfassen.md) |
| AC3 | Alternativ ist eine manuelle Eingabe möglich, mit Hinweis auf den plausiblen Wertebereich. | 2 | ✅ erfüllt | Neben dem Scan gibt es ausdrücklich die manuelle Eingabe des Zählerstands sowie den Hinweis auf einen plausiblen Wertebereich. Beides ist sichtbar. | [ZS-01 – Zählerstand erfassen](../screens/feature-zaehlerstand-abgeben/zs-01-zaehlerstand-erfassen.md) |
| AC4 | Das Ablesedatum ist sichtbar und änderbar. | 1 | ✅ erfüllt | Das Ablesedatum wird angezeigt und es gibt eine eigene Datumsauswahl für die Änderung. Damit ist Sichtbarkeit und Änderbarkeit erkennbar. | [ZS-01 – Zählerstand erfassen](../screens/feature-zaehlerstand-abgeben/zs-01-zaehlerstand-erfassen.md) |
| AC5 | Vor dem Absenden wird erklärt, was nach der Übermittlung passiert. | 1 | ✅ erfüllt | Vor dem Absenden steht ein Hinweis, was nach der Übermittlung passiert: „Dein Abschlag wird nach der Übermittlung automatisch geprüft.“ Das erklärt den nächsten Schritt klar genug. | [ZS-01 – Zählerstand erfassen](../screens/feature-zaehlerstand-abgeben/zs-01-zaehlerstand-erfassen.md) |

Gewichtung: erfüllt zählt voll, teilweise halb, offen gar nicht.

## Bitte selbst prüfen

- Prüfen, ob der Kamerascan technisch wirklich gestartet werden kann und nicht nur als Text/Platzhalter dargestellt ist.
- Prüfen, ob die manuelle Eingabe mit dem plausiblen Bereich auch validiert wird, also bei falschen Werten eine Rückmeldung erscheint.
- Prüfen, ob das Ablesedatum tatsächlich änderbar ist und welche Auswahloptionen bzw. Einschränkungen es gibt.

## Screens im Flow „Feature: Zählerstand abgeben“

- [ZS-01 – Zählerstand erfassen](../screens/feature-zaehlerstand-abgeben/zs-01-zaehlerstand-erfassen.md)
