---
title: EmfPlusLinearGradientBrushOptionalData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto EmfPlusLinearGradientBrushOptionalData especifica datos opcionales para un pincel de degradado lineal.
type: docs
weight: 5570
url: /es/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
## EmfPlusLinearGradientBrushOptionalData class

El objeto EmfPlusLinearGradientBrushOptionalData especifica datos opcionales para un pincel de degradado lineal.

```csharp
public sealed class EmfPlusLinearGradientBrushOptionalData : EmfPlusStructureObjectType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData](emfpluslineargradientbrushoptionaldata)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpattern) { get; set; } | Obtiene o establece un patrón de fusión opcional para el pincel de degradado lineal. Si este campo está presente, DEBE contener un objeto EmfPlusBlendColors (sección 2.2.2.4), o uno o dos objetos EmfPlusBlendFactors (sección 2.2.2.5), pero NO DEBE contener ambos. La siguiente tabla muestra las combinaciones válidas de indicadores EmfPlusLinearGradientBrushData BrushData y los patrones de combinación correspondientes: EmfPlusBlendFactors |
| [BlendPatternAsBlendFactorsH](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsh) { get; } | Obtiene el patrón de fusión como factores de fusión h. |
| [BlendPatternAsBlendFactorsV](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsv) { get; } | Obtiene el patrón de mezcla como factores de mezcla v. |
| [BlendPatternAsPresetColors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternaspresetcolors) { get; } | Obtiene el patrón de fusión como colores preestablecidos. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/transformmatrix) { get; set; } | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) que especifica una transformación de espacio mundial a espacio de dispositivo para el pincel de degradado lineal. Este campo DEBE estar presente si el indicador BrushDataTransform está establecido en el campo BrushDataFlags del objeto EmfPlusLinearGradientBrushData. |

### Ver también

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
