---
title: "EmfPie"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_PIE especifica una cuña en forma de pastel delimitada por la intersección de una elipse y dos radiales."
type: docs
weight: 82
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

El registro EMR\_PIE especifica una cuña en forma de pastel delimitada por la intersección de una elipse y dos radiales. El pastel se contornea usando el lápiz actual y se rellena usando el pincel actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPie`. |
| [EmfPie()](#EmfPie--) | Inicializa una nueva instancia de la clase `EmfPie`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBox()](#getBox--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo. |
| [getStart()](#getStart--) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final del primer radial. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final del primer radial. |
| [getEnd()](#getEnd--) | Obtiene o establece un objeto PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final del segundo radial. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Obtiene o establece un objeto PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final del segundo radial. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPie`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


Inicializa una nueva instancia de la clase `EmfPie`.

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


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final del primer radial.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas, en unidades lógicas, del punto final del primer radial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Obtiene o establece un objeto PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final del segundo radial.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Obtiene o establece un objeto PointL de 64 bits que indica las coordenadas, en unidades lógicas, del punto final del segundo radial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

