---
title: EmfPolyPolygon
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_POLYPOLYGON especifica una serie de polígonos cerrados.
type: docs
weight: 4020
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---
## EmfPolyPolygon class

El registro EMR_POLYPOLYGON especifica una serie de polígonos cerrados.

```csharp
public sealed class EmfPolyPolygon : EmfDrawingRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPolyPolygon](emfpolypolygon#constructor)() | Inicializa una nueva instancia del[`EmfPolyPolygon`](../emfpolypolygon) clase. |
| [EmfPolyPolygon](emfpolypolygon#constructor_1)(EmfRecord) | Inicializa una nueva instancia del[`EmfPolyPolygon`](../emfpolypolygon) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/apoints) { get; set; } | Obtiene o establece una matriz de objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica los puntos para todos los polígonos en unidades lógicas. El número de puntos se especifica mediante el valor del campo de recuento . |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo delimitador , en unidades de dispositivo. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |

### Observaciones

Cada polígono DEBE delinearse con el lápiz actual y rellenarse con el pincel actual y el modo de relleno de polígono que se definen en el contexto del dispositivo de reproducción. Los polígonos definidos por este registro pueden superponerse.

### Ver también

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
