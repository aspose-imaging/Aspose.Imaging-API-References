---
title: "GifImage.GifImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ GifImage. أنشئ كائن GifImage جديد بالمعلمات المحددة للإطار الأول واللوحة العامة. ابدأ بإدارة صور GIF بسرعة مع ضمان تمثيل دقيق وإعدادات قابلة للتخصيص للحصول على أفضل النتائج."
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

أنشئ كائنًا جديدًا [`GifImage`](../) بالمعلمات المحددة للإطار الأول واللوحة العامة. ابدأ بإدارة صور GIF بسرعة، مع ضمان تمثيل دقيق وإعدادات قابلة للتخصيص للحصول على أفضل النتائج.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| firstFrame | GifFrameBlock | الإطار الأول لتهيئة صورة GIF به. |
| globalPalette | IColorPalette | اللوحة العامة للاستخدام. لاحظ أنه إذا كان كل من *firstFrame* و *globalPalette* فارغين فإن اللوحة العامة الافتراضية تُستخدم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون *firstFrame* فارغًا |
| ArgumentException | الإطار *firstFrame* ينتمي بالفعل إلى صورة أخرى. تحقق من خاصية Container. |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception/) | يجب أن يحتوي *globalPalette* المحدد على عدد الإدخالات مساويًا لقوة 2. الحد الأدنى لحجم اللوحة هو 2، والحد الأقصى هو 256. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة GIF مع لوحة ألوان مخصصة وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء كتلة إطار GIF بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // ملء الكتلة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // استخدم لوحة ألوان 4-بت لتقليل حجم الصورة. قد تتدهور الجودة.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### انظر أيضًا

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

تصميم صور GIF يصبح سهلًا مع مُنشئ [`GifImage`](../). باستخدام معامل firstFrame فقط، يدخل إلى عالم التواصل البصري الديناميكي.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| firstFrame | GifFrameBlock | الإطار الأول لتهيئة صورة GIF به. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون *firstFrame* فارغًا |
| ArgumentException | الإطار *firstFrame* ينتمي بالفعل إلى صورة أخرى. تحقق من خاصية Container. |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception/) | يجب أن تحتوي اللوحة المحددة على عدد الإدخالات مساويًا لقوة 2. الحد الأدنى لحجم اللوحة هو 2، والحد الأقصى هو 256. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة GIF وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء كتلة إطار GIF بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // ملء الكتلة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

المثال التالي يوضح كيفية تجميع صورة GIF متحركة من كتل GIF فردية.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة GIF بحجم 100 × 100 بكسل.
// الكتلة الأولى تكون سوداء بالكامل بشكل افتراضي.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد تدريجياً زاوية الشكل القوسي الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // زد تدريجياً زاوية القوس الأسود وأزل القوس الأحمر.
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

### انظر أيضًا

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

ابدأ بسهولة مع مُنشئ [`GifImage`](../). باستخدام هذه الطريقة البسيطة، يمكنك الغوص في إنشاء صور GIF متحركة بسهولة. فقط قدم firstFrame، globalPalette، paletteColorResolution، aspectRatio، وغيرها من المعاملات، وستكون جاهزًا لإحياء مرئياتك.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| firstFrame | GifFrameBlock | الإطار الأول لتهيئة صورة GIF به. |
| globalPalette | IColorPalette | اللوحة العامة للاستخدام. لاحظ أنه إذا كان كل من *firstFrame* و *globalPalette* فارغين فإن اللوحة العامة الافتراضية تُستخدم. |
| isPaletteSorted | Boolean | إذا تم تعيينه إلى `true` يتم فرز اللوحة. لاحظ أن المعامل يُستخدم عندما يكون *globalPalette* غير فارغ. |
| paletteColorResolution | بايت | دقة ألوان اللوحة. لاحظ أن المعامل يُستخدم عندما يكون *globalPalette* غير فارغ. |
| paletteBackgroundColorIndex | بايت | فهرس لون خلفية اللوحة. |
| aspectRatio | بايت | نسبة العرض إلى الارتفاع. |
| hasTrailer | Boolean | إذا تم تعيينه إلى `true` تحتوي صورة GIF على مقطع ختامي، وإلا لن يُكتب أي مقطع ختامي في نهاية الدفق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون *firstFrame* فارغًا |
| ArgumentException | الإطار *firstFrame* ينتمي بالفعل إلى صورة أخرى. تحقق من خاصية Container. |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception/) | يجب أن يحتوي *globalPalette* المحدد على عدد الإدخالات مساويًا لقوة 2. الحد الأدنى لحجم اللوحة هو 2، والحد الأقصى هو 256. |

### انظر أيضًا

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


