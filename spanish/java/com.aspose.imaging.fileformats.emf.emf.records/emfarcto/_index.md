---
title: "EmfArcTo"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_ARCTO especifica un arco elíptico."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

El registro EMR\_ARCTO especifica un arco elíptico. Restablece la posición actual al punto final del arco.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfArcTo`. |
| [EmfArcTo()](#EmfArcTo--) | Inicializa una nueva instancia de la clase `EmfArcTo`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBox()](#getBox--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [getStart()](#getStart--) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas del primer punto final radial, en unidades lógicas. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas del primer punto final radial, en unidades lógicas. |
| [getEnd()](#getEnd--) | Obtiene o establece un objeto WMF PointL de 64 bits que especifica las coordenadas del segundo punto final radial, en unidades lógicas. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits que especifica las coordenadas del segundo punto final radial, en unidades lógicas. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfArcTo`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


Inicializa una nueva instancia de la clase `EmfArcTo`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas del primer punto final radial, en unidades lógicas.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas del primer punto final radial, en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Obtiene o establece un objeto WMF PointL de 64 bits que especifica las coordenadas del segundo punto final radial, en unidades lógicas.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits que especifica las coordenadas del segundo punto final radial, en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

