---
title: ArcShape
second_title: Aspose.Imaging لمرجع NET API
description: يمثل شكل قوس .
type: docs
weight: 10950
url: /ar/aspose.imaging.shapes/arcshape/
---
## ArcShape class

يمثل شكل قوس .

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ArcShape](arcshape#constructor)() | يقوم بتهيئة مثيل جديد لملف[`ArcShape`](../arcshape) فئة . |
| [ArcShape](arcshape#constructor_1)(RectangleF, float, float) | يقوم بتهيئة مثيل جديد لملف[`ArcShape`](../arcshape) فئة . |
| [ArcShape](arcshape#constructor_2)(RectangleF, float, float, bool) | يقوم بتهيئة مثيل جديد لملف[`ArcShape`](../arcshape) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | يحصل على حدود الكائن . |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | يحصل على مركز الشكل. |
| [EndPoint](../../aspose.imaging.shapes/arcshape/endpoint) { get; } | الحصول على نقطة شكل النهاية . |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | الحصول على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [IsClosed](../../aspose.imaging.shapes/arcshape/isclosed) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة الشكل المرتب المغلق ، لا معنى لنقطتي البداية والنهاية. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | يحصل على نقطة المستطيل السفلي الأيسر . |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | يحصل على نقطة المستطيل العلوية اليسرى. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | الحصول على ارتفاع المستطيل . |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | الحصول على عرض المستطيل . |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | يحصل على نقطة المستطيل السفلية اليمنى . |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | الحصول على نقطة المستطيل العلوية اليمنى . |
| override [Segments](../../aspose.imaging.shapes/arcshape/segments) { get; } | الحصول على شرائح الشكل . |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle) { get; set; } | الحصول على زاوية البداية أو تحديدها . |
| [StartPoint](../../aspose.imaging.shapes/arcshape/startpoint) { get; } | يحصل على نقطة شكل البداية . |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle) { get; set; } | الحصول على أو تحديد زاوية المسح. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds)(Matrix) | يحصل على حدود الكائن . |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن . |
| [Reverse](../../aspose.imaging.shapes/arcshape/reverse)() | عكس ترتيب النقاط لهذا الشكل. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform)(Matrix) | يطبق التحويل المحدد على الشكل. |

### أمثلة

ينشئ هذا المثال صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures and GraphicsPath على سطح الصورة

```csharp
[C#]

// ينشئ مثيلاً لـ BmpOptions ويضبط خصائصه المختلفة            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل BmpOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان الملف المراد إنشاؤه ثابتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

// إنشاء مثيل للصورة 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // إنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // إنشاء مثيل لفئة GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    // إنشاء مثيل لفئة الشكل
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    // إضافة شكل إلى كائن الشكل
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // إنشاء مثيل لفئة الشكل
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    // إضافة شكل إلى كائن الشكل
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    // إضافة كائن الشكل إلى GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // رسم المسار باستخدام كائن القلم ذي اللون الأسود
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // احفظ جميع التغييرات.
    image.Save();
}
```

### أنظر أيضا

* class [PieShape](../pieshape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* مساحة الاسم [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
