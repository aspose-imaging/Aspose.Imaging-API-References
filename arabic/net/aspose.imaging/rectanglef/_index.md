---
title: "الهيكل RectangleF"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الهيكل Aspose.Imaging.RectangleF. يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل"
type: docs
weight: 11420
url: /ar/net/aspose.imaging/rectanglef/
---
## RectangleF structure

يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل.

```csharp
public struct RectangleF
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | يُهيئ نسخة جديدة من بنية `RectangleF` بالموقع والحجم المحددين. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | يُهيئ نسخة جديدة من بنية `RectangleF` بالموقع والحجم المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty/) { get; } | يسترجع نسخة جديدة من بنية `RectangleF` التي تحتوي على قيم [`X`](./x/)، [`Y`](./y/)، [`Width`](./width/) و[`Height`](./height/) مضبوطة على الصفر. |
| [Bottom](../../aspose.imaging/rectanglef/bottom/) { get; set; } | يحصل أو يضبط إحداثي الصادي الذي هو مجموع [`Y`](./y/) و[`Height`](./height/) لهذه البنية `RectangleF`. |
| [Height](../../aspose.imaging/rectanglef/height/) { get; set; } | يحصل أو يضبط ارتفاع هذه البنية `RectangleF`. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty/) { get; } | يسترجع قيمة تشير إلى ما إذا كانت خاصية [`Width`](./width/) أو [`Height`](./height/) لهذه البنية `RectangleF` لها قيمة صفر. |
| [Left](../../aspose.imaging/rectanglef/left/) { get; set; } | يحصل أو يضبط إحداثي السين الذي يمثل الحافة اليسرى لهذه البنية `RectangleF`. |
| [Location](../../aspose.imaging/rectanglef/location/) { get; set; } | يحصل أو يضبط إحداثيات الزاوية العليا اليسرى لهذه البنية `RectangleF`. |
| [Right](../../aspose.imaging/rectanglef/right/) { get; set; } | يحصل أو يضبط إحداثي السين الذي هو مجموع [`X`](./x/) و[`Width`](./width/) لهذه البنية `RectangleF`. |
| [Size](../../aspose.imaging/rectanglef/size/) { get; set; } | يحصل أو يضبط حجم هذه البنية `RectangleF`. |
| [Top](../../aspose.imaging/rectanglef/top/) { get; set; } | يحصل أو يضبط إحداثي الصادي للحافة العلوية لهذه البنية `RectangleF`. |
| [Width](../../aspose.imaging/rectanglef/width/) { get; set; } | يحصل أو يضبط عرض هذه البنية `RectangleF`. |
| [X](../../aspose.imaging/rectanglef/x/) { get; set; } | يحصل أو يضبط إحداثي السين للزاوية العليا اليسرى لهذه البنية `RectangleF`. |
| [Y](../../aspose.imaging/rectanglef/y/) { get; set; } | يحصل أو يضبط إحداثي الصادي للزاوية العليا اليسرى لهذه البنية `RectangleF`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | ينشئ بنية `RectangleF` مع الزاوية العليا اليسرى والزاوية السفلى اليمنى في المواقع المحددة. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints/)(PointF, PointF) | ينشئ [`Rectangle`](../rectangle/) جديدًا من نقطتين محددتين. سيكون رأسا الـ [`Rectangle`](../rectangle/) المُنشأ مساويين للنقطتين *point1* و *point2* الممررتين. عادةً ما تكون هذه هي الرؤوس المتقابلة. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate/)(RectangleF, float, float) | ينشئ ويعيد نسخة موسعة من بنية `RectangleF` المحددة. يتم توسيع النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect/)(RectangleF, RectangleF) | يعيد بنية `RectangleF` تمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع `RectangleF` فارغ. |
| static [Union](../../aspose.imaging/rectanglef/union/)(RectangleF, RectangleF) | ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا. |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains)(PointF) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية `RectangleF` هذه. |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains_1)(RectangleF) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها *rect* موجودة بالكامل داخل بنية `RectangleF` هذه. |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains_2)(float, float) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية `RectangleF` هذه. |
| override [Equals](../../aspose.imaging/rectanglef/equals/)(object) | يفحص ما إذا كان *obj* هو `RectangleF` بنفس الموقع والحجم لهذا `RectangleF`. |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode/)() | يحصل على رمز التجزئة لهذه البنية `RectangleF`. |
| [Inflate](../../aspose.imaging/rectanglef/inflate/#inflate)(SizeF) | يوسع هذا `RectangleF` بالمقدار المحدد. |
| [Inflate](../../aspose.imaging/rectanglef/inflate/#inflate_1)(float, float) | يوسع بنية `RectangleF` هذه بالمقدار المحدد. |
| [Intersect](../../aspose.imaging/rectanglef/intersect/)(RectangleF) | يستبدل بنية `RectangleF` هذه بتقاطعها مع بنية `RectangleF` المحددة. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith/)(RectangleF) | يحدد ما إذا كان هذا المستطيل يتقاطع مع *rect*. |
| [Normalize](../../aspose.imaging/rectanglef/normalize/)() | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أعلى من الأسفل. |
| [Offset](../../aspose.imaging/rectanglef/offset/#offset)(PointF) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.imaging/rectanglef/offset/#offset_1)(float, float) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.imaging/rectanglef/tostring/)() | يحوّل خصائص هذا `RectangleF` إلى سلسلة قابلة للقراءة البشرية. |
| [operator /](../../aspose.imaging/rectanglef/op_division/) | يُنفّذ العامل /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality/) | يفحص ما إذا كان بناؤا `RectangleF` اثنان لهما نفس الموقع والحجم. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit/) | يحوّل بنية [`Rectangle`](../rectangle/) المحددة إلى بنية `RectangleF`. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality/) | يفحص ما إذا كان بناؤا `RectangleF` اثنان يختلفان في الموقع أو الحجم. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply/) | يُنفّذ العامل *. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


