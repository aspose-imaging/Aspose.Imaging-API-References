---
title: EmfPlusPenData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto EmfPlusPenData especifica las propiedades de una pluma gráfica.
type: docs
weight: 5670
url: /es/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
## EmfPlusPenData class

El objeto EmfPlusPenData especifica las propiedades de una pluma gráfica.

```csharp
public sealed class EmfPlusPenData : EmfPlusStructureObjectType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusPenData](emfpluspendata)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/optionaldata) { get; set; } | Obtiene o establece el objeto opcional EmfPlusPenOptionalData (sección 2.2.2.34) que especifica datos adicionales para el objeto pluma. El contenido específico de este campo está determinado por el valor del campo PenDataFlags. |
| [PenDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/pendataflags) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. Este valor DEBE estar compuesto por banderas PenData (sección 2.1.2.7). |
| [PenUnit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penunit) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica las unidades de medida para la pluma. El valor DEBE ser de la enumeración UnitType (sección 2.1.1.33). |
| [PenWidth](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penwidth) { get; set; } | Obtiene o establece un valor de coma flotante de 32 bits que especifica el ancho de la línea dibujada por la pluma en las unidades especificadas por el campo PenUnit . Si se especifica un ancho cero, se usa un valor mínimo, que está determinado por las unidades |

### Ver también

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->