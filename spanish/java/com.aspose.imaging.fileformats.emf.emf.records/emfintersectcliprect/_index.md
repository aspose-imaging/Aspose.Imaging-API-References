---
title: "EmfIntersectClipRect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_INTERSECTCLIPRECT especifica una nueva región de recorte a partir de la intersección de la región de recorte actual y el rectángulo especificado."
type: docs
weight: 66
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

El registro EMR\_INTERSECTCLIPRECT especifica una nueva región de recorte a partir de la intersección de la región de recorte actual y el rectángulo especificado. Nota: los campos que no se describen en esta sección se especifican en la sección 2.3.2.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfIntersectClipRect`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getClip()](#getClip--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo en unidades lógicas. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo en unidades lógicas. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfIntersectClipRect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo en unidades lógicas.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

