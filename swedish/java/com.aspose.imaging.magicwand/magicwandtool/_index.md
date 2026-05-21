---
title: "MagicWandTool"
second_title: "Aspose.Imaging för Java API-referens"
description: "Klassen för huvudlogiken i Magic Wand-algoritmen."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

Klassen för huvudlogiken i Magic Wand-algoritmen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Skapar en ny [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) baserad på [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) och käll- [RasterImage](../../com.aspose.imaging/rasterimage). |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Bearbetar de inlästa pixlarna. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Skapa en ny mask med magiskt stav-verktyg baserat på ton och färg för pixel (120, 100) med anpassad tröskel lika med 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Applicera masken på bilden
            .apply();

    // Spara bilden med tvingad transparensfärgstyp‑alternativ
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
    // Skapa en ny mask med magiskt stav-verktyg baserat på ton och färg för pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Förena den befintliga masken med den angivna som skapats av magiskt stav-verktyg
            .union(new MagicWandSettings(416, 387))
            // Invertera den befintliga masken
            .invert()
            // Subtrahera den angivna masken skapad av magiskt stav-verktyg med specificerad tröskel från den befintliga
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Subtrahera fyra angivna rektangelmasker från den befintliga masken en efter en
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Mjukgör masken med angivna inställningar
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applicera masken på bilden
            .apply();

    // Spara bilden
    image.save(outputFilePath);
}

```

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Skapar en ny [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) baserad på [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) och käll- [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbild för algoritmen att arbeta på. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magiskt stav-algoritmen som används vid skapande av mask. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Bearbetar de inlästa pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Pixelrektangeln. |
| pixlar | int[] | De 32-bitars ARGB-pixlarna. |
| start | [Point](../../com.aspose.imaging/point) | Startpunkten för pixlarna. Om den inte är lika med (vänster,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](../../com.aspose.imaging/point) | Slutpunkten för pixlarna. Om den inte är lika med (höger,botten) betyder det att vi inte har en fullständig rektangel. |

