---
title: "الفئة Region"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Region. تصف داخل الشكل الرسومي المكوّن من المستطيلات والمسارات. لا يمكن وراثة هذه الفئة."
type: docs
weight: 11430
url: /ar/net/aspose.imaging/region/
---
## Region class

يصف الجزء الداخلي لشكل رسومي مكوّن من مستطيلات ومسارات. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class Region
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Region](region/#constructor)() | يُنشئ `Region` جديدًا. |
| [Region](region/#constructor_1)(GraphicsPath) | يُنشئ `Region` جديدًا باستخدام [`GraphicsPath`](../graphicspath/) المحدد. |
| [Region](region/#constructor_2)(Rectangle) | يُنشئ `Region` جديدًا من البنية [`Rectangle`](../rectangle/) المحددة. |
| [Region](region/#constructor_3)(RectangleF) | يُنشئ `Region` جديدًا من البنية [`RectangleF`](../rectanglef/) المحددة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement/#complement)(GraphicsPath) | يُحدّث هذا `Region` ليحتوي على الجزء من [`GraphicsPath`](../graphicspath/) المحدد الذي لا يتقاطع مع هذا `Region`. |
| [Complement](../../aspose.imaging/region/complement/#complement_1)(Rectangle) | يُحدّث هذا `Region` ليحتوي على الجزء من البنية [`Rectangle`](../rectangle/) المحددة الذي لا يتقاطع مع هذا `Region`. |
| [Complement](../../aspose.imaging/region/complement/#complement_2)(RectangleF) | يُحدّث هذا `Region` ليحتوي على الجزء من البنية [`RectangleF`](../rectanglef/) المحددة الذي لا يتقاطع مع هذا `Region`. |
| [Complement](../../aspose.imaging/region/complement/#complement_3)(Region) | يُحدّث هذا `Region` ليحتوي على الجزء من `Region` المحدد الذي لا يتقاطع مع هذا `Region`. |
| [DeepClone](../../aspose.imaging/region/deepclone/)() | ينشئ نسخة عميقة دقيقة من هذا `Region`. |
| override [Equals](../../aspose.imaging/region/equals/#equals_1)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| [Equals](../../aspose.imaging/region/equals/#equals)(Region, Graphics) | يفحص ما إذا كان `Region` المحدد مطابقًا لهذا `Region` على سطح الرسم المحدد. |
| [Exclude](../../aspose.imaging/region/exclude/#exclude)(GraphicsPath) | يُحدّث هذا `Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع [`GraphicsPath`](../graphicspath/) المحدد. |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_1)(Rectangle) | يُحدّث هذا `Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع البنية [`Rectangle`](../rectangle/) المحددة. |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_2)(RectangleF) | يُحدّث هذا `Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع البنية [`RectangleF`](../rectanglef/) المحددة. |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_3)(Region) | يُحدّث هذا `Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع `Region` المحدد. |
| override [GetHashCode](../../aspose.imaging/region/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [Intersect](../../aspose.imaging/region/intersect/#intersect)(GraphicsPath) | يُحدّث هذا `Region` إلى تقاطع نفسه مع [`GraphicsPath`](../graphicspath/) المحدد. |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_1)(Rectangle) | يُحدّث هذا `Region` إلى تقاطع نفسه مع البنية [`Rectangle`](../rectangle/) المحددة. |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_2)(RectangleF) | يُحدّث هذا `Region` إلى تقاطع نفسه مع البنية [`RectangleF`](../rectanglef/) المحددة. |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_3)(Region) | يُحدّث هذا `Region` إلى تقاطع نفسه مع `Region` المحدد. |
| [IsEmpty](../../aspose.imaging/region/isempty/)(Graphics) | يفحص ما إذا كان لهذا `Region` داخل فارغ على سطح الرسم المحدد. |
| [IsInfinite](../../aspose.imaging/region/isinfinite/)(Graphics) | يفحص ما إذا كان لهذا `Region` داخل لا نهائي على سطح الرسم المحدد. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible)(Point) | يفحص ما إذا كانت البنية [`Point`](../point/) المحددة موجودة داخل هذا `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_2)(PointF) | يفحص ما إذا كانت البنية [`PointF`](../pointf/) المحددة موجودة داخل هذا `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_4)(Rectangle) | يفحص ما إذا كان أي جزء من البنية [`Rectangle`](../rectangle/) المحددة موجودًا داخل هذا `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_6)(RectangleF) | يفحص ما إذا كان أي جزء من البنية [`RectangleF`](../rectanglef/) المحددة موجودًا داخل هذا `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_11)(float, float) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذه `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_1)(Point, Graphics) | يفحص ما إذا كانت بنية [`Point`](../point/) المحددة موجودة داخل هذه `Region` عند رسمها باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_3)(PointF, Graphics) | يفحص ما إذا كانت بنية [`PointF`](../pointf/) المحددة موجودة داخل هذه `Region` عند رسمها باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_5)(Rectangle, Graphics) | يفحص ما إذا كان أي جزء من بنية [`Rectangle`](../rectangle/) المحددة موجودًا داخل هذه `Region` عند رسمه باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_7)(RectangleF, Graphics) | يفحص ما إذا كان أي جزء من بنية [`RectangleF`](../rectanglef/) المحددة موجودًا داخل هذه `Region` عند رسمه باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_12)(float, float, Graphics) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذه `Region` عند رسمها باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_8)(int, int, Graphics) | يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن `Region` هذا عند رسمه باستخدام كائن الـ[`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_13)(float, float, float, float) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_9)(int, int, int, int) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region` عند رسمه باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region` عند رسمه باستخدام الـ[`Graphics`](../graphics/). |
| [MakeEmpty](../../aspose.imaging/region/makeempty/)() | يُهيئ هذه `Region` إلى داخل فارغ. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite/)() | يُهيئ كائن `Region` هذا إلى داخل لا نهائي. |
| [Transform](../../aspose.imaging/region/transform/)(Matrix) | يحوّل هذه `Region` باستخدام الـ[`Matrix`](../matrix/) المحدد. |
| [Translate](../../aspose.imaging/region/translate/#translate_1)(float, float) | يُزاحِم إحداثيات هذه `Region` بالمقدار المحدد. |
| [Translate](../../aspose.imaging/region/translate/#translate)(int, int) | يُزاحِم إحداثيات هذه `Region` بالمقدار المحدد. |
| [Union](../../aspose.imaging/region/union/#union)(GraphicsPath) | يُحدّث هذه `Region` إلى اتحادها مع الـ[`GraphicsPath`](../graphicspath/) المحدد. |
| [Union](../../aspose.imaging/region/union/#union_1)(Rectangle) | يُحدّث هذه `Region` إلى اتحادها مع بنية [`Rectangle`](../rectangle/) المحددة. |
| [Union](../../aspose.imaging/region/union/#union_2)(RectangleF) | يُحدّث هذه `Region` إلى اتحادها مع بنية [`RectangleF`](../rectanglef/) المحددة. |
| [Union](../../aspose.imaging/region/union/#union_3)(Region) | يُحدّث هذه `Region` إلى اتحادها مع الـ`Region` المحدد. |
| [Xor](../../aspose.imaging/region/xor/#xor)(GraphicsPath) | يُحدّث هذه `Region` إلى اتحادها مطروحًا منه تقاطعها مع الـ[`GraphicsPath`](../graphicspath/) المحدد. |
| [Xor](../../aspose.imaging/region/xor/#xor_1)(Rectangle) | يُحدّث هذه `Region` إلى اتحادها مطروحًا منه تقاطعها مع بنية [`Rectangle`](../rectangle/) المحددة. |
| [Xor](../../aspose.imaging/region/xor/#xor_2)(RectangleF) | يُحدّث هذه `Region` إلى اتحادها مطروحًا منه تقاطعها مع بنية [`RectangleF`](../rectanglef/) المحددة. |
| [Xor](../../aspose.imaging/region/xor/#xor_3)(Region) | يُحدّث هذه `Region` إلى اتحادها مطروحًا منه تقاطعها مع الـ`Region` المحدد. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


