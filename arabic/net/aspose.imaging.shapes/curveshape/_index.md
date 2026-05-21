---
title: "الفئة CurveShape"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Shapes.CurveShape. تمثّل شكلاً منحنياً."
type: docs
weight: 11560
url: /ar/net/aspose.imaging.shapes/curveshape/
---
## CurveShape class

يمثل شكل منحنى منحنٍ.

```csharp
public sealed class CurveShape : PolygonShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | ينشئ مثيلاً جديدًا للفئة `CurveShape`. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | ينشئ مثيلاً جديدًا للفئة `CurveShape`. يتم استخدام الشد الافتراضي بقيمة 0.5. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | ينشئ مثيلاً جديدًا للفئة `CurveShape`. يتم استخدام الشد الافتراضي بقيمة 0.5. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | ينشئ مثيلاً جديدًا للفئة `CurveShape`. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | ينشئ مثيلاً جديدًا للفئة `CurveShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/curveshape/bounds/) { get; } | يحصل على حدود الكائن. |
| override [Center](../../aspose.imaging.shapes/curveshape/center/) { get; } | يحصل على مركز الشكل. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint/) { get; } | يحصل على نقطة النهاية للشكل. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على قطاعات. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| [Points](../../aspose.imaging.shapes/polygonshape/points/) { get; set; } | يحصل أو يعيّن نقاط المنحنى. |
| override [Segments](../../aspose.imaging.shapes/curveshape/segments/) { get; } | يحصل على قطاعات الشكل. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint/) { get; } | يحصل على نقطة البداية للشكل. |
| [Tension](../../aspose.imaging.shapes/curveshape/tension/) { get; set; } | يحصل أو يعيّن شد المنحنى. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/curveshape/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| override [GetHashCode](../../aspose.imaging.shapes/curveshape/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse/)() | يعكس ترتيب النقاط لهذا الشكل. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

### انظر أيضًا

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


