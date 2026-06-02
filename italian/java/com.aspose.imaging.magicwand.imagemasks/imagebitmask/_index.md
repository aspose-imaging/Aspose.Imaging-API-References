---
title: "ImageBitMask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive una maschera immagine binaria."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.magicwand.imagemasks/imagebitmask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class ImageBitMask extends ImageMask
```

Descrive una maschera immagine binaria.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageBitMask(int width, int height)](#ImageBitMask-int-int-) | Inizializza una nuova istanza della classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con la larghezza e l'altezza specificate. |
| [ImageBitMask(RasterImage image)](#ImageBitMask-com.aspose.imaging.RasterImage-) | Inizializza una nuova istanza della classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con le dimensioni dell'[RasterImage](../../com.aspose.imaging/rasterimage) esistente specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Restituisce i limiti della parte selezionata della maschera, in pixel. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ottiene l'opacità del pixel specificato. |
| [inflate(int size)](#inflate-int-) | Espande questa maschera dell'importo specificato. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia la maschera con il rettangolo specificato. |
| [deepClone()](#deepClone--) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
| [setMaskPixel(int x, int y, boolean value)](#setMaskPixel-int-int-boolean-) | Imposta l'opacità al pixel specificato. |
| [op_LogicalNot(ImageBitMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Inverte la maschera. |
| [op_Addition(ImageBitMask a, ImageBitMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Unione di due maschere. |
| [op_Subtraction(ImageBitMask a, ImageBitMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Sottrai la seconda maschera dalla prima. |
| [op_Multiply(ImageBitMask a, ImageBitMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Intersezione di due maschere. |
| [op_ExclusiveOr(ImageBitMask a, ImageBitMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Disgiunzione esclusiva di due maschere. |
### ImageBitMask(int width, int height) {#ImageBitMask-int-int-}
```
public ImageBitMask(int width, int height)
```


Inizializza una nuova istanza della classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con la larghezza e l'altezza specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | Larghezza della maschera. |
| height | int | Altezza della maschera. |

### ImageBitMask(RasterImage image) {#ImageBitMask-com.aspose.imaging.RasterImage-}
```
public ImageBitMask(RasterImage image)
```


Inizializza una nuova istanza della classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con le dimensioni dell'[RasterImage](../../com.aspose.imaging/rasterimage) esistente specificato. L'[RasterImage](../../com.aspose.imaging/rasterimage) specificato verrà memorizzato come immagine di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine sorgente. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Restituisce i limiti della parte selezionata della maschera, in pixel.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Ottiene l'opacità del pixel specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. Valore: true se il pixel specificato è opaco; altrimenti, false. |

**Returns:**
boolean
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Espande questa maschera dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La quantità da gonfiare questa maschera. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Ritaglia la maschera con il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo specificato. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns:**
java.lang.Object - Un nuovo oggetto che è una copia di questa istanza.
### setMaskPixel(int x, int y, boolean value) {#setMaskPixel-int-int-boolean-}
```
public final void setMaskPixel(int x, int y, boolean value)
```


Imposta l'opacità al pixel specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |
| valore | boolean | true se il pixel specificato è opaco; altrimenti, false. |

### op_LogicalNot(ImageBitMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_LogicalNot(ImageBitMask a)
```


Inverte la maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La maschera da invertire. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageBitMask a, ImageBitMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Addition(ImageBitMask a, ImageBitMask b)
```


Unione di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La prima maschera. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageBitMask a, ImageBitMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Subtraction(ImageBitMask a, ImageBitMask b)
```


Sottrai la seconda maschera dalla prima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La prima maschera. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageBitMask a, ImageBitMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Multiply(ImageBitMask a, ImageBitMask b)
```


Intersezione di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La prima maschera. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageBitMask a, ImageBitMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageBitMask a, ImageBitMask b)
```


Disgiunzione esclusiva di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La prima maschera. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
