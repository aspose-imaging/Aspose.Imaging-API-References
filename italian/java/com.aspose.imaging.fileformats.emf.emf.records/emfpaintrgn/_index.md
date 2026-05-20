---
title: "EmfPaintRgn"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_PAINTRGN dipinge la regione specificata utilizzando il pennello attualmente selezionato nel contesto del dispositivo di riproduzione."
type: docs
weight: 80
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

Il record EMR\_PAINTRGN dipinge la regione specificata utilizzando il pennello attualmente selezionato nel contesto del dispositivo di riproduzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPaintRgn`. |
| [EmfPaintRgn()](#EmfPaintRgn--) | Inizializza una nuova istanza della classe `EmfPaintRgn`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene un oggetto WMF RectL a 128 bit, specificato nella sezione 2.2.2.19 di [MS-WMF], che definisce il rettangolo di delimitazione. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Imposta un oggetto WMF RectL a 128 bit, specificato nella sezione 2.2.2.19 di [MS-WMF], che definisce il rettangolo di delimitazione. |
| [getRgnDataSize()](#getRgnDataSize--) | Ottiene un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [getRgnData()](#getRgnData--) | Ottiene un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData (sezione 2.2.24), in unità logiche. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Imposta un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData (sezione 2.2.24), in unità logiche. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPaintRgn`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


Inizializza una nuova istanza della classe `EmfPaintRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene un oggetto WMF RectL a 128 bit, specificato nella sezione 2.2.2.19 di [MS-WMF], che definisce il rettangolo di delimitazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Imposta un oggetto WMF RectL a 128 bit, specificato nella sezione 2.2.2.19 di [MS-WMF], che definisce il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Ottiene un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Ottiene un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData (sezione 2.2.24), in unità logiche.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Imposta un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData (sezione 2.2.24), in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

