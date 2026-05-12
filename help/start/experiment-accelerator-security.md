---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Datennutzung in KI mit Journey Optimizer Experimentation Accelerator
topic: Content Management
role: User
level: Beginner
keywords: Inhalt, Experiment, mehrere, Zielgruppe, Abwandlung
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b3538224-471e-4c63-a444-9b19d89ae29cid: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dcid: b5ce8718-c3af-4fdb-a1a9-fca32f83a87cid: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: d095671a-1355-40aa-8b5f-06c33c68080bid: e1e0219c-f879-479f-8427-888ed2a6e9c2id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 100%

---

# Datennutzung in KI mit Journey Optimizer Experimentation Accelerator{#experiment-accelerator-security}

Mit **Adobe Journey Optimizer Experimentation Accelerator** können Sie automatisch Erkenntnisse gewinnen und Möglichkeiten zur Verbesserung Ihrer Experimente und Experimentprogramme empfehlen. Zur Bereitstellung dieser Empfehlungen nutzt die Lösung KI und maschinelles Lernen. Diese Anweisung verdeutlicht, wie die Daten Ihrer Kundinnen und Kunden in **Journey Optimizer Experimentation Accelerator** verwendet werden.

## Welche Daten verwendet Journey Optimizer Experimentation Accelerator?

Derzeit gibt es drei Datentypen, die von **Journey Optimizer Experimentation Accelerator** verwendet werden:

* **Metadaten zu Experimenten**: Experimentname, die Definition der im Experiment verwendeten Zielgruppe und die Abwandlungen im Experiment, z. B. Name, Aufspaltungsprozentsätze, Ort oder Oberfläche, in der das Experiment bereitgestellt wird.

* **Leistung der Abwandlungen**: Anzahl der Personen, Durchschnitt der Erfolgsmetrik und Standardabweichung für die einzelnen Abwandlungen.

* **Inhalt der Abwandlung**: Die gerenderte HTML und der Screenshot der Abwandlung, wie sie für Benutzende auf Ihrer Website erscheinen würde.

## Was macht Journey Optimizer Experimentation Accelerator mit diesen Daten?

**Journey Optimizer Experimentation Accelerator** nimmt die Inhalte für die einzelnen Abwandlungen und erstellt eine Einbettung (d. h. eine mathematische Darstellung des Inhalts) und korreliert diese Einbettungen dann mit der Leistung der Abwandlungen. Dieser Prozess ermöglicht die Extraktion der Inhaltsattribute, die am besten abgeschnitten haben, für eine zukünftige Verwendung. Diese Attribute werden dann in ein von Adobe gehostetes Large Language Model (LLM) aufgenommen, das sie in für Menschen lesbare Anweisungen umwandelt, die dazu dienen, Erkenntnisse zu generieren und Opportunities vorzuschlagen.

## Welche Einschränkungen weist Journey Optimizer Experimentation Accelerator in Bezug auf die verwendeten Daten auf?

Jede Kundin bzw. jeder Kunde wird einer bestimmten Organisation und Sandbox zugewiesen. Für jede Sandbox wird ein eigenes Modell trainiert. Wenn eine Sandbox gelöscht wird, werden alle zugehörigen Daten, Signale und Modelle dauerhaft entfernt.

* Wir verwenden Kundendaten nur, um das kundenspezifische Modell zu trainieren oder zu optimieren.

* Wir mischen niemals Kundschaft, um ein Modell zu trainieren oder zu optimieren.

## Ändern Adobe-Modelle oder KI das Anwendererlebnis einer Marke automatisch?

Nein. **Journey Optimizer Experimentation Accelerator** empfiehlt nur, was geändert werden könnte und wie dies geändert werden könnte. Nur Benutzende, die berechtigt sind, das Erlebnis mithilfe von Journey Optimizer oder Target zu ändern, können diese Empfehlungen umsetzen. Alle Empfehlungen können überprüft und bearbeitet werden, bevor sie bereitgestellt werden.

## Besteht ein Risiko für die Daten- oder Systemstabilität?

**Journey Optimizer Experimentation Accelerator** nimmt nur Daten auf und analysiert sie, wodurch Erkenntnisse und Empfehlungen für zukünftige Tests entstehen. Das Tool hat keine Zugriffsberechtigung zum Ändern von Testeinstellungen. Alle im Tool generierten Vorschläge werden zur Implementierung an Target und Journey Optimizer gesendet. So wird sichergestellt, dass sie keine Auswirkungen auf die aktuellen Aktivitäten von Kundschaft haben.
