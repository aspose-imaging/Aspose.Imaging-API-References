---
title: "حجم البنية"
second_title: "Aspose.Imaging for .NET API Reference"
description: "هيكل Aspose.Imaging.Size. يمثل الحجم"
type: docs
weight: 11630
url: /ar/net/aspose.imaging/size/
---
## Size structure

يمثل الحجم.

```csharp
public struct Size
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Size](size/#constructor)(Point) | يُنشئ نسخة جديدة من بنية `Size` من الـ [`Point`](../point/) المحدد. |
| [Size](size/#constructor_1)(int, int) | يُنشئ نسخة جديدة من بنية `Size` من الأبعاد المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.imaging/size/empty/) { get; } | يحصل على نسخة جديدة من بنية `Size` التي تحتوي على قيم [`Width`](./width/) و[`Height`](./height/) مضبوطة على الصفر. |
| [Height](../../aspose.imaging/size/height/) { get; set; } | يحصل أو يضبط المكوّن العمودي لهذا `Size`. |
| [IsEmpty](../../aspose.imaging/size/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `Size` له عرض وارتفاع يساويان 0. |
| [Width](../../aspose.imaging/size/width/) { get; set; } | يحصل أو يضبط المكوّن الأفقي لهذا `Size`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Add](../../aspose.imaging/size/add/)(Size, Size) | يضيف العرض والارتفاع لهيكل `Size` واحد إلى العرض والارتفاع لهيكل `Size` آخر. |
| static [Ceiling](../../aspose.imaging/size/ceiling/)(SizeF) | يحوّل الهيكل [`SizeF`](../sizef/) المحدد إلى هيكل `Size` عن طريق تقريب قيم هيكل `Size` إلى القيم الصحيحة الأعلى. |
| static [Round](../../aspose.imaging/size/round/)(SizeF) | يحوّل الهيكل [`SizeF`](../sizef/) المحدد إلى هيكل `Size` عن طريق تقريب قيم الهيكل [`SizeF`](../sizef/) إلى أقرب قيمة صحيحة. |
| static [Subtract](../../aspose.imaging/size/subtract/)(Size, Size) | يطرح العرض والارتفاع لهيكل `Size` واحد من العرض والارتفاع لهيكل `Size` آخر. |
| static [Truncate](../../aspose.imaging/size/truncate/)(SizeF) | يحوّل الهيكل [`SizeF`](../sizef/) المحدد إلى هيكل `Size` عن طريق قطع قيم الهيكل [`SizeF`](../sizef/) إلى القيم الصحيحة الأدنى. |
| override [Equals](../../aspose.imaging/size/equals/)(object) | يفحص ما إذا كان الكائن المحدد هو `Size` له نفس الأبعاد مثل هذا `Size`. |
| override [GetHashCode](../../aspose.imaging/size/gethashcode/)() | يرجع رمز تجزئة لهذا الهيكل `Size`. |
| override [ToString](../../aspose.imaging/size/tostring/)() | ينشئ سلسلة قابلة للقراءة تمثل هذا `Size`. |
| [operator +](../../aspose.imaging/size/op_addition/) | يضيف العرض والارتفاع لهيكل `Size` واحد إلى العرض والارتفاع لهيكل `Size` آخر. |
| [operator ==](../../aspose.imaging/size/op_equality/) | يفحص ما إذا كان هيكلي `Size` اثنان متساويين. |
| [explicit operator](../../aspose.imaging/size/op_explicit/) | يحوّل الـ `Size` المحدد إلى [`Point`](../point/). |
| [implicit operator](../../aspose.imaging/size/op_implicit/) | يحوّل الـ `Size` المحدد إلى [`SizeF`](../sizef/). |
| [operator !=](../../aspose.imaging/size/op_inequality/) | يفحص ما إذا كان هيكلي `Size` اثنان مختلفين. |
| [operator -](../../aspose.imaging/size/op_subtraction/) | يطرح العرض والارتفاع لهيكل `Size` واحد من العرض والارتفاع لهيكل `Size` آخر. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


