---
title: "الهيكل PointF"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الهيكل Aspose.Imaging.PointF. يمثل زوجاً مرتباً من إحداثيات x و y ذات الفاصلة العائمة التي تحدد نقطة في مستوى ثنائي الأبعاد"
type: docs
weight: 11320
url: /ar/net/aspose.imaging/pointf/
---
## PointF structure

يمثل زوجًا مرتبًا من إحداثيات x و y عائمة يحدد نقطة في مستوى ثنائي الأبعاد.

```csharp
public struct PointF
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PointF](pointf/)(float, float) | يُنشئ مثلاً جديداً من الهيكل `PointF` بالإحداثيات المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.imaging/pointf/empty/) { get; } | يحصل على مثلاً جديداً من الهيكل `PointF` الذي يحتوي على قيم [`X`](./x/) و [`Y`](./y/) مضبوطة على الصفر. |
| [IsEmpty](../../aspose.imaging/pointf/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `PointF` فارغاً. |
| [X](../../aspose.imaging/pointf/x/) { get; set; } | يحصل أو يعيّن الإحداثي x لهذا `PointF`. |
| [Y](../../aspose.imaging/pointf/y/) { get; set; } | يحصل أو يعيّن الإحداثي y لهذا `PointF`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Add](../../aspose.imaging/pointf/add/#add)(PointF, Size) | يحوّل `PointF` معيناً بالحجم المحدد [`Size`](../size/). |
| static [Add](../../aspose.imaging/pointf/add/#add_1)(PointF, SizeF) | يحوّل `PointF` معيناً بالحجم المحدد [`SizeF`](../sizef/). |
| static [Subtract](../../aspose.imaging/pointf/subtract/#subtract)(PointF, Size) | يحوّل `PointF` بالسالب للحجم المحدد. |
| static [Subtract](../../aspose.imaging/pointf/subtract/#subtract_1)(PointF, SizeF) | يحوّل `PointF` بالسالب للحجم المحدد. |
| override [Equals](../../aspose.imaging/pointf/equals/)(object) | يحدد ما إذا كان هذا `PointF` يحتوي على نفس الإحداثيات كما في الكائن المحدد. |
| override [GetHashCode](../../aspose.imaging/pointf/gethashcode/)() | يرجع رمز تجزئة لهذا الهيكل `PointF`. |
| override [ToString](../../aspose.imaging/pointf/tostring/)() | يحوّل هذا `PointF` إلى سلسلة قابلة للقراءة البشرية. |
| [operator +](../../aspose.imaging/pointf/op_addition/#op_addition) | يحوّل `PointF` بحجم معين [`Size`](../size/). (عاملان) |
| [operator ==](../../aspose.imaging/pointf/op_equality/) | يقارن بين هيكلي `PointF` اثنين. النتيجة تحدد ما إذا كانت قيم خصائص [`X`](./x/) و [`Y`](./y/) للهيكلين `PointF` متساوية. |
| [operator !=](../../aspose.imaging/pointf/op_inequality/) | يحدد ما إذا كانت إحداثيات النقاط المحددة غير متساوية. |
| [operator -](../../aspose.imaging/pointf/op_subtraction/#op_subtraction) | ينقل `PointF` بالسالب للـ [`Size`](../size/) المعطى. (2 عمليات) |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


