---
title: "MagicWandTool"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La classe pour la logique principale de l'algorithme magic wand."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

La classe pour la logique principale de l'algorithme magic wand.
## Méthodes

| Méthode | Description |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Crée un nouveau [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basé sur [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) et le [RasterImage](../../com.aspose.imaging/rasterimage) source. |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Traite les pixels chargés. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Créez un nouveau masque en utilisant le magic wand tool basé sur la tonalité et la couleur du pixel (120, 100) avec un seuil personnalisé égal à 150.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Appliquez le masque à l'image.
            .apply();

    // Enregistrez l'image avec l'option de type de couleur de transparence forcée.
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
    // Créez un nouveau masque en utilisant le magic wand tool basé sur la tonalité et la couleur du pixel (845, 128).
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Fusionnez le masque existant avec celui spécifié créé par le magic wand tool.
            .union(new MagicWandSettings(416, 387))
            // Inversez le masque existant.
            .invert()
            // Soustrayez le masque spécifié créé par le magic wand tool avec le seuil spécifié du masque existant.
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Soustrayez quatre masques rectangulaires spécifiés du masque existant un par un.
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Adoucissez le masque avec les paramètres spécifiés.
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Appliquez le masque à l'image.
            .apply();

    // Enregistrez l'image.
    image.save(outputFilePath);
}

```

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Crée un nouveau [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basé sur [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) et le [RasterImage](../../com.aspose.imaging/rasterimage) source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Image raster sur laquelle l'algorithme doit travailler. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Paramètres de l'algorithme magic wand utilisés pour créer le masque. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Traite les pixels chargés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle des pixels. |
| pixels | int[] | Les pixels ARGB 32 bits. |
| start | [Point](../../com.aspose.imaging/point) | Le point de départ des pixels. S'il n'est pas égal à (gauche,haut), cela signifie que nous n'avons pas un rectangle complet. |
| end | [Point](../../com.aspose.imaging/point) | Le point de fin des pixels. S'il n'est pas égal à (droite,bas), cela signifie que nous n'avons pas un rectangle complet. |

