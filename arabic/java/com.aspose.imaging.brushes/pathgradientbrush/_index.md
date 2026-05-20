---
title: "PathGradientBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على كائن Aspose.Imaging.Brush مع تدرج."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

يحتوي على كائن `Aspose.Imaging.Brush` مع تدرج. لا يمكن وراثة هذه الفئة.

لون المركز أبيض بشكل افتراضي. يمكن للمستخدم تغيير هذه القيمة في أي وقت لاحق.

يتم تهيئة مصفوفة ألوان المحيط بعنصر واحد يحتوي على اللون الأبيض بشكل افتراضي. قد يتم تغيير ألوان المحيط لاحقًا، ومع ذلك يلزم وجود عنصر واحد على الأقل عند إعداد ألوان المحيط.

انظر إلى `Blend` لمزيد من التفاصيل حول تهيئتها.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالمسار المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | يحصل على `com.aspose.imaging.ColorBlend` الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | يضبط `com.aspose.imaging.ColorBlend` الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [getCenterColor()](#getCenterColor--) | يحصل على اللون في مركز تدرج المسار. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | يضبط اللون في مركز تدرج المسار. |
| [getSurroundColors()](#getSurroundColors--) | يحصل على مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا `PathGradientBrush`. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | يضبط مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا `PathGradientBrush`. |
| [getBlend()](#getBlend--) | يحصل على `Aspose.Imaging.Blend` يحدد المواضع والعوامل التي تعرف انخفاضًا مخصصًا للمتدرج. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | يضبط `Aspose.Imaging.Blend` يحدد المواضع والعوامل التي تعرف انخفاضًا مخصصًا للمتدرج. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدوده الخارجية. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدوده الخارجية. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | ينشئ تدرجًا بلون مركزي وتناقص خطي إلى لون محيط واحد. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | ينشئ تدرجًا بلون مركزي وتناقص خطي إلى كل لون محيط. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة من هياكل `Aspose.Imaging.PointF` التي تمثل النقاط التي تشكل رؤوس المسار. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة من هياكل `Aspose.Imaging.PointF` التي تمثل النقاط التي تشكل رؤوس المسار. |
| wrapMode | int | `Aspose.Imaging.WrapMode` هو وضع يحدد كيفية تجانب التعبئات المرسومة باستخدام هذا `PathGradientBrush`. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | مصفوفة من هياكل `Aspose.Imaging.Point` التي تمثل النقاط التي تشكل رؤوس المسار. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | مصفوفة من هياكل `Aspose.Imaging.Point` التي تمثل النقاط التي تشكل رؤوس المسار. |
| wrapMode | int | `Aspose.Imaging.WrapMode` هو وضع يحدد كيفية تجانب التعبئات المرسومة باستخدام هذا `PathGradientBrush`. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


يُنشئ نسخة جديدة من فئة `PathGradientBrush` بالمسار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` الذي يحدد المنطقة التي يملأها هذا `PathGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


يحصل على `com.aspose.imaging.ColorBlend` الذي يحدد تدرجًا خطيًا متعدد الألوان.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


يضبط `com.aspose.imaging.ColorBlend` الذي يحدد تدرجًا خطيًا متعدد الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | `com.aspose.imaging.ColorBlend` يحدد تدرجًا خطيًا متعدد الألوان. |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


يحصل على اللون في مركز تدرج المسار.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


يضبط اللون في مركز تدرج المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | `com.aspose.imaging.Color` الذي يمثل اللون في مركز تدرج المسار. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


يحصل على مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا `PathGradientBrush`.

**Returns:**
com.aspose.imaging.Color[] - مصفوفة من هياكل `com.aspose.imaging.Color` التي تمثل الألوان المرتبطة بكل نقطة في المسار الذي يملأه هذا `PathGradientBrush`.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


يضبط مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا `PathGradientBrush`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | مصفوفة من هياكل `com.aspose.imaging.Color` التي تمثل الألوان المرتبطة بكل نقطة في المسار الذي يملأه هذا `PathGradientBrush`. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


يحصل على `Aspose.Imaging.Blend` يحدد المواضع والعوامل التي تعرف انخفاضًا مخصصًا للمتدرج.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


يضبط `Aspose.Imaging.Blend` يحدد المواضع والعوامل التي تعرف انخفاضًا مخصصًا للمتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | `Aspose.Imaging.Blend` الذي يمثل انخفاضًا مخصصًا للتدرج. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدوده الخارجية. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدوده الخارجية. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |
| المقياس | float | قيمة تتراوح بين 0 و 1 تحدد أقصى شدة للون المركز الذي يختلط مع لون الحد. القيمة 1 تسبب أعلى شدة ممكنة للون المركز، وهي القيمة الافتراضية. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


ينشئ تدرجًا بلون مركزي وتناقص خطي إلى لون محيط واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


ينشئ تدرجًا بلون مركزي وتناقص خطي إلى كل لون محيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |
| المقياس | float | قيمة تتراوح بين 0 و 1 تحدد أقصى شدة للون المركز الذي يختلط مع لون الحد. القيمة 1 تسبب أعلى شدة ممكنة للون المركز، وهي القيمة الافتراضية. |

