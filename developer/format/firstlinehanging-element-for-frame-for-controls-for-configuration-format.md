---
title: Elemento FirstLineHanging marco para los controles de configuración (formato) | Microsoft Docs
ms.custom: ''
ms.date: 09/13/2016
ms.reviewer: ''
ms.suite: ''
ms.tgt_pltfrm: ''
ms.topic: article
ms.assetid: 679c8bcb-b49d-4bb4-91f5-ea1af6c217e3
caps.latest.revision: 8
ms.openlocfilehash: 4553f95e48a2b1440c00b4951bea56376b00628a
ms.sourcegitcommit: e7445ba8203da304286c591ff513900ad1c244a4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "62065893"
---
# <a name="firstlinehanging-element-for-frame-for-controls-for-configuration-format"></a>Elemento FirstLineHanging para Frame for Controls for Configuration (formato)

Especifica cuántos caracteres de la primera línea de datos se desplaza a la izquierda. Este elemento se usa al definir un control común que puede usarse en todas las vistas en el archivo de formato.

Elemento de configuración (formato) elemento controles de elemento de Control de configuración (formato) para los controles de elemento de control personalizado de configuración (formato) para el Control de elemento de configuración (formato) CustomEntries para el control personalizado para la configuración ( Elemento de CustomEntry Format) para el control personalizado para los controles de elemento de configuración (formato) CustomItem para CustomEntry para los controles de elemento de marco de configuración para CustomItem para los controles de elemento de configuración (formato) FirstLineHanging de marco para los controles de configuración (formato)

## <a name="syntax"></a>Sintaxis

```xml
<FirstLineHanging>NumberOfCharactersToShift</FirstLineHanging>
```

## <a name="attributes-and-elements"></a>Atributos y elementos

Las secciones siguientes describen los atributos, elementos secundarios y elemento primario de la `FirstLineHanging` elemento.

### <a name="attributes"></a>Atributos

Ninguna.

### <a name="child-elements"></a>Elementos secundarios

Ninguna.

### <a name="parent-elements"></a>Elementos primarios

|Elemento|Descripción|
|-------------|-----------------|
|[Elemento de marco para CustomItem para los controles de configuración (formato)](./frame-element-for-customitem-for-controls-for-configuration-format.md)|Define cómo se muestran los datos, por ejemplo, cuando se desplaza los datos a la izquierda o derecha.|

## <a name="text-value"></a>Valor de texto

Especifique el número de caracteres que se desean desplazar la primera línea de los datos.

## <a name="remarks"></a>Observaciones

Si se especifica este elemento, no se puede especificar el `FirstLineIndent` elemento.

## <a name="see-also"></a>Véase también

[Elemento de marco para CustomItem para los controles de configuración (formato)](./frame-element-for-customitem-for-controls-for-configuration-format.md)

[Escribir un archivo de formato de PowerShell](./writing-a-powershell-formatting-file.md)
