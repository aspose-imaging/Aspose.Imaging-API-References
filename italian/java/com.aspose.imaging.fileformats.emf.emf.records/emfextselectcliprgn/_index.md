---
title: "EmfExtSelectClipRgn"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_EXTSELECTCLIPRGN combina la regione specificata con la regione di clip corrente utilizzando la modalità specificata."
type: docs
weight: 55
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

Il record EMR\_EXTSELECTCLIPRGN combina la regione specificata con la regione di clip corrente utilizzando la modalità specificata. Nota: i campi non descritti in questa sezione sono specificati nella sezione 2.3.2.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfExtSelectClipRgn`. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Inizializza una nuova istanza della classe `EmfExtSelectClipRgn`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione in byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione in byte. |
| [getRegionMode()](#getRegionMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare la regione. |
| [setRegionMode(int value)](#setRegionMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare la regione. |
| [getRgnData()](#getRgnData--) | Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData in unità logiche. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData in unità logiche. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfExtSelectClipRgn`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Inizializza una nuova istanza della classe `EmfExtSelectClipRgn`.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione in byte.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati della regione in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare la regione. Il valore DEVE essere nell'enumerazione RegionMode (sezione 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare la regione. Il valore DEVE essere nell'enumerazione RegionMode (sezione 2.1.29).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData in unità logiche. Se RegionMode è RGN\_COPY, questi dati possono essere omessi e la regione di clip DOVREBBE essere impostata sulla regione di clip predefinita (NULL).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Ottiene o imposta un array di byte di lunghezza RgnDataSize che specifica un oggetto RegionData in unità logiche. Se RegionMode è RGN\_COPY, questi dati possono essere omessi e la regione di clip DOVREBBE essere impostata sulla regione di clip predefinita (NULL).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

