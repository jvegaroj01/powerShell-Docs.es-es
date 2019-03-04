---
title: Elemento ExpressionBinding para CustomItem para los controles de configuración (formato) | Microsoft Docs
ms.custom: ''
ms.date: 09/13/2016
ms.reviewer: ''
ms.suite: ''
ms.tgt_pltfrm: ''
ms.topic: article
ms.assetid: c6649d07-4762-4602-9b4b-d9e2e9e63312
caps.latest.revision: 13
ms.openlocfilehash: 531ff447f8407a737131a38351d7e4c6e7da90fb
ms.sourcegitcommit: b6871f21bd666f9cd71dd336bb3f844cf472b56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/03/2019
ms.locfileid: "56855141"
---
# <a name="expressionbinding-element-for-customitem-for-controls-for-configuration-format"></a><span data-ttu-id="f672d-102">Elemento ExpressionBinding para CustomItem for Controls for Configuration (formato)</span><span class="sxs-lookup"><span data-stu-id="f672d-102">ExpressionBinding Element for CustomItem for Controls for Configuration (Format)</span></span>

<span data-ttu-id="f672d-103">Define los datos que se muestran el control.</span><span class="sxs-lookup"><span data-stu-id="f672d-103">Defines the data that is displayed by the control.</span></span> <span data-ttu-id="f672d-104">Este elemento se usa al definir un control común que puede usarse en todas las vistas en el archivo de formato.</span><span class="sxs-lookup"><span data-stu-id="f672d-104">This element is used when defining a common control that can be used by all the views in the formatting file.</span></span>

<span data-ttu-id="f672d-105">Elemento de configuración (formato) elemento controles de elemento de Control de configuración (formato) para los controles de elemento de control personalizado de configuración (formato) para el Control de elemento de configuración (formato) CustomEntries para el control personalizado para la configuración ( Elemento de CustomEntry Format) para el control personalizado para los controles de elemento de configuración (formato) CustomItem para CustomEntry para los controles de elemento de configuración ExpressionBinding CustomItem para los controles de configuración (formato)</span><span class="sxs-lookup"><span data-stu-id="f672d-105">Configuration Element (Format) Controls Element of Configuration (Format) Control Element for Controls for Configuration (Format) CustomControl Element for Control for Configuration (Format) CustomEntries Element for CustomControl for Configuration (Format) CustomEntry Element for CustomControl for Controls for Configuration (Format) CustomItem Element for CustomEntry for Controls for Configuration ExpressionBinding Element for CustomItem for Controls for Configuration (Format)</span></span>

## <a name="syntax"></a><span data-ttu-id="f672d-106">Sintaxis</span><span class="sxs-lookup"><span data-stu-id="f672d-106">Syntax</span></span>

```xml
<ExpressionBinding>
  <CustomControl>...</CustomControl>
  <CustomControlName>NameofCommonCustomControl</CustomControlName>
  <EnumerateCollection/>
  <ItemSelectionCondition>...</ItemSelectionCondition>
  <PropertyName>Nameof.NetTypeProperty</PropertyName>
  <ScriptBlock>ScriptToEvaluate></ScriptBlock>
</ExpressionBinding>
```

## <a name="attributes-and-elements"></a><span data-ttu-id="f672d-107">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="f672d-107">Attributes and Elements</span></span>

<span data-ttu-id="f672d-108">Las secciones siguientes describen los atributos, elementos secundarios y el elemento primario de la `ExpressionBinding` elemento.</span><span class="sxs-lookup"><span data-stu-id="f672d-108">The following sections describe attributes, child elements, and the parent element of the `ExpressionBinding` element.</span></span>

### <a name="attributes"></a><span data-ttu-id="f672d-109">Atributos</span><span class="sxs-lookup"><span data-stu-id="f672d-109">Attributes</span></span>

<span data-ttu-id="f672d-110">Ninguna.</span><span class="sxs-lookup"><span data-stu-id="f672d-110">None.</span></span>

### <a name="child-elements"></a><span data-ttu-id="f672d-111">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="f672d-111">Child Elements</span></span>

