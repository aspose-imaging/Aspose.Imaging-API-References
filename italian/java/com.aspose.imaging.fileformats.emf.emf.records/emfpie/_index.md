---
title: "EmfPie"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_PIE specifica una sezione a forma di torta delimitata dall'intersezione di un'ellisse e due raggi."
type: docs
weight: 82
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

Il record EMR\_PIE specifica una sezione a forma di torta delimitata dall'intersezione di un'ellisse e due raggi. La torta è delineata usando la penna corrente e riempita usando il pennello corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPie`. |
| [EmfPie()](#EmfPie--) | Inizializza una nuova istanza della classe `EmfPie`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBox()](#getBox--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, che definisce il rettangolo di delimitazione inclusivo-inclusivo. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, che definisce il rettangolo di delimitazione inclusivo-inclusivo. |
| [getStart()](#getStart--) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che specifica le coordinate, in unità logiche, del punto finale del primo raggio. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che specifica le coordinate, in unità logiche, del punto finale del primo raggio. |
| [getEnd()](#getEnd--) | Ottiene o imposta un oggetto PointL a 64 bit che specifica le coordinate, in unità logiche, del punto finale del secondo raggio. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto PointL a 64 bit che specifica le coordinate, in unità logiche, del punto finale del secondo raggio. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPie`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


Inizializza una nuova istanza della classe `EmfPie`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, che definisce il rettangolo di delimitazione inclusivo-inclusivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, che definisce il rettangolo di delimitazione inclusivo-inclusivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che specifica le coordinate, in unità logiche, del punto finale del primo raggio.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che specifica le coordinate, in unità logiche, del punto finale del primo raggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Ottiene o imposta un oggetto PointL a 64 bit che specifica le coordinate, in unità logiche, del punto finale del secondo raggio.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Ottiene o imposta un oggetto PointL a 64 bit che specifica le coordinate, in unità logiche, del punto finale del secondo raggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

