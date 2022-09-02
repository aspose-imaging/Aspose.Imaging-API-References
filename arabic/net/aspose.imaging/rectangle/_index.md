---
title: Rectangle
second_title: Aspose.Imaging لمرجع NET API
description: يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.
type: docs
weight: 10830
url: /ar/net/aspose.imaging/rectangle/
---
## Rectangle structure

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.

```csharp
public struct Rectangle
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | يقوم بتهيئة مثيل جديد لملف[`Rectangle`](../rectangle) هيكل بالموقع والحجم المحددين. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | يقوم بتهيئة مثيل جديد لملف[`Rectangle`](../rectangle) هيكل بالموقع والحجم المحددين. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | يحصل على مثيل جديد لملف[`Rectangle`](../rectangle) هيكل لديه[`X`](./x) و[`Y`](./y) و[`Width`](./width) و[`Height`](./height) تم ضبط القيم على الصفر. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | الحصول على أو تحديد إحداثي ص الذي يمثل مجموع[`Y`](./y) و[`Height`](./height) قيم خاصية هذا[`Rectangle`](../rectangle) هيكل . |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | الحصول على أو تحديد ارتفاع هذا[`Rectangle`](../rectangle) هيكل . |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا[`Rectangle`](../rectangle) لها قيم صفرية . |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | الحصول على أو تحديد إحداثيات x للحافة اليسرى لهذا[`Rectangle`](../rectangle) هيكل . |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | الحصول على إحداثيات الزاوية اليسرى العلوية أو تحديدها[`Rectangle`](../rectangle) هيكل . |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | الحصول على أو تحديد الإحداثي x الذي يمثل مجموع[`X`](./x) و[`Width`](./width) قيم خاصية هذا[`Rectangle`](../rectangle) هيكل . |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | الحصول على أو تحديد حجم هذا[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | الحصول على أو تحديد إحداثيات y للحافة العلوية لهذا[`Rectangle`](../rectangle) هيكل . |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | الحصول على أو تحديد عرض هذا[`Rectangle`](../rectangle) هيكل . |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | الحصول على أو تحديد إحداثيات x للركن الأيسر العلوي لهذا[`Rectangle`](../rectangle) هيكل . |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | الحصول على أو تحديد إحداثيات y للركن الأيسر العلوي لهذا[`Rectangle`](../rectangle) هيكل . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | تحويل المحدد[`RectangleF`](../rectanglef) هيكل ل[`Rectangle`](../rectangle) هيكل عن طريق تقريب[`RectangleF`](../rectanglef) القيم إلى قيم الأعداد الصحيحة الأعلى التالية. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | ينشئ ملف[`Rectangle`](../rectangle) هيكل مع مواقع الحافة المحددة. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | ينشئ ملفًا جديدًا[`Rectangle`](../rectangle) من نقطتين محددتين. عمودين من خلق[`Rectangle`](../rectangle) سوف تكون مساوية لتمريرها*point1* و*point2* . ستكون هذه عادةً الرؤوس المعاكسة. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | إنشاء وإرجاع نسخة مضخمة من المحدد[`Rectangle`](../rectangle) بنية. يتم تضخيم النسخة بالمبلغ المحدد. الأصلي[`Rectangle`](../rectangle) تظل البنية غير معدلة. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | إرجاع ثلث[`Rectangle`](../rectangle) الهيكل الذي يمثل تقاطع اثنين آخرين[`Rectangle`](../rectangle) الهياكل. إذا لم يكن هناك تقاطع ، فارغ[`Rectangle`](../rectangle) تم إرجاعه . |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | تحويل المحدد[`RectangleF`](../rectanglef) إلى أ[`Rectangle`](../rectangle) عن طريق تقريب[`RectangleF`](../rectanglef)القيم لأقرب قيم عدد صحيح. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | تحويل المحدد[`RectangleF`](../rectanglef) إلى أ[`Rectangle`](../rectangle) عن طريق اقتطاع[`RectangleF`](../rectanglef) القيم . |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | يحصل على أ[`Rectangle`](../rectangle) هيكل يحتوي على اتحاد اثنين[`Rectangle`](../rectangle) الهياكل . |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا[`Rectangle`](../rectangle) هيكل . |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | لتحديد ما إذا كانت المنطقة المستطيلة ممثلة بـ*rect* موجود بالكامل في هذا[`Rectangle`](../rectangle) هيكل . |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا[`Rectangle`](../rectangle) هيكل . |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | اختبارات سواء*obj* هو[`Rectangle`](../rectangle)هيكل مع نفس الموقع وحجم هذا[`Rectangle`](../rectangle) هيكل . |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | إرجاع كود التجزئة لهذا[`Rectangle`](../rectangle) هيكل . |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | ينفخ هذا[`Rectangle`](../rectangle) بالمبلغ المحدد. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | ينفخ هذا[`Rectangle`](../rectangle) بالمبلغ المحدد. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | يستبدل هذا[`Rectangle`](../rectangle) مع تقاطع نفسها والمحددة[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | لتحديد ما إذا كان هذا المستطيل يتقاطع مع*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | تسوية المستطيل بجعل عرضه وارتفاعه موجبين ، اليسار أقل من اليمين والجزء العلوي أقل من الأسفل . |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | تحويل سمات هذا[`Rectangle`](../rectangle) لسلسلة يمكن للبشر قراءتها. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | اختبارات ما إذا كان اثنان[`Rectangle`](../rectangle)الهياكل لها موقع وحجم متساويين. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | اختبارات ما إذا كان اثنان[`Rectangle`](../rectangle) تختلف الهياكل في الموقع أو الحجم. |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
