---
title: RectangleF
second_title: Aspose.Imaging لمرجع NET API
description: يخزن مجموعة من أربعة أرقام فاصلة عائمة تمثل موقع وحجم المستطيل.
type: docs
weight: 10840
url: /ar/aspose.imaging/rectanglef/
---
## RectangleF structure

يخزن مجموعة من أربعة أرقام فاصلة عائمة تمثل موقع وحجم المستطيل.

```csharp
public struct RectangleF
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | يقوم بتهيئة مثيل جديد لملف[`RectangleF`](../rectanglef) هيكل بالموقع والحجم المحددين. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | يقوم بتهيئة مثيل جديد لملف[`RectangleF`](../rectanglef) هيكل بالموقع والحجم المحددين. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | يحصل على مثيل جديد لملف[`RectangleF`](../rectanglef) هيكل لديه[`X`](./x) و[`Y`](./y) و[`Width`](./width) و[`Height`](./height) تم ضبط القيم على الصفر. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | الحصول على أو تحديد إحداثي ص الذي يمثل مجموع[`Y`](./y) و[`Height`](./height) من هذا[`RectangleF`](../rectanglef) هيكل . |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | الحصول على أو تحديد ارتفاع هذا[`RectangleF`](../rectanglef) هيكل . |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | يحصل على قيمة تشير إلى ما إذا كان ملف[`Width`](./width) أو[`Height`](./height) ملكية هذا[`RectangleF`](../rectanglef) بقيمة صفر . |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | الحصول على أو تحديد إحداثيات x للحافة اليسرى لهذا[`RectangleF`](../rectanglef) هيكل . |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | الحصول على إحداثيات الزاوية اليسرى العلوية أو تحديدها[`RectangleF`](../rectanglef) هيكل . |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | الحصول على أو تحديد الإحداثي x الذي يمثل مجموع[`X`](./x) و[`Width`](./width) من هذا[`RectangleF`](../rectanglef) هيكل . |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | الحصول على أو تحديد حجم هذا[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | الحصول على أو تحديد إحداثيات y للحافة العلوية لهذا[`RectangleF`](../rectanglef) هيكل . |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | الحصول على أو تحديد عرض هذا[`RectangleF`](../rectanglef) هيكل . |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | الحصول على أو تحديد إحداثيات x للركن الأيسر العلوي لهذا[`RectangleF`](../rectanglef) هيكل . |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | الحصول على أو تحديد إحداثيات y للركن الأيسر العلوي لهذا[`RectangleF`](../rectanglef) هيكل . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | ينشئ ملف[`RectangleF`](../rectanglef) هيكل مع الزاوية العلوية اليسرى والزاوية اليمنى السفلية في المواقع المحددة. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | ينشئ ملفًا جديدًا[`Rectangle`](../rectangle) من نقطتين محددتين. رأسين من المخلوقات[`Rectangle`](../rectangle) سوف تكون مساوية لتمريرها*point1* و*point2* . ستكون هذه عادةً الرؤوس المعاكسة. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | إنشاء وإرجاع نسخة مضخمة من المحدد[`RectangleF`](../rectanglef)بنية. يتم تضخيم النسخة بالمبلغ المحدد. يبقى المستطيل الأصلي بدون تعديل. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | إرجاع أ[`RectangleF`](../rectanglef) الهيكل الذي يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع وخالٍ[`RectangleF`](../rectanglef) تم إرجاعه . |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | لإنشاء أصغر مستطيل ثالث ممكن يمكن أن يحتوي على كلا المستطيلين اللذين يشكلان اتحادًا. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا[`RectangleF`](../rectanglef) هيكل . |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | لتحديد ما إذا كانت المنطقة المستطيلة ممثلة بـ*rect* موجود بالكامل في هذا[`RectangleF`](../rectanglef) هيكل . |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا[`RectangleF`](../rectanglef) هيكل . |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | اختبارات سواء*obj* هو[`RectangleF`](../rectanglef) بنفس موقع وحجم هذا[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | يحصل على كود التجزئة لهذا[`RectangleF`](../rectanglef) هيكل . |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | ينفخ هذا[`RectangleF`](../rectanglef) بالمبلغ المحدد. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | ينفخ هذا[`RectangleF`](../rectanglef) هيكل بالمبلغ المحدد. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | يستبدل هذا[`RectangleF`](../rectanglef)هيكل مع تقاطع نفسه والمحددة[`RectangleF`](../rectanglef) هيكل . |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | لتحديد ما إذا كان هذا المستطيل يتقاطع مع*rect* . |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | تسوية المستطيل بجعل عرضه وارتفاعه موجبين ، اليسار أقل من اليمين والجزء العلوي أقل من الأسفل . |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | تحويل سمات هذا[`RectangleF`](../rectanglef) لسلسلة يمكن للبشر قراءتها. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | ينفذ المشغل /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | اختبارات ما إذا كان اثنان[`RectangleF`](../rectanglef)الهياكل لها موقع وحجم متساويين. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | تحويل المحدد[`Rectangle`](../rectangle) هيكل ل[`RectangleF`](../rectanglef) هيكل . |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | اختبارات ما إذا كان اثنان[`RectangleF`](../rectanglef) تختلف الهياكل في الموقع أو الحجم. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | تنفيذ عامل التشغيل * . |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
