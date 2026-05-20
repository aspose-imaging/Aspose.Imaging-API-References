---
title: "EmfMaskBlt"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_MASKBLT specifica un trasferimento a blocchi di pixel da una bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un motivo di pennello e con l'applicazione di una bitmap maschera di colore secondo le operazioni raster di primo piano e sfondo specificate."
type: docs
weight: 69
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

Il record EMR\_MASKBLT specifica un trasferimento a blocchi di pixel da una bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello e con l'applicazione di una bitmap maschera di colore, secondo le operazioni raster di primo piano e sfondo specificate.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfMaskBlt`. |
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
| [getRop4()](#getRop4--) | Ottiene o imposta un'operazione raster quaternaria, che specifica operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | Ottiene o imposta un'operazione raster quaternaria, che specifica operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap. |
| [getXSrc()](#getXSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine. |
| [setXSrc(int value)](#setXSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine. |
| [getYSrc()](#getYSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine. |
| [setYSrc(int value)](#setYSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine. |
| [getXformSrc()](#getXformSrc--) | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine. |
| [getUsageSrc()](#getUsageSrc--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [getXMask()](#getXMask--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap maschera. |
| [setXMask(int value)](#setXMask-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap maschera. |
| [getYMask()](#getYMask--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap maschera. |
| [setYMask(int value)](#setYMask-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap maschera. |
| [getUsageMask()](#getUsageMask--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap maschera. |
| [setUsageMask(int value)](#setUsageMask-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap maschera. |
| [getSourceBitmap()](#getSourceBitmap--) | Ottiene o imposta un buffer contenente le bitmap sorgente, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente le bitmap sorgente, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. |
| [getMaskBitmap()](#getMaskBitmap--) | Ottiene o imposta un buffer contenente le bitmap maschera, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente le bitmap maschera, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfMaskBlt`.

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

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


Ottiene o imposta un'operazione raster quaternaria, che specifica operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap. Questi valori definiscono come i dati colore del rettangolo sorgente devono essere combinati con i dati colore del rettangolo di destinazione.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


Ottiene o imposta un'operazione raster quaternaria, che specifica operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap. Questi valori definiscono come i dati colore del rettangolo sorgente devono essere combinati con i dati colore del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

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

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine.

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

### getXMask() {#getXMask--}
```
public int getXMask()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap maschera.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap maschera.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap maschera. Questo valore DEVE appartenere all'enumerazione DIBColors.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap maschera. Questo valore DEVE appartenere all'enumerazione DIBColors.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Ottiene o imposta un buffer contenente le bitmap sorgente, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati come \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente le bitmap sorgente, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati come \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Ottiene o imposta un buffer contenente le bitmap maschera, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati come \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente le bitmap maschera, che non è necessario siano contigue con la parte fissa del record EMR\_MASKBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati come \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

