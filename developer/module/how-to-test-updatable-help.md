---
title: Cómo probar la Ayuda actualizable | Microsoft Docs
ms.custom: ''
ms.date: 09/12/2016
ms.reviewer: ''
ms.suite: ''
ms.tgt_pltfrm: ''
ms.topic: article
ms.assetid: 3e064048-2b94-4365-bdb7-f1ee7c0a7fd7
caps.latest.revision: 6
ms.openlocfilehash: f2f319a3cab4b4bd91e9b634dda57d58a6476b62
ms.sourcegitcommit: b6871f21bd666f9cd71dd336bb3f844cf472b56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/03/2019
ms.locfileid: "56854741"
---
# <a name="how-to-test-updatable-help"></a><span data-ttu-id="025f0-102">Cómo probar la Ayuda actualizable</span><span class="sxs-lookup"><span data-stu-id="025f0-102">How to Test Updatable Help</span></span>

<span data-ttu-id="025f0-103">Este tema describen métodos para probar la Ayuda actualizable de un módulo.</span><span class="sxs-lookup"><span data-stu-id="025f0-103">This topic describes approaches to testing Updatable Help for a module.</span></span>

## <a name="using-verbose-to-detect-errors"></a><span data-ttu-id="025f0-104">Uso detallado para detectar errores</span><span class="sxs-lookup"><span data-stu-id="025f0-104">Using Verbose to Detect Errors</span></span>

<span data-ttu-id="025f0-105">Después de cargar el archivo XML HelpInfo y los archivos .cab para el módulo, los archivos de prueba mediante la ejecución de un [Update-Help](/powershell/module/Microsoft.PowerShell.Core/Update-Help) comando con el **detallado** parámetro.</span><span class="sxs-lookup"><span data-stu-id="025f0-105">After uploading the HelpInfo XML file and CAB files for your module, test the files by running an [Update-Help](/powershell/module/Microsoft.PowerShell.Core/Update-Help) command with the **Verbose** parameter.</span></span> <span data-ttu-id="025f0-106">El **detallado** dirige el parámetro `Update-Help` para informar de los pasos fundamentales en sus acciones, lean la **HelpInfoUri** clave en el manifiesto de módulo para validar los tipos de archivo en el archivo CAB desempaquetado y la colocación de los archivos en el directorio del módulo específico del idioma.</span><span class="sxs-lookup"><span data-stu-id="025f0-106">The **Verbose** parameter directs `Update-Help` to report the critical steps in its actions, from reading the **HelpInfoUri** key in the module manifest to validating the file types in the unpacked CAB file and placing the files in the language-specific module directory.</span></span>
<span data-ttu-id="025f0-107">Después de cargar el archivo XML HelpInfo y los archivos .cab para el módulo, los archivos de prueba mediante la ejecución de un [Update-Help](/powershell/module/Microsoft.PowerShell.Core/Update-Help) comando con el **detallado** parámetro.</span><span class="sxs-lookup"><span data-stu-id="025f0-107">After uploading the HelpInfo XML file and CAB files for your module, test the files by running an [Update-Help](/powershell/module/Microsoft.PowerShell.Core/Update-Help) command with the **Verbose** parameter.</span></span> <span data-ttu-id="025f0-108">El **detallado** dirige el parámetro `Update-Help` para informar de los pasos fundamentales en sus acciones, lean la **HelpInfoUri** clave en el manifiesto de módulo para validar los tipos de archivo en el archivo CAB desempaquetado y la colocación de los archivos en el directorio del módulo específico del idioma.</span><span class="sxs-lookup"><span data-stu-id="025f0-108">The **Verbose** parameter directs `Update-Help` to report the critical steps in its actions, from reading the **HelpInfoUri** key in the module manifest to validating the file types in the unpacked CAB file and placing the files in the language-specific module directory.</span></span>

<span data-ttu-id="025f0-109">Cuando se resuelven todos los mensajes detallados, ejecute un `Update-Help` comando con el **depurar** parámetro.</span><span class="sxs-lookup"><span data-stu-id="025f0-109">When all verbose messages are resolved, run an `Update-Help` command with the **Debug** parameter.</span></span> <span data-ttu-id="025f0-110">Este parámetro debe detectar los demás problemas con los archivos de ayuda actualizable.</span><span class="sxs-lookup"><span data-stu-id="025f0-110">This parameter should detect any remaining problems with the Updatable Help files.</span></span>