---
title: EmfRecorderGraphics2D
second_title: Aspose.Imaging لمرجع NET API
description: رسومات مسجل Emf
type: docs
weight: 6490
url: /ar/net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
## EmfRecorderGraphics2D class

رسومات مسجل Emf

```csharp
public sealed class EmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfRecorderGraphics2D](emfrecordergraphics2d)(Rectangle, Size, Size) | يقوم بتهيئة مثيل جديد لملف[`EmfRecorderGraphics2D`](../emfrecordergraphics2d) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | الحصول على لون الخلفية أو تعيينه . |
| [BackgroundMode](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/backgroundmode) { get; set; } | الحصول على أو تعيين وضع الخلفية . |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | الحصول على أو تعيين منطقة تحدد منطقة الرسم لهذه Graphics |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | ربط المقطع. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromEmfImage](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage)(EmfImage) | يحصل على مثيل لملف[`EmfRecorderGraphics2D`](../emfrecordergraphics2d) تحتوي على جميع السجلات من صورة Emf. |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | مسح حالة الكائن الرسومي |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة بنية مستطيل. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | رسم البيزير المكعب . |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | يرسم القطع الناقص . |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Point) | رسم الصورة المحددة ، باستخدام حجمها المادي الأصلي ، في المكان المحدد. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(byte[], Rectangle, GraphicsUnit) | يرسم الصورة . |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(Stream, Rectangle, GraphicsUnit) | يرسم الصورة . |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | رسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, Point, Point) | يرسم الخط . |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, int, int, int, int) | يرسم الخط . |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | يرسم المسار . |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | يرسم الكعكة . |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | يرسم بيزير مكعب بولي . |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | يرسم المضلع . |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | يرسم الشكل متعدد الخطوط . |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, Rectangle) | يرسم المستطيل . |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, int, int, int, int) | يرسم المستطيل . |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int) | يرسم السلسلة . |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int, float) | يرسم السلسلة . |
| [EndRecording](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/endrecording)() | إنهاء التسجيل . |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Rectangle) | يحدّث منطقة القصاصة في هذه الرسومات لاستبعاد المنطقة المحددة بواسطة بنية المستطيل. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Region) | يحدّث منطقة المقطع لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة المنطقة. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | يملأ القطع الناقص . |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | يملأ المسار . |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | يملأ الكعكة . |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[]) | يملأ المضلع . |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[], FillMode) | يملأ المضلع . |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | يملأ المستطيل . |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | يجعل العالم يتحول. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(RectangleF) | يحدّث منطقة القصاصة في هذه الرسومات لتقاطع منطقة المقطع الحالية وهيكل المستطيل المحدد. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(Region) | يحدّث منطقة القصاصة لهذه الرسومات لتقاطع منطقة المقطع الحالية والمنطقة المحددة. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix) | يضاعف التحول العالمي لهذه الرسومات ويحدد المصفوفة. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix, MatrixOrder) | يضاعف التحول العالمي لهذه الرسومات ويحدد المصفوفة بالترتيب المحدد. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | يعيد ضبط المقطع. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float) | يطبق الاستدارة المحددة على مصفوفة التحويل لهذه الرسومات. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float, PointF, MatrixOrder) | يطبق الاستدارة المحددة على مصفوفة التحويل لهذه الرسومات بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float) | يطبق عملية التحجيم المحددة على مصفوفة التحويل لهذه الرسومات عن طريق إضافتها إلى مصفوفة تحويل الكائن. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float, MatrixOrder) | يطبق عملية القياس المحددة على مصفوفة التحويل لهذه الرسومات بالترتيب المحدد . |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | يضبط التحويل. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float) | يغير أصل النظام الإحداثي عن طريق إضافة الترجمة المحددة مسبقًا إلى مصفوفة التحويل لهذه الرسومات. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float, MatrixOrder) | يغير أصل النظام الإحداثي عن طريق تطبيق الترجمة المحددة على مصفوفة التحويل لهذه الرسومات بالترتيب المحدد. |

### أنظر أيضا

* class [MetafileRecorderGraphics2D](../metafilerecordergraphics2d)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
