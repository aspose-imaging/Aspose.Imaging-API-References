---
title: "EmfPlusBitmap"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusBitmap specifica una bitmap che contiene un'immagine grafica."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

L'oggetto EmfPlusBitmap specifica una bitmap che contiene un'immagine grafica.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Ottiene o imposta i dati bitmap BitmapData (variabile): Dati di lunghezza variabile che definiscono l'oggetto dati bitmap specificato nel campo Type. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Ottiene o imposta i dati bitmap BitmapData (variabile): Dati di lunghezza variabile che definiscono l'oggetto dati bitmap specificato nel campo Type. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza bitmap Height (4 byte): Un intero con segno a 32 bit che specifica l'altezza in pixel dell'area occupata dal bitmap. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta l'altezza bitmap Height (4 byte): Un intero con segno a 32 bit che specifica l'altezza in pixel dell'area occupata dal bitmap. |
| [getPixelFormat()](#getPixelFormat--) | Ottiene o imposta il formato pixel PixelFormat (4 byte): Un intero senza segno a 32 bit che specifica il formato dei pixel che compongono l'immagine bitmap. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Ottiene o imposta il formato pixel PixelFormat (4 byte): Un intero senza segno a 32 bit che specifica il formato dei pixel che compongono l'immagine bitmap. |
| [getStride()](#getStride--) | Ottiene o imposta lo stride dell'immagine Stride (4 byte): Un intero con segno a 32 bit che specifica lo spostamento in byte tra l'inizio di una linea di scansione e la successiva. |
| [setStride(int value)](#setStride-int-) | Ottiene o imposta lo stride dell'immagine Stride (4 byte): Un intero con segno a 32 bit che specifica lo spostamento in byte tra l'inizio di una linea di scansione e la successiva. |
| [getType()](#getType--) | Ottiene o imposta il tipo dell'immagine Type (4 byte): Un intero senza segno a 32 bit che specifica il tipo di dati nel campo BitmapData. |
| [setType(int value)](#setType-int-) | Ottiene o imposta il tipo dell'immagine Type (4 byte): Un intero senza segno a 32 bit che specifica il tipo di dati nel campo BitmapData. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza dell'immagine Width (4 byte): Un intero con segno a 32 bit che specifica la larghezza in pixel dell'area occupata dal bitmap. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta la larghezza dell'immagine Width (4 byte): Un intero con segno a 32 bit che specifica la larghezza in pixel dell'area occupata dal bitmap. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Ottiene o imposta i dati bitmap BitmapData (variabile): Dati di lunghezza variabile che definiscono l'oggetto dati bitmap specificato nel campo Type. Il contenuto e il formato dei dati possono variare per ogni tipo di bitmap.

Valore: I dati bitmap.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Ottiene o imposta i dati bitmap BitmapData (variabile): Dati di lunghezza variabile che definiscono l'oggetto dati bitmap specificato nel campo Type. Il contenuto e il formato dei dati possono variare per ogni tipo di bitmap.

Valore: I dati bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta l'altezza bitmap Height (4 byte): Un intero con segno a 32 bit che specifica l'altezza in pixel dell'area occupata dal bitmap. Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: L'altezza.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta l'altezza bitmap Height (4 byte): Un intero con segno a 32 bit che specifica l'altezza in pixel dell'area occupata dal bitmap. Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: L'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Ottiene o imposta il formato pixel PixelFormat (4 byte): Un intero senza segno a 32 bit che specifica il formato dei pixel che compongono l'immagine bitmap. I formati pixel supportati sono specificati nell'enumerazione `EmfPlusPixelFormat` (sezione 2.1.1.25). Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: Il formato pixel.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Ottiene o imposta il formato pixel PixelFormat (4 byte): Un intero senza segno a 32 bit che specifica il formato dei pixel che compongono l'immagine bitmap. I formati pixel supportati sono specificati nell'enumerazione `EmfPlusPixelFormat` (sezione 2.1.1.25). Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: Il formato pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Ottiene o imposta lo stride dell'immagine Stride (4 byte): Un intero con segno a 32 bit che specifica lo spostamento in byte tra l'inizio di una linea di scansione e la successiva. Questo valore è il numero di byte per pixel, specificato nel campo PixelFormat, moltiplicato per la larghezza in pixel, specificata nel campo Width. Il valore di questo campo DEVE essere un multiplo di quattro. Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: Lo stride.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Ottiene o imposta lo stride dell'immagine Stride (4 byte): Un intero con segno a 32 bit che specifica lo spostamento in byte tra l'inizio di una linea di scansione e la successiva. Questo valore è il numero di byte per pixel, specificato nel campo PixelFormat, moltiplicato per la larghezza in pixel, specificata nel campo Width. Il valore di questo campo DEVE essere un multiplo di quattro. Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: Lo stride.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getType() {#getType--}
```
public int getType()
```


Ottiene o imposta il tipo dell'immagine Type (4 byte): Un intero senza segno a 32 bit che specifica il tipo di dati nel campo BitmapData. Questo valore DEVE essere definito nell'enumerazione `EmfPlusBitmapDataType` (sezione 2.1.1.2).

Valore: Il tipo.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Ottiene o imposta il tipo dell'immagine Type (4 byte): Un intero senza segno a 32 bit che specifica il tipo di dati nel campo BitmapData. Questo valore DEVE essere definito nell'enumerazione `EmfPlusBitmapDataType` (sezione 2.1.1.2).

Valore: Il tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene o imposta la larghezza dell'immagine Width (4 byte): Un intero con segno a 32 bit che specifica la larghezza in pixel dell'area occupata dal bitmap. Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: La larghezza.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ottiene o imposta la larghezza dell'immagine Width (4 byte): Un intero con segno a 32 bit che specifica la larghezza in pixel dell'area occupata dal bitmap. Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato.

Valore: La larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

