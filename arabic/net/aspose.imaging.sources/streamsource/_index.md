---
title: "الفئة StreamSource"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.Sources.StreamSource فئة. تمثّل مصدر تدفق"
type: docs
weight: 11700
url: /ar/net/aspose.imaging.sources/streamsource/
---
## StreamSource class

يمثل مصدر تدفق.

```csharp
public sealed class StreamSource : Source
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [StreamSource](streamsource/#constructor)() | يُنشئ مثيلًا جديدًا من الفئة `StreamSource`. |
| [StreamSource](streamsource/#constructor_1)(Stream) | يُنشئ مثيلًا جديدًا من الفئة `StreamSource`. |
| [StreamSource](streamsource/#constructor_2)(Stream, bool) | يُنشئ مثيلًا جديدًا من الفئة `StreamSource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisposeStream](../../aspose.imaging.sources/streamsource/disposestream/) { get; } | يحصل على قيمة تشير إلى ما إذا كان يجب تحرير الـ stream كلما تم تحرير الـ container. |
| [Stream](../../aspose.imaging.sources/streamsource/stream/) { get; } | يحصل على الـ stream. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetStreamContainer](../../aspose.imaging.sources/streamsource/getstreamcontainer/)() | يحصل على حاوية الدفق. |

## أمثلة

يوضح هذا المثال استخدام System.IO.Stream لإنشاء ملف صورة جديد (نوع JPEG).

```csharp
[C#]

//ينشئ مثيلًا من JpegOptions ويضبط خصائصه المتنوعة.
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//إنشاء مثيل من System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//حدد خاصية المصدر للمثيل من JpegOptions.
//المعامل المنطقي الثاني يحدد ما إذا كان سيتم التخلص من الـ Stream بمجرد الخروج من النطاق.
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//ينشئ مثيلًا من Image ويستدعي طريقة Create مع JpegOptions كمعامل لتهيئة كائن Image.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.
}
```

يستخدم هذا المثال فئة Graphics لإنشاء أشكال أولية على سطح Image. لتوضيح العملية، ينشئ المثال صورة جديدة بصيغة PNG ويرسم أشكالًا أولية على سطح Image باستخدام طرق Draw التي توفرها فئة Graphics.

```csharp
[C#]

//ينشئ مثيلًا من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //إنشاء مثيل من PngOptions وتعيين خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //تعيين المصدر لـ PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //إنشاء وتهيئة مثيل من فئة Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //مسح سطح Graphics
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //رسم قوس بتحديد كائن Pen الذي له اللون الأسود،
        //مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //رسم منحنى بيزيير بتحديد كائن Pen الذي له اللون الأزرق ونقاط الإحداثيات.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //رسم منحنى بتحديد كائن Pen الذي له اللون الأخضر ومصفوفة من النقاط
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //رسم إهليلج باستخدام كائن Pen ومستطيل محيط
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //رسم خط
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //رسم قطعة فطيرة
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //رسم مضلع بتحديد كائن Pen الذي له اللون الأحمر ومصفوفة من النقاط
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //رسم مستطيل
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //إنشاء كائن SolidBrush وتعيين خصائصه المتنوعة
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //رسم نص باستخدام كائن SolidBrush والخط، عند نقطة محددة
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### انظر أيضًا

* class [Source](../../aspose.imaging/source/)
* namespace [Aspose.Imaging.Sources](../../aspose.imaging.sources/)
* assembly [Aspose.Imaging](../../)


