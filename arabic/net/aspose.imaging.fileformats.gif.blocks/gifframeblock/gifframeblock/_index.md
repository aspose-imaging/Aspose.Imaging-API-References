---
title: GifFrameBlock
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | UInt16 | عرض الصورة. |
| height | UInt16 | ارتفاع الصورة. |

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

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |
| width | UInt16 | عرض الصورة. |
| height | UInt16 | ارتفاع الصورة. |

### أنظر أيضا

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |
| width | UInt16 | عرض الصورة. |
| height | UInt16 | ارتفاع الصورة. |
| colorPalette | IColorPalette | لوحة الألوان. |
| isPaletteSorted | Boolean | إذا تم التعيين على`حقيقي` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم التعيين على`حقيقي` إطار GIF متشابك. |
| bitsPerPixel | Byte | وحدات البت لكل بكسل. |

### أنظر أيضا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(RasterImage image)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة المراد تهيئة بكسل الإطار وبيانات اللوحة بها. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة المراد تهيئة بكسل الإطار وبيانات اللوحة بها. |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة المراد تهيئة بكسل الإطار وبيانات اللوحة بها. |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |
| isPaletteSorted | Boolean | إذا تم التعيين على`حقيقي` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم التعيين على`حقيقي` إطار GIF متشابك. |
| lzwCodeSize | Byte | وحدات البت لكل بكسل. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل صورة من وتهيئة بكسل الإطار وبيانات اللوحة باستخدام. |

### أنظر أيضا

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل صورة من وتهيئة بكسل الإطار وبيانات اللوحة باستخدام. |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |

### أنظر أيضا

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل صورة من وتهيئة بكسل الإطار وبيانات اللوحة باستخدام. |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |
| isPaletteSorted | Boolean | إذا تم التعيين على`حقيقي` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم التعيين على`حقيقي` إطار GIF متشابك. |
| lzwCodeSize | Byte | وحدات البت لكل بكسل. |

### أنظر أيضا

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المطلوب تحميل صورة منه وتهيئة بكسل الإطار وبيانات اللوحة به. |

### أنظر أيضا

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المطلوب تحميل صورة منه وتهيئة بكسل الإطار وبيانات اللوحة به. |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |

### أنظر أيضا

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

يقوم بتهيئة مثيل جديد لملف[`GifFrameBlock`](../../gifframeblock) فئة .

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المطلوب تحميل صورة منه وتهيئة بكسل الإطار وبيانات اللوحة به. |
| left | UInt16 | موضع الصورة الأيسر. |
| top | UInt16 | موضع الصورة العلوي. |
| isPaletteSorted | Boolean | إذا تم التعيين على`حقيقي` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم التعيين على`حقيقي` إطار GIF متشابك. |
| lzwCodeSize | Byte | وحدات البت لكل بكسل. |

### أنظر أيضا

* class [GifFrameBlock](../../gifframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
