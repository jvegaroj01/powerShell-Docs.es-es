---
ms.date: 06/12/2017
contributor: JKeithB
ms.topic: conceptual
keywords: gallery,powershell,cmdlet,psgallery
title: Implementar en Automatización de Azure
ms.openlocfilehash: 1efdc289228d3a6962302d12ccf44143ce63a806
ms.sourcegitcommit: e9ad4d85fd7eb72fb5bc37f6ca3ae1282ae3c6d7
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/10/2018
---
# <a name="deploy-to-azure-automation"></a>Implementar en Automatización de Azure

El botón Deploy to Azure Automation (Implementar en Automatización de Azure) en la página de detalles del elemento implementará el elemento desde la Galería de PowerShell en Automatización de Azure.

![Botón Deploy to Azure Automation (Implementar en Automatización de Azure)](../../Images/DeployToAzureAutomationButton.png)

Al hacer clic en él, se le redirigirá al Portal de administración de Azure, donde deberá iniciar sesión con sus credenciales de la cuenta de Azure.
Si el elemento incluye dependencias, también se implementan en Automatización de Azure.

> [!WARNING]
> Si ya existen en la cuenta de Automation el mismo elemento y versión, al implementarse de nuevo desde la Galería de PowerShell el elemento se sobrescribirá en la cuenta de Automation.

Si se implementa un módulo, aparecerá en la sección Módulos de Automatización de Azure.  Si se implementa un script, aparecerá en la sección Runbooks de Automatización de Azure.

El botón Deploy to Azure Automation (Implementar en Automatización de Azure) se puede deshabilitar mediante la adición de la etiqueta AzureAutomationNotSupported a los metadatos del elemento.

## <a name="require-license-acceptance-on-deploy-to-azure-automation"></a>Requerir la aceptación de licencia de Implementar en Azure Automation

Si el módulo que se implementa en Azure Automation requiere la aceptación de la licencia, la UI del portal mostrará una advertencia que indica que el módulo requiere la aceptación de la licencia. Si hace clic en Aceptar, indica que está de acuerdo con los términos de licencia.

![Implementar en Azure Automation requiere la aceptación de la licencia](../../Images/DeployToAzureAutomationRequireLicenseAcceptanceDisclaimer.png)

## <a name="more-details"></a>Más detalles

- [Requerir la aceptación de la licencia en PowerShellGet](../../concepts/module-license-acceptance.md)
- [Requerir la aceptación de la licencia en la Galería de PowerShell](items-that-require-license-acceptance.md)
- [Sitio web de Azure Automation](http://azure.microsoft.com/services/automation/)