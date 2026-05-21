---
title: "EmfArcTo"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_ARCTO specifica un arco ellittico."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

Il record EMR\_ARCTO specifica un arco ellittico. Reimposta la posizione corrente al punto finale dell'arco.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfArcTo`. |
| [EmfArcTo()](#EmfArcTo--) | Inizializza una nuova istanza della classe `EmfArcTo`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBox()](#getBox--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione. |
| [getStart()](#getStart--) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate del primo punto finale radiale, in unità logiche. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate del primo punto finale radiale, in unità logiche. |
| [getEnd()](#getEnd--) | Ottiene o imposta un oggetto WMF PointL a 64 bit che specifica le coordinate del secondo punto finale radiale, in unità logiche. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL a 64 bit che specifica le coordinate del secondo punto finale radiale, in unità logiche. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfArcTo`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


Inizializza una nuova istanza della classe `EmfArcTo`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate del primo punto finale radiale, in unità logiche.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate del primo punto finale radiale, in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Ottiene o imposta un oggetto WMF PointL a 64 bit che specifica le coordinate del secondo punto finale radiale, in unità logiche.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Ottiene o imposta un oggetto WMF PointL a 64 bit che specifica le coordinate del secondo punto finale radiale, in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

