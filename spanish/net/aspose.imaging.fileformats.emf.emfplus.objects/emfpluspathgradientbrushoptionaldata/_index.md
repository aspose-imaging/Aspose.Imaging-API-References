---
title: EmfPlusPathGradientBrushOptionalData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto EmfPlusPathGradientBrushOptionalData especifica datos opcionales para un pincel de degradado de ruta.
type: docs
weight: 5630
url: /es/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
## EmfPlusPathGradientBrushOptionalData class

El objeto EmfPlusPathGradientBrushOptionalData especifica datos opcionales para un pincel de degradado de ruta.

```csharp
public sealed class EmfPlusPathGradientBrushOptionalData : EmfPlusStructureObjectType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData](emfpluspathgradientbrushoptionaldata)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/blendpattern) { get; set; } | Obtiene o establece un patrón de fusión opcional para el pincel de degradado de ruta. Si este campo es presente, DEBE contener un objeto EmfPlusBlendColors (sección 2.2.2.4), o un objeto EmfPlusBlendFactors (sección 2.2.2.5), pero NO DEBE contener ambos. La siguiente tabla muestra las combinaciones válidas de indicadores EmfPlusPathGradientBrushData BrushData y los patrones de mezcla correspondientes: |
| [FocusScaleData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/focusscaledata) { get; set; } | Obtiene o establece un objeto EmfPlusFocusScaleData opcional (sección 2.2.2.18) que especifica escalas de enfoque para el pincel de degradado de ruta. Este campo DEBE estar presente si el indicador BrushDataFocusScales está establecido en el campo BrushDataFlags del objeto EmfPlusPathGradientBrushData. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/transformmatrix) { get; set; } | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado de ruta. Este campo DEBE estar presente si el indicador BrushDataTransform está establecido en el campo BrushDataFlags del objeto EmfPlusPathGradientBrushData. |

### Ver también

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
