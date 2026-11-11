---
typ: feature-fortschritt
id: "umzug-vertrag-mitnehmen"
feature: "Umzug – Vertrag mitnehmen"
figma_page: "Feature: Umzug – Vertrag mitnehmen"
fortschritt_ki: 29
kriterien_erfuellt: "1 von 5"
freigabe: keine
quelle: theydo-simulation/features.json
erzeugt_von: fortschritt-workflow
bewertung_von: ki
zuletzt_geaendert: 2026-11-11
---

# Umzug – Vertrag mitnehmen

> **Ziel:** Mehr Kund:innen nehmen ihren Vertrag beim Umzug mit, weil sie den Weg in der App finden und die Fristen kennen.

**Fortschritt laut KI:** `███░░░░░░░` **29 %** · 1 von 5 Kriterien erfüllt

**Freigabe:** Nächste Freigabe bei 50 %

Der Einstieg in den Umzug ist sichtbar, aber zentrale Schritte wie Frist, Formular, Zählerstand und Bestätigung sind in den gelieferten Screens noch nicht umgesetzt.

> **Datenvertrag:** Der Status je Kriterium ist eine KI-Bewertung der aktuellen Screens (Hypothese).
> Verbindlich fertig ist ein Feature erst nach Freigabe durch UX per Pull Request.

## Kriterien

| ID | Kriterium | Gewicht | Status | Begründung | Screens |
|---|---|---|---|---|---|
| AC1 | Im Vertragsbereich gibt es einen klar erkennbaren Einstieg 'Ich ziehe um'. | 1 | ✅ erfüllt | Im Vertragsbereich ist ein klar benannter Einstieg „Ich ziehe um“ sichtbar, inklusive erklärendem Untertext zur Vertragsmitnahme. Der Screen gehört eindeutig zum Vertragsbereich. | [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md) |
| AC2 | Es wird erklärt, dass der Vertrag mitgenommen werden kann und bis wann der Umzug gemeldet werden muss. | 2 | ⚠️ teilweise | Es wird erklärt, dass der Vertrag mitgenommen werden kann („ohne neuen Vertrag“ / „Vertrag an deine neue Adresse mitnehmen“). Eine Frist oder bis wann der Umzug gemeldet werden muss, ist in den Screens nicht ersichtlich. | [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md), [UM-02 – Umzug melden (WIP)](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden-wip.md) |
| AC3 | Nutzer:innen können neue Adresse und Umzugsdatum eingeben. | 2 | ❌ offen | Auf dem WIP-Screen steht nur ein Platzhalter „TODO: Formular für neue Adresse & Umzugsdatum“. Eingabefelder oder konkrete Erfassung der Daten sind nicht gezeigt. | [UM-02 – Umzug melden (WIP)](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden-wip.md) |
| AC4 | Der Zählerstand bei Auszug kann im Ablauf erfasst werden. | 1 | ❌ offen | In den Screens gibt es keinen Hinweis auf die Erfassung eines Zählerstands beim Auszug. Ein entsprechendes Feld oder Schritt ist nicht sichtbar. | [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md), [UM-02 – Umzug melden (WIP)](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden-wip.md) |
| AC5 | Ein Bestätigungsscreen fasst zusammen, was als Nächstes passiert. | 1 | ❌ offen | Ein Bestätigungsscreen oder eine Zusammenfassung der nächsten Schritte ist nicht vorhanden. Der gezeigte Umzugs-Screen endet bei einem „Weiter“-Button ohne Abschlusszustand. | [UM-02 – Umzug melden (WIP)](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden-wip.md) |

Gewichtung: erfüllt zählt voll, teilweise halb, offen gar nicht.

## Bitte selbst prüfen

- Prüfen, ob die Frist zum Umzugsmelden fachlich korrekt und gut sichtbar im Flow platziert ist.
- Prüfen, ob nach „Weiter“ tatsächlich ein Formular- bzw. Bestätigungsschritt folgt, der hier nur nicht im Figma-Ausschnitt enthalten ist.
- Prüfen, ob für den Umzug auch ein Zählerstand-Auszugsschritt vorgesehen ist, obwohl er in den Screens fehlt.

## Screens im Flow „Feature: Umzug – Vertrag mitnehmen“

- [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md)
- [UM-02 – Umzug melden (WIP)](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden-wip.md)
