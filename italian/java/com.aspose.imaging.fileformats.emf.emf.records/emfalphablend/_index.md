---
title: "EmfAlphaBlend"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_ALPHABLEND specifica un trasferimento a blocchi di pixel da una bitmap sorgente a un rettangolo di destinazione, includendo i dati di trasparenza alfa secondo un'operazione di fusione specificata."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfAlphaBlend extends EmfBitmapRecordType
```

Il record EMR\_ALPHABLEND specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, includendo dati di trasparenza alfa, secondo un'operazione di fusione specificata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfAlphaBlend(EmfRecord source)](#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfAlphaBlend`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo. |
| [getXDest()](#getXDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione. |
| [setXDest(int value)](#setXDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione. |
| [getYDest()](#getYDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione. |
| [setYDest(int value)](#setYDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione. |
| [getCxDest()](#getCxDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [setCxDest(int value)](#setCxDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [getCyDest()](#getCyDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [setCyDest(int value)](#setCyDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [getBlendFunction()](#getBlendFunction--) | Ottiene o imposta una struttura che specifica le operazioni di fusione per le bitmap di origine e destinazione |
| [setBlendFunction(EmfBlendFunction value)](#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) | Ottiene o imposta una struttura che specifica le operazioni di fusione per le bitmap di origine e destinazione |
| [getXSrc()](#getXSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine. |
| [setXSrc(int value)](#setXSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine. |
| [getYSrc()](#getYSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine. |
| [setYSrc(int value)](#setYSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine. |
| [getXformSr()](#getXformSr--) | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine. |
| [setXformSr(Matrix value)](#setXformSr-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine. |
| [getUsageSrc()](#getUsageSrc--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [getCxSrc()](#getCxSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| [setCxSrc(int value)](#setCxSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| [getCySrc()](#getCySrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| [setCySrc(int value)](#setCySrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| [getSourceBitmap()](#getSourceBitmap--) | Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\\_ALPHABLEND. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\\_ALPHABLEND. |
### EmfAlphaBlend(EmfRecord source) {#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAlphaBlend(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfAlphaBlend`.

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

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. Questo valore DEVE essere maggiore di zero.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. Questo valore DEVE essere maggiore di zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. Questo valore DEVE essere maggiore di zero.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. Questo valore DEVE essere maggiore di zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBlendFunction() {#getBlendFunction--}
```
public EmfBlendFunction getBlendFunction()
```


Ottiene o imposta una struttura che specifica le operazioni di fusione per le bitmap di origine e destinazione

**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### setBlendFunction(EmfBlendFunction value) {#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void setBlendFunction(EmfBlendFunction value)
```


Ottiene o imposta una struttura che specifica le operazioni di fusione per le bitmap di origine e destinazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getXformSr() {#getXformSr--}
```
public Matrix getXformSr()
```


Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSr(Matrix value) {#setXformSr-com.aspose.imaging.Matrix-}
```
public void setXformSr(Matrix value)
```


Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine.

Valore: Il colore ARGB a 32 bit

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine.

Valore: Il colore ARGB a 32 bit

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

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. Questo valore DEVE essere maggiore di zero.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. Questo valore DEVE essere maggiore di zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. Questo valore DEVE essere maggiore di zero.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. Questo valore DEVE essere maggiore di zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\\_ALPHABLEND. Di conseguenza, i campi in questo buffer etichettati \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\\_ALPHABLEND. Di conseguenza, i campi in questo buffer etichettati \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

