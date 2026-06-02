---
title: "MagicWandTool"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Magic Wand algoritması ana mantığı için sınıf."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

Magic Wand algoritması ana mantığı için sınıf.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Yeni bir [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) oluşturur; [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) ve kaynak [RasterImage](../../com.aspose.imaging/rasterimage) temel alınarak. |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Yüklenen pikselleri işler. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Özel eşik değeri 150 olan, (120, 100) pikselinin ton ve rengine dayanarak magic wand aracıyla yeni bir maske oluşturun.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Maskeyi görüntüye uygula
            .apply();

    // Zorunlu şeffaflık renk tipi seçeneğiyle görüntüyü kaydet
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
    // (845, 128) pikselinin ton ve rengine dayanarak magic wand aracıyla yeni bir maske oluşturun.
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Mevcut maskeyi, magic wand aracıyla oluşturulan belirtilen maske ile birleştir
            .union(new MagicWandSettings(416, 387))
            // Mevcut maskeyi tersine çevir
            .invert()
            // Belirtilen eşik değeriyle magic wand aracıyla oluşturulan maskeyi mevcut maskeden çıkar
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Belirtilen dört dikdörtgen maskeyi mevcut maskeden tek tek çıkar
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Maskeyi belirtilen ayarlarla yumuşat
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Maskeyi görüntüye uygula
            .apply();

    // Görüntüyü kaydet
    image.save(outputFilePath);
}

```

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Yeni bir [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) oluşturur; [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) ve kaynak [RasterImage](../../com.aspose.imaging/rasterimage) temel alınarak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Algoritmanın çalışacağı raster görüntü. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Maskeyi oluşturmak için kullanılan magic wand algoritması ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Yüklenen pikselleri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksel dikdörtgeni. |
| pikseller | int[] | 32-bit ARGB pikselleri. |
| start | [Point](../../com.aspose.imaging/point) | Başlangıç piksel noktası. (sol,üst) ile eşit değilse, tam bir dikdörtgen olmadığını gösterir. |
| end | [Point](../../com.aspose.imaging/point) | Bitiş piksel noktası. (sağ,alt) ile eşit değilse, tam bir dikdörtgen olmadığını gösterir. |

