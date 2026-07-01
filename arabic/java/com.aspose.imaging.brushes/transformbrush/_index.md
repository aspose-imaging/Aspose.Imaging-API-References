---
title: "TransformBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فرشاة ذات قدرات تحويل."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

`Brush` بقدرات تحويل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | يحصل أو يعيّن تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يعيّن تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`. |
| [getTransform()](#getTransform--) | يحصل أو يعيّن نسخة من `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | يحصل أو يعيّن نسخة من `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. |
| [resetTransform()](#resetTransform--) | يعيد تعيين الخاصية `TransformBrush.Transform` إلى الهوية. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | يضرب `Aspose.Imaging.Matrix` التي تمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة عن طريق إلحاق `Aspose.Imaging.Matrix` المحددة في المقدمة. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | يضرب `Aspose.Imaging.Matrix` التي تمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة وفق الترتيب المحدد. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة وفق الترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة وفق الترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالمقدار المحدد. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفق الترتيب المحدد. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يعيّن تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`.

**Returns:**
int - `Aspose.Imaging.WrapMode` الذي يحدد كيفية تجانب التعبئات المرسومة بهذا `TransformBrush`.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يعيّن تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل أو يعيّن نسخة من `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


يحصل أو يعيّن نسخة من `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال، تعيين مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لتوفير التوافق العكسي مع GDI+.

القيمة: `True` إذا تم تغيير التحويل؛ وإلا `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد تعيين الخاصية `TransformBrush.Transform` إلى الهوية.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب `Aspose.Imaging.Matrix` التي تمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة عن طريق إلحاق `Aspose.Imaging.Matrix` المحددة في المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة `Aspose.Imaging.Matrix` التي يُستخدم لضرب التحويل الهندسي. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب `Aspose.Imaging.Matrix` التي تمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة `Aspose.Imaging.Matrix` التي يُستخدم لضرب التحويل الهندسي. |
| الترتيب | int | `Aspose.Imaging.MatrixOrder` الذي يحدد الترتيب الذي تُضرب به المصفوفتان. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة. تُضيف هذه الطريقة الترجمة إلى التحويل في المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الإزاحة في الاتجاه x. |
| dy | float | قيمة الإزاحة في الاتجاه y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الإزاحة في الاتجاه x. |
| dy | float | قيمة الإزاحة في الاتجاه y. |
| الترتيب | int | الترتيب (إضافة في البداية أو في النهاية) الذي يُطبق فيه الإزاحة. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة. تُضيف هذه الطريقة مصفوفة التوسيع إلى التحويل في المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يُوسّع به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُوسّع به التحويل في اتجاه المحور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يُوسّع به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُوسّع به التحويل في اتجاه المحور y. |
| الترتيب | int | `Aspose.Imaging.MatrixOrder` الذي يحدد ما إذا كان يجب إلحاق مصفوفة التوسيع في النهاية أو في المقدمة. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد. تُضيف هذه الطريقة الدوران إلى التحويل في المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |
| الترتيب | int | `Aspose.Imaging.MatrixOrder` الذي يحدد ما إذا كان يجب إلحاق مصفوفة الدوران في النهاية أو في المقدمة. |

