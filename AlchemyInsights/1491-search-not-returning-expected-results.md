---
title: 1491-Search-not-Returning-Expected-Results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964911"
---
# <a name="content-search-not-returning-expected-results"></a>Satura meklēšana nav atgriešanās gaidāmie rezultāti

Braucot satura meklēšanu no & biroja 365 drošības ievērošanu centrs var saņemt negaidītu meklēšanas rezultātus. Apsveriet šādas lietas, kas var ietekmēt meklēšanas rezultātus:

- **Satura atrašanās vietu un meklēšanas nosacījumus**: Pārliecinieties, vai esat izvēlējies atbilstošu satura atrašanās vietu un meklēšanas nosacījumiem. Ja jūs vadīja lielu meklēšanas (ar daudzām vietām), uzskata, sadalot to vairākās meklēšanas.

- **Daļēji indeksē vienumus**: [daļēji indeksē vienumus](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) no pastkastes paredzamo meklēšanas rezultātos tiek iekļautas. Tomēr daļēji indeksē vienumus no vietas savā SharePoint un OneDrive netiek iekļauti meklēšanas budžetu.

- **Meklēšanas kļūmes**: meklējot lielu skaitu pastkastītes (vairāk nekā 100000 pastkastes), jūs varat saņemt meklēšanas kļūdas, kļūdas kodus, piem., CS008-009 un CS012-002). Šādā gadījumā mēģiniet vēlreiz tikai meklēt neizdevās satura atrašanās vietu. Skatiet [šajā rakstā](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) plašāku informāciju.