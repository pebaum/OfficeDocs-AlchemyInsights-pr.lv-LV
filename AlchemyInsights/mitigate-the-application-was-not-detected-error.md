---
title: Kļūdas Lietojumprogramma netika atrasta novēršana
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810490"
---
# <a name="mitigate-the-application-was-not-detected-error"></a><span data-ttu-id="ddc2e-102">Kļūdas Lietojumprogramma netika atrasta novēršana</span><span class="sxs-lookup"><span data-stu-id="ddc2e-102">Mitigate "The application was not detected" error</span></span>

<span data-ttu-id="ddc2e-103">Lietojumprogrammas instalēšanas kļūda “Lietojumprogramma nav atrasta pēc veiksmīgas instalēšanas”, par kuru ziņo Intune, var notikt visās lielākajās operētājsistēmās (Windows, iOS un Android).</span><span class="sxs-lookup"><span data-stu-id="ddc2e-103">The app installation error, “The application was not detected after installation completed successfully,” reported by Intune, may occur on all major OS platforms (Windows, iOS and Android).</span></span>

<span data-ttu-id="ddc2e-104">Scenāriji, kas ģenerē šo problēmu visbiežāk:</span><span class="sxs-lookup"><span data-stu-id="ddc2e-104">The most common scenarios that generate this error include:</span></span>

- <span data-ttu-id="ddc2e-105">Pēc sākotnējās izvietošanas lietojumprogramma tika atjaunināta ārpus Intune (no trešās puses lietojumprogrammu veikala).</span><span class="sxs-lookup"><span data-stu-id="ddc2e-105">The app has been updated outside of Intune (from a third-party app store) after the initial deployment.</span></span> <span data-ttu-id="ddc2e-106">Piemēram, lietojumprogramma Google Chrome var veikt automātisko atjaunināšanu.</span><span class="sxs-lookup"><span data-stu-id="ddc2e-106">For example some applications such as Google Chrome may perform auto updates.</span></span>
- <span data-ttu-id="ddc2e-107">Lietotājs ir atinstalējis lietojumprogrammu pēc sākotnējās instalēšanas.</span><span class="sxs-lookup"><span data-stu-id="ddc2e-107">A user has uninstalled the app after the initial install.</span></span>

<span data-ttu-id="ddc2e-108">Lai novērstu šo problēmu, vispirms ir jāpārskata skartās ierīces, lai noteiktu scenārijus, kuros notiek šī kļūda.</span><span class="sxs-lookup"><span data-stu-id="ddc2e-108">To mitigate this issue, first perform a review of the affected devices to determine the scenario in which the error occurs.</span></span>

- <span data-ttu-id="ddc2e-109">Ja lietojumprogramma tika atjaunināta ārpus Intune, lietojumprogrammas izvietošanu var iestatīt, lai tā ignorētu lietojumprogrammas versiju.</span><span class="sxs-lookup"><span data-stu-id="ddc2e-109">If the app has been updated outside of Intune, the app deployment can be set to ignore the application version.</span></span> <span data-ttu-id="ddc2e-110">Lai to izdarītu, sadaļā **Lietojumprogrammas konfigurācija > Informācija** iestatiet **Ignorēt lietojumprogrammas** versiju uz **Jā**.</span><span class="sxs-lookup"><span data-stu-id="ddc2e-110">To do so, under **App Configuration > App Information**, set **Ignore App** version to **Yes**.</span></span>
- <span data-ttu-id="ddc2e-111">Veicot ar klientu saistītās darbības, atbilstošs risinājums var būt lietojumprogrammu izvietošana “pēc vajadzības”, lai nodrošinātu jaunākās versijas izvietošanu.</span><span class="sxs-lookup"><span data-stu-id="ddc2e-111">When targeting the client, it may be appropriate to deploy the application as “required,” and to ensure that the latest version is deployed.</span></span>
- <span data-ttu-id="ddc2e-112">Alternatīvs risinājums iOS platformā ir izmantot **automātiskās atjaunināšanas** funkciju, kas ir saistīta ar Apple lielapjoma pirkumu programmu, kuru ir iespējams konfigurēt automātiskai atjaunināšanai tiklīdz ir pieejamas jaunas lietojumprogrammas versijas.</span><span class="sxs-lookup"><span data-stu-id="ddc2e-112">Alternatively, on the iOS platform, it is possible to use the **autoupdate** functionality associated with the Apple Volume Purchase Program, which can be configured to automatically update to new application versions as they become available.</span></span>

<span data-ttu-id="ddc2e-113">Lai uzzinātu vairāk par instalēšanas problēmu novēršanu, lasiet [Lietojumprogrammu instalēšanas problēmu novēršana](https://docs.microsoft.com/intune/troubleshoot-app-install).</span><span class="sxs-lookup"><span data-stu-id="ddc2e-113">For more information about troubleshooting app installation issues, please see [Troubleshoot app installation issues](https://docs.microsoft.com/intune/troubleshoot-app-install).</span></span>