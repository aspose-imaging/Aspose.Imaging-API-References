---
title: "مصفوفة"
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

معظم الخوارزميات مأخوذة من AffineTransform.java الخاص بـ Sun. تُستخدم أسماء Java لعناصر المصفوفة داخليًا. خريطة أسماء Java إلى .net مع الوصف: m00 M11 مقياس X m10 M12 قص Y m01 M21 قص X m11 M22 مقياس Y m02 M31 ترجمة X m12 M32 ترجمة Y
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Matrix()](#Matrix--) | يُنشئ مثيلًا جديدًا لفئة Matrix كمصفوفة هوية. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | يُنشئ مثيلًا جديدًا لفئة [Matrix](../../com.aspose.imaging/matrix). |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | يُنشئ مثيلًا جديدًا لفئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | يُنشئ مثيلًا جديدًا لفئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | ينشئ نسخة من فئة [Matrix](../../com.aspose.imaging/matrix). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | التحويل الهوية هو ذلك الذي تكون فيه إحداثيات الإخراج دائمًا هي نفسها إحداثيات الإدخال. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | التحويل الإزاحي ينقل الإحداثيات بمقدار ثابت في الاتجاهين x و y دون تغيير طول أو زاوية المتجهات. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | المقياس المتساوي يضاعف طول المتجهات بنفس المقدار في الاتجاهين x و y دون تغيير الزاوية بين المتجهات. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | المقياس العام يضاعف طول المتجهات بمقادير مختلفة في الاتجاهين x و y دون تغيير الزاوية بين المتجهات المتعامدة. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | هذه الثابتة هي قناع بت لأي من بتات علم المقياس. |
| [TYPE_FLIP](#TYPE-FLIP) | هذه البتة العلم تشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بعكس صورة مرآة حول محور ما، مما يغيّر نظام الإحداثيات المعتاد الأيمن إلى نظام إحداثيات أيسر، بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | هذه البتة العلم تشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران ربعي بمضاعفات 90 درجة، بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | هذه البتة العلم تشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران بزاوية عشوائية، بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | هذه الثابتة هي قناع بت لأي من بتات علم الدوران. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | هذه الثابتة تشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بتحويل عشوائي لإحداثيات الإدخال. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | يحدد ما إذا كانت مصفوفتان متساويتان. |
| [getM11()](#getM11--) | يحصل على عنصر المصفوفة في الصف الأول والعمود الأول. |
| [getM12()](#getM12--) | يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. |
| [getM21()](#getM21--) | يحصل على عنصر المصفوفة في الصف الثاني والعمود الأول. |
| [getM22()](#getM22--) | يحصل على عنصر المصفوفة في الصف الثاني والعمود الثاني. |
| [getM31()](#getM31--) | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. |
| [getM32()](#getM32--) | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. |
| [toString()](#toString--) | يرجع String يمثل هذه المثيلة. |
| [getElements()](#getElements--) | يحصل على نسخة من عناصر المصفوفة. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | يطبق التحويل الهندسي الممثّل بواسطة هذه [Matrix](../../com.aspose.imaging/matrix) على مصفوفة محددة من النقاط. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه [Matrix](../../com.aspose.imaging/matrix) باستخدام الترتيب المحدد. |
| [scale(float sx, float sy)](#scale-float-float-) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه Matrix باستخدام ترتيب Prepend (الافتراضي). |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | يطبق متجه الترجمة المحدد على هذه المصفوفة بالترتيب المحدد. |
| [translate(float tx, float ty)](#translate-float-float-) | يطبق متجه الترجمة المحدد على هذه [Matrix](../../com.aspose.imaging/matrix) باستخدام ترتيب (Prepend) الافتراضي. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | يضرب هذه المصفوفة بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | يضرب هذه المصفوفة بالمصفوفة المحددة في معامل matrix باستخدام ترتيب (Prepend) الافتراضي. |
| [rotate(float angle, int order)](#rotate-float-int-) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب المحدد. |
| [rotate(float angle)](#rotate-float-) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب الافتراضي (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب المحدد. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب الافتراضي (Prepend). |
| [reset()](#reset--) | يعيد تعيين هذه المصفوفة لتحتوي على عناصر مصفوفة الهوية. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة. |
| [isIdentity()](#isIdentity--) | يرجع `true` إذا كان هذا `AffineTransform` تحويل هوية. |
### Matrix() {#Matrix--}
```
public Matrix()
```


يُنشئ مثيلًا جديدًا لفئة Matrix كمصفوفة هوية.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


يُنشئ مثيلًا جديدًا لفئة [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


يُنشئ مثيلًا جديدًا لفئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل [RectangleF](../../com.aspose.imaging/rectanglef) يمثل المستطيل الذي سيُحوَّل. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة من ثلاثة هياكل [PointF](../../com.aspose.imaging/pointf) تمثل نقاط متوازي أضلاع الذي سيتم تحويل الزوايا العليا اليسرى، العليا اليمنى، والسفلى اليسرى للمستطيل إليه. الزاوية السفلى اليمنى لمتوازي الأضلاع تُستنتج من الزوايا الثلاث الأولى. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


يُنشئ مثيلًا جديدًا لفئة [Matrix](../../com.aspose.imaging/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل [Rectangle](../../com.aspose.imaging/rectangle) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | مصفوفة من ثلاثة هياكل [Point](../../com.aspose.imaging/point) تمثل نقاط متوازي أضلاع التي سيتم تحويل الزوايا العلوية اليسرى والعليا اليمنى والسفلية اليسرى للمستطيل إليها. الزاوية السفلية اليمنى للمتوازي أضلاع مفترضة بناءً على الزوايا الثلاث الأولى. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


ينشئ نسخة من فئة [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | مصفوفة أساسية للمعالجة |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


التحويل الهوية هو التحويل الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال. إذا كان هذا التحويل أي شيء غير التحويل الهوية، فسيكون النوع إما الثابت GENERAL\_TRANSFORM أو مزيجًا من بتات العلامة المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بهذا التحويل بأدائها.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


التحويل الإزاحي ينقل الإحداثيات بمقدار ثابت في الاتجاهين x و y دون تغيير طول أو زاوية المتجهات.

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


هذه الثابتة هي قناع بت لأي من بتات علم المقياس.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


تشير هذه البتة العلامية إلى أن التحويل المعرفة بهذا الكائن تقوم بعكس صورة مرآة حول محور ما مما يغيّر نظام الإحداثيات اليمني المعتاد إلى نظام إحداثيات أيسر، بالإضافة إلى التحويلات المشار إليها ببتات العلامة الأخرى. نظام الإحداثيات اليمني هو النظام الذي يدور فيه المحور X الموجب عكس اتجاه عقارب الساعة ليطابق المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليمنى عندما تنظر إلى إبهامك من الطرف. نظام الإحداثيات الأيسر هو النظام الذي يدور فيه المحور X الموجب مع اتجاه عقارب الساعة ليطابق المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليسرى. لا توجد طريقة رياضية لتحديد زاوية التحويل الأصلي للانعكاس أو المرآة لأن جميع زوايا الانعكاس متطابقة عند تطبيق دوران تعديل مناسب. ملاحظة: تم إضافة TypeFlip بعد أن أصبح GENERAL\_TRANSFORM متداولًا علنًا ولم يعد من الممكن إعادة ترقيم بتات العلامة بسهولة دون إدخال عدم توافق ثنائي في الشيفرة الخارجية.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


تشير هذه البتة العلامية إلى أن التحويل المعرفة بهذا الكائن تقوم بدوران ربعي ب multiples من 90 درجة بالإضافة إلى التحويلات المشار إليها ببتات العلامة الأخرى. الدوران يغيّر زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذه البتة العلامية متعارضة مع علم TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


تشير هذه البتة العلامية إلى أن التحويل المعرفة بهذا الكائن تقوم بدوران بزاوية عشوائية بالإضافة إلى التحويلات المشار إليها ببتات العلامة الأخرى. الدوران يغيّر زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذه البتة العلامية متعارضة مع

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


هذه الثابتة هي قناع بت لأي من بتات علم الدوران.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


تشير هذه الثابتة إلى أن التحويل المعرفة بهذا الكائن تقوم بتحويل عشوائي لإحداثيات الإدخال. إذا كان يمكن تصنيف هذا التحويل بأحد الثوابت المذكورة أعلاه، فسيكون النوع إما الثابت TypeIdentity أو مزيجًا من بتات العلامة المناسبة للتحويلات المختلفة للإحداثيات التي يقوم بهذا التحويل بأدائها.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


يحدد ما إذا كانت مصفوفتان متساويتان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة الأولى للمقارنة. |
| b | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة الثانية للمقارنة. |

**Returns:**
منطقي - صحيح إذا كانت المصفوفات متساوية.
### getM11() {#getM11--}
```
public final float getM11()
```


يحصل على عنصر المصفوفة في الصف الأول والعمود الأول. يمثل المقياس على المحور X.

**Returns:**
عائم - عنصر المصفوفة في الصف الأول والعمود الأول.
### getM12() {#getM12--}
```
public final float getM12()
```


يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. يمثل القص على المحور Y.

**Returns:**
عائم - عنصر المصفوفة في الصف الأول والعمود الثاني.
### getM21() {#getM21--}
```
public final float getM21()
```


يحصل على عنصر المصفوفة في الصف الثاني والعمود الأول. يمثل القص على المحور X.

**Returns:**
عائم - عنصر المصفوفة في الصف الثاني والعمود الأول.
### getM22() {#getM22--}
```
public final float getM22()
```


يحصل على عنصر المصفوفة في الصف الثاني والعمود الثاني. يمثل المقياس على المحور Y.

**Returns:**
عائم - عنصر المصفوفة في الصف الثاني والعمود الثاني.
### getM31() {#getM31--}
```
public final float getM31()
```


يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور X.

**Returns:**
عائم - عنصر المصفوفة في الصف الثالث والعمود الأول.
### getM32() {#getM32--}
```
public final float getM32()
```


يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور Y.

**Returns:**
عائم - عنصر المصفوفة في الصف الثالث والعمود الأول.
### toString() {#toString--}
```
public String toString()
```


يرجع String يمثل هذه المثيلة.

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


يطبق التحويل الهندسي الممثّل بواسطة هذه [Matrix](../../com.aspose.imaging/matrix) على مصفوفة محددة من النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | النقاط. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه [Matrix](../../com.aspose.imaging/matrix) باستخدام الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleX | float | المقياس X. |
| scaleY | float | المقياس Y. |
| الترتيب | int | الترتيب. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه Matrix باستخدام ترتيب Prepend (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


يطبق متجه الترجمة المحدد على هذه المصفوفة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| offsetX | float | الإزاحة X. |
| offsetY | float | الإزاحة Y. |
| الترتيب | int | الترتيب. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


يطبق متجه الترجمة المحدد على هذه [Matrix](../../com.aspose.imaging/matrix) باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tx | float | tx. tx. tx. |
| ty | float | ty. ty. ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


يضرب هذه المصفوفة بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | tx. tx. tx. |
| الترتيب | int | الترتيب. الترتيب. الترتيب. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


يضرب هذه المصفوفة بالمصفوفة المحددة في معامل matrix باستخدام ترتيب (Prepend) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة التي يتم الضرب معها. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |
| الترتيب | int | ترتيب المصفوفة. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذه المصفوفة بالترتيب الافتراضي (Prepend).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | الزاوية. |
| point | [PointF](../../com.aspose.imaging/pointf) | النقطة. |
| الترتيب | int | الترتيب. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب الافتراضي (Prepend).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | الزاوية. |
| point | [PointF](../../com.aspose.imaging/pointf) | النقطة. |

### reset() {#reset--}
```
public final void reset()
```


يعيد تعيين هذه المصفوفة لتحتوي على عناصر مصفوفة الهوية.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - قيمة تجزئة (hash code) لهذا الكائن، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن `Object` للمقارنة مع هذه المثيلة. |

**Returns:**
منطقية - `true` إذا كان الـ `Object` المحدد مساويًا لهذه المثيلة؛ وإلا `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


يرجع `true` إذا كان هذا `AffineTransform` تحويل هوية.

**Returns:**
منطقية - `true` إذا كان هذا الـ `AffineTransform` تحويل هوية؛ `false` خلاف ذلك.
