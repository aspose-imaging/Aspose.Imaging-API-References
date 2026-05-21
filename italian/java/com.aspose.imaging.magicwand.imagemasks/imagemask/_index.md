---
title: "ImageMask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Descrive una maschera immagine binaria."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.magicwand.imagemasks/imagemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public abstract class ImageMask implements IImageMask
```

Descrive una maschera immagine binaria.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [to_ImageGrayscaleMask(ImageMask mask)](#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Conversione di `mask` a un [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask). |
| [op_LogicalNot(ImageMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Inverte la maschera. |
| [op_Addition(ImageMask a, ImageMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Unione di due maschere. |
| [op_Subtraction(ImageMask a, ImageMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Sottrai la seconda maschera dalla prima. |
| [op_Multiply(ImageMask a, ImageMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Intersezione di due maschere. |
| [op_ExclusiveOr(ImageMask a, ImageMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Disgiunzione esclusiva di due maschere. |
| [getSource()](#getSource--) | Restituisce l'immagine sorgente utilizzata per creare questa maschera, se esiste. |
| [getWidth()](#getWidth--) | Restituisce la larghezza, in pixel, di questa maschera. |
| [getHeight()](#getHeight--) | Restituisce l'altezza, in pixel, di questa maschera. |
| [getBounds()](#getBounds--) | Restituisce i limiti, in pixel, di questa maschera. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ottiene l'opacità del pixel specificato. |
| [inflate(int size)](#inflate-int-) | Espande questa maschera dell'importo specificato. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Ritaglia la maschera con la dimensione specificata. |
| [crop(int width, int height)](#crop-int-int-) | Ritaglia la maschera con la larghezza e l'altezza specificate. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia la maschera con il rettangolo specificato. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Verifica se il pixel specificato è opaco. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Verifica se il pixel specificato è trasparente. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Ottiene l'opacità del pixel specificato con precisione a byte. |
| [getFeathered()](#getFeathered--) | Ottiene la maschera in scala di grigi con il bordo sfumato con le impostazioni predefinite. |
| [getFeathered(FeatheringSettings settings)](#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-) | Ottiene la maschera in scala di grigi con il bordo sfumato con le impostazioni specificate. |
| [apply()](#apply--) | Applica la maschera corrente alla sorgente [RasterImage](../../com.aspose.imaging/rasterimage), se esiste. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Applica la maschera corrente alla [RasterImage](../../com.aspose.imaging/rasterimage) specificata. |
| [invert()](#invert--) | Ottiene l'inversione della maschera corrente. |
| [union(ImageMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ottiene l'unione della maschera corrente con quella fornita. |
| [union()](#union--) | Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera. |
| [union(MagicWandSettings settings)](#union-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera. |
| [union(RasterImage image)](#union-com.aspose.imaging.RasterImage-) | Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata all'immagine fornita. |
| [union(RasterImage image, MagicWandSettings settings)](#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata all'immagine fornita. |
| [subtract(ImageMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ottiene la sottrazione della maschera fornita dalla corrente. |
| [subtract()](#subtract--) | Ottiene il risultato della selezione magic wand applicata alla sorgente della maschera corrente sottratto dalla maschera. |
| [subtract(MagicWandSettings settings)](#subtract-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene il risultato della selezione magic wand applicata alla sorgente della maschera corrente sottratto dalla maschera. |
| [subtract(RasterImage image)](#subtract-com.aspose.imaging.RasterImage-) | Ottiene il risultato della selezione magic wand applicata all'immagine fornita, sottratto dalla maschera corrente. |
| [subtract(RasterImage image, MagicWandSettings settings)](#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene il risultato della selezione magic wand applicata all'immagine fornita, sottratto dalla maschera corrente. |
| [intersect(ImageMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ottiene l'intersezione della maschera corrente con quella fornita. |
| [intersect()](#intersect--) | Ottiene l'intersezione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera. |
| [intersect(MagicWandSettings settings)](#intersect-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene l'intersezione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera. |
| [intersect(RasterImage image)](#intersect-com.aspose.imaging.RasterImage-) | Ottiene l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita. |
| [intersect(RasterImage image, MagicWandSettings settings)](#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita. |
| [exclusiveDisjunction(ImageMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita. |
| [exclusiveDisjunction()](#exclusiveDisjunction--) | Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera. |
| [exclusiveDisjunction(MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera. |
| [exclusiveDisjunction(RasterImage image)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-) | Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita. |
| [exclusiveDisjunction(RasterImage image, MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita. |

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

### to_ImageGrayscaleMask(ImageMask mask) {#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageGrayscaleMask to_ImageGrayscaleMask(ImageMask mask)
```


