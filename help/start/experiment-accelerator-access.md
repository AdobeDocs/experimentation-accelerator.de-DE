---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Verbessern Ihrer Fähigkeit, Experimente effektiv durchzuführen und Erkenntnisse zu gewinnen
topic: Content Management
role: User
level: Beginner
keywords: Inhalt, Experiment, mehrere, Zielgruppe, Abwandlung
TQID: https://experienceleague.adobe.com/nCmogRT9JCTYK7VjfO-MNjz8lnDkRsaeCiZL4bIy0RQ
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: d998adac-2f81-400b-a669-d07bb196e4eb
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
  - id: fe338112-e2ce-4876-8989-fc4d497613f1
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 507
ht-degree: 100%

---

# Zugreifen auf Journey Optimizer Experimentation Accelerator

Nachdem Sie [Ihr Experiment erstellt und konfiguriert](https://experienceleague.adobe.com/de/docs/journey-optimizer/using/content-management/content-experiment/content-experiment) und Ihre Kampagnen oder Journeys an Ihre Profile gesendet haben, können Sie auf **[!UICONTROL Journey Optimizer Experimentation Accelerator]** zugreifen, um sich eingehender mit der Leistung Ihres Experiments zu befassen.

Der Zugriff auf **[!UICONTROL Journey Optimizer Experimentation Accelerator]** erfolgt entweder über das Menü links mit der Dropdown-Liste [!UICONTROL Experimente] oder über den Anwendungsschalter. Beachten Sie, dass Benutzende, die nur eine Target-Lizenz haben, ausschließlich über den Anwendungsschalter darauf zugreifen können.

![](assets/access.png)

Die verfügbaren Experimente hängen von Ihrem Setup ab:

* **Für Benutzende, die Adobe Journey Optimizer verwenden**: Experimente, die in der Sandbox Ihrer aktivierten Organisation eingerichtet wurden, werden automatisch einbezogen.

* **Für Benutzende, die Adobe Target mit Journey Optimizer verwenden**: Alle A/B-Aktivitäten in Target werden in **[!UICONTROL Journey Optimizer Experimentation Accelerator]** in der Produktions-Sandbox von Journey Optimizer angezeigt.

* **Für Benutzende, die nur Adobe Target verwenden**: Alle A/B-Aktivitäten in Ihrer Zielorganisation sind in der Produktions-Sandbox von Journey Optimizer enthalten.

Um **[!UICONTROL Journey Optimizer Experimentation Accelerator]** verwenden zu können, benötigen Sie Zugriff auf die Sandbox und die folgende zugehörige Berechtigung:

* **[!UICONTROL Experimente anzeigen]**
* **[!UICONTROL Metadaten zu Experimenten verwalten]**

+++ Informationen zur Zuweisung von Berechtigungen für Experimente mit einer Lizenz für Adobe Experience Platform oder Adobe Journey Optimizer

1. Navigieren Sie im Produkt **[!DNL Permissions]** zur Registerkarte **[!UICONTROL Rollen]** und wählen Sie die gewünschte **[!UICONTROL Rolle]** aus.

1. Klicken Sie auf **[!UICONTROL Bearbeiten]**, um die Berechtigungen zu ändern.

1. Fügen Sie die Ressource **[!UICONTROL Experimentation Accelerator]** hinzu und wählen Sie dann **[!UICONTROL Experimente anzeigen]** und/oder **[!UICONTROL Metadaten zu Experimenten verwalten]** aus dem Dropdown-Menü aus.

   ![](assets/permissions-experiment.png)

1. Klicken Sie auf **[!UICONTROL Speichern]**, um die Änderungen anzuwenden.

Die Berechtigungen aller Benutzenden, die dieser Rolle bereits zugewiesen sind, werden automatisch aktualisiert.

So weisen Sie diese Rolle neuen Benutzenden zu:

1. Navigieren Sie zur Registerkarte **[!UICONTROL Benutzende]** in Ihrem Rollen-Dashboard und klicken Sie auf **[!UICONTROL Benutzerin oder Benutzer hinzufügen]**.

1. Geben Sie den Namen und die E-Mail-Adresse der Benutzerin oder des Benutzers ein oder wählen Sie aus der Liste aus und klicken Sie dann auf **[!UICONTROL Speichern]**.

   Wenn die Benutzerin bzw. der Benutzer vorher noch nicht erstellt wurde, lesen Sie [diese Dokumentation](https://experienceleague.adobe.com/de/docs/experience-platform/access-control/abac/permissions-ui/users).

Die Benutzerin oder der Benutzer erhält eine E-Mail mit Anweisungen zum Zugriff auf Ihre Instanz.

+++

</br>

+++ Informationen zur Zuweisung von Berechtigungen für Experimente mit einer Lizenz für Adobe Target

1. Öffnen Sie die **[Admin Console](http://adminconsole.adobe.com/)**.

1. Wählen Sie unter **[!UICONTROL Produkte]** die Option **[!UICONTROL Adobe Experience Platform]**.

1. Klicken Sie auf **[!UICONTROL Neues Profil]**.

   ![](assets/permission-target.png)

1. Geben Sie einen **[!UICONTROL Namen]** und eine **[!UICONTROL Beschreibung]** für das Profil ein und klicken Sie dann auf **[!UICONTROL Speichern]**.

1. Öffnen Sie das neu erstellte **[!UICONTROL Profil]** und navigieren Sie zur Registerkarte **[!UICONTROL Berechtigungen]**.

1. Klicken Sie neben der Berechtigung **[!UICONTROL experimentation-accelerator]** auf ![](assets/do-not-localize/Smock_Edit_18_N.svg).

   ![](assets/permission-target-1.png)

1. Fügen Sie die Berechtigungen hinzu, über die dieses Profil verfügen soll, z. B. **[!UICONTROL Experimente anzeigen]** und **[!UICONTROL Experimentmetadaten verwalten]** und klicken Sie dann auf **[!UICONTROL Speichern]**.

   >[!TIP]
   >
   > Erstellen Sie separate Profile, wenn Benutzende unterschiedliche Zugriffsebenen benötigen. Erstellen Sie beispielsweise ein Profil **[!UICONTROL Experimentation Accelerator-Betrachterin bzw. -Betrachter]** mit nur der Berechtigung **[!UICONTROL Experimente anzeigen]** und ein Profil **[!UICONTROL Experimentation Accelerator-Bearbeiterin bzw. Bearbeiter]** mit den Berechtigungen **[!UICONTROL Experimente anzeigen]** und **[!UICONTROL Experimentmetadaten verwalten]**.

   ![](assets/permission-target-2.png)

1. Wählen Sie auf der Registerkarte **[!UICONTROL Berechtigungen]** die Option **[!UICONTROL Sandboxes]**.

1. Fügen Sie die Sandboxes hinzu, in denen Benutzende Journey Optimizer Experimentation Accelerator verwenden können, und klicken Sie dann auf **[!UICONTROL Speichern]**.

1. Öffnen Sie die Registerkarte **[!UICONTROL Benutzer]** und klicken Sie dann auf **[!UICONTROL Benutzer hinzufügen]**.

   ![](assets/permission-target-3.png)

1. Fügen Sie die Benutzenden hinzu, die diesen Zugriff erhalten sollen, und klicken Sie dann auf **[!UICONTROL Speichern]**.

Benutzende, die diesem Profil hinzugefügt wurden, können jetzt über den Anwendungsschalter auf Journey Optimizer Experimentation Accelerator zugreifen.

+++


<!--
table style="table-layout:fixed"><tr style="border: 0;">
<td><img alt="Overview" href="experiment-accelerator-overview.md" src="assets/do-not-localize/experiments-2.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-overview.md">Overview</a></strong></p></div></td>
<td><img alt="Experiments" href="experiment-accelerator-monitor.md" src="assets/do-not-localize/experiment-overview.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-monitor.md">Experiments</a></strong></p></div></td>
<td><img alt="Metrics" href="experiment-accelerator-metrics.md" src="assets/do-not-localize/experiment-metrics.png">
<div align="center"><p><strong><a href="experiment-accelerator-metrics.md">Metrics</a></strong></p></div></td>
</tr></table
-->
