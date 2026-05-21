---
title: "EmfStretchDiBits"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_STRETCHDIBITS specifica un trasferimento a blocchi di pixel da un bitmap di origine a un rettangolo di destinazione, opzionalmente in combinazione con un motivo di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione se necessario."
type: docs
weight: 150
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

Il record EMR\_STRETCHDIBITS specifica un trasferimento a blocchi di pixel da un bitmap di origine a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario.

Questo record supporta immagini di origine nei formati JPEG e PNG. Il campo Compression nell'intestazione del bitmap di origine specifica il formato dell'immagine. Se i segni dei campi di altezza e larghezza di origine e destinazione differiscono, questo record specifica una copia speculare del bitmap di origine nella destinazione. Cioè, se cxSrc e cxDest hanno segni diversi, viene specificata un'immagine speculare del bitmap di origine lungo l'asse x. Se cySrc e cyDest hanno segni diversi, viene specificata un'immagine speculare del bitmap di origine lungo l'asse y.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfStretchDiBits`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo. |
| [getXDest()](#getXDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione. |
| [setXDest(int value)](#setXDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione. |
| [getYDest()](#getYDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione. |
| [setYDest(int value)](#setYDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione. |
| [getXSrc()](#getXSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo superiore sinistro del rettangolo di origine. |
| [setXSrc(int value)](#setXSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo superiore sinistro del rettangolo di origine. |
| [getYSrc()](#getYSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo superiore sinistro del rettangolo di origine. |
| [setYSrc(int value)](#setYSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo superiore sinistro del rettangolo di origine. |
| [getCxSrc()](#getCxSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine. |
| [setCxSrc(int value)](#setCxSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine. |
| [getCySrc()](#getCySrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine. |
| [setCySrc(int value)](#setCySrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine. |
| [getUsageSrc()](#getUsageSrc--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Ottiene o imposta un intero senza segno a 32 bit che specifica un codice di operazione raster. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica un codice di operazione raster. |
| [getCxDest()](#getCxDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [setCxDest(int value)](#setCxDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [getCyDest()](#getCyDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [setCyDest(int value)](#setCyDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [getSourceBitmap()](#getSourceBitmap--) | Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_STRETCHDIBITS. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_STRETCHDIBITS. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfStretchDiBits`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo superiore sinistro del rettangolo di origine.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo superiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo superiore sinistro del rettangolo di origine.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo superiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. Questo valore DEVE appartenere all'enumerazione DIBColors (sezione 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. Questo valore DEVE appartenere all'enumerazione DIBColors (sezione 2.1.9).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un codice di operazione raster. Questi codici definiscono come i dati di colore del rettangolo di origine devono essere combinati con i dati di colore del rettangolo di destinazione e, opzionalmente, con un motivo di pennello, per ottenere il colore finale.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un codice di operazione raster. Questi codici definiscono come i dati di colore del rettangolo di origine devono essere combinati con i dati di colore del rettangolo di destinazione e, opzionalmente, con un motivo di pennello, per ottenere il colore finale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_STRETCHDIBITS. Di conseguenza, i campi in questo buffer etichettati come "UndefinedSpace" sono opzionali e DEVONO essere ignorati.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_STRETCHDIBITS. Di conseguenza, i campi in questo buffer etichettati come "UndefinedSpace" sono opzionali e DEVONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

