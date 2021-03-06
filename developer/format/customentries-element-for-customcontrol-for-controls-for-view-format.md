---
title: Elemento CustomEntries para el control personalizado para los controles de vista (formato) | Microsoft Docs
ms.custom: ''
ms.date: 09/13/2016
ms.reviewer: ''
ms.suite: ''
ms.tgt_pltfrm: ''
ms.topic: article
ms.assetid: 3485958a-ba87-4932-907c-a8f140c4abdb
caps.latest.revision: 8
ms.openlocfilehash: 4856aee930285781a101868bd6cb67824585bce1
ms.sourcegitcommit: e7445ba8203da304286c591ff513900ad1c244a4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "62066590"
---
# <a name="customentries-element-for-customcontrol-for-controls-for-view-format"></a>Elemento CustomEntries para CustomControl for Controls for View (formato)

Proporciona las definiciones para el control. Este elemento se usa al definir los controles que pueden usarse en una vista.

Elemento (formato) elemento ViewDefinitions (formato) vista elemento (formato) controles (formato) del elemento Control elemento de configuración para los controles de elemento de control personalizado (formato) de la vista de Control para los controles de elemento de vista (formato) CustomEntries para Control personalizado para los controles de vista (formato)

## <a name="syntax"></a>Sintaxis

```xml
<CustomEntries>
  <CustomEntry>...</CustomEntry>
</CustomEntries>
```

## <a name="attributes-and-elements"></a>Atributos y elementos

Las secciones siguientes describen los atributos, elementos secundarios y elementos primarios de la `CustomEntries` elemento. No hay ningún límite máximo para el número de elementos secundarios que se pueden especificar.

### <a name="attributes"></a>Atributos

Ninguna.

### <a name="child-elements"></a>Elementos secundarios

|Elemento|Descripción|
|-------------|-----------------|
|[Elemento CustomEntry para CustomEntries para los controles de vista (formato)](./customentry-element-for-customentries-for-controls-for-view-format.md)|Elemento necesario.<br /><br /> Proporciona una definición del control.|

### <a name="parent-elements"></a>Elementos primarios

|Elemento|Descripción|
|-------------|-----------------|
|[Elemento de control personalizado para el Control para los controles de vista (formato)](./customcontrol-element-for-control-for-controls-for-view-format.md)|Define el control utilizado por la vista.|

## <a name="remarks"></a>Observaciones

En la mayoría de los casos, un control tiene solo una definición, que se especifica en una sola `CustomEntry` elemento. Sin embargo, es posible proporcionar varias definiciones si desea utilizar el mismo control para mostrar diferentes objetos. NET. En esos casos, puede definir un `CustomEntry` (elemento) para cada objeto o conjunto de objetos.

## <a name="see-also"></a>Véase también

[Elemento CustomEntry para CustomEntries para los controles de vista (formato)](./customentry-element-for-customentries-for-controls-for-view-format.md)

[Elemento de control personalizado para el Control para los controles de vista (formato)](./customcontrol-element-for-control-for-controls-for-view-format.md)

[Escribir un archivo de formato de PowerShell](./writing-a-powershell-formatting-file.md)
