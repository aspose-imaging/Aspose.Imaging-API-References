---
title: "LinearGradientBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يغلف Aspose.Imaging.Brush بخط متدرج خطي."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

يغلف `Aspose.Imaging.Brush` بخط متدرج خطي. لا يمكن توريث هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush()](#LinearGradientBrush--) | ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) باستخدام المعلمات الافتراضية. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | يحصل على `com.aspose.imaging.ColorBlend` الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | يضبط `com.aspose.imaging.ColorBlend` الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [getLinearColors()](#getLinearColors--) | يحصل على ألوان البداية والنهاية للمتدرج. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | يضبط ألوان البداية والنهاية للمتدرج. |
| [getStartColor()](#getStartColor--) | يحصل على لون البداية للمتدرج. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | يضبط لون البداية للمتدرج. |
| [getEndColor()](#getEndColor--) | يحصل على لون النهاية للمتدرج. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | يضبط لون النهاية للمتدرج. |
| [getBlend()](#getBlend--) | يحصل على `Aspose.Imaging.Blend` يحدد المواضع والعوامل التي تعرف انخفاضًا مخصصًا للمتدرج. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | يضبط `Aspose.Imaging.Blend` يحدد المواضع والعوامل التي تعرف انخفاضًا مخصصًا للمتدرج. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | ينشئ انخفاضًا للمتدرج يعتمد على منحنى على شكل جرس. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | ينشئ انخفاضًا للمتدرج يعتمد على منحنى على شكل جرس. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | ينشئ متدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | ينشئ متدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل. |
| color1 | [Color](../../com.aspose.imaging/color) | اللون1. |
| color2 | [Color](../../com.aspose.imaging/color) | اللون2. |
| angle | float | الزاوية. |
| isAngleScalable | boolean | إذا تم تعيينه إلى `true` [قابل لتوسيع الزاوية]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| color1 | [Color](../../com.aspose.imaging/color) | اللون1. |
| color2 | [Color](../../com.aspose.imaging/color) | اللون2. |
| angle | float | الزاوية. |
| isAngleScalable | boolean | إذا تم تعيينه إلى `true` [قابل لتوسيع الزاوية]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل. |
| color1 | [Color](../../com.aspose.imaging/color) | اللون1. |
| color2 | [Color](../../com.aspose.imaging/color) | اللون2. |
| angle | float | الزاوية. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| color1 | [Color](../../com.aspose.imaging/color) | اللون1. |
| color2 | [Color](../../com.aspose.imaging/color) | اللون2. |
| angle | float | الزاوية. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | النقطة1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | النقطة2. |
| color1 | [Color](../../com.aspose.imaging/color) | اللون1. |
| color2 | [Color](../../com.aspose.imaging/color) | اللون2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | النقطة1. |
| point2 | [Point](../../com.aspose.imaging/point) | النقطة2. |
| color1 | [Color](../../com.aspose.imaging/color) | اللون1. |
| color2 | [Color](../../com.aspose.imaging/color) | اللون2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


ينشئ مثيلاً جديداً للفئة [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) باستخدام المعلمات الافتراضية. اللون الابتدائي هو الأسود، اللون النهائي هو الأبيض، الزاوية 45 درجة والمستطيل يقع في (0,0) بحجم (1,1).

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

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


يحصل على ألوان البداية والنهاية للمتدرج.

**Returns:**
com.aspose.imaging.Color[] - مصفوفة من هيكليتين `Color` تمثل ألوان البداية والنهاية للمتدرج.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


يضبط ألوان البداية والنهاية للمتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | مصفوفة من هيكليتين `Color` تمثل ألوان البداية والنهاية للمتدرج. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


يحصل على لون البداية للمتدرج.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


يضبط لون البداية للمتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون البداية للمتدرج. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


يحصل على لون النهاية للمتدرج.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


يضبط لون النهاية للمتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون النهاية للمتدرج. |

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


ينشئ انخفاضًا للمتدرج يعتمد على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتم فيها خلط اللون الابتدائي واللون النهائي بالتساوي). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


ينشئ انخفاضًا للمتدرج يعتمد على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| المقياس | float | قيمة من 0 إلى 1 تحدد مدى سرعة انخفاض الألوان من `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


ينشئ متدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


ينشئ متدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التركيز | float | قيمة من 0 إلى 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| المقياس | float | قيمة من 0 إلى 1 تحدد مدى سرعة انخفاض الألوان من اللون الابتدائي إلى `focus` (اللون النهائي). |

