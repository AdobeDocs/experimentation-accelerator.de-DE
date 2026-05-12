---
solution: Journey Optimizer
product: journey optimizer
title: Metriken zu Journey Optimizer Experimentation Accelerator
description: Verbessern Ihrer Fähigkeit, Experimente effektiv durchzuführen und Erkenntnisse zu gewinnen
topic: Content Management
role: User
level: Beginner
keywords: Inhalt, Experiment, mehrere, Zielgruppe, Abwandlung
TQID: https://experienceleague.adobe.com/OrtdIfQfKMIWODRi9fr-dEuc7g06hISv6-Dq-54qGeY
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: aa2f3246-cb95-4b30-8899-fdf7d73550ccid: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: e1e0219c-f879-479f-8427-888ed2a6e9c2
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 364
ht-degree: 100%

---

# Metriken {#experiment-accelerator-metrics}

Auf der Seite **[!UICONTROL Metriken]** werden Erfolgsmetriken aus Journey Optimizer- und Target-Experimenten an einer Stelle angezeigt, was Leistungs-Monitoring, Vergleiche und gründlichere Erkenntnisse ermöglicht.

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
