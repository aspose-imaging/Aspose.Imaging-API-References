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
| [getWrapMode()](#getWrapMode--) | يحصل أو يضبط تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يضبط تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`. |
| [getTransform()](#getTransform--) | يحصل أو يضبط نسخة `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | يحصل أو يضبط نسخة `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. |
| [resetTransform()](#resetTransform--) | يعيد تعيين الخاصية `TransformBrush.Transform` إلى الهوية. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | يضرب `Aspose.Imaging.Matrix` الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة عن طريق إلحاق المصفوفة `Aspose.Imaging.Matrix` المحددة في البداية. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | يضرب `Aspose.Imaging.Matrix` الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة بالترتيب المحدد. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالمقدار المحدد. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يضبط تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`.

**Returns:**
int - `Aspose.Imaging.WrapMode` يحدد كيفية تكرار التعبئات المرسومة باستخدام هذا `TransformBrush`.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يضبط تعداد `Aspose.Imaging.WrapMode` الذي يشير إلى وضع الالتفاف لهذا `TransformBrush`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل أو يضبط نسخة `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


يحصل أو يضبط نسخة `Aspose.Imaging.Matrix` التي تحدد تحويلًا هندسيًا محليًا لهذا `TransformBrush`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+.

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


يضرب `Aspose.Imaging.Matrix` الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة عن طريق إلحاق المصفوفة `Aspose.Imaging.Matrix` المحددة في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `Aspose.Imaging.Matrix` التي يتم ضرب التحويل الهندسي بها. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب `Aspose.Imaging.Matrix` الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة `Aspose.Imaging.Matrix` المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `Aspose.Imaging.Matrix` التي يتم ضرب التحويل الهندسي بها. |
| order | int | `Aspose.Imaging.MatrixOrder` يحدد ترتيب ضرب المصفوفتين. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في الاتجاه x. |
| dy | float | قيمة الترجمة في الاتجاه y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في الاتجاه x. |
| dy | float | قيمة الترجمة في الاتجاه y. |
| order | int | الترتيب (prepend أو append) الذي تُطبق فيه الترجمة. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور y. |
| order | int | `Aspose.Imaging.MatrixOrder` يحدد ما إذا كان سيتم إلحاق أو سابقة مصفوفة التكبير. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |
| order | int | `Aspose.Imaging.MatrixOrder` يحدد ما إذا كان سيتم إلحاق أو سابقة مصفوفة الدوران. |

