---
title: "EmfRoundRect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_ROUNDRECT especifica un rectángulo con esquinas redondeadas."
type: docs
weight: 111
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

El registro EMR\\_ROUNDRECT especifica un rectángulo con esquinas redondeadas. El rectángulo se delimita usando la pluma actual y se rellena usando el pincel actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfRoundRect`. |
| [EmfRoundRect()](#EmfRoundRect--) | Inicializa una nueva instancia de la clase [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBox()](#getBox--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar. |
| [getCorner()](#getCorner--) | Obtiene o establece un objeto WMF SizeL de 64 bits, especificado en la sección 2.2.2.22 de [MS-WMF], que define el ancho y la altura, en coordenadas lógicas, de la elipse utilizada para dibujar las esquinas redondeadas. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Obtiene o establece un objeto WMF SizeL de 64 bits, especificado en la sección 2.2.2.22 de [MS-WMF], que define el ancho y la altura, en coordenadas lógicas, de la elipse utilizada para dibujar las esquinas redondeadas. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfRoundRect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Inicializa una nueva instancia de la clase [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect).

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Obtiene o establece un objeto WMF SizeL de 64 bits, especificado en la sección 2.2.2.22 de [MS-WMF], que define el ancho y la altura, en coordenadas lógicas, de la elipse utilizada para dibujar las esquinas redondeadas.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Obtiene o establece un objeto WMF SizeL de 64 bits, especificado en la sección 2.2.2.22 de [MS-WMF], que define el ancho y la altura, en coordenadas lógicas, de la elipse utilizada para dibujar las esquinas redondeadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

