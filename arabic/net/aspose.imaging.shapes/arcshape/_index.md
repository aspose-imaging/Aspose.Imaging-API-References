---
title: "الفئة ArcShape"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.Shapes.ArcShape الفئة. تمثل شكلاً قوسيًا"
type: docs
weight: 11540
url: /ar/net/aspose.imaging.shapes/arcshape/
---
## ArcShape class

يمثل شكل قوس.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | ينشئ نسخة جديدة من الفئة `ArcShape`. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | ينشئ نسخة جديدة من الفئة `ArcShape`. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | ينشئ نسخة جديدة من الفئة `ArcShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds/) { get; } | يحصل على حدود الكائن. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center/) { get; } | يحصل على مركز الشكل. |
| [EndPoint](../../aspose.imaging.shapes/arcshape/endpoint/) { get; } | يحصل على نقطة النهاية للشكل. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على قطاعات. |
| [IsClosed](../../aspose.imaging.shapes/arcshape/isclosed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتّب مغلقًا. عند معالجة شكل مرتّب مغلق لا يكون لنقطتي البداية والنهاية معنى. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom/) { get; } | يحصل على نقطة المستطيل اليسرى السفلية. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop/) { get; } | يحصل على نقطة المستطيل اليسرى العليا. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight/) { get; } | يحصل على ارتفاع المستطيل. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | يحصل على عرض المستطيل. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom/) { get; } | يحصل على نقطة المستطيل اليمنى السفلية. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop/) { get; } | يحصل على نقطة المستطيل اليمنى العليا. |
| override [Segments](../../aspose.imaging.shapes/arcshape/segments/) { get; } | يحصل على قطاعات الشكل. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle/) { get; set; } | يحصل أو يعيّن زاوية البدء. |
| [StartPoint](../../aspose.imaging.shapes/arcshape/startpoint/) { get; } | يحصل على نقطة البداية للشكل. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle/) { get; set; } | يحصل أو يعيّن زاوية المسح. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/arcshape/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| override [GetHashCode](../../aspose.imaging.shapes/arcshape/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [Reverse](../../aspose.imaging.shapes/arcshape/reverse/)() | يعكس ترتيب النقاط لهذا الشكل. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

## أمثلة

هذا المثال ينشئ صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures و GraphicsPath على سطح الصورة

```csharp
[C#]

//ينشئ نسخة من BmpOptions ويضبط خصائصه المتنوعة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//المعامل المنطقي الثاني يحدد ما إذا كان الملف الذي سيُنشأ مؤقتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//إنشاء مثيل من Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //إنشاء وتهيئة مثيل من فئة Graphics
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //إنشاء مثيل من فئة GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //إنشاء كائن من الفئة Figure
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    //إضافة شكل إلى كائن Figure
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //إنشاء كائن من الفئة Figure
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    //إضافة شكل إلى كائن Figure
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //رسم المسار باستخدام كائن Pen باللون الأسود
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // احفظ جميع التغييرات.
    image.Save();
}
```

### انظر أيضًا

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


