---
title: SharePoint Designer savienojuma problēmas
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511551"
---
# <a name="sharepoint-designer-connection-issues"></a>SharePoint Designer savienojuma problēmas 

Ja programmā SharePoint Designer ir radušās savienojuma problēmas ar SharePoint vietnēm, lūdzu, izmēģiniet tālāk minētie Kopīgie risinājumi.

1. darbība: Pārbaudiet, vai SharePoint Designer 2013 tiek atjaunināts ar [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) un [2. augusts 2016 atjaunināt SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



2. darbība: notīriet lokālās kešatmiņas failus.

1. Aizveriet SharePoint Designer 2013.

2. Lokālajā datorā, noņemiet visus failus atrasti katrā no šīm mapēm.

    - %APPDATA%\Microsoft\Web Server Extensions\Cache
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Atveriet SharePoint Designer 2013 un ievadiet kontu vēlreiz, lai redzētu, vai tā darbojas.

3. darbība: [Iespējot mūsdienu autentifikācijas Office 2013 Windows ierīcēs](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).

4. darbība: administratoriem ir **jāatļauj pielāgotu skriptu** SharePoint administrēšanas centrs iestatījumus, lai atļautu SharePoint Designer savienojumu. Papildinformāciju skatiet sadaļā [Atļaut vai aizliegt pielāgotu skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) .


