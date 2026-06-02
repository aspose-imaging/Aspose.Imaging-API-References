---
title: "PathGradientBrushBase"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل فرشاة ذات وظيفة تدرج مسار أساسي."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

يمثل `Brush` بوظيفة تدرج مسار أساسي.

لاحظ أنه عند إنشاء الفئة `PathGradientBrushBase` يجب تهيئتها بما لا يقل عن نقطتين. المسار الداخلي المُنشأ سيكون دائمًا شكلًا مغلقًا، حيث تربط النقطة الأخيرة النقطة الأولى. يُملأ ذلك الشكل باستخدام هذا `PathGradientBrushBase`. تنفّذ GDI+ استثناء `OutOfMemoryError` عند تمرير مصفوفات فارغة أو مجموعة نقاط ذات إحداثيات متماثلة. ترمي الفئة `PathGradientBrushBase` استثناءً عندما تحتوي مصفوفة النقاط على أقل من نقطتين، ويتم إلقاء `ArgumentException` بدلاً من `OutOfMemoryError` عندما تكون مصفوفة النقاط غير مقبولة. يُحسب نقطة المركز كقُرص مركز للنتائج الممررة افتراضيًا. يمكن للمستخدم تغيير هذه النقطة لاحقًا. مقاييس التركيز هي نقطة فارغة (0.0, 0.0) افتراضيًا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة. |
| [getGraphicsPath()](#getGraphicsPath--) | يحصل على مسار الرسومات الذي بُنيت عليه هذه الفرشاة. |
| [getCenterPoint()](#getCenterPoint--) | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [getFocusScales()](#getFocusScales--) | يحصل على نقطة التركيز لتلاشي التدرج. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | يحصل أو يضبط نقطة التركيز لتلاشي التدرج. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة.

**Returns:**
com.aspose.imaging.PointF[] - نقاط المسار.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


يحصل على مسار الرسومات الذي بُنيت عليه هذه الفرشاة.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


يحصل أو يضبط نقطة المركز لتدرج المسار.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


يحصل أو يضبط نقطة المركز لتدرج المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | `Aspose.Imaging.PointF` يحدد نقطة المركز لتدرج المسار. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


يحصل على نقطة التركيز لتلاشي التدرج.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


يحصل أو يضبط نقطة التركيز لتلاشي التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | كائن `Aspose.Imaging.PointF` يمثل نقطة التركيز لتلاشي التدرج. |

