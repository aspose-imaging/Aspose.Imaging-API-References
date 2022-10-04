---
title: DrawRectangles
second_title: Aspose.Imaging لمرجع NET API
description: يرسم سلسلة من المستطيلات المحددة بواسطةRectangleFaspose.imaging/rectanglef الهياكل .
type: docs
weight: 310
url: /ar/net/aspose.imaging/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

يرسم سلسلة من المستطيلات المحددة بواسطة[`RectangleF`](../../rectanglef) الهياكل .

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)التي تحدد لون وعرض ونمط مخططات المستطيلات. |
| rects | RectangleF[] | مصفوفة من[`RectangleF`](../../rectanglef) الهياكل التي تمثل المستطيلات المراد رسمها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *rects* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

يرسم سلسلة من المستطيلات المحددة بواسطة[`Rectangle`](../../rectangle) الهياكل .

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)التي تحدد لون وعرض ونمط مخططات المستطيلات. |
| rects | Rectangle[] | مصفوفة من[`Rectangle`](../../rectangle) الهياكل التي تمثل المستطيلات المراد رسمها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *rects* باطل. |

### أمثلة

يوضح هذا المثال إنشاء كائنات القلم واستخدامها. يقوم المثال بإنشاء صورة جديدة ورسم مستطيلات على سطح الصورة.

```csharp
[C#]

// قم بإنشاء مثيل لـ BmpOptions وقم بتعيين خصائصه المختلفة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل BmpOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان الملف المراد إنشاؤه ثابتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

// إنشاء مثيل للصورة في المسار المحدد
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // قم بإنشاء مثيل للرسومات وقم بتهيئته باستخدام كائن صورة
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // مسح واجهة الرسومات باللون الأبيض
    graphics.Clear(Aspose.Imaging.Color.White);

    // إنشاء مثيل من القلم باللون الأحمر والعرض 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    // قم بإنشاء مثيل لـ HatchBrush وعيّن خصائصه
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    // إنشاء مثيل من Pen
    // قم بتهيئته باستخدام كائن وعرض HatchBrush
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // احفظ جميع التغييرات.
    image.Save();
}
```

### أنظر أيضا

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->