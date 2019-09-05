---
title: SharePoint Online terminu krātuvē trūkst terminu
ms.author: pebaum
author: Techwriter40
ms.date: 10/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 0f9efe980987c9ffc64fcf9d5d72a67f0a622867
ms.sourcegitcommit: 23772ebd25a86a879ced40b10566a35e76a79eb5
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 09/05/2019
ms.locfileid: "36762073"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>BitLocker šifrēšanas ar InTune iespējošana

InTune galapunkta aizsardzības politiku var izmantot, lai konfigurētu Windows ierīču Boitlocker šifrēšanas iestatījumus, kā aprakstīts: Windows10 (un jaunākām versijām) iestatījumus, lai aizsargātu ierīces, izmantojot InTune

Ņemiet vērā, ka daudzas jaunākas ierīces, kurās darbojas operētājsistēma Windows 10, atbalsta automātisku BitLocker šifrēšanu, kas tiek izraisīta, nepiemērojot MDM politiku. Tas var ietekmēt politikas piemērošanu, ja nav noklusējuma iestatījumi ir konfigurēti. Detalizētāku informāciju skatiet sadaļā BUJ.


FAQ  Q: kādi Windows izdevumi atbalsta ierīču šifrēšanu, izmantojot galapunktu aizsardzības politiku?
 A: InTune galapunkta aizsardzības politikas iestatījumi tiek ieviesti, izmantojot BitLocker CSP.Ne visi izdevumi, ne arī veido Windows atbalsta BitLocker CSP. 
      Šajā laikā Windows izdevumi: Enterprise; Education, Mobile, Mobile Enterprise un Professional (no Build 1809 gada) tiek atbalstīti.




Q: ja ierīce jau ir šifrēts ar BitLocker, izmantojot OS noklusējuma iestatījumus šifrēšanas metodei un šifra stiprums (XTS-AES-128), piemērojot politiku ar atšķirīgiem iestatījumiem, automātiski aktivizēs diska atkārtotu šifrēšanu ar jaunajiem iestatījumiem?

A: Nē. Lai lietotu jaunos šifra iestatījumus, vispirms disks ir atšifrēts.

Piezīme ierīcēm, kas uzņemti ar Autopilot automātiskās šifrēšanas, kas varētu rasties OOBE laikā nav aktivizēta līdz InTune politika tiek novērtēta, kas ļauj politikas iestatījumus izmantot vietā OS noklusējumus




Q Ja ierīce tiek šifrēta, kā rezultātā lietojumprogrammas InTune politika tiks atšifrēti, šī politika tiek noņemta?

A: noņemšana šifrēšanas saistīto politiku nerada atšifrēšana diskus, kas tika konfigurēts.




Q: kāpēc InTune atbilstības politika parāda, ka mana ierīce nav "BitLocker iespējota", bet tas ir?

: "BitLocker iespējots" iestatījums InTune atbilstības politika izmanto Windows Device Health apliecinājums (DHA) klientu. Šis klients tikai mēra ierīces stāvokli sāknēšanas laikā. Tātad, ja ierīce nav rebooted tā kā BitLocker šifrēšana tika pabeigta, DHA klienta pakalpojums neziņos par BitLocker kā aktīvu.