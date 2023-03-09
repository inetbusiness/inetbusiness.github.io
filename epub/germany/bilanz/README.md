# Dies ist die Bilanz-Sektion der Publikationsplattform Deutschland
---

Eintragungen in diesem Bereich halten sich an aktuelles Lernmaterial zur Erstellung von **Bilanzen**

Jede Bilanz ist in die entsprechenden Unterordner, die dem Geschäftsjahr entsprechen, einzufügen.

Der Ordnername sollte dem Unternehmensnamen entsprechen und leerzeichen sollten durch Unterstriche ersetzt werden, der Dateiname muss README.md lauten:

*/epub/germany/bilanz/2010/Beispiel_Unternehmen_GmbH/README.md*

## Beispiel Unternehmen
Beispiel Unternehmen GmbH  
Beispielstraße 5  
0815 Beispielort  

### Bilanz zum 31. Dezember 2023
> :warning: Es ist wichtig eine Leerzeile vor einer Tabelle stehen zu lassen!

| **Aktiva** | Wert | **Passiva** | Wert |
| :--- | ---: | :--- | ---: |
| *I. Anlagevermögen* | | *I. Eigenkapital* | 192.633,00 |
|       1. Gebäude | 152.000,00 | *II. Fremdkapital* | |
|       2. Fahrzeuge | 25.000,00 |     1. Darlehen | 25.000,00 |
|       3. Geschäftsausstattung | 18.450,00 |      2. Verbindlichkeiten | 14.630,00 |
| *II. Umlaufvermögen* | | | |
|   1. Rohstoffe | 8.600,00 | | |
|   2. Hilfs- und Betriebsstoffe | 4.250,00 | | |
|   3. Warenvorräte | 2.150,00 | | |
|   4. Forderungen | 2.380,00 | | |
|   5. Kassenbestand | 450,00 | | |
|   6. Bankguthaben | 18.983,00 | | |
| | Gesamt: 232.263,00 | | Gesamt: 232.263,00 |

Der entsprechende Markdown für die oberhalb abgebildete Tabelle sieht wie folgt aus:  
```markdown
| **Aktiva** | Wert | **Passiva** | Wert |
| :--- | ---: | :--- | ---: |
| *I. Anlagevermögen* |  | *I. Eigenkapital* | 192.633,00 |
|       1. Gebäude | 152.000,00 | *II. Fremdkapital* | |
|       2. Fahrzeuge | 25.000,00 |     1. Darlehen | 25.000,00 |
|       3. Geschäftsausstattung | 18.450,00 |      2. Verbindlichkeiten | 14.630,00 |
| *II. Umlaufvermögen* | | | |
|   1. Rohstoffe | 8.600,00 |  |  |
|   2. Hilfs- und Betriebsstoffe | 4.250,00 | | |
|   3. Warenvorräte | 2.150,00 | | |
|   4. Forderungen | 2.380,00 | | |
|   5. Kassenbestand | 450,00 | | |
|   6. Bankguthaben | 18.983,00 | | |
| | Gesamt: 232.263,00 | | Gesamt: 232.263,00 |
```