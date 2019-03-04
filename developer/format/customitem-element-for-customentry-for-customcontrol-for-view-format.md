---
title: Elemento CustomItem para CustomEntry para el control personalizado para la vista (formato) | Microsoft Docs
ms.custom: ''
ms.date: 09/13/2016
ms.reviewer: ''
ms.suite: ''
ms.tgt_pltfrm: ''
ms.topic: article
ms.assetid: 98708c1d-6f39-4a76-b454-31153a6ade8c
caps.latest.revision: 12
ms.openlocfilehash: 3c110bd5fe3ef2f790ef136556afa7c29d0b5b29
ms.sourcegitcommit: b6871f21bd666f9cd71dd336bb3f844cf472b56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/03/2019
ms.locfileid: "56856191"
---
# <a name="customitem-element-for-customentry-for-customcontrol-for-view-format"></a><span data-ttu-id="a7501-102">Elemento CustomItem para CustomEntry for CustomControl for View (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-102">CustomItem Element for CustomEntry for CustomControl for View (Format)</span></span>

<span data-ttu-id="a7501-103">Define qué datos se muestran la vista de control personalizado y cómo se muestran.</span><span class="sxs-lookup"><span data-stu-id="a7501-103">Defines what data is displayed by the custom control view and how it is displayed.</span></span> <span data-ttu-id="a7501-104">Este elemento se usa al definir una vista de control personalizado.</span><span class="sxs-lookup"><span data-stu-id="a7501-104">This element is used when defining a custom control view.</span></span>

<span data-ttu-id="a7501-105">Elemento (formato) elemento ViewDefinitions (formato) vista elemento (formato) el elemento de control personalizado (formato) CustomEntries elemento de configuración control personalizado de vista (formato) del elemento CustomEntry para CustomEntries de vista (formato) del elemento CustomItem para CustomEntry para vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-105">Configuration Element (Format) ViewDefinitions Element (Format) View Element (Format) CustomControl Element (Format) CustomEntries Element for CustomControl for View (Format) CustomEntry Element for CustomEntries for View (Format) CustomItem Element for CustomEntry for View (Format)</span></span>

## <a name="syntax"></a><span data-ttu-id="a7501-106">Sintaxis</span><span class="sxs-lookup"><span data-stu-id="a7501-106">Syntax</span></span>

```xml
<CustomItem>
  <ExpressionBinding>...</ExpressionBinding>
  <Frame>...</Frame>
  <NewLine/>
  <Text>TextToDisplay</Text>
</CustomItem>
```

## <a name="attributes-and-elements"></a><span data-ttu-id="a7501-107">Atributos y elementos</span><span class="sxs-lookup"><span data-stu-id="a7501-107">Attributes and Elements</span></span>

<span data-ttu-id="a7501-108">Las secciones siguientes describen los atributos, elementos secundarios y el elemento primario de la `CustomItem` elemento.</span><span class="sxs-lookup"><span data-stu-id="a7501-108">The following sections describe attributes, child elements, and the parent element of the `CustomItem` element.</span></span>

### <a name="attributes"></a><span data-ttu-id="a7501-109">Atributos</span><span class="sxs-lookup"><span data-stu-id="a7501-109">Attributes</span></span>

<span data-ttu-id="a7501-110">Ninguna.</span><span class="sxs-lookup"><span data-stu-id="a7501-110">None.</span></span>

### <a name="child-elements"></a><span data-ttu-id="a7501-111">Elementos secundarios</span><span class="sxs-lookup"><span data-stu-id="a7501-111">Child Elements</span></span>

|<span data-ttu-id="a7501-112">Elemento</span><span class="sxs-lookup"><span data-stu-id="a7501-112">Element</span></span>|<span data-ttu-id="a7501-113">Descripción</span><span class="sxs-lookup"><span data-stu-id="a7501-113">Description</span></span>|
|-------------|-----------------|
|[<span data-ttu-id="a7501-114">Elemento ExpressionBinding para CustomItem para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-114">ExpressionBinding Element for CustomItem for CustomControl for View (Format)</span></span>](./expressionbinding-element-for-customitem-for-customcontrol-for-view-format.md)|<span data-ttu-id="a7501-115">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="a7501-115">Optional element.</span></span><br /><br /> <span data-ttu-id="a7501-116">Define los datos que se muestran el control.</span><span class="sxs-lookup"><span data-stu-id="a7501-116">Defines the data that is displayed by the control.</span></span>|
|[<span data-ttu-id="a7501-117">Elemento de marco para CustomItem para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-117">Frame Element for CustomItem for CustomControl for View (Format)</span></span>](./frame-element-for-customitem-for-customcontrol-for-view-format.md)|<span data-ttu-id="a7501-118">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="a7501-118">Optional element.</span></span><br /><br /> <span data-ttu-id="a7501-119">Define qué datos se muestran la vista de control personalizado y cómo se muestran.</span><span class="sxs-lookup"><span data-stu-id="a7501-119">Defines what data is displayed by the custom control view and how it is displayed.</span></span>|
|[<span data-ttu-id="a7501-120">Elemento de nueva línea para CustomItem para un Control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-120">NewLine Element for CustomItem for Custom Control for View (Format)</span></span>](./newline-element-for-customitem-for-customcontrol-for-view-format.md)|<span data-ttu-id="a7501-121">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="a7501-121">Optional element.</span></span><br /><br /> <span data-ttu-id="a7501-122">Agrega una línea en blanco a la presentación del control.</span><span class="sxs-lookup"><span data-stu-id="a7501-122">Adds a blank line to the display of the control.</span></span>|
|[<span data-ttu-id="a7501-123">Elemento de texto para CustomItem para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-123">Text Element for CustomItem for CustomControl for View (Format)</span></span>](./text-element-for-customitem-for-customview-for-view-format.md)|<span data-ttu-id="a7501-124">Elemento opcional.</span><span class="sxs-lookup"><span data-stu-id="a7501-124">Optional element.</span></span><br /><br /> <span data-ttu-id="a7501-125">Especifica que los datos mostrados por el control de texto adicional.</span><span class="sxs-lookup"><span data-stu-id="a7501-125">Specifies additional text to the data displayed by the control.</span></span>|

### <a name="parent-elements"></a><span data-ttu-id="a7501-126">Elementos primarios</span><span class="sxs-lookup"><span data-stu-id="a7501-126">Parent Elements</span></span>

|<span data-ttu-id="a7501-127">Elemento</span><span class="sxs-lookup"><span data-stu-id="a7501-127">Element</span></span>|<span data-ttu-id="a7501-128">Descripción</span><span class="sxs-lookup"><span data-stu-id="a7501-128">Description</span></span>|
|-------------|-----------------|
|[<span data-ttu-id="a7501-129">Elemento CustomEntry para CustomEntries para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-129">CustomEntry Element for CustomEntries for CustomControl for View (Format)</span></span>](./customentry-element-for-customentries-for-customcontrol-for-view-format.md)|<span data-ttu-id="a7501-130">Proporciona una definición de la vista de control personalizado.</span><span class="sxs-lookup"><span data-stu-id="a7501-130">Provides a definition of the custom control view.</span></span>|

## <a name="remarks"></a><span data-ttu-id="a7501-131">Observaciones</span><span class="sxs-lookup"><span data-stu-id="a7501-131">Remarks</span></span>

## <a name="see-also"></a><span data-ttu-id="a7501-132">Véase también</span><span class="sxs-lookup"><span data-stu-id="a7501-132">See Also</span></span>

[<span data-ttu-id="a7501-133">Elemento CustomEntry para CustomEntries para vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-133">CustomEntry Element for CustomEntries for View (Format)</span></span>](./customentry-element-for-customentries-for-customcontrol-for-view-format.md)

[<span data-ttu-id="a7501-134">Elemento ExpressionBinding para CustomItem para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-134">ExpressionBinding Element for CustomItem for CustomControl for View (Format)</span></span>](./expressionbinding-element-for-customitem-for-customcontrol-for-view-format.md)

[<span data-ttu-id="a7501-135">Elemento de marco para CustomItem para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-135">Frame Element for CustomItem for CustomControl for View (Format)</span></span>](./frame-element-for-customitem-for-customcontrol-for-view-format.md)

[<span data-ttu-id="a7501-136">Elemento de nueva línea para CustomItem para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-136">NewLine Element for CustomItem for CustomControl for View (Format)</span></span>](./newline-element-for-customitem-for-customcontrol-for-view-format.md)

[<span data-ttu-id="a7501-137">Elemento de texto para CustomItem para el control personalizado para la vista (formato)</span><span class="sxs-lookup"><span data-stu-id="a7501-137">Text Element for CustomItem for CustomControl for View (Format)</span></span>](./text-element-for-customitem-for-customview-for-view-format.md)

[<span data-ttu-id="a7501-138">Escribir un archivo de formato de PowerShell</span><span class="sxs-lookup"><span data-stu-id="a7501-138">Writing a PowerShell Formatting File</span></span>](./writing-a-powershell-formatting-file.md)