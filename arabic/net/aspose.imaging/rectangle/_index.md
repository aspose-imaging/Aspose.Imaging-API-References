---
title: "بنية Rectangle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "بنية Aspose.Imaging.Rectangle. تخزن مجموعة من أربعة أعداد صحيحة تمثل الموقع والحجم لمستطيل"
type: docs
weight: 11410
url: /ar/net/aspose.imaging/rectangle/
---
## Rectangle structure

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.

```csharp
public struct Rectangle
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | ينشئ مثيلاً جديداً لبنية `Rectangle` بالموقع والحجم المحددين. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | ينشئ مثيلاً جديداً لبنية `Rectangle` بالموقع والحجم المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty/) { get; } | يحصل على مثيل جديد لبنية `Rectangle` تكون قيم [`X`](./x/)، [`Y`](./y/)، [`Width`](./width/) و[`Height`](./height/) مضبوطة على الصفر. |
| [Bottom](../../aspose.imaging/rectangle/bottom/) { get; set; } | يحصل أو يضبط إحداثي الصادي الذي هو مجموع قيمتي الخاصيتين [`Y`](./y/) و[`Height`](./height/) لهذه البنية `Rectangle`. |
| [Height](../../aspose.imaging/rectangle/height/) { get; set; } | يحصل أو يضبط ارتفاع هذه البنية `Rectangle`. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذه البنية `Rectangle` قيمتها صفر. |
| [Left](../../aspose.imaging/rectangle/left/) { get; set; } | يحصل أو يضبط إحداثي السين الذي يخص الحافة اليسرى لهذه البنية `Rectangle`. |
| [Location](../../aspose.imaging/rectangle/location/) { get; set; } | يحصل أو يضبط إحداثيات الزاوية العليا اليسرى لهذه البنية `Rectangle`. |
| [Right](../../aspose.imaging/rectangle/right/) { get; set; } | يحصل أو يضبط إحداثي السين الذي هو مجموع قيمتي الخاصيتين [`X`](./x/) و[`Width`](./width/) لهذه البنية `Rectangle`. |
| [Size](../../aspose.imaging/rectangle/size/) { get; set; } | يحصل أو يضبط حجم هذه البنية `Rectangle`. |
| [Top](../../aspose.imaging/rectangle/top/) { get; set; } | يحصل أو يضبط إحداثي الصادي للحافة العلوية لهذه البنية `Rectangle`. |
| [Width](../../aspose.imaging/rectangle/width/) { get; set; } | يحصل أو يضبط عرض هذه البنية `Rectangle`. |
| [X](../../aspose.imaging/rectangle/x/) { get; set; } | يحصل أو يضبط إحداثي السين للزاوية العليا اليسرى لهذه البنية `Rectangle`. |
| [Y](../../aspose.imaging/rectangle/y/) { get; set; } | يحصل أو يضبط إحداثي الصادي للزاوية العليا اليسرى لهذه البنية `Rectangle`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling/)(RectangleF) | يحوّل البنية المحددة [`RectangleF`](../rectanglef/) إلى بنية `Rectangle` عن طريق تقريب قيم [`RectangleF`](../rectanglef/) إلى القيم الصحيحة الأعلى. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom/)(int, int, int, int) | ينشئ بنية `Rectangle` بالمواقع المحددة للحواف. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints/)(Point, Point) | ينشئ `Rectangle` جديداً من نقطتين محددتين. سيكون العمودان في الـ `Rectangle` المُنشأ مساويين للنقطتين *point1* و*point2* الممررتين. عادةً ما تكون هاتان النقطتان رؤوساً متقابلة. |
| static [Inflate](../../aspose.imaging/rectangle/inflate/)(Rectangle, int, int) | ينشئ ويعيد نسخة مُوسَّعة من البنية المحددة `Rectangle`. تُوسَّع النسخة بالمقدار المحدد. تظل البنية الأصلية `Rectangle` دون تعديل. |
| static [Intersect](../../aspose.imaging/rectangle/intersect/)(Rectangle, Rectangle) | يعيد بنية `Rectangle` ثالثة تمثل تقاطع بنيتين `Rectangle` أخريين. إذا لم يكن هناك تقاطع، يتم إرجاع `Rectangle` فارغ. |
| static [Round](../../aspose.imaging/rectangle/round/)(RectangleF) | يحوّل الـ [`RectangleF`](../rectanglef/) المحدد إلى `Rectangle` عن طريق تقريب قيم [`RectangleF`](../rectanglef/) إلى أقرب قيمة صحيحة. |
| static [Truncate](../../aspose.imaging/rectangle/truncate/)(RectangleF) | يحوّل الـ [`RectangleF`](../rectanglef/) المحدد إلى `Rectangle` عن طريق قطع قيم [`RectangleF`](../rectanglef/). |
| static [Union](../../aspose.imaging/rectangle/union/)(Rectangle, Rectangle) | يحصل على بنية `Rectangle` التي تحتوي على اتحاد بنيتين `Rectangle`. |
| [Contains](../../aspose.imaging/rectangle/contains/#contains)(Point) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية `Rectangle` هذه. |
| [Contains](../../aspose.imaging/rectangle/contains/#contains_1)(Rectangle) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها *rect* موجودة بالكامل داخل بنية `Rectangle` هذه. |
| [Contains](../../aspose.imaging/rectangle/contains/#contains_2)(int, int) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية `Rectangle` هذه. |
| override [Equals](../../aspose.imaging/rectangle/equals/)(object) | يفحص ما إذا كان *obj* بنية `Rectangle` ذات نفس الموقع والحجم لبنية `Rectangle` هذه. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode/)() | يعيد رمز التجزئة لهذه بنية `Rectangle`. |
| [Inflate](../../aspose.imaging/rectangle/inflate/#inflate)(Size) | يوسع هذه `Rectangle` بالمقدار المحدد. |
| [Inflate](../../aspose.imaging/rectangle/inflate/#inflate_1)(int, int) | يوسع هذه `Rectangle` بالمقدار المحدد. |
| [Intersect](../../aspose.imaging/rectangle/intersect/)(Rectangle) | يستبدل هذه `Rectangle` بالتقاطع بين نفسها و`Rectangle` المحددة. |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith/)(Rectangle) | يحدد ما إذا كان هذا المستطيل يتقاطع مع *rect*. |
| [Normalize](../../aspose.imaging/rectangle/normalize/)() | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أعلى من الأسفل. |
| [Offset](../../aspose.imaging/rectangle/offset/#offset)(Point) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.imaging/rectangle/offset/#offset_1)(int, int) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.imaging/rectangle/tostring/)() | يحوّل خصائص هذه `Rectangle` إلى سلسلة قابلة للقراءة البشرية. |
| [operator ==](../../aspose.imaging/rectangle/op_equality/) | يفحص ما إذا كانت بنية `Rectangle`تين لهما نفس الموقع والحجم. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality/) | يفحص ما إذا كانت بنية `Rectangle`تين تختلفان في الموقع أو الحجم. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


