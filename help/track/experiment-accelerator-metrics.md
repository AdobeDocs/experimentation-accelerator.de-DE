---
solution: Journey Optimizer
product: journey optimizer
title: Metriken zu Journey Optimizer Experimentation Accelerator
description: Verbessern Ihrer Fähigkeit, Experimente effektiv durchzuführen und Erkenntnisse zu gewinnen
topic: Content Management
role: User
level: Beginner
keywords: Inhalt, Experiment, mehrere, Zielgruppe, Abwandlung
source-git-commit: c52010f196f46d234066fd34ae8e9c0be7d2148b
workflow-type: ht
source-wordcount: '348'
ht-degree: 100%

---

# Metriken {#experiment-accelerator-metrics}

Auf der Seite **[!UICONTROL Metriken]** werden Erfolgsmetriken aus Journey Optimizer- und Target-Experimenten an einer Stelle angezeigt, was eine Leistungsüberwachung, Vergleiche und gründlichere Erkenntnisse ermöglicht.

## Dashboard {#dashboard}

Beim Zugriff auf die Registerkarte **[!UICONTROL Metriken]** werden alle verfügbaren Erfolgsmetriken aus Journey Optimizer und Adobe Target in einer konsolidierten Ansicht aufgelistet. So können die Leistung über verschiedene Initiativen hinweg verfolgen, Ergebnisse vergleichen und schnell Bereiche identifizieren, die Aufmerksamkeit erfordern.

Greifen Sie auf Filter zu, indem Sie auf ![](assets/do-not-localize/Smock_Filter_18_N.svg) klicken. Dadurch stehen kontextspezifische Optionen zur Verfügung, z. B. Filterung nach **[!UICONTROL Quelle]** oder **[!UICONTROL In aktiven Experimenten verwendet]**.

Alternativ können Sie schnell nach einer Metrik suchen, indem Sie ihren Namen in die Suchleiste eingeben.

![](assets/experiment-monitor-metrics.png)

## Metrikdetails {#metric-details}

### Inkrementell im Zeitverlauf

![](assets/experiment-monitor-metrics-2.png)

Das Diagramm **[!UICONTROL Inkrementell im Zeitverlauf]** bietet eine visuelle Aufschlüsselung der Entwicklung der ausgewählten Metrik über einen ausgewählten Zeitraum hinweg. Verwenden Sie das Dropdown-Menü, um zwischen der täglichen oder wöchentlichen Ansicht zu wechseln und die Granularität anzupassen.

Folgende Zusammenfassungswerte stehen als Kurzreferenz zur Verfügung:

* **[!UICONTROL Gesamt]**: Der kumulative Wert der ausgewählten Metrik über den Berichtszeitraum hinweg.

* **[!UICONTROL Durchschnitt]**: Der typische Wert der Metrik, berechnet für den ausgewählten Zeitraum. Durch den Ausgleich von täglichen oder wöchentlichen Schwankungen liefert er ein klareres Bild der normalen Leistung und kann als Ausgangsbasis für Vergleiche verwendet werden.

* **[!UICONTROL Konversionsrate]**: Prozentsatz der Profile, die die gewünschte Aktion (z. B. Kauf, Anmeldung) abgeschlossen haben, nachdem sie die Abwandlung gesehen haben.

Jeder Wert enthält eine prozentuale Änderung gegenüber dem vorherigen Zeitraum, sodass leicht erkennbar ist, ob die Leistung zunimmt, abnimmt oder stabil bleibt.

### Experimenteffekt

![](assets/experiment-monitor-metrics-3.png)

In diesem Abschnitt werden alle aktiven Experimente innerhalb des ausgewählten Zeitraums (letzte 90 Tage, letzte 30 Tage oder letzte 7 Tage) angezeigt und ihr Beitrag zur Metrik hervorgehoben.

Folgende Metriken sind verfügbar:

* **[!UICONTROL Steigerung]**: Messung der prozentualen Verbesserung der Konversionsrate einer bestimmten Abwandlung im Vergleich zur Baseline.

* **[!UICONTROL Konfidenz]**: Belege dafür, dass eine bestimmte Abwandlung mit der Baseline-Abwandlung identisch ist. [Weitere Informationen](http://experienceleague.adobe.com/de/docs/journey-optimizer/using/content-management/content-experiment/technotes/experiment-calculations)

* **[!UICONTROL Beitrag]**: Der Anteil der Gesamtänderung der Metrik, der einem bestimmten Experiment oder einer bestimmten Abwandlung zugeschrieben werden kann, sodass sich die Initiativen mit der größten relativen Wirkung identifizieren lassen.
