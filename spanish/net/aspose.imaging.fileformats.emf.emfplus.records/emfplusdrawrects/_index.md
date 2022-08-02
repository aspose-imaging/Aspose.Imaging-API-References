---
title: EmfPlusDrawRects
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusDrawRects especifica dibujar una serie de rectángulos
type: docs
weight: 6010
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
## EmfPlusDrawRects class

El registro EmfPlusDrawRects especifica dibujar una serie de rectángulos

```csharp
public sealed class EmfPlusDrawRects : EmfPlusDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusDrawRects](emfplusdrawrects)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusDrawRects`](../emfplusdrawrects) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/compressed) { get; set; } | Obtiene o establece un valor que indica si PointData está comprimido. Si se establece, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está claro, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/objectid) { get; set; } | Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar los rectángulos. El valor DEBE ser cero a 63, inclusive. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/rectdata) { get; set; } | Obtiene o establece los datos rect. Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Ver también

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->