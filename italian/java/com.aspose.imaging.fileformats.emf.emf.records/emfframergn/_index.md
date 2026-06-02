---
title: "EmfFrameRgn"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_FRAMERGN disegna un bordo attorno alla regione specificata utilizzando il pennello specificato."
type: docs
weight: 62
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

Il record EMR\_FRAMERGN disegna un bordo attorno alla regione specificata usando il pennello specificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfFrameRgn`. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Inizializza una nuova istanza della classe [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che specifica il rettangolo di delimitazione. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che specifica il rettangolo di delimitazione. |
| [getRgnDataSize()](#getRgnDataSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [getIhBrush()](#getIhBrush--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della brush EMF Object Table. |
| [setIhBrush(int value)](#setIhBrush-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della brush EMF Object Table. |
| [getWidth()](#getWidth--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza del tratto del pennello verticale, in unità logiche. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza del tratto del pennello verticale, in unità logiche. |
| [getHeight()](#getHeight--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza del tratto del pennello orizzontale, in unità logiche. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza del tratto del pennello orizzontale, in unità logiche. |
| [getRgnData()](#getRgnData--) | Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfFrameRgn`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Inizializza una nuova istanza della classe [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che specifica il rettangolo di delimitazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che specifica il rettangolo di delimitazione.

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


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della brush EMF Object Table.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della brush EMF Object Table.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza del tratto del pennello verticale, in unità logiche.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza del tratto del pennello verticale, in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza del tratto del pennello orizzontale, in unità logiche.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza del tratto del pennello orizzontale, in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

