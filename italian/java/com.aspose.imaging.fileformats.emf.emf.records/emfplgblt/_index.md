---
title: "EmfPlgBlt"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_PLGBLT specifica un trasferimento a blocchi di pixel da una bitmap sorgente a un parallelogramma di destinazione con l'applicazione di una bitmap maschera di colore."
type: docs
weight: 84
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

Il record EMR\_PLGBLT specifica un trasferimento a blocchi di pixel da una bitmap sorgente a un parallelogramma di destinazione, con l'applicazione di una bitmap maschera di colore.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPlgBlt`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione, in unità dispositivo, per l'output verso la destinazione. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione, in unità dispositivo, per l'output verso la destinazione. |
| [getAptlDest()](#getAptlDest--) | Ottiene o imposta un array di tre oggetti WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica tre angoli di un'area di destinazione a forma di parallelogramma per il trasferimento a blocchi. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | Ottiene o imposta un array di tre oggetti WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica tre angoli di un'area di destinazione a forma di parallelogramma per il trasferimento a blocchi. |
| [getXSrc()](#getXSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine. |
| [setXSrc(int value)](#setXSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di origine. |
| [getYSrc()](#getYSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine. |
| [setYSrc(int value)](#setYSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di origine. |
| [getCxSrc()](#getCxSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| [setCxSrc(int value)](#setCxSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| [getCySrc()](#getCySrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| [setCySrc(int value)](#setCySrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| [getXFormSrc()](#getXFormSrc--) | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il colore di sfondo del bitmap di origine. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il colore di sfondo del bitmap di origine. |
| [getUsageSrc()](#getUsageSrc--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [getXMask()](#getXMask--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap maschera. |
| [setXMask(int value)](#setXMask-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap maschera. |
| [getYMask()](#getYMask--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap maschera. |
| [setYMask(int value)](#setYMask-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap maschera. |
| [getUsageMask()](#getUsageMask--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap maschera. |
| [setUsageMask(int value)](#setUsageMask-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap maschera. |
| [getSourceBitmap()](#getSourceBitmap--) | Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. |
| [getMaskBitmap()](#getMaskBitmap--) | Ottiene o imposta un buffer contenente il bitmap di maschera, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente il bitmap di maschera, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPlgBlt`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione, in unità dispositivo, per l'output verso la destinazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione, in unità dispositivo, per l'output verso la destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


Ottiene o imposta un array di tre oggetti WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica tre angoli di un'area di destinazione a forma di parallelogramma per il trasferimento a blocchi. L'angolo in alto a sinistra del rettangolo di origine è mappato al primo punto di questo array, l'angolo in alto a destra al secondo punto e l'angolo in basso a sinistra al terzo punto. L'angolo in basso a destra del rettangolo di origine è mappato al quarto punto implicito nel parallelogramma, che è calcolato dai primi tre punti (A, B e C) trattandoli come vettori. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


Ottiene o imposta un array di tre oggetti WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica tre angoli di un'area di destinazione a forma di parallelogramma per il trasferimento a blocchi. L'angolo in alto a sinistra del rettangolo di origine è mappato al primo punto di questo array, l'angolo in alto a destra al secondo punto e l'angolo in basso a sinistra al terzo punto. L'angolo in basso a destra del rettangolo di origine è mappato al quarto punto implicito nel parallelogramma, che è calcolato dai primi tre punti (A, B e C) trattandoli come vettori. D = B + C A

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

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

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare alla bitmap di origine.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
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


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il colore di sfondo del bitmap di origine.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il colore di sfondo del bitmap di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione del bitmap di origine. Questo valore DEVE appartenere all'enumerazione DIBColors.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione del bitmap di origine. Questo valore DEVE appartenere all'enumerazione DIBColors.

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


Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente il bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Ottiene o imposta un buffer contenente il bitmap di maschera, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente il bitmap di maschera, che non è necessario sia contiguo con la parte fissa del record EMR\_PLGBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

