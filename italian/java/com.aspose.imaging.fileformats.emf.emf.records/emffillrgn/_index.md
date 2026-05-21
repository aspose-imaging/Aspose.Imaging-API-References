---
title: "EmfFillRgn"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_FILLRGN riempie la regione specificata utilizzando il pennello specificato."
type: docs
weight: 59
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

Il record EMR\_FILLRGN riempie la regione specificata usando il pennello specificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfFillRgn`. |
| [EmfFillRgn()](#EmfFillRgn--) | Inizializza una nuova istanza della classe `EmfFillRgn`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione. |
| [getRgnDataSize()](#getRgnDataSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [getIhBrush()](#getIhBrush--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della Brush EMF Object Table per riempire la regione. |
| [setIhBrush(int value)](#setIhBrush-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della Brush EMF Object Table per riempire la regione. |
| [getRgnData()](#getRgnData--) | Ottiene o imposta un array di byte di lunghezza RgnDataSize che contiene un oggetto RegionData (sezione 2.2.24). |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Ottiene o imposta un array di byte di lunghezza RgnDataSize che contiene un oggetto RegionData (sezione 2.2.24). |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfFillRgn`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


Inizializza una nuova istanza della classe `EmfFillRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della Brush EMF Object Table per riempire la regione.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della Brush EMF Object Table per riempire la regione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Ottiene o imposta un array di byte di lunghezza RgnDataSize che contiene un oggetto RegionData (sezione 2.2.24).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Ottiene o imposta un array di byte di lunghezza RgnDataSize che contiene un oggetto RegionData (sezione 2.2.24).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

