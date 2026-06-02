---
title: "Pen.Pen"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ Pen. يهيئ نسخة جديدة من فئة Pen باللون المحدد"
type: docs
weight: 10
url: /ar/net/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

يهيئ نسخة جديدة من فئة [`Pen`](../) باللون المحدد.

```csharp
public Pen(Color color)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| color | Color | هيكل [`Color`](../color/) يحدد لون هذا [`Pen`](../). |

### انظر أيضًا

* struct [Color](../../color/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

يُنشئ مثيلاً جديدًا لفئة [`Pen`](../) بالخصائص المحددة [`Color`](../color/) و[`Width`](../width/).

```csharp
public Pen(Color color, float width)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| color | Color | هيكل [`Color`](../color/) يحدد لون هذا [`Pen`](../). |
| width | Single | قيمة تشير إلى عرض هذا [`Pen`](../). |

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

* struct [Color](../../color/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

يُنشئ مثيلاً جديدًا لفئة [`Pen`](../) بالـ[`Brush`](../brush/) المحدد.

```csharp
public Pen(Brush brush)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../brush/) يحدد خصائص التعبئة لهذا [`Pen`](../). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

يُنشئ مثيلاً جديدًا لفئة [`Pen`](../) بالـ[`Brush`](../brush/) و[`Width`](../width/) المحددين.

```csharp
public Pen(Brush brush, float width)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../brush/) يحدد خصائص هذا [`Pen`](../). |
| width | Single | عرض الـ[`Pen`](../) الجديد. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)


