---
title: "الفئة EmfRecorderGraphics2D"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D. رسومات مسجل Emf"
type: docs
weight: 6610
url: /ar/net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
## EmfRecorderGraphics2D class

رسومات مسجل Emf

```csharp
public sealed class EmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfRecorderGraphics2D](emfrecordergraphics2d/)(Rectangle, Size, Size) | ينشئ مثيلاً جديداً للفئة `EmfRecorderGraphics2D`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor/) { get; set; } | تحصل أو تعين لون الخلفية. |
| [BackgroundMode](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/backgroundmode/) { get; set; } | تحصل أو تعين وضع الخلفية. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip/) { get; set; } | تحصل أو تعين Region التي تحد من منطقة الرسم لهذه Graphics |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds/) { get; } | تحصل على حدود القص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromEmfImage](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage/)(EmfImage) | يحصل على مثيل من `EmfRecorderGraphics2D` يحتوي على جميع السجلات من صورة Emf. |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear/)() | يمسح حالة كائن الرسومات |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc/)(Pen, Rectangle, float, float) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier/)(Pen, Point, Point, Point, Point) | يرسم المنحنى المكعب Bezier. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse/)(Pen, Rectangle) | يرسم الإهليلج. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(RasterImage, Point) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(byte[], Rectangle, GraphicsUnit) | يرسم الصورة. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(Stream, Rectangle, GraphicsUnit) | يرسم الصورة. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline/)(Pen, Point, Point) | يرسم الخط. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline/)(Pen, int, int, int, int) | يرسم الخط. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath/)(Pen, GraphicsPath) | يرسم المسار. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie/)(Pen, Rectangle, float, float) | يرسم الفطيرة. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier/)(Pen, Point[]) | يرسم بيزيه متعدد المكعبات. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon/)(Pen, Point[]) | يرسم المضلع. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline/)(Pen, Point[]) | يرسم الخط المتعدد. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle/)(Pen, Rectangle) | يرسم المستطيل. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle/)(Pen, int, int, int, int) | يرسم المستطيل. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring/)(string, Font, Color, int, int) | يرسم النص. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring/)(string, Font, Color, int, int, float) | يرسم النص. |
| [EndRecording](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/endrecording/)() | ينهي التسجيل. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip/)(Rectangle) | يقوم بتحديث منطقة القص لهذا Graphics لاستبعاد المنطقة المحددة بواسطة بنية المستطيل. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip/)(Region) | يقوم بتحديث منطقة القص لهذا Graphics لاستبعاد المنطقة المحددة بواسطة Region. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse/)(Brush, Rectangle) | يملأ القطع الناقص. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath/)(Pen, Brush, GraphicsPath) | يملأ المسار. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie/)(Brush, Rectangle, float, float) | يملأ الفطيرة. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon/)(Brush, Point[]) | يملأ المضلع. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon/)(Brush, Point[], FillMode) | يملأ المضلع. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle/)(Brush, Rectangle) | يملأ المستطيل. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform/)() | يحصل على تحويل العالم. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip/)(RectangleF) | يقوم بتحديث منطقة القص لهذا Graphics إلى تقاطع منطقة القص الحالية والمنطقة المحددة بواسطة بنية المستطيل. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip/)(Region) | يقوم بتحديث منطقة القص لهذا Graphics إلى تقاطع منطقة القص الحالية والمنطقة المحددة بواسطة Region. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform/)(Matrix) | يضرب تحويل العالم لهذا Graphics بالمصفوفة المحددة. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform/)(Matrix, MatrixOrder) | يضرب تحويل العالم لهذا Graphics بالمصفوفة المحددة بالترتيب المحدد. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip/)() | يعيد تعيين القص. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform/)(float) | يطبق الدوران المحدد على مصفوفة التحويل لهذا Graphics. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform/)(float, PointF, MatrixOrder) | يطبق الدوران المحدد على مصفوفة التحويل لهذا Graphics بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform/)(float, float) | يطبق عملية التحجيم المحددة على مصفوفة التحويل لهذا Graphics عن طريق إضافتها إلى مقدمة مصفوفة التحويل الخاصة بالكائن. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform/)(float, float, MatrixOrder) | يطبق عملية التحجيم المحددة على مصفوفة التحويل لهذا Graphics بالترتيب المحدد. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform/)(Matrix) | يضبط التحويل. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform/)(float, float) | يغيّر أصل نظام الإحداثيات عن طريق إضافة الترجمة المحددة إلى مقدمة مصفوفة التحويل لهذا Graphics. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform/)(float, float, MatrixOrder) | يغيّر أصل نظام الإحداثيات عن طريق تطبيق الترجمة المحددة على مصفوفة التحويل لهذا Graphics بالترتيب المحدد. |

### انظر أيضًا

* class [MetafileRecorderGraphics2D](../metafilerecordergraphics2d/)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics/)
* assembly [Aspose.Imaging](../../)


