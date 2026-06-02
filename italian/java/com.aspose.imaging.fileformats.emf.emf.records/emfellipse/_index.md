---
title: "EmfEllipse"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_ELLIPSE specifica un'ellisse."
type: docs
weight: 46
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfEllipse extends EmfDrawingRecordType
```

Il record EMR\_ELLIPSE specifica un'ellisse. Il centro dell'ellisse è il centro del rettangolo di delimitazione specificato. L'ellisse è delineata usando la penna corrente ed è riempita usando il pennello corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfEllipse(EmfRecord source)](#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfEllipse`. |
| [EmfEllipse()](#EmfEllipse--) | Inizializza una nuova istanza della classe `EmfEllipse`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBox()](#getBox--) | Ottiene o imposta un oggetto RectL a 128 bit (WMF), specificato nella sezione 2.2.2.19 di [MS-WMF], che specifica il rettangolo di delimitazione inclusivo-inclusivo. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto RectL a 128 bit (WMF), specificato nella sezione 2.2.2.19 di [MS-WMF], che specifica il rettangolo di delimitazione inclusivo-inclusivo. |
### EmfEllipse(EmfRecord source) {#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEllipse(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfEllipse`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfEllipse() {#EmfEllipse--}
```
public EmfEllipse()
```


Inizializza una nuova istanza della classe `EmfEllipse`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Ottiene o imposta un oggetto RectL a 128 bit (WMF), specificato nella sezione 2.2.2.19 di [MS-WMF], che specifica il rettangolo di delimitazione inclusivo-inclusivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Ottiene o imposta un oggetto RectL a 128 bit (WMF), specificato nella sezione 2.2.2.19 di [MS-WMF], che specifica il rettangolo di delimitazione inclusivo-inclusivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