Conversione di `mask` a un [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Il valore della maschera. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - The new [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) base on `mask`.
### op_LogicalNot(ImageMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_LogicalNot(ImageMask a)
```


Inverte la maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La maschera da invertire. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageMask a, ImageMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Addition(ImageMask a, ImageMask b)
```


Unione di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La prima maschera. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageMask a, ImageMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Subtraction(ImageMask a, ImageMask b)
```


Sottrai la seconda maschera dalla prima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La prima maschera. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageMask a, ImageMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Multiply(ImageMask a, ImageMask b)
```


Intersezione di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La prima maschera. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageMask a, ImageMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageMask a, ImageMask b)
```


Disgiunzione esclusiva di due maschere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La prima maschera. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La seconda maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
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
### get_Item(int x, int y) {#get-Item-int-int-}
```
public abstract boolean get_Item(int x, int y)
```


Ottiene l'opacità del pixel specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel. |
| y | int | La coordinata y del pixel. |

**Returns:**
boolean - true se il pixel specificato è opaco; altrimenti, false.
### inflate(int size) {#inflate-int-}
```
public abstract ImageMask inflate(int size)
```


Espande questa maschera dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La quantità da gonfiare questa maschera. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageMask crop(Size size)
```


Ritaglia la maschera con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | La dimensione specificata. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(int width, int height) {#crop-int-int-}
```
public final ImageMask crop(int width, int height)
```


Ritaglia la maschera con la larghezza e l'altezza specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza specificata. |
| height | int | L'altezza specificata. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public abstract ImageMask crop(Rectangle rectangle)
```


Ritaglia la maschera con il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo specificato. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
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
### getFeathered() {#getFeathered--}
```
public final ImageGrayscaleMask getFeathered()
```


Ottiene la maschera in scala di grigi con il bordo sfumato con le impostazioni predefinite.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### getFeathered(FeatheringSettings settings) {#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-}
```
public final ImageGrayscaleMask getFeathered(FeatheringSettings settings)
```


Ottiene la maschera in scala di grigi con il bordo sfumato con le impostazioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| settings | [FeatheringSettings](../../com.aspose.imaging.magicwand.imagemasks/featheringsettings) | Impostazioni di sfumatura. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### apply() {#apply--}
```
public final void apply()
```


Applica la maschera corrente alla sorgente [RasterImage](../../com.aspose.imaging/rasterimage), se esiste.


**Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nuova maschera usando lo strumento magic wand basata sul tono e sul colore del pixel (120, 100) con soglia personalizzata pari a 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Applica la maschera all'immagine
            .apply();

    // Salva l'immagine con l'opzione di tipo colore di trasparenza forzata
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Applica la maschera corrente alla [RasterImage](../../com.aspose.imaging/rasterimage) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine a cui applicare la maschera. |

### invert() {#invert--}
```
public final ImageBitMask invert()
```


Ottiene l'inversione della maschera corrente.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).

**Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).**

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

### union(ImageMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask union(ImageMask mask)
```


Ottiene l'unione della maschera corrente con quella fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Maschera fornita |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union() {#union--}
```
public final ImageBitMask union()
```


Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(MagicWandSettings settings) {#union-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(MagicWandSettings settings)
```


Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image) {#union-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask union(RasterImage image)
```


Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata all'immagine fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image, MagicWandSettings settings) {#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(RasterImage image, MagicWandSettings settings)
```


Ottiene l'unione della maschera corrente con il risultato della selezione magic wand applicata all'immagine fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(ImageMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask subtract(ImageMask mask)
```


Ottiene la sottrazione della maschera fornita dalla corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Maschera fornita |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract() {#subtract--}
```
public final ImageBitMask subtract()
```


Ottiene il risultato della selezione magic wand applicata alla sorgente della maschera corrente sottratto dalla maschera.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(MagicWandSettings settings) {#subtract-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(MagicWandSettings settings)
```


Ottiene il risultato della selezione magic wand applicata alla sorgente della maschera corrente sottratto dalla maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image) {#subtract-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask subtract(RasterImage image)
```


Ottiene il risultato della selezione magic wand applicata all'immagine fornita, sottratto dalla maschera corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image, MagicWandSettings settings) {#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(RasterImage image, MagicWandSettings settings)
```


Ottiene il risultato della selezione magic wand applicata all'immagine fornita, sottratto dalla maschera corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(ImageMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask intersect(ImageMask mask)
```


Ottiene l'intersezione della maschera corrente con quella fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Maschera fornita |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect() {#intersect--}
```
public final ImageBitMask intersect()
```


Ottiene l'intersezione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(MagicWandSettings settings) {#intersect-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(MagicWandSettings settings)
```


Ottiene l'intersezione della maschera corrente con il risultato della selezione magic wand applicata alla sorgente della maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image) {#intersect-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask intersect(RasterImage image)
```


Ottiene l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image, MagicWandSettings settings) {#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(RasterImage image, MagicWandSettings settings)
```


Ottiene l'intersezione della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(ImageMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask exclusiveDisjunction(ImageMask mask)
```


Ottiene la disgiunzione esclusiva della maschera corrente con quella fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Maschera fornita |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction() {#exclusiveDisjunction--}
```
public final ImageBitMask exclusiveDisjunction()
```


Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(MagicWandSettings settings)
```


Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata alla sorgente della maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image)
```


Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image, MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image, MagicWandSettings settings)
```


Ottiene la disgiunzione esclusiva della maschera corrente con il risultato della selezione bacchetta magica applicata all'immagine fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine per la bacchetta magica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni della bacchetta magica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
