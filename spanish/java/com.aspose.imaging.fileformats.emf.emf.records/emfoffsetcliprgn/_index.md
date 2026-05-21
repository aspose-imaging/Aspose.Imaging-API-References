---
title: "EmfOffsetClipRgn"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_OFFSETCLIPRGN desplaza la región de recorte actual en el contexto del dispositivo de reproducción por los desplazamientos especificados."
type: docs
weight: 78
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfOffsetClipRgn extends EmfClippingRecordType
```

El registro EMR\_OFFSETCLIPRGN mueve la región de recorte actual en el contexto del dispositivo de reproducción mediante los desplazamientos especificados.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfOffsetClipRgn(EmfRecord source)](#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfOffsetClipRgn`. |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn--) | Inicializa una nueva instancia de la clase `EmfOffsetClipRgn`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOffset()](#getOffset--) | Obtiene un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica los desplazamientos horizontal y vertical en unidades lógicas. |
| [setOffset(Point value)](#setOffset-com.aspose.imaging.Point-) | Establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica los desplazamientos horizontal y vertical en unidades lógicas. |
### EmfOffsetClipRgn(EmfRecord source) {#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfOffsetClipRgn(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfOffsetClipRgn`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfOffsetClipRgn() {#EmfOffsetClipRgn--}
```
public EmfOffsetClipRgn()
```


Inicializa una nueva instancia de la clase `EmfOffsetClipRgn`.

### getOffset() {#getOffset--}
```
public Point getOffset()
```


Obtiene un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica los desplazamientos horizontal y vertical en unidades lógicas.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOffset(Point value) {#setOffset-com.aspose.imaging.Point-}
```
public void setOffset(Point value)
```


Establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica los desplazamientos horizontal y vertical en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

