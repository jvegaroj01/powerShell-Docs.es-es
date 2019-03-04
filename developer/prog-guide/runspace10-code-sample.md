---
title: Ejemplo de código RunSpace10 | Microsoft Docs
ms.custom: ''
ms.date: 09/13/2016
ms.reviewer: ''
ms.suite: ''
ms.tgt_pltfrm: ''
ms.topic: article
ms.assetid: 5337dc40-c56e-458b-aedc-5f5d401dfd28
caps.latest.revision: 6
ms.openlocfilehash: 95b25746a8e99deb871905734700aba51cd7765e
ms.sourcegitcommit: b6871f21bd666f9cd71dd336bb3f844cf472b56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/03/2019
ms.locfileid: "56854611"
---
# <a name="runspace10-code-sample"></a><span data-ttu-id="b83e1-102">Ejemplo de código Runspace10</span><span class="sxs-lookup"><span data-stu-id="b83e1-102">RunSpace10 Code Sample</span></span>

<span data-ttu-id="b83e1-103">Este es el código fuente del ejemplo Runspace10.</span><span class="sxs-lookup"><span data-stu-id="b83e1-103">Here is the source code for the Runspace10 sample.</span></span> <span data-ttu-id="b83e1-104">Esta aplicación de ejemplo agrega un cmdlet para [System.Management.Automation.Runspaces.Runspaceconfiguration](/dotnet/api/System.Management.Automation.Runspaces.RunspaceConfiguration) y, a continuación, usa la información de configuración modificado para crear el espacio de ejecución.</span><span class="sxs-lookup"><span data-stu-id="b83e1-104">This sample application adds a cmdlet to [System.Management.Automation.Runspaces.Runspaceconfiguration](/dotnet/api/System.Management.Automation.Runspaces.RunspaceConfiguration) and then uses the modified configuration information to create the runspace.</span></span>

> [!NOTE]
> <span data-ttu-id="b83e1-105">Puede descargar el C# el archivo de código fuente (runspace10.cs) mediante el Kit del desarrollo de Software de Windows para Windows Vista y Microsoft .NET Framework 3.0 Runtime Components.</span><span class="sxs-lookup"><span data-stu-id="b83e1-105">You can download the C# source file (runspace10.cs) by using the Windows Software Development Kit for Windows Vista and Microsoft .NET Framework 3.0 Runtime Components.</span></span> <span data-ttu-id="b83e1-106">Para obtener instrucciones de descarga, vea [cómo instalar Windows PowerShell y descarga el SDK de Windows PowerShell](/powershell/developer/installing-the-windows-powershell-sdk).</span><span class="sxs-lookup"><span data-stu-id="b83e1-106">For download instructions, see [How to Install Windows PowerShell and Download the Windows PowerShell SDK](/powershell/developer/installing-the-windows-powershell-sdk).</span></span>
> <span data-ttu-id="b83e1-107">Puede descargar el C# el archivo de código fuente (runspace10.cs) mediante el Kit del desarrollo de Software de Windows para Windows Vista y Microsoft .NET Framework 3.0 Runtime Components.</span><span class="sxs-lookup"><span data-stu-id="b83e1-107">You can download the C# source file (runspace10.cs) by using the Windows Software Development Kit for Windows Vista and Microsoft .NET Framework 3.0 Runtime Components.</span></span> <span data-ttu-id="b83e1-108">Para obtener instrucciones de descarga, vea [cómo instalar Windows PowerShell y descarga el SDK de Windows PowerShell](/powershell/developer/installing-the-windows-powershell-sdk).</span><span class="sxs-lookup"><span data-stu-id="b83e1-108">For download instructions, see [How to Install Windows PowerShell and Download the Windows PowerShell SDK](/powershell/developer/installing-the-windows-powershell-sdk).</span></span>
>
> <span data-ttu-id="b83e1-109">Están disponibles en los archivos de origen descargado el  **\<ejemplos de PowerShell >** directory.</span><span class="sxs-lookup"><span data-stu-id="b83e1-109">The downloaded source files are available in the **\<PowerShell Samples>** directory.</span></span>

## <a name="code-sample"></a><span data-ttu-id="b83e1-110">Ejemplo de código</span><span class="sxs-lookup"><span data-stu-id="b83e1-110">Code Sample</span></span>

[!code-csharp[Runspace10.cs](../../powershell-sdk-samples/SDK-2.0/csharp/Runspace10/Runspace10.cs#L11-L118 "Runspace10.cs")]

## <a name="see-also"></a><span data-ttu-id="b83e1-111">Véase también</span><span class="sxs-lookup"><span data-stu-id="b83e1-111">See Also</span></span>

[<span data-ttu-id="b83e1-112">Guía del programador de Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="b83e1-112">Windows PowerShell Programmer's Guide</span></span>](./windows-powershell-programmer-s-guide.md)

[<span data-ttu-id="b83e1-113">Windows PowerShell SDK</span><span class="sxs-lookup"><span data-stu-id="b83e1-113">Windows PowerShell SDK</span></span>](../windows-powershell-reference.md)