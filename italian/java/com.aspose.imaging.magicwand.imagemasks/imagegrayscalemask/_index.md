---
title: "ImageGrayscaleMask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive una maschera immagine in scala di grigi."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

Descrive una maschera immagine in scala di grigi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | Inizializza una nuova istanza della classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con la larghezza e l'altezza specificate. |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | Inizializza una nuova istanza della classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con le dimensioni dell'[RasterImage](../../com.aspose.imaging/rasterimage) esistente specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSource()](#getSource--) | Restituisce l'immagine sorgente utilizzata per creare questa maschera, se esiste. |
| [getWidth()](#getWidth--) | Restituisce la larghezza, in pixel, di questa maschera. |
| [getHeight()](#getHeight--) | Restituisce l'altezza, in pixel, di questa maschera. |
| [getBounds()](#getBounds--) | Restituisce i limiti, in pixel, di questa maschera. |
| [getSelectionBounds()](#getSelectionBounds--) | Restituisce i limiti della parte selezionata della maschera, in pixel. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ottiene l'opacità del pixel specificato. |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | Imposta l'opacità del pixel specificato. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Verifica se il pixel specificato è opaco. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Verifica se il pixel specificato è trasparente. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Ottiene l'opacità del pixel specificato con precisione a byte. |
| [deepClone()](#deepClone--) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
| [apply()](#apply--) | Applica la maschera corrente alla sorgente [RasterImage](../../com.aspose.imaging/rasterimage), se esiste. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Applica la maschera corrente alla [RasterImage](../../com.aspose.imaging/rasterimage) specificata. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Ritaglia la maschera con la dimensione specificata. |
| [crop(int width, int height)](#crop-int-int-) | Ritaglia la maschera con la larghezza e l'altezza specificate. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia la maschera con il rettangolo specificato. |
| [invert()](#invert--) | Ottiene l'inversione della maschera corrente. |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Unione di due maschere. |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Ottiene la sottrazione della maschera fornita dalla corrente. |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Ottiene l'intersezione della maschera corrente con quella fornita. |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita. |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Inverte la maschera. |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Unione di due maschere. |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Sottrai la seconda maschera dalla prima. |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Intersezione di due maschere. |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Disgiunzione esclusiva di due maschere. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nuova maschera usando lo strumento magic wand basata sul tono e sul colore del pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Unisci la maschera esistente con quella specificata creata dallo strumento magic wand
            .union(new MagicWandSettings(416, 387))
            // Inverti la maschera esistente
            .invert()
            // Sottrai la maschera specificata creata dallo strumento magic wand con soglia specificata dalla maschera esistente
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Sottrai quattro maschere rettangolari specificate dalla maschera esistente una alla volta
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Sfuma la maschera con le impostazioni specificate
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applica la maschera all'immagine
            .apply();

    // Salva immagine
    image.save(outputFilePath);
}

```

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


Inizializza una nuova istanza della classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con la larghezza e l'altezza specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | Larghezza della maschera. |
| height | int | Altezza della maschera. |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


Inizializza una nuova istanza della classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con le dimensioni dell'[RasterImage](../../com.aspose.imaging/rasterimage) esistente specificato. L'[RasterImage](../../com.aspose.imaging/rasterimage) specificato sarà memorizzato come immagine sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine sorgente. |

### getSource() {#getSource--}
```
public final RasterImage getSource()
```


Restituisce l'immagine sorgente utilizzata per creare questa maschera, se esiste.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza, in pixel, di questa maschera.

**Returns:**
int - la larghezza, in pixel, di questa maschera.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza, in pixel, di questa maschera.

**Returns:**
int - l'altezza, in pixel, di questa maschera.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Restituisce i limiti, in pixel, di questa maschera.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


Restituisce i limiti della parte selezionata della maschera, in pixel.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


Ottiene l'opacità del pixel specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. Valore: valore byte; 0 se trasparente; 255 se opaco. |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


Imposta l'opacità del pixel specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. Valore: valore byte; 0 se trasparente; 255 se opaco. |
| valore | byte | l'opacità del pixel specificato. |

### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
```


Verifica se il pixel specificato è opaco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
boolean - true se il pixel specificato è opaco; altrimenti, false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public final boolean isTransparent(int x, int y)
```


Verifica se il pixel specificato è trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
boolean - true se il pixel specificato è trasparente; altrimenti, false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public final byte getByteOpacity(int x, int y)
```


Ottiene l'opacità del pixel specificato con precisione a byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
byte - Valore byte, che rappresenta l'opacità del pixel specificato.
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns:**
java.lang.Object - Un nuovo oggetto che è una copia di questa istanza.
### apply() {#apply--}
```
public final void apply()
```


Applica la maschera corrente alla sorgente [RasterImage](../../com.aspose.imaging/rasterimage), se esiste.

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Applica la maschera corrente alla [RasterImage](../../com.aspose.imaging/rasterimage) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine a cui applicare la maschera. |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


Ritaglia la maschera con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | La dimensione specificata. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


Ritaglia la maschera con la larghezza e l'altezza specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza specificata. |
| height | int | L'altezza specificata. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


Ritaglia la maschera con il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo specificato. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


Ottiene l'inversione della maschera corrente.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


Unione di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Maschera fornita |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


Ottiene la sottrazione della maschera fornita dalla corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Maschera fornita |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


Ottiene l'intersezione della maschera corrente con quella fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Maschera fornita |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Maschera fornita |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


Inverte la maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La maschera da invertire. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Unione di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La prima maschera. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La seconda maschera. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Sottrai la seconda maschera dalla prima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La prima maschera. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La seconda maschera. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Intersezione di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La prima maschera. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La seconda maschera. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Disgiunzione esclusiva di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La prima maschera. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La seconda maschera. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
