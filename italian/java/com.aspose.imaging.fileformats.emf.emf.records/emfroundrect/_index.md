---
title: "EmfRoundRect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_ROUNDRECT specifica un rettangolo con angoli arrotondati."
type: docs
weight: 111
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

Il record EMR\_ROUNDRECT specifica un rettangolo con angoli arrotondati. Il rettangolo è delineato usando la penna corrente e riempito usando il pennello corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfRoundRect`. |
| [EmfRoundRect()](#EmfRoundRect--) | Inizializza una nuova istanza della classe [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBox()](#getBox--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare. |
| [getCorner()](#getCorner--) | Ottiene o imposta un oggetto WMF SizeL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.22, che definisce la larghezza e l'altezza, in coordinate logiche, dell'ellisse utilizzata per disegnare gli angoli arrotondati. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Ottiene o imposta un oggetto WMF SizeL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.22, che definisce la larghezza e l'altezza, in coordinate logiche, dell'ellisse utilizzata per disegnare gli angoli arrotondati. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfRoundRect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Inizializza una nuova istanza della classe [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect).

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Ottiene o imposta un oggetto WMF SizeL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.22, che definisce la larghezza e l'altezza, in coordinate logiche, dell'ellisse utilizzata per disegnare gli angoli arrotondati.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Ottiene o imposta un oggetto WMF SizeL a 64 bit, specificato in [MS-WMF] sezione 2.2.2.22, che definisce la larghezza e l'altezza, in coordinate logiche, dell'ellisse utilizzata per disegnare gli angoli arrotondati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

