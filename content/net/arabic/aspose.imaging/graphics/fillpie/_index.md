---
title: FillPie
second_title: Aspose.Imaging لمرجع NET API
description: يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطةRectangleFaspose.imaging/rectanglef هيكل وخطين شعاعي.
type: docs
weight: 370
url: /ar/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة[`RectangleF`](../../rectanglef) هيكل وخطين شعاعي.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) التي تحدد خصائص التعبئة. |
| rect | Rectangle | [`Rectangle`](../../rectangle)الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه القسم الدائري. |
| startAngle | Single | تُقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من المقطع الدائري. |
| sweepAngle | Single | قياس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* المعلمة إلى الجانب الثاني من قسم الفطيرة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* باطل. |

### أمثلة

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

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة[`RectangleF`](../../rectanglef) هيكل وخطين شعاعي.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) التي تحدد خصائص التعبئة. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه القسم الدائري. |
| startAngle | Single | تُقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من المقطع الدائري. |
| sweepAngle | Single | قياس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* المعلمة إلى الجانب الثاني من قسم الفطيرة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* باطل. |

### أنظر أيضا

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج من الإحداثيات والعرض والارتفاع وخطين نصف قطريين.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) التي تحدد خصائص التعبئة. |
| x | Single | الإحداثي x للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه المقطع الدائري. |
| y | Single | الإحداثي y للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه المقطع الدائري. |
| width | Single | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه القسم الدائري. |
| height | Single | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه القسم الدائري. |
| startAngle | Single | تُقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من المقطع الدائري. |
| sweepAngle | Single | قياس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* المعلمة إلى الجانب الثاني من قسم الفطيرة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* باطل. |

### أنظر أيضا

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج من الإحداثيات والعرض والارتفاع وخطين نصف قطريين.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) التي تحدد خصائص التعبئة. |
| x | Int32 | الإحداثي x للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه المقطع الدائري. |
| y | Int32 | الإحداثي y للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه المقطع الدائري. |
| width | Int32 | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه القسم الدائري. |
| height | Int32 | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه القسم الدائري. |
| startAngle | Int32 | تُقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من المقطع الدائري. |
| sweepAngle | Int32 | قياس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* المعلمة إلى الجانب الثاني من قسم الفطيرة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* باطل. |

### أنظر أيضا

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
