---
title: "GifFrameBlock.GifFrameBlock"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ GifFrameBlock. يهيئ مثيلاً جديداً من الفئة GifFrameBlock"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | UInt16 | عرض الصورة. |
| الارتفاع | UInt16 | ارتفاع الصورة. |

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

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |
| العرض | UInt16 | عرض الصورة. |
| الارتفاع | UInt16 | ارتفاع الصورة. |

### انظر أيضًا

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |
| العرض | UInt16 | عرض الصورة. |
| الارتفاع | UInt16 | ارتفاع الصورة. |
| colorPalette | IColorPalette | لوحة الألوان. |
| isPaletteSorted | Boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكاً. |
| bitsPerPixel | بايت | عدد البتات لكل بكسل. |

### انظر أيضًا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(RasterImage image)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة المستخدمة لتهيئة بكسلات الإطار وبيانات اللوحة. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة المستخدمة لتهيئة بكسلات الإطار وبيانات اللوحة. |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة المستخدمة لتهيئة بكسلات الإطار وبيانات اللوحة. |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |
| isPaletteSorted | Boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكاً. |
| lzwCodeSize | بايت | عدد البتات لكل بكسل. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |

### انظر أيضًا

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |

### انظر أيضًا

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |
| isPaletteSorted | Boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكاً. |
| lzwCodeSize | بايت | عدد البتات لكل بكسل. |

### انظر أيضًا

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |

### انظر أيضًا

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |

### انظر أيضًا

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

يهيئ مثيلاً جديداً من الفئة [`GifFrameBlock`](../).

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |
| يسار | UInt16 | موضع الصورة الأيسر. |
| أعلى | UInt16 | موضع الصورة العلوي. |
| isPaletteSorted | Boolean | إذا تم تعيينه إلى `true` يتم فرز لوحة الألوان. |
| isGifFrameInterlaced | Boolean | إذا تم تعيينه إلى `true` يكون إطار GIF متشابكاً. |
| lzwCodeSize | بايت | عدد البتات لكل بكسل. |

### انظر أيضًا

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)


