---
title: Overview of the productivity pane | Microsoft Docs
description: Overview of the productivity pane in Dynamics 365 Customer Service workspace.
author: lalexms
ms.author: laalexan
manager: shujoshi
ms.date: 08/03/2020
ms.topic: article
ms.service: 
  - dynamics-365-customerservice
ms.custom: 
  - dyn365-customerservice
search.audienceType: 
  - admin
  - customizer
  - enduser
search.app: 
  - D365CE
  - D365CS
---

# Preview: Use the productivity pane to help resolve customer issues

[!include[cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

> [!IMPORTANT]
>
> - A preview is a feature that is not complete, as it may employ reduced privacy, security, and/or compliance commitments, but is made available before it is officially released for general availability so customers can get early access and provide feedback. Previews are provided "as-is," "with all faults," "as available," and without warranty.
> - This preview feature does not come with technical support and Microsoft Dynamics 365 Technical Support won't be able to help you with issues or questions.  If Microsoft does elect to provide any type of support, such support is provided "as is," "with all faults," and without warranty, and may be discontinued at any time.
> - Previews are not meant for production use, especially to process Personal Data or other data that is subject to heightened compliance requirements, and any use of "live" or production data is at your sole risk. All previews are subject to separate [Terms and Conditions](../legal/supp-dynamics365-preview.md).

The productivity pane in the Customer Service workspace is an auxiliary work area that contains productivity tools that support or expedite an agent's tasks when resolving customer issues.

For the Wave 2 2020 Early Access release, the productivity pane includes the **Smart assist** control, where agents can quickly view and interact with relevant AI-generated knowledge articles and similar cases suggestions for the case they are working on. Other productivity pane controls will be added in upcoming releases.

> [!Important]
> The productivity pane only displays information (for example, knowledge article and similar case suggestions) for the first tab (referred to as the anchor tab) of an active case session.

The productivity pane has two modes: expanded and collapsed. You can use the arrow to set the mode of the productivity pane, and the mode you choose is preserved in different sessions. For example, say in session A you expanded the pane, but while in session B, you collapsed it. When you switch from session A to session B, the pane mode changes from expanded to collapsed. Then if you switch back to session A, the pane is still in its expanded mode.

![Productivity pane mode](media/csw-productivity-pane-mode.png "View of the productivity pane")

Expanded mode:

![Productivity pane expanded view](media/csw-productivity-pane-expanded-mode.png "View of the productivity pane in expanded mode")

Collapsed mode:

![Productivity pane collapsed view](media/csw-productivity-pane-collapsed-mode.png "View of the productivity pane mode in collapsed mode")

## Smart assist

Smart assist is an intelligent assistant that is designed to help agents resolve customer issues quickly by providing real-time suggestions of the best course of actions to take while working on an assigned case. It shows relevant, AI-generated suggestions, such as knowledge articles and similar cases that match the context of the active case.

In the Customer Service workspace application, **Smart assist** appears in the productivity pane on the right-hand side of the session.

> [!Important]
> For the preview release, the **productivity pane** is automatically enabled and will expand, showing the **Smart assist** tab whenever an active case is opened as a new session using the Shift+click action.

![Smart assist tab](media/csw-smart-assist-tab.png "View of the Smart assist tab on the productivity pane")

Smart assist displays the relevant suggestions as individual cards that are grouped as either **Knowledge article suggestions** or **Similar cases suggestions**. For more information, see [View AI-suggested similar cases and knowledge articles](csw-view-ai-suggested-cases-knowledge-articles.md).

### See also

[Customer Service workspace - overview](csw-overview.md)   </br>
[View AI-suggested similar cases and knowledge articles](csw-view-ai-suggested-cases-knowledge-articles.md)
