---
title: "EmfChord"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CHORD specifica una corda, che è una regione delimitata dall'intersezione di un'ellisse e di un segmento di linea chiamato secante."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

Il record EMR\_CHORD specifica una corda, che è una regione delimitata dall'intersezione di un'ellisse e di un segmento di linea, chiamato secante. La corda è delineata usando la penna corrente e riempita usando il pennello corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfChord`. |
| [EmfChord()](#EmfChord--) | Inizializza una nuova istanza della classe `EmfChord`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBox()](#getBox--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, che definisce il rettangolo di delimitazione inclusivo-inclusivo. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, che definisce il rettangolo di delimitazione inclusivo-inclusivo. |
| [getStart()](#getStart--) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate logiche del punto finale del raggio che definisce l'inizio della corda. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate logiche del punto finale del raggio che definisce l'inizio della corda. |
| [getEnd()](#getEnd--) | Ottiene o imposta un oggetto WMF PointL a 64 bit che definisce le coordinate logiche del punto finale del raggio che definisce la fine della corda. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL a 64 bit che definisce le coordinate logiche del punto finale del raggio che definisce la fine della corda. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfChord`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


Inizializza una nuova istanza della classe `EmfChord`.

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


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate logiche del punto finale del raggio che definisce l'inizio della corda.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che definisce le coordinate logiche del punto finale del raggio che definisce l'inizio della corda.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Ottiene o imposta un oggetto WMF PointL a 64 bit che definisce le coordinate logiche del punto finale del raggio che definisce la fine della corda.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Ottiene o imposta un oggetto WMF PointL a 64 bit che definisce le coordinate logiche del punto finale del raggio che definisce la fine della corda.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

