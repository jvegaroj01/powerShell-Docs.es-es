---
ms.date: 06/12/2017
keywords: dsc,powershell,configuration,setup
title: Recurso WaitForSome de DSC
ms.openlocfilehash: 888da1810f0a9233579bad5eef8d5dd556947c61
ms.sourcegitcommit: e7445ba8203da304286c591ff513900ad1c244a4
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "62076861"
---
# <a name="dsc-waitforsome-resource"></a>Recurso WaitForSome de DSC

> Se aplica a: Windows PowerShell 5.0 y versiones posteriores

El recurso **WaitForSome** de Desired State Configuration (DSC) se puede usar dentro de un bloque de nodos en una [configuración de DSC](../../../configurations/configurations.md) para especificar las dependencias de las configuraciones de otros nodos.

Este recurso se ejecuta si el recurso especificado por la propiedad **ResourceName** está en el estado deseado en un número mínimo de nodos (especificado por **NodeCount**) definido por la propiedad **NodeName**.


## <a name="syntax"></a>Sintaxis

```
WaitForSome [String] #ResourceName
{
    NodeCount = [UInt32]
    NodeName = [string[]]
    ResourceName = [string]
    [DependsOn = [string[]]]
    [PsDscRunAsCredential = [PSCredential]]
    [RetryCount = [UInt32]]
    [RetryIntervalSec = [UInt64]]
    [ThrottleLimit = [UInt32]]
}
```

## <a name="properties"></a>Propiedades

|  Propiedad  |  Descripción   |
|---|---|
| NodeCount| El número mínimo de nodos que deben tener el estado deseado para que se ejecute este recurso.|
| NodeName| Los nodos de destino del recurso de dependencia.|
| nombreDelRecurso| El nombre del recurso de dependencia. Si el recurso pertenece a una configuración diferente, asegúrese de que el formato del nombre sea el siguiente: "[__TipoDeRecurso__]__NombreDeRecurso__::[__NombreDeConfiguración__]::[__NombreDeConfiguración__]".|
| RetryIntervalSec| El número de segundos antes de reintentar la operación. El valor mínimo es 1.|
| RetryCount| El número máximo de reintentos.|
| ThrottleLimit| El número de máquinas que se pueden conectar de forma simultánea. El valor predeterminado es new-cimsession.|
| DependsOn | Indica que la configuración de otro recurso debe ejecutarse antes de que se configure este recurso. Por ejemplo, si el elemento ID del bloque del script de configuración del recurso que quiere ejecutar primero es __ResourceName__ y su tipo es __ResourceType__, la sintaxis para usar esta propiedad es `DependsOn = "[ResourceType]ResourceName"`.|
| PsDscRunAsCredential | Consulte el artículo sobre el [uso de DSC con credenciales de usuario](https://docs.microsoft.com/powershell/dsc/runasuser) |

## <a name="example"></a>Ejemplo

Para un ejemplo de cómo usar este recurso, consulte [Especificación de dependencias entre nodos](../../../configurations/crossNodeDependencies.md)
