---
title: Elemento FirstLineHanging marco para los controles de vista (formato) | Microsoft Docs
ms.custom: ''
ms.date: 09/13/2016
ms.reviewer: ''
ms.suite: ''
ms.tgt_pltfrm: ''
ms.topic: article
ms.assetid: 53694f08-57f7-4185-b443-1636a0918afc
caps.latest.revision: 8
ms.openlocfilehash: 387340cd9b0aae2ad0419b187d96ab4fee183d5a
ms.sourcegitcommit: e7445ba8203da304286c591ff513900ad1c244a4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "62065814"
---
# <a name="firstlinehanging-element-for-frame-for-controls-for-view-format"></a>Elemento FirstLineHanging para Frame for Controls for View (formato)

Especifica cuántos caracteres de la primera línea de datos se desplaza a la izquierda. Este elemento se usa al definir los controles que pueden usarse en una vista.

Elemento (formato) elemento ViewDefinitions (formato) vista elemento (formato) controles (formato) del elemento Control elemento de configuración para los controles de elemento de control personalizado (formato) de la vista de Control para los controles de elemento de vista (formato) CustomEntries para Control personalizado de vista (formato) del elemento CustomEntry para CustomEntries para los controles de elemento de vista (formato) CustomItem para CustomEntry para los controles de elemento de marco de vista (formato) para CustomItem para los controles de vista (formato) FirstLineHanging del elemento de Marco de controles de vista (formato)

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
|[Elemento de marco para CustomItem para los controles de vista (formato)](./frame-element-for-customitem-for-controls-for-view-format.md)|Define cómo se muestran los datos, por ejemplo, cuando se desplaza los datos a la izquierda o derecha.|

## <a name="text-value"></a>Valor de texto

Especifique el número de caracteres que se desean desplazar la primera línea de los datos.

## <a name="remarks"></a>Observaciones

Si se especifica este elemento, no se puede especificar el [FirstLineIndent](./firstlineindent-element-for-frame-for-controls-for-view-format.md) elemento.

## <a name="see-also"></a>Véase también

[Elemento FirstLineIndent marco para los controles de vista (formato)](./firstlineindent-element-for-frame-for-controls-for-view-format.md)

[Elemento de marco para CustomItem para los controles de vista (formato)](./frame-element-for-customitem-for-controls-for-view-format.md)

[Escribir un archivo de formato de PowerShell](./writing-a-powershell-formatting-file.md)
