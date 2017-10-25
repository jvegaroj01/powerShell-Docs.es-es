---
ms.date: 2017-06-09
schema: 2.0.0
keywords: powershell
title: RequireLicenseAcceptanceScript
ms.openlocfilehash: 7092fb2e63b9e2b1eca59cd418317631bff8b172
ms.sourcegitcommit: cd66d4f49ea762a31887af2c72d087b219ddbe10
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/11/2017
---
# <a name="requiring-license-acceptance-for-scripts"></a><span data-ttu-id="6f0fe-103">Requerir la aceptación de la licencia para Scripts</span><span class="sxs-lookup"><span data-stu-id="6f0fe-103">Requiring License Acceptance for Scripts</span></span>

<span data-ttu-id="6f0fe-104">No se admite la aceptación de la licencia para los scripts.</span><span class="sxs-lookup"><span data-stu-id="6f0fe-104">License Acceptance is not supported for scripts.</span></span> <span data-ttu-id="6f0fe-105">Sin embargo, sí se admite el escenario en que un script depende de un módulo que requiere la aceptación de la licencia.</span><span class="sxs-lookup"><span data-stu-id="6f0fe-105">However, the scenario where a script depends on a module that requires license acceptance is supported.</span></span>

<span data-ttu-id="6f0fe-106">Los comandos de script (Install-Script/Save-Script/Update-Script) admiten un parámetro nuevo, -AcceptLicense, que se comporta como si el usuario hubiese visto la licencia.</span><span class="sxs-lookup"><span data-stu-id="6f0fe-106">Script commands(Install-Script/Save-Script/Update-Script) support a new parameter -AcceptLicense that behaves as though user saw the license.</span></span> <span data-ttu-id="6f0fe-107">Si no se especifica -AcceptLicense, el usuario verá el archivo license.txt para el módulo dependiente y se le pedirá que acepte la licencia.</span><span class="sxs-lookup"><span data-stu-id="6f0fe-107">If -AcceptLicense is not specified; the user will be shown license.txt for dependent module and prompted to accept the license.</span></span>

## <a name="examples"></a><span data-ttu-id="6f0fe-108">EJEMPLOS</span><span class="sxs-lookup"><span data-stu-id="6f0fe-108">EXAMPLES</span></span>

### <a name="example-1-install-script-with-dependencies-requiring-license-acceptance"></a><span data-ttu-id="6f0fe-109">Ejemplo 1: instalación de un script con dependencias que requiere la aceptación de la licencia</span><span class="sxs-lookup"><span data-stu-id="6f0fe-109">Example 1: Install Script with dependencies requiring license acceptance</span></span>
<span data-ttu-id="6f0fe-110">El script "ScriptRequireLicenseAcceptance" depende del módulo "ModuleRequireLicenseAcceptance".</span><span class="sxs-lookup"><span data-stu-id="6f0fe-110">Script 'ScriptRequireLicenseAcceptance' depends on module 'ModuleRequireLicenseAcceptance'.</span></span> <span data-ttu-id="6f0fe-111">Se solicita al usuario que acepte la licencia.</span><span class="sxs-lookup"><span data-stu-id="6f0fe-111">User is prompted to Accept License.</span></span>
```PowerShell
PS C:\> Install-Script -Name ScriptRequireLicenseAcceptance

License Acceptance
MIT License 2.0
Copyright (c) 2016 PowerShell Team
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.

Do you accept the license terms for module 'ModuleRequireLicenseAcceptance'.
[Y] Yes  [A] Yes to All  [N] No  [L] No to All  [S] Suspend  [?] Help (default is "N"): 
```

### <a name="example-2-install-script-with-dependencies-requiring-license-acceptance-and--acceptlicense"></a><span data-ttu-id="6f0fe-112">Ejemplo 2: instalación de un script con dependencias que requiere la aceptación de la licencia y -AcceptLicense</span><span class="sxs-lookup"><span data-stu-id="6f0fe-112">Example 2: Install Script with dependencies requiring license acceptance and -AcceptLicense</span></span>
<span data-ttu-id="6f0fe-113">El script "ScriptRequireLicenseAcceptance" depende del módulo "ModuleRequireLicenseAcceptance".</span><span class="sxs-lookup"><span data-stu-id="6f0fe-113">Script 'ScriptRequireLicenseAcceptance' depends on module 'ModuleRequireLicenseAcceptance'.</span></span> <span data-ttu-id="6f0fe-114">No se le pide al usuario que acepte la licencia porque se especifica -AcceptLicense.</span><span class="sxs-lookup"><span data-stu-id="6f0fe-114">User is not prompted to accept license as -AcceptLicense is specified.</span></span>
```PowerShell
PS C:\> Install-Script -Name ScriptRequireLicenseAcceptance -AcceptLicense
```

## <a name="more-details"></a><span data-ttu-id="6f0fe-115">Más detalles</span><span class="sxs-lookup"><span data-stu-id="6f0fe-115">More details</span></span>
### <a name="require-license-acceptance-support-for-modulesmodulerequirelicenseacceptancemd"></a>[<span data-ttu-id="6f0fe-116">Compatibilidad de Requerir la aceptación de la licencia para los módulos</span><span class="sxs-lookup"><span data-stu-id="6f0fe-116">Require License Acceptance support for Modules</span></span>](../module/RequireLicenseAcceptance.md)

### <a name="require-license-acceptance-support-on-powershellgallerypsgallerypsgalleryrequireslicenseacceptancemd"></a>[<span data-ttu-id="6f0fe-117">Compatibilidad de Requerir la aceptación de la licencia en PowerShellGallery</span><span class="sxs-lookup"><span data-stu-id="6f0fe-117">Require License Acceptance support on PowerShellGallery</span></span>](../../psgallery/psgallery_requires_license_acceptance.md)

### <a name="require-license-acceptance-on-deploy-to-azure-automationpsgallerypsgallerydeploytoazureautomationrequirelicenseacceptancemd"></a>[<span data-ttu-id="6f0fe-118">Requerir la aceptación de licencia de Implementar en Azure Automation</span><span class="sxs-lookup"><span data-stu-id="6f0fe-118">Require License Acceptance on Deploy to Azure Automation</span></span>](../../psgallery/psgallery_deploy_to_azure_automation_requireLicenseAcceptance.md)