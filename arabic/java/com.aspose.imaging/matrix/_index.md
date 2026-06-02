---
title: "Matrix"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يستبدل مصفوفة GDI."
type: docs
weight: 72
url: /ar/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

يستبدل مصفوفة GDI+.

--------------------

معظم الخوارزميات مأخوذة من AffineTransform.java الخاص بـ Sun. أسماء Java لعناصر المصفوفة المستخدمة داخليًا. خريطة أسماء Java إلى .net مع الوصف: m00 M11 مقياس X m10 M12 قص Y m01 M21 قص X m11 M22 مقياس Y m02 M31 ترجمة X m12 M32 ترجمة Y
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Matrix()](#Matrix--) | ينشئ مثيلاً جديدًا من فئة Matrix كمصفوفة هوية. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | ينشئ مثيلاً جديدًا من فئة [Matrix](../../com.aspose.imaging/matrix). |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | ينشئ مثيلاً جديدًا من فئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | ينشئ مثيلاً جديدًا من فئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | ينشئ نسخة من فئة [Matrix](../../com.aspose.imaging/matrix). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | التحويل الهوية هو ذلك الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | الترجمة تنقل الإحداثيات بمقدار ثابت في x و y دون تغيير طول أو زاوية المتجهات. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | المقياس المتساوي يضاعف طول المتجهات بنفس المقدار في اتجاهي x و y دون تغيير الزاوية بين المتجهات. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | يقوم مقياس عام بضرب طول المتجهات بمقادير مختلفة في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | هذا الثابت هو قناع بت لأي من بتات علم المقياس. |
| [TYPE_FLIP](#TYPE-FLIP) | هذا بت العلم يشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بعكس صورة مرآة حول محور ما، مما يغيّر نظام الإحداثيات عادةً الأيمن إلى نظام إحداثيات أيسر، بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | هذا بت العلم يشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران ربعي بضعف من 90 درجة، بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | هذا بت العلم يشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران بزاوية عشوائية، بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | هذا الثابت هو قناع بت لأي من بتات علم الدوران. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | هذا الثابت يشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بتحويل عشوائي لإحداثيات الإدخال. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | يحدد ما إذا كان مصفوفتان متساويتان. |
| [getM11()](#getM11--) | يحصل على عنصر المصفوفة في الصف الأول والعمود الأول. |
| [getM12()](#getM12--) | يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. |
| [getM21()](#getM21--) | يحصل على عنصر المصفوفة في الصف الثاني والعمود الأول. |
| [getM22()](#getM22--) | يحصل على عنصر المصفوفة في الصف الثاني والعمود الثاني. |
| [getM31()](#getM31--) | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. |
| [getM32()](#getM32--) | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. |
| [toString()](#toString--) | يعيد سلسلة تمثل هذه الحالة. |
| [getElements()](#getElements--) | يحصل على نسخة من عناصر المصفوفة. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | يطبق التحويل الهندسي الممثّل بواسطة هذا [Matrix](../../com.aspose.imaging/matrix) على مصفوفة محددة من النقاط. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا [Matrix](../../com.aspose.imaging/matrix) باستخدام الترتيب المحدد. |
| [scale(float sx, float sy)](#scale-float-float-) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا Matrix باستخدام ترتيب Prepend (الافتراضي). |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | يطبق متجه الإزاحة المحدد على هذا Matrix بالترتيب المحدد. |
| [translate(float tx, float ty)](#translate-float-float-) | يطبق متجه الإزاحة المحدد على هذا [Matrix](../../com.aspose.imaging/matrix) باستخدام ترتيب Prepend (الافتراضي). |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix باستخدام ترتيب Prepend (الافتراضي). |
| [rotate(float angle, int order)](#rotate-float-int-) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بالترتيب المحدد. |
| [rotate(float angle)](#rotate-float-) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بترتيب Prepend (الافتراضي). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بالترتيب المحدد. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بترتيب Prepend (الافتراضي). |
| [reset()](#reset--) | يعيد تعيين هذه المصفوفة لتحتوي على عناصر مصفوفة الوحدة. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة. |
| [isIdentity()](#isIdentity--) | يعيد `true` إذا كان الـ `AffineTransform` هذا تحويل هوية. |
### Matrix() {#Matrix--}
```
public Matrix()
```


ينشئ مثيلاً جديدًا من فئة Matrix كمصفوفة هوية.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


ينشئ مثيلاً جديدًا من فئة [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m11 | float | m00 M11 مقياس X |
| m12 | float | m10 M12 قص Y |
| m21 | float | m01 M21 قص X |
| m22 | float | m11 M22 مقياس Y |
| m31 | float | m02 M31 ترجمة X |
| m32 | float | m12 M32 ترجمة Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


ينشئ مثيلاً جديدًا من فئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل [RectangleF](../../com.aspose.imaging/rectanglef) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة مكوّنة من ثلاث هياكل [PointF](../../com.aspose.imaging/pointf) تمثل نقاط متوازي أضلاع التي سيتم تحويل الزوايا العليا اليسرى، العليا اليمنى، والسفلى اليسرى للمستطيل إليها. الزاوية السفلى اليمنى للمتوازي أضلاع تُستنتج من الزوايا الثلاث الأولى. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


ينشئ مثيلاً جديدًا من فئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل [Rectangle](../../com.aspose.imaging/rectangle) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | مصفوفة مكوّنة من ثلاث هياكل [Point](../../com.aspose.imaging/point) تمثل نقاط متوازي أضلاع التي سيتم تحويل الزوايا العليا اليسرى، العليا اليمنى، والسفلى اليسرى للمستطيل إليها. الزاوية السفلى اليمنى للمتوازي أضلاع تُستنتج من الزوايا الثلاث الأولى. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


ينشئ نسخة من فئة [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | مصفوفة أساسية للنسخ |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


تحويل الهوية هو التحويل الذي تكون فيه إحداثيات الإخراج دائمًا هي نفسها إحداثيات الإدخال. إذا كان هذا التحويل غير تحويل هوية، فسيكون النوع إما الثابت GENERAL\\_TRANSFORM أو مزيجًا من بتات العلامة المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بهذا التحويل بأدائها.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


الترجمة تنقل الإحداثيات بمقدار ثابت في x و y دون تغيير طول أو زاوية المتجهات.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


المقياس المتساوي يضاعف طول المتجهات بنفس المقدار في اتجاهي x و y دون تغيير الزاوية بين المتجهات. هذه البتة العلامية متعارضة مع علم TypeGeneralScale.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


المقياس العام يضاعف طول المتجهات بمقادير مختلفة في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة. هذه البتة العلامية متعارضة مع علم TypeUniformScale.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


هذا الثابت هو قناع بت لأي من بتات علم المقياس.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


تشير هذه البتة العلامية إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بعكس صورة مرآة حول محور ما، مما يغيّر نظام الإحداثيات الأيمن إلى نظام إحداثيات أيسر بالإضافة إلى التحويلات المشار إليها ببتات العلامة الأخرى. نظام إحداثيات أيمن هو الذي يدور فيه المحور X الموجب عكس اتجاه عقارب الساعة ليصطف مع المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليمنى عندما تنظر إلى إبهامك من الطرف. نظام إحداثيات أيسر هو الذي يدور فيه المحور X الموجب مع اتجاه عقارب الساعة ليصطف مع المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليسرى. لا توجد طريقة رياضية لتحديد زاوية التحويل الأصلي للانعكاس أو المرآة لأن جميع زوايا الانعكاس متطابقة عند تطبيق دوران تعديل مناسب. ملاحظة: تم إضافة TypeFlip بعد أن كان GENERAL\\_TRANSFORM متداولًا علنًا ولم يعد من الممكن إعادة ترقيم بتات العلامة بسهولة دون إحداث عدم توافق ثنائي في الشيفرة الخارجية.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


تشير هذه البتة العلامية إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران ربعي بمضاعفات 90 درجة بالإضافة إلى التحويلات المشار إليها ببتات العلامة الأخرى. الدوران يغيّر زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذه البتة العلامية متعارضة مع علم TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران بزاوية عشوائية بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى. يغيّر الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذه البتة flag متعارضة مع الـ

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


هذا الثابت هو قناع بت لأي من بتات علم الدوران.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


تشير هذه الثابت إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بتحويل عشوائي لإحداثيات الإدخال. إذا كان يمكن تصنيف هذا التحويل بأي من الثوابت أعلاه، فسيكون النوع إما الثابت TypeIdentity أو مزيجًا من بتات flag المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بها هذا التحويل.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


يحدد ما إذا كان مصفوفتان متساويتان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة الأولى للمقارنة. |
| b | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة الثانية للمقارنة. |

**Returns:**
boolean - True إذا كانت المصفوفات متساوية.
### getM11() {#getM11--}
```
public final float getM11()
```


يحصل على عنصر المصفوفة في الصف الأول العمود الأول. يمثل المقياس على المحور X.

**Returns:**
float - عنصر المصفوفة في الصف الأول العمود الأول.
### getM12() {#getM12--}
```
public final float getM12()
```


يحصل على عنصر المصفوفة في الصف الأول العمود الثاني. يمثل القص على المحور Y.

**Returns:**
float - عنصر المصفوفة في الصف الأول العمود الثاني.
### getM21() {#getM21--}
```
public final float getM21()
```


يحصل على عنصر المصفوفة في الصف الثاني العمود الأول. يمثل القص على المحور X.

**Returns:**
float - عنصر المصفوفة في الصف الثاني العمود الأول.
### getM22() {#getM22--}
```
public final float getM22()
```


يحصل على عنصر المصفوفة في الصف الثاني العمود الثاني. يمثل المقياس على المحور Y.

**Returns:**
float - عنصر المصفوفة في الصف الثاني العمود الثاني.
### getM31() {#getM31--}
```
public final float getM31()
```


يحصل على عنصر المصفوفة في الصف الثالث العمود الأول. يمثل الإزاحة على المحور X.

**Returns:**
float - عنصر المصفوفة في الصف الثالث العمود الأول.
### getM32() {#getM32--}
```
public final float getM32()
```


يحصل على عنصر المصفوفة في الصف الثالث العمود الأول. يمثل الإزاحة على المحور Y.

**Returns:**
float - عنصر المصفوفة في الصف الثالث العمود الأول.
### toString() {#toString--}
```
public String toString()
```


يعيد سلسلة تمثل هذه الحالة.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
### getElements() {#getElements--}
```
public final float[] getElements()
```


يحصل على نسخة من عناصر المصفوفة.

**Returns:**
float[] - نسخة من عناصر المصفوفة.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


يطبق التحويل الهندسي الممثّل بواسطة هذا [Matrix](../../com.aspose.imaging/matrix) على مصفوفة محددة من النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | النقاط. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا [Matrix](../../com.aspose.imaging/matrix) باستخدام الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleX | float | المقياس X. |
| scaleY | float | المقياس Y. |
| order | int | الترتيب. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا Matrix باستخدام ترتيب Prepend (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | ال sx. ال sx. ال sx. |
| sy | float | ال sy. ال sy. ال sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


يطبق متجه الإزاحة المحدد على هذا Matrix بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| offsetX | float | ال offset X. |
| offsetY | float | ال offset Y. |
| order | int | الترتيب. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


يطبق متجه الإزاحة المحدد على هذا [Matrix](../../com.aspose.imaging/matrix) باستخدام ترتيب Prepend (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tx | float | ال tx. ال tx. ال tx. |
| ty | float | ال ty. ال ty. ال ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | ال tx. ال tx. ال tx. |
| order | int | ال order. ال order. ال order. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


يضرب هذا Matrix بالمصفوفة المحددة في معامل matrix باستخدام ترتيب Prepend (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة للضرب معها. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |
| order | int | ترتيب المصفوفة. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذا Matrix بترتيب Prepend (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | الزاوية. |
| point | [PointF](../../com.aspose.imaging/pointf) | النقطة. |
| order | int | الترتيب. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذا Matrix بترتيب Prepend (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | الزاوية. |
| point | [PointF](../../com.aspose.imaging/pointf) | النقطة. |

### reset() {#reset--}
```
public final void reset()
```


يعيد تعيين هذه المصفوفة لتحتوي على عناصر مصفوفة الوحدة.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | ال `Object` للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الـ `Object` المحدد يساوي هذه الحالة؛ وإلا `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


يعيد `true` إذا كان الـ `AffineTransform` هذا تحويل هوية.

**Returns:**
منطقي - `true` إذا كان هذا `AffineTransform` تحويل هوية؛ `false` خلاف ذلك.
