---
title: "MagicWandTool"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفئة الخاصة بالمنطق الرئيسي لخوارزمية magic wand."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

الفئة الخاصة بالمنطق الرئيسي لخوارزمية magic wand.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | ينشئ نسخة جديدة من [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) بناءً على [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) وصورة المصدر [RasterImage](../../com.aspose.imaging/rasterimage). |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | يعالج البكسلات المحمّلة. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // أنشئ قناعًا جديدًا باستخدام أداة العصا السحرية بناءً على درجة اللون ولون البكسل (120, 100) مع عتبة مخصصة مساوية لـ 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // تطبيق القناع على الصورة
            .apply();

    // احفظ الصورة مع خيار فرض نوع لون الشفافية
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
    // أنشئ قناعًا جديدًا باستخدام أداة العصا السحرية بناءً على درجة اللون ولون البكسل (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // ادمج القناع الحالي مع القناع المحدد الذي تم إنشاؤه بواسطة أداة العصا السحرية
            .union(new MagicWandSettings(416, 387))
            // عكس القناع الحالي
            .invert()
            // اطرح القناع المحدد الذي تم إنشاؤه بأداة العصا السحرية مع العتبة المحددة من القناع الحالي
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // اطرح أربعة أقنعة مستطيلة محددة من القناع الحالي واحدًا تلو الآخر
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // تنعيم القناع بالإعدادات المحددة
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // تطبيق القناع على الصورة
            .apply();

    // حفظ الصورة
    image.save(outputFilePath);
}

```

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


ينشئ نسخة جديدة من [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) بناءً على [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) وصورة المصدر [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة نقطية لتعمل الخوارزمية عليها. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات خوارزمية العصا السحرية المستخدمة في إنشاء القناع. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


يعالج البكسلات المحمّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل البكسلات. |
| بكسلات | int[] | بكسلات ARGB 32-بت. |
| start | [Point](../../com.aspose.imaging/point) | نقطة بكسلات البداية. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| end | [Point](../../com.aspose.imaging/point) | نقطة بكسلات النهاية. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |

