---
title: Klasiskās SharePoint audita žurnāla atskaites
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 0aedb549f11db54d3cd480671fb0767c60680ad3
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509607"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>SharePoint un OneDrive audita žurnāli

## <a name="sharepoint-classic-audit-logs"></a>SharePoint Classic audita žurnāli

SPO mantotā auditēšana tika migrēta uz vienoto audita žurnālu (UAL). Visi SPO mantotie audita ziņojumi tagad tiks aprīkoti ar UAL, un mantotie audita signāli ir pārvietoti uz UAL.

Galvenās izmaiņas:

* Apgriešana nav pieejama kā iespēja.
* Konkrētu audita pasākumu izvēle nav pieejama. Skatiet [šo dokumentu](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance) , lai iegūtu pilnīgu sarakstu ar auditētajiem notikumiem, kas pieejami pēc noklusējuma.
* Sadaļā **pielāgoti pārskati** opcija **atrašanās vieta** nav pieejama.
* **Atverot vai lejupielādējot dokumentu** notikumu opcija nav pieejama.

[Vietņu kolekcijas audita iestatījumu konfigurēšana](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a>SharePoint un OneDrive mūsdienu vienotā audita žurnālus no atbilstības

* [Ieslēgt/izslēgt vienoto audita reģistrēšanu](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off) 

Nav nepieciešama papildu konfigurācija programmā SharePoint vai OneDrive.

Izmantojiet audita reģistrēšanas meklēšanu, lai pārbaudītu faila (-u), mapes (u), lietotāja (u) darbību, atļaujas:

* [Failu un lappušu darbības](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)
* [Mapes darbības](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [Koplietošanas un piekļuves pieprasījumu darbības](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [Sinhronizēšanas darbības](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [Vietnes administrēšanas darbības](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

Lai iegūtu papildinformāciju par to, kā izgūt šos notikumus, skatiet [Meklēt audita žurnālā](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
