---
title: "الهيكل Point"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الهيكل Aspose.Imaging.Point. يمثل زوجًا مرتبًا من الإحداثيين الصحيحين x و y الذي يحدد نقطة في مستوى ثنائي الأبعاد."
type: docs
weight: 11310
url: /ar/net/aspose.imaging/point/
---
## Point structure

يمثل زوجًا مرتبًا من إحداثيات x و y صحيحة يحدد نقطة في مستوى ثنائي الأبعاد.

```csharp
public struct Point
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Point](point/#constructor_1)(int) | يُنشئ مثيلاً جديدًا لهياكل `Point` باستخدام إحداثيات محددة بقيمة عدد صحيح. |
| [Point](point/#constructor)(Size) | يُنشئ مثيلاً جديدًا لهياكل `Point` من بنية [`Size`](../size/). |
| [Point](point/#constructor_2)(int, int) | يُنشئ مثيلاً جديدًا لهياكل `Point` بالإحداثيات المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.imaging/point/empty/) { get; } | يحصل على مثيل جديد لهياكل `Point` تكون قيمتي [`X`](./x/) و[`Y`](./y/) مضبوطة على الصفر. |
| [IsEmpty](../../aspose.imaging/point/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `Point` فارغًا. |
| [X](../../aspose.imaging/point/x/) { get; set; } | يحصل أو يعيّن إحداثي x لهذا `Point`. |
| [Y](../../aspose.imaging/point/y/) { get; set; } | يحصل أو يعيّن إحداثي y لهذا `Point`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Add](../../aspose.imaging/point/add/)(Point, Size) | يضيف الـ[`Size`](../size/) المحدد إلى الـ`Point` المحدد. |
| static [Ceiling](../../aspose.imaging/point/ceiling/)(PointF) | يحوّل الـ[`PointF`](../pointf/) المحدد إلى `Point` عن طريق تقريب قيم الـ[`PointF`](../pointf/) إلى القيم الصحيحة الأعلى. |
| static [Round](../../aspose.imaging/point/round/)(PointF) | يحوّل الـ[`PointF`](../pointf/) المحدد إلى كائن `Point` عن طريق تقريب قيم الـ`Point` إلى أقرب عدد صحيح. |
| static [Subtract](../../aspose.imaging/point/subtract/)(Point, Size) | يعيد نتيجة طرح الـ[`Size`](../size/) المحدد من الـ`Point` المحدد. |
| static [Truncate](../../aspose.imaging/point/truncate/)(PointF) | يحوّل الـ[`PointF`](../pointf/) المحدد إلى `Point` عن طريق قطع قيم الـ`Point`. |
| override [Equals](../../aspose.imaging/point/equals/)(object) | يحدد ما إذا كان هذا `Point` يحتوي على نفس الإحداثيات كالكائن المحدد. |
| override [GetHashCode](../../aspose.imaging/point/gethashcode/)() | يعيد رمز تجزئة لهذا `Point`. |
| [Offset](../../aspose.imaging/point/offset/#offset)(Point) | يُترجم هذا `Point` بواسطة الـ`Point` المحدد. |
| [Offset](../../aspose.imaging/point/offset/#offset_1)(int, int) | يُترجم هذا `Point` بالمقدار المحدد. |
| [ToLong](../../aspose.imaging/point/tolong/)() | حوّل هذا Point إلى قيمة طويلة واحدة، تحتوي على إحداثيات X وY في البتات العليا والسفلى. |
| override [ToString](../../aspose.imaging/point/tostring/)() | يحوّل هذا `Point` إلى سلسلة قابلة للقراءة من قبل الإنسان. |
| static [FromLong](../../aspose.imaging/point/fromlong/)(long, out int, out int) | يفكّ تركيب كائن Point المعبأ في كائن طويل إلى قيم X وY صحيحة منفصلة. |
| [operator +](../../aspose.imaging/point/op_addition/) | يُترجم `Point` بمقاس [`Size`](../size/) معين. |
| [operator ==](../../aspose.imaging/point/op_equality/) | يقارن كائنين `Point`. النتيجة تحدد ما إذا كانت قيم خصائص [`X`](./x/) و[`Y`](./y/) لكائنين `Point` متساوية. |
| [explicit operator](../../aspose.imaging/point/op_explicit/) | يحوّل بنية `Point` المحددة إلى بنية [`Size`](../size/). |
| [implicit operator](../../aspose.imaging/point/op_implicit/) | يحوّل بنية `Point` المحددة إلى بنية [`PointF`](../pointf/). |
| [operator !=](../../aspose.imaging/point/op_inequality/) | يقارن كائنين `Point`. النتيجة تحدد ما إذا كانت قيم خصائص [`X`](./x/) أو [`Y`](./y/) لكائنين `Point` غير متساوية. |
| [operator -](../../aspose.imaging/point/op_subtraction/) | يُترجم `Point` بالسالب للـ[`Size`](../size/) المعطى. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


