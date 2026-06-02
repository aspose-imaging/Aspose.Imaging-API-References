---
title: "EmfExcludeClipRect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EXCLUDECLIPRECT especifica una nueva región de recorte que consiste en la región de recorte existente menos el rectángulo especificado."
type: docs
weight: 50
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

El registro EMR\\_EXCLUDECLIPRECT especifica una nueva región de recorte que consiste en la región de recorte existente menos el rectángulo especificado. Nota: los campos que no se describen en esta sección se especifican en la sección 2.3.2.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfExcludeClipRect`. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Inicializa una nueva instancia de la clase `EmfExcludeClipRect`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getClip()](#getClip--) | Obtiene un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de recorte en unidades lógicas. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de recorte en unidades lógicas. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfExcludeClipRect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Inicializa una nueva instancia de la clase `EmfExcludeClipRect`.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Obtiene un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de recorte en unidades lógicas.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de recorte en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

