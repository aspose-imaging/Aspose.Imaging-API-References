---
title: "الفئة EllipseShape"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Shapes.EllipseShape. تمثّل شكلاً بيضاويًا."
type: docs
weight: 11570
url: /ar/net/aspose.imaging.shapes/ellipseshape/
---
## EllipseShape class

يمثل شكل بيضاوي.

```csharp
public class EllipseShape : RectangleShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | ينشئ مثيلاً جديدًا للفئة `EllipseShape`. |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | ينشئ مثيلاً جديدًا للفئة `EllipseShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds/) { get; } | يحصل على حدود الكائن. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center/) { get; } | يحصل على مركز الشكل. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على قطاعات. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom/) { get; } | يحصل على نقطة المستطيل اليسرى السفلية. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop/) { get; } | يحصل على نقطة المستطيل اليسرى العليا. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight/) { get; } | يحصل على ارتفاع المستطيل. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | يحصل على عرض المستطيل. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom/) { get; } | يحصل على نقطة المستطيل اليمنى السفلية. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop/) { get; } | يحصل على نقطة المستطيل اليمنى العليا. |
| override [Segments](../../aspose.imaging.shapes/ellipseshape/segments/) { get; } | يحصل على قطاعات الشكل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/ellipseshape/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds/)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | يحصل على حدود الكائن. |
| override [GetHashCode](../../aspose.imaging.shapes/ellipseshape/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
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

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


