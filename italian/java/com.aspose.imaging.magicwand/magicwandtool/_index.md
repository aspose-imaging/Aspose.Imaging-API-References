---
title: "MagicWandTool"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe per la logica principale dell'algoritmo magic wand."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

La classe per la logica principale dell'algoritmo magic wand.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Crea un nuovo [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basato su [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) e sull'[RasterImage](../../com.aspose.imaging/rasterimage). |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Elabora i pixel caricati. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

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

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Crea un nuovo [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basato su [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) e sull'[RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine raster su cui l'algoritmo deve operare. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Impostazioni dell'algoritmo magic wand usate per creare la maschera. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Elabora i pixel caricati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo dei pixel. |
| pixel | int[] | I pixel ARGB a 32 bit. |
| start | [Point](../../com.aspose.imaging/point) | Il punto di partenza dei pixel. Se non è uguale a (left,top) significa che non è un rettangolo completo. |
| end | [Point](../../com.aspose.imaging/point) | Il punto finale dei pixel. Se non è uguale a (right,bottom) significa che non è un rettangolo completo. |

