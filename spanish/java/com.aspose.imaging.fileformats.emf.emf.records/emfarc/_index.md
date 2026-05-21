---
title: "EmfArc"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_ARC especifica un arco elíptico."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArc extends EmfDrawingRecordType
```

El registro EMR\_ARC especifica un arco elíptico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfArc(EmfRecord source)](#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfArc`. |
| [EmfArc()](#EmfArc--) | Inicializa una nueva instancia de la clase `EmfArc`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBox()](#getBox--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo. |
| [getStart()](#getStart--) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto de inicio del arco. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto de inicio del arco. |
| [getEnd()](#getEnd--) | Obtiene o establece un objeto WMF PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto final del arco. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto final del arco. |
### EmfArc(EmfRecord source) {#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArc(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfArc`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfArc() {#EmfArc--}
```
public EmfArc()
```


Inicializa una nueva instancia de la clase `EmfArc`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto de inicio del arco.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto de inicio del arco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Obtiene o establece un objeto WMF PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto final del arco.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final de la línea radial que define el punto final del arco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

