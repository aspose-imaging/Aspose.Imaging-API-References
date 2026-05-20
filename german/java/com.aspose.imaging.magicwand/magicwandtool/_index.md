---
title: "MagicWandTool"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Klasse für die Hauptlogik des Magic‑Wand‑Algorithmus."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

Die Klasse für die Hauptlogik des Magic‑Wand‑Algorithmus.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Erstellt eine neue [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basierend auf [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) und der Quell-[RasterImage](../../com.aspose.imaging/rasterimage). |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Verarbeitet die geladenen Pixel. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Erstellen Sie eine neue Maske mit dem Magic‑Wand‑Tool basierend auf Ton und Farbe des Pixels (120, 100) mit einem benutzerdefinierten Schwellenwert von 150.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Maske auf das Bild anwenden.
            .apply();

    // Bild mit erzwungenem Transparenzfarbtyp‑Option speichern.
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
    // Erstellen Sie eine neue Maske mit dem Magic‑Wand‑Tool basierend auf Ton und Farbe des Pixels (845, 128).
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Vereinen Sie die vorhandene Maske mit der angegebenen, die vom Magic‑Wand‑Tool erstellt wurde.
            .union(new MagicWandSettings(416, 387))
            // Invertieren Sie die vorhandene Maske.
            .invert()
            // Subtrahieren Sie die angegebene, vom Magic‑Wand‑Tool erstellte Maske mit dem angegebenen Schwellenwert von der vorhandenen Maske.
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Subtrahieren Sie vier angegebene Rechteckmasken nacheinander von der vorhandenen Maske.
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Weichzeichnen Sie die Maske mit den angegebenen Einstellungen.
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Maske auf das Bild anwenden.
            .apply();

    // Bild speichern.
    image.save(outputFilePath);
}

```

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Erstellt eine neue [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) basierend auf [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) und der Quell-[RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbild, über dem der Algorithmus arbeiten soll. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Einstellungen des Magic‑Wand‑Algorithmus, der zur Maskenerstellung verwendet wird. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Verarbeitet die geladenen Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Pixelrechteck. |
| Pixel | int[] | Die 32‑Bit‑ARGB‑Pixel. |
| start | [Point](../../com.aspose.imaging/point) | Der Startpixelpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](../../com.aspose.imaging/point) | Der Endpixelpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