|<span data-ttu-id="f672d-112">Elemento</span><span class="sxs-lookup"><span data-stu-id="f672d-112">Element</span></span>|<span data-ttu-id="f672d-113">Descripción</span><span class="sxs-lookup"><span data-stu-id="f672d-113">Description</span></span>|
|-------------|-----------------|
|`CustomControl Element`|<span data-ttu-id="f672d-114">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="f672d-114">Optional element.</span></span><br /><br /> <span data-ttu-id="f672d-115">Define un control que se usa este control.</span><span class="sxs-lookup"><span data-stu-id="f672d-115">Defines a control that is used by this control.</span></span>|
|[<span data-ttu-id="f672d-116">Elemento CustomControlName para ExpressionBinding para los controles de configuración (formato)</span><span class="sxs-lookup"><span data-stu-id="f672d-116">CustomControlName Element for ExpressionBinding for Controls for Configuration (Format)</span></span>](./customcontrolname-element-for-expressionbinding-for-controls-for-configuration-format.md)|<span data-ttu-id="f672d-117">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="f672d-117">Optional element.</span></span><br /><br /> <span data-ttu-id="f672d-118">Especifica el nombre de un control común o un control de vista.</span><span class="sxs-lookup"><span data-stu-id="f672d-118">Specifies the name of a common control or a view control.</span></span>|
|[<span data-ttu-id="f672d-119">Elemento EnumerateCollection para ExpressionBinding para los controles de configuración (formato)</span><span class="sxs-lookup"><span data-stu-id="f672d-119">EnumerateCollection Element for ExpressionBinding for Controls for Configuration (Format)</span></span>](./enumeratecollection-element-for-expressionbinding-for-controls-for-configuration-format.md)|<span data-ttu-id="f672d-120">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="f672d-120">Optional element.</span></span><br /><br /> <span data-ttu-id="f672d-121">Especifica que se muestran los elementos de colecciones mediante el control.</span><span class="sxs-lookup"><span data-stu-id="f672d-121">Specified that the elements of collections are displayed by the control.</span></span>|
|[<span data-ttu-id="f672d-122">Elemento ItemSelectionCondition para ExpressionBinding para los controles de configuración (formato)</span><span class="sxs-lookup"><span data-stu-id="f672d-122">ItemSelectionCondition Element for ExpressionBinding for Controls for Configuration (Format)</span></span>](./itemselectioncondition-element-for-expressionbinding-for-controls-for-configuration-format.md)|<span data-ttu-id="f672d-123">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="f672d-123">Optional element.</span></span><br /><br /> <span data-ttu-id="f672d-124">Define la condición que debe existir para que este control común que se usará.</span><span class="sxs-lookup"><span data-stu-id="f672d-124">Defines the condition that must exist for this common control to be used.</span></span>|
|[<span data-ttu-id="f672d-125">Elemento PropertyName para ExpressionBinding para los controles de configuración (formato)</span><span class="sxs-lookup"><span data-stu-id="f672d-125">PropertyName Element for ExpressionBinding for Controls for Configuration (Format)</span></span>](./propertyname-element-for-expressionbinding-for-controls-for-configuration-format.md)|<span data-ttu-id="f672d-126">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="f672d-126">Optional element.</span></span><br /><br /> <span data-ttu-id="f672d-127">Especifica la propiedad de .NET cuyo valor se muestra el control común.</span><span class="sxs-lookup"><span data-stu-id="f672d-127">Specifies the .NET property whose value is displayed by the common control.</span></span>|
|[<span data-ttu-id="f672d-128">Elemento de bloque de script para ExpressionBinding para los controles de configuración (formato)</span><span class="sxs-lookup"><span data-stu-id="f672d-128">ScriptBlock Element for ExpressionBinding for Controls for Configuration (Format)</span></span>](./scriptblock-element-for-expressionbinding-for-controls-for-configuration-format.md)|<span data-ttu-id="f672d-129">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="f672d-129">Optional element.</span></span><br /><br /> <span data-ttu-id="f672d-130">Especifica la secuencia de comandos cuyo valor se muestra el control común.</span><span class="sxs-lookup"><span data-stu-id="f672d-130">Specifies the script whose value is displayed by the common control.</span></span>|

### <a name="parent-elements"></a><span data-ttu-id="f672d-131">Elementos primarios</span><span class="sxs-lookup"><span data-stu-id="f672d-131">Parent Elements</span></span>

|<span data-ttu-id="f672d-132">Elemento</span><span class="sxs-lookup"><span data-stu-id="f672d-132">Element</span></span>|<span data-ttu-id="f672d-133">Descripción</span><span class="sxs-lookup"><span data-stu-id="f672d-133">Description</span></span>|
|-------------|-----------------|
|[<span data-ttu-id="f672d-134">Elemento CustomItem para CustomEntry para los controles de configuración</span><span class="sxs-lookup"><span data-stu-id="f672d-134">CustomItem Element for CustomEntry for Controls for Configuration</span></span>](./customitem-element-for-customentry-for-controls-for-configuration-format.md)|<span data-ttu-id="f672d-135">Define qué datos se muestran la vista de control personalizado y cómo se muestran.</span><span class="sxs-lookup"><span data-stu-id="f672d-135">Defines what data is displayed by the custom control view and how it is displayed.</span></span>|

## <a name="remarks"></a><span data-ttu-id="f672d-136">Observaciones</span><span class="sxs-lookup"><span data-stu-id="f672d-136">Remarks</span></span>

## <a name="see-also"></a><span data-ttu-id="f672d-137">Véase también</span><span class="sxs-lookup"><span data-stu-id="f672d-137">See Also</span></span>

[<span data-ttu-id="f672d-138">Elemento CustomItem para CustomEntry para los controles de configuración</span><span class="sxs-lookup"><span data-stu-id="f672d-138">CustomItem Element for CustomEntry for Controls for Configuration</span></span>](./customitem-element-for-customentry-for-controls-for-configuration-format.md)

[<span data-ttu-id="f672d-139">Escribir un archivo de formato de PowerShell</span><span class="sxs-lookup"><span data-stu-id="f672d-139">Writing a PowerShell Formatting File</span></span>](./writing-a-powershell-formatting-file.md)