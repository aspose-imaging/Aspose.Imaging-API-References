---
title: "Graphics.DrawRectangles"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Graphics. ترسم سلسلة من المستطيلات المحددة بواسطة بنى RectangleF."
type: docs
weight: 320
url: /ar/net/aspose.imaging/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

ترسم سلسلة من المستطيلات المحددة بواسطة بنى [`RectangleF`](../../rectanglef/).

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | RectangleF[] | مصفوفة من بنى [`RectangleF`](../../rectanglef/) التي تمثل المستطيلات التي سيتم رسمها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو- *rects* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

ترسم سلسلة من المستطيلات المحددة بواسطة بنى [`Rectangle`](../../rectangle/).

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | Rectangle[] | مصفوفة من بنى [`Rectangle`](../../rectangle/) التي تمثل المستطيلات التي سيتم رسمها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو- *rects* فارغ. |

## أمثلة

يوضح هذا المثال إنشاء واستخدام كائنات Pen. ينشئ المثال صورة جديدة ويرسم مستطيلات على سطح الصورة.

```csharp
[C#]

//أنشئ مثيلاً من BmpOptions وعيّن خصائصه المتنوعة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//المعامل المنطقي الثاني يحدد ما إذا كان الملف الذي سيُنشأ مؤقتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//أنشئ مثيلاً من Image في المسار المحدد
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //أنشئ مثيلاً من Graphics وابدأه باستخدام كائن Image
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //امسح سطح Graphics باللون الأبيض
    graphics.Clear(Aspose.Imaging.Color.White);

    //أنشئ مثيلاً من Pen باللون الأحمر وعرض 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //أنشئ مثيلاً من HatchBrush وعيّن خصائصه
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //أنشئ مثيلاً من Pen
    //ابدأه بكائن HatchBrush والعرض
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //ارسم مستطيلات بتحديد كائن Pen
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //ارسم مستطيلات بتحديد كائن Pen
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // احفظ جميع التغييرات.
    image.Save();
}
```

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


