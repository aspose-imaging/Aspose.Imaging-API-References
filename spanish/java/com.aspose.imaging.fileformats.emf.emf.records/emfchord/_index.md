---
title: "EmfChord"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CHORD especifica una cuerda que es una región delimitada por la intersección de una elipse y un segmento de línea llamado secante."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

El registro EMR\_CHORD especifica una cuerda, que es una región delimitada por la intersección de una elipse y un segmento de línea, llamado secante. La cuerda se traza usando la pluma actual y se rellena usando el pincel actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfChord`. |
| [EmfChord()](#EmfChord--) | Inicializa una nueva instancia de la clase `EmfChord`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBox()](#getBox--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador inclusivo-inclusivo. |
| [getStart()](#getStart--) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas lógicas del punto final del radial que define el comienzo de la cuerda. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas lógicas del punto final del radial que define el comienzo de la cuerda. |
| [getEnd()](#getEnd--) | Obtiene o establece un objeto WMF PointL de 64 bits que define las coordenadas lógicas del punto final del radial que define el final de la cuerda. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits que define las coordenadas lógicas del punto final del radial que define el final de la cuerda. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfChord`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


Inicializa una nueva instancia de la clase `EmfChord`.

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


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas lógicas del punto final del radial que define el comienzo de la cuerda.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que define las coordenadas lógicas del punto final del radial que define el comienzo de la cuerda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Obtiene o establece un objeto WMF PointL de 64 bits que define las coordenadas lógicas del punto final del radial que define el final de la cuerda.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits que define las coordenadas lógicas del punto final del radial que define el final de la cuerda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

