---
title: "EmfInvertRgn"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_INVERTRGN inverte i colori nella regione specificata."
type: docs
weight: 67
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

Il record EMR\_INVERTRGN inverte i colori nella regione specificata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfInvertRgn`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo di delimitazione. |
| [getRgnDataSize()](#getRgnDataSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione, in byte. |
| [getRgnData()](#getRgnData--) | Ottiene o imposta un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | Ottiene o imposta un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfInvertRgn`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

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

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


Ottiene o imposta un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


Ottiene o imposta un array di byte della lunghezza RgnDataSize che specifica un oggetto RegionData, in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

