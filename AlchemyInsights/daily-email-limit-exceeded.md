---
title: Pārsniegts ikdienas e-pasta limits. Darbplūsma ir apturēta.
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 5a510f1137c7c49cd1de3d3fd2a470759e37ba1e
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 04/27/2020
ms.locfileid: "43908711"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a>Pārsniegts ikdienas e-pasta limits. Darbplūsma ir apturēta.

Šī kļūda var tikt saņemta šādos gadījumos:

- Jums ir darbplūsma SharePoint Online, kas izmanto SharePoint 2010 vai SharePoint 2013 darbplūsmas platformas tips.
- Darbplūsma ir konfigurēta, lai nosūtītu pielāgotu e-pasta ziņojumu vairāk nekā 200 lietotājiem laikā, vairāk nekā 10 000 adresāti dienā vai vairāk nekā 30 ziņojumi minūtē.
- Palaižot darbplūsmu, e-pasta ziņojums netiek nosūtīts un pamanāt, ka šādas darbības:
    - Darbplūsmu, izmantojot SharePoint 2013 platformas tips, pārlūkojot lapu **darbplūsmas statuss** . Lapā Darbplūsmas statuss **iekšējais statuss** ir iestatīts uz **sākts**un informācijas balons parāda **nevar nosūtīt adresātam**.

Lai novērstu šo problēmu, konfigurējiet darbplūsmas nosūtīt e-pasta ziņojumus, nepārsniedzot [Exchange Online sūtītāja ierobežojumus](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits). Piemēram, izmantojiet pauzi darbplūsmā, sūtiet e-pastu uz Microsoft 365 grupu, adresātu grupu vai iespējotu pasta drošības grupu vai nosūtiet ziņojumu mazāk nekā 200 adresātiem vienlaikus.


Lai iegūtu papildinformāciju, skatiet šo [rakstu](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).

## <a name="related-topics"></a>Saistītās tēmas
- [Izveidot plūsmu](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint un plūsmas](https://flow.microsoft.com/blog/sharepoint-and-flow/) 