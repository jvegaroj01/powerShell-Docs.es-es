---
ms.date: 06/12/2017
keywords: dsc,powershell,configuration,setup
title: Método RemoveConfiguration de la clase MSFT_DSCLocalConfigurationManager
ms.openlocfilehash: 03555cc73da1272bdebebc3d93b26aaf8fabc18e
ms.sourcegitcommit: e04292a9c10de9a8391d529b7f7aa3753b362dbe
ms.translationtype: MTE95
ms.contentlocale: es-ES
ms.lasthandoff: 01/04/2019
ms.locfileid: "54048038"
---
# <a name="removeconfiguration-method-of-the-msftdsclocalconfigurationmanager-class"></a>Método RemoveConfiguration de la clase MSFT_DSCLocalConfigurationManager

Quita los archivos de configuración.

## <a name="syntax"></a>Sintaxis

```mof
uint32 RemoveConfiguration(
  [in] uint32  Stage,
  [in] boolean Force
);
```

## <a name="parameters"></a>Parámetros

*Stage* \[in\] Especifica qué documento de configuración quiere quitar. Los valores siguientes son válidos:

|Value |Descripción |
|:--- |:---|
|**1** | Documento de configuración **Current** (current.mof). |
|**2** | Documento de configuración **Pending** (pending.mof).  |
|**4** | Documento de configuración **Previous** (previous.mof). |

*Force* \[in\] **true** para forzar la eliminación de la configuración.

## <a name="return-value"></a>Valor devuelto

Devuelve cero si se ejecuta correctamente; de lo contrario, devuelve un código de error.

## <a name="remarks"></a>Observaciones

Se trata de un método estático.

## <a name="requirements"></a>Requisitos

MOF** DscCore.mof

Espacio de nombres {0} Root\Microsoft\Windows\DesiredStateConfiguration

## <a name="see-also"></a>Vea también

[**MSFT_DSCLocalConfigurationManager**](msft-dsclocalconfigurationmanager.md)