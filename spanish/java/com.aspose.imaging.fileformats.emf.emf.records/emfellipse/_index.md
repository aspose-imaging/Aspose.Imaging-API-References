---
title: "EmfEllipse"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_ELLIPSE especifica una elipse."
type: docs
weight: 46
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfEllipse extends EmfDrawingRecordType
```

El registro EMR\\_ELLIPSE especifica una elipse. El centro de la elipse es el centro del rectángulo delimitador especificado. La elipse se traza usando la pluma actual y se rellena usando el pincel actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfEllipse(EmfRecord source)](#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfEllipse`. |
| [EmfEllipse()](#EmfEllipse--) | Inicializa una nueva instancia de la clase `EmfEllipse`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBox()](#getBox--) | Obtiene o establece un objeto RectL de 128 bits (WMF), especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador inclusivo-inclusivo. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto RectL de 128 bits (WMF), especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador inclusivo-inclusivo. |
### EmfEllipse(EmfRecord source) {#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEllipse(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfEllipse`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfEllipse() {#EmfEllipse--}
```
public EmfEllipse()
```


Inicializa una nueva instancia de la clase `EmfEllipse`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtiene o establece un objeto RectL de 128 bits (WMF), especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador inclusivo-inclusivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtiene o establece un objeto RectL de 128 bits (WMF), especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador inclusivo-inclusivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

