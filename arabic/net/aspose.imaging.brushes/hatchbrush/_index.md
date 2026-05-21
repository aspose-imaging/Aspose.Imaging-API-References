---
title: "الفئة HatchBrush"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Brushes.HatchBrush. تُعرّف فرشاة مستطيلة بنمط تظليل ولون أمامي ولون خلفي. لا يمكن وراثة هذه الفئة"
type: docs
weight: 140
url: /ar/net/aspose.imaging.brushes/hatchbrush/
---
## HatchBrush class

يعرف فرشاة مستطيلة مع نمط تظليل، ولون أمامي، ولون خلفية. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class HatchBrush : Brush
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HatchBrush](hatchbrush/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.brushes/hatchbrush/backgroundcolor/) { get; set; } | يحصل أو يعيّن لون الفراغات بين خطوط التظليل. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ForegroundColor](../../aspose.imaging.brushes/hatchbrush/foregroundcolor/) { get; set; } | يحصل أو يعيّن لون خطوط التظليل. |
| [HatchStyle](../../aspose.imaging.brushes/hatchbrush/hatchstyle/) { get; set; } | يحصل أو يعيّن نمط التظليل لهذه الفرشاة. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | ينشئ نسخة عميقة جديدة من [`Brush`](../../aspose.imaging/brush/) الحالي. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |

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

* class [Brush](../../aspose.imaging/brush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


