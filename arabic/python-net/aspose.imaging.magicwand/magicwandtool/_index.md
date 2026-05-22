---
title: "فئة MagicWandTool"
type: docs
weight: 100
url: /ar/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | يعالج البكسلات المحملة. |
| [select(source, settings)](#select_source_settings_2) | ينشئ قناعًا جديدًا من [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) استنادًا إلى [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) وصورة المصدر [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

يعالج البكسلات المحملة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مستطيل البكسلات. |
| البكسلات | int[] | بكسلات ARGB 32-بت. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة بكسلات البداية. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة بكسلات النهاية. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

ينشئ قناعًا جديدًا من [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) استنادًا إلى [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) وصورة المصدر [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة نقطية لتعمل الخوارزمية عليها. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات خوارزمية العصا السحرية المستخدمة في إنشاء القناع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


