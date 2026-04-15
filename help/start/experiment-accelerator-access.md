---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Verbessern Ihrer Fähigkeit, Experimente effektiv durchzuführen und Erkenntnisse zu gewinnen
topic: Content Management
role: User
level: Beginner
keywords: Inhalt, Experiment, mehrere, Zielgruppe, Abwandlung
source-git-commit: 020ed6c652c66ed78789a5a90dfc8c8dece624a9
workflow-type: ht
source-wordcount: '507'
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
