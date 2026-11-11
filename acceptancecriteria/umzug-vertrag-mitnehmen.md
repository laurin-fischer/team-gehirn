---
typ: feature-fortschritt
id: "umzug-vertrag-mitnehmen"
feature: "Umzug – Vertrag mitnehmen"
figma_page: "Feature: Umzug – Vertrag mitnehmen"
fortschritt_ki: 71
kriterien_erfuellt: "3 von 5"
freigabe: ausstehend
quelle: theydo-simulation/features.json
erzeugt_von: fortschritt-workflow
bewertung_von: ki
zuletzt_geaendert: 2026-11-11
---

# Umzug – Vertrag mitnehmen

> **Ziel:** Mehr Kund:innen nehmen ihren Vertrag beim Umzug mit, weil sie den Weg in der App finden und die Fristen kennen.

**Fortschritt laut KI:** `███████░░░` **71 %** · 3 von 5 Kriterien erfüllt

**Freigabe:** [Freigabe für 50 % bei UX angefragt](https://github.com/laurin-fischer/team-gehirn/pulls?q=is%3Apr+head%3Afreigabe%2Fumzug-vertrag-mitnehmen%2F50%2Fed32928c)

Der Umzugs-Flow ist mit Einstieg, Erklärung sowie Eingabe von Adresse und Datum weitgehend sichtbar, aber Zählerstand und Bestätigungszusammenfassung fehlen in den Screens.

> **Datenvertrag:** Der Status je Kriterium ist eine KI-Bewertung der aktuellen Screens (Hypothese).
> Verbindlich fertig ist ein Feature erst nach Freigabe durch UX per Pull Request.

## Kriterien

| ID | Kriterium | Gewicht | Status | Begründung | Screens |
|---|---|---|---|---|---|
| AC1 | Im Vertragsbereich gibt es einen klar erkennbaren Einstieg 'Ich ziehe um'. | 1 | ✅ erfüllt | Im Vertragsbereich ist der Einstieg „Ich ziehe um“ sichtbar, inklusive Hinweis „Vertrag an deine neue Adresse mitnehmen“. Das ist klar als Umzugs-Einstieg erkennbar. | [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md) |
| AC2 | Es wird erklärt, dass der Vertrag mitgenommen werden kann und bis wann der Umzug gemeldet werden muss. | 2 | ✅ erfüllt | Der Flow erklärt, dass der bestehende Vertrag mitgenommen werden kann („ohne neuen Vertrag“) und nennt zusätzlich den Fristen-/Prüfschritt: „Wir prüfen im nächsten Schritt, ob Yello an deiner neuen Adresse liefern kann.“ | [UM-02 – Umzug melden](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden.md), [UM-03 – Neue Adresse](../screens/feature-umzug-vertrag-mitnehmen/um-03-neue-adresse.md) |
| AC3 | Nutzer:innen können neue Adresse und Umzugsdatum eingeben. | 2 | ✅ erfüllt | Auf dem Screen „Neue Adresse“ gibt es Eingabefelder für Straße und Hausnummer, PLZ, Ort sowie ein Feld für das Umzugsdatum. Die Nutzer:innen können diese Daten erfassen bzw. ändern. | [UM-03 – Neue Adresse](../screens/feature-umzug-vertrag-mitnehmen/um-03-neue-adresse.md) |
| AC4 | Der Zählerstand bei Auszug kann im Ablauf erfasst werden. | 1 | ❌ offen | In den gelieferten Screens gibt es keinen Hinweis auf die Erfassung des Zählerstands beim Auszug. Es werden nur Adresse und Umzugsdatum gezeigt. | [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md), [UM-02 – Umzug melden](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden.md), [UM-03 – Neue Adresse](../screens/feature-umzug-vertrag-mitnehmen/um-03-neue-adresse.md) |
| AC5 | Ein Bestätigungsscreen fasst zusammen, was als Nächstes passiert. | 1 | ❌ offen | Ein Bestätigungsscreen mit Zusammenfassung der nächsten Schritte ist nicht enthalten. Gezeigt werden nur die Einstiegs- und Eingabescreens des Umzugsflows. | [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md), [UM-02 – Umzug melden](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden.md), [UM-03 – Neue Adresse](../screens/feature-umzug-vertrag-mitnehmen/um-03-neue-adresse.md) |

Gewichtung: erfüllt zählt voll, teilweise halb, offen gar nicht.

## Bitte selbst prüfen

- Prüfen, ob nach „Weiter“ tatsächlich ein Bestätigungs-/Zusammenfassungsscreen folgt und welche Inhalte dort stehen.
- Prüfen, ob die Frist zum Umzugsmelden konkret genannt wird oder nur indirekt über den Prüfhint angedeutet ist.
- Prüfen, ob der Zählerstand an anderer Stelle im Flow erfasst wird, die in den gelieferten Screens nicht sichtbar ist.

## Screens im Flow „Feature: Umzug – Vertrag mitnehmen“

- [UM-01 – Vertrag mit Umzug-Einstieg](../screens/feature-umzug-vertrag-mitnehmen/um-01-vertrag-mit-umzug-einstieg.md)
- [UM-02 – Umzug melden](../screens/feature-umzug-vertrag-mitnehmen/um-02-umzug-melden.md)
- [UM-03 – Neue Adresse](../screens/feature-umzug-vertrag-mitnehmen/um-03-neue-adresse.md)
