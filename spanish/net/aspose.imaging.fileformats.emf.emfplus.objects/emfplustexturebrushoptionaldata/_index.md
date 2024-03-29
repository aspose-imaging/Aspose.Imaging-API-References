---
title: EmfPlusTextureBrushOptionalData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto EmfPlusTextureBrushOptionalData especifica datos opcionales para un pincel de textura.
type: docs
weight: 5820
url: /es/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
## EmfPlusTextureBrushOptionalData class

El objeto EmfPlusTextureBrushOptionalData especifica datos opcionales para un pincel de textura.

```csharp
public sealed class EmfPlusTextureBrushOptionalData : EmfPlusStructureObjectType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusTextureBrushOptionalData](emfplustexturebrushoptionaldata)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ImageObject](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/imageobject) { get; set; } | Obtiene o establece un objeto EmfPlusImage opcional (sección 2.2.1.4) que especifica la textura del pincel . Este campo DEBE estar presente si el tamaño del registro EmfPlusObject (sección 2.3.5.1) que define este pincel de textura es lo suficientemente grande como para acomodar un objeto EmfPlusImage en además de los campos obligatorios del objeto EmfPlusTextureBrushData y, opcionalmente, un objeto EmfPlusTransformMatrix . |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/transformmatrix) { get; set; } | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de textura . Este campo DEBE estar presente si el indicador BrushDataTransform está establecido en el campo BrushDataFlags del objeto EmfPlusTextureBrushData. |

### Observaciones

Nota Cada campo de este objeto es opcional y puede no estar presente en el campo OptionalData de un objeto EmfPlusTextureBrushData (sección 2.2.2.45), dependiendo de las banderas BrushData (sección 2.1.2.1) establecidas en su campo BrushDataFlags. Aunque no lo es práctica para representar cada combinación posible de campos presentes o ausentes, esta sección especifica su orden relativo en el objeto. El implementador de es responsable de determinar qué campos están realmente presentes en un registro de metarchivo dado, y de descifrar los datos para campos individuales por separado y de manera apropiada.

### Ver también

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
