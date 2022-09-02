---
title: GifImage
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفGifImageaspose.imaging.fileformats.gif/gifimage فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`GifImage`](../../gifimage) فئة .

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstFrame | GifFrameBlock | الإطار الأول لتهيئة صورة gif به. |
| globalPalette | IColorPalette | اللوحة العالمية المراد استخدامها. لاحظ إذا كان كلاهما*firstFrame* و*globalPalette* فارغة ثم يتم استخدام لوحة الألوان العامة الافتراضية. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون الإطار فارغًا ؛ FirstFrame |
| ArgumentException | الإطار الأول ينتمي بالفعل إلى بعض الصور الأخرى. تحقق من خاصية الحاوية. ؛ FirstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | يجب أن تحتوي اللوحة المحددة على عدد إدخالات يساوي قوة 2. الحد الأدنى لحجم اللوحة هو 2 ، والحد الأقصى هو 256. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة GIF باستخدام لوحة مخصصة وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بإنشاء كتلة إطار GIF بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // املأ الكتلة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // استخدم لوحة 4 بت لتقليل حجم الصورة. يمكن أن تسوء الجودة.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### أنظر أيضا

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* المجسم [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`GifImage`](../../gifimage) فئة .

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstFrame | GifFrameBlock | الإطار الأول لتهيئة صورة gif به. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون الإطار فارغًا ؛ FirstFrame |
| ArgumentException | الإطار الأول ينتمي بالفعل إلى بعض الصور الأخرى. تحقق من خاصية الحاوية. ؛ FirstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | يجب أن تحتوي اللوحة المحددة على عدد إدخالات يساوي قوة 2. الحد الأدنى لحجم اللوحة هو 2 ، والحد الأقصى هو 256. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة GIF وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بإنشاء كتلة إطار GIF بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // املأ الكتلة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

يوضح المثال التالي كيفية إنشاء صورة GIF متحركة من كتل GIF فردية.

```csharp
[C#]

string dir = "c:\\temp\\";

// أنشئ صورة بتنسيق GIF 100 × 100 بكسل.
// الكتلة الأولى سوداء بالكامل بشكل افتراضي.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد زاوية شكل القوس الأحمر تدريجيًا.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // زد زاوية القوس الأسود تدريجيًا وامسح القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### أنظر أيضا

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* المجسم [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`GifImage`](../../gifimage) فئة .

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstFrame | GifFrameBlock | الإطار الأول لتهيئة صورة gif به. |
| globalPalette | IColorPalette | اللوحة العالمية المراد استخدامها. لاحظ إذا كان كلاهما*firstFrame* و*globalPalette* فارغة ثم يتم استخدام لوحة الألوان العامة الافتراضية. |
| isPaletteSorted | Boolean | إذا تم التعيين على`حقيقي` يتم فرز اللوحة. لاحظ استخدام المعلمة عندما*globalPalette* هو ليس لاشيء. |
| paletteColorResolution | Byte | دقة لون اللوحة. لاحظ استخدام المعلمة عندما*globalPalette* هو ليس لاشيء. |
| paletteBackgroundColorIndex | Byte | فهرس لون خلفية اللوحة. |
| aspectRatio | Byte | نسبة العرض إلى الارتفاع. |
| hasTrailer | Boolean | إذا تم التعيين على`حقيقي` صورة gif لها مقطع دعائي وإلا فلن يتم كتابة مقطع دعائي في نهاية البث. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون الإطار فارغًا ؛ FirstFrame |
| ArgumentException | الإطار الأول ينتمي بالفعل إلى بعض الصور الأخرى. تحقق من خاصية الحاوية. ؛ FirstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | يجب أن تحتوي اللوحة المحددة على عدد إدخالات يساوي قوة 2. الحد الأدنى لحجم اللوحة هو 2 ، والحد الأقصى هو 256. |

### أنظر أيضا

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
