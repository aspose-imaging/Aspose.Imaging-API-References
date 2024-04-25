---
title: Region
second_title: Aspose.Imaging لمرجع NET API
description: يصف الجزء الداخلي لشكل رسومي مكون من مستطيلات ومسارات. لا يمكن توريث هذه الفئة.
type: docs
weight: 10850
url: /ar/aspose.imaging/region/
---
## Region class

يصف الجزء الداخلي لشكل رسومي مكون من مستطيلات ومسارات. لا يمكن توريث هذه الفئة.

```csharp
public sealed class Region
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Region](region#constructor)() | يقوم بتهيئة ملف[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | يقوم بتهيئة ملف[`Region`](../region) مع المحدد[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | يقوم بتهيئة ملف[`Region`](../region) من المحدد[`Rectangle`](../rectangle) هيكل . |
| [Region](region#constructor_3)(RectangleF) | يقوم بتهيئة ملف[`Region`](../region) من المحدد[`RectangleF`](../rectanglef) هيكل . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | يقوم بتحديث هذا[`Region`](../region) لاحتواء الجزء المحدد[`GraphicsPath`](../graphicspath) هذا لا يتقاطع مع هذا[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | يقوم بتحديث هذا[`Region`](../region) لاحتواء الجزء المحدد[`Rectangle`](../rectangle) هيكل لا يتقاطع مع هذا[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | يقوم بتحديث هذا[`Region`](../region) لاحتواء الجزء المحدد[`RectangleF`](../rectanglef) هيكل لا يتقاطع مع هذا[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | يقوم بتحديث هذا[`Region`](../region) لاحتواء الجزء المحدد[`Region`](../region) هذا لا يتقاطع مع هذا[`Region`](../region) . |
| [DeepClone](../../aspose.imaging/region/deepclone)() | لإنشاء نسخة مطابقة عميقة من هذا[`Region`](../region) . |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | تختبر ما إذا كان الملف المحدد[`Region`](../region) مطابق لهذا[`Region`](../region) على سطح الرسم المحدد. |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | يقوم بتحديث هذا[`Region`](../region) لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | يقوم بتحديث هذا[`Region`](../region) لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد[`Rectangle`](../rectangle) هيكل . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | يقوم بتحديث هذا[`Region`](../region) لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد[`RectangleF`](../rectanglef) هيكل . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | يقوم بتحديث هذا[`Region`](../region) لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد[`Region`](../region) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | يقوم بتحديث هذا[`Region`](../region) إلى تقاطع نفسه مع المحدد[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | يقوم بتحديث هذا[`Region`](../region) إلى تقاطع نفسه مع المحدد[`Rectangle`](../rectangle) هيكل . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | يقوم بتحديث هذا[`Region`](../region) إلى تقاطع نفسه مع المحدد[`RectangleF`](../rectanglef) هيكل . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | يقوم بتحديث هذا[`Region`](../region) إلى تقاطع نفسه مع المحدد[`Region`](../region) . |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | اختبارات ما إذا كان هذا[`Region`](../region) يحتوي على مساحة داخلية فارغة على سطح الرسم المحدد. |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | اختبارات ما إذا كان هذا[`Region`](../region) له مساحة داخلية لا نهائية على سطح الرسم المحدد. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | تختبر ما إذا كان الملف المحدد[`Point`](../point) هيكل وارد في هذا[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | تختبر ما إذا كان الملف المحدد[`PointF`](../pointf) هيكل وارد في هذا[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | اختبارات ما إذا كان أي جزء من المحدد[`Rectangle`](../rectangle) هيكل وارد في هذا[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | اختبارات ما إذا كان أي جزء من المحدد[`RectangleF`](../rectanglef) هيكل وارد في هذا[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | يختبر ما إذا كانت النقطة المحددة متضمنة في هذا[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | تختبر ما إذا كان الملف المحدد[`Point`](../point) هيكل وارد في هذا[`Region`](../region)عند رسمها باستخدام المحدد[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | تختبر ما إذا كان الملف المحدد[`PointF`](../pointf) هيكل وارد في هذا[`Region`](../region)عند رسمها باستخدام المحدد[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | اختبارات ما إذا كان أي جزء من المحدد[`Rectangle`](../rectangle) هيكل وارد في هذا[`Region`](../region)عند رسمها باستخدام المحدد[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | اختبارات ما إذا كان أي جزء من المحدد[`RectangleF`](../rectanglef) هيكل وارد في هذا[`Region`](../region)عند رسمها باستخدام المحدد[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | يختبر ما إذا كانت النقطة المحددة متضمنة في هذا[`Region`](../region)عند رسمها باستخدام المحدد[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | يختبر ما إذا كانت النقطة المحددة متضمنة في هذا[`Region`](../region) الكائن عند رسمه باستخدام المحدد[`Graphics`](../graphics) الكائن . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../region)عند رسمها باستخدام المحدد[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا[`Region`](../region)عند رسمها باستخدام المحدد[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | يقوم بتهيئة هذا[`Region`](../region) إلى مساحة داخلية فارغة. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | يقوم بتهيئة هذا[`Region`](../region) كائن داخلي لانهائي . |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | يحول هذا[`Region`](../region) حسب المحدد[`Matrix`](../matrix) . |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | يزيح إحداثيات هذا[`Region`](../region) بالمبلغ المحدد. |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | يزيح إحداثيات هذا[`Region`](../region) بالمبلغ المحدد. |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | يقوم بتحديث هذا[`Region`](../region) لاتحاد نفسه والمحددة[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | يقوم بتحديث هذا[`Region`](../region) لاتحاد نفسه والمحددة[`Rectangle`](../rectangle) هيكل . |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | يقوم بتحديث هذا[`Region`](../region) لاتحاد نفسه والمحددة[`RectangleF`](../rectanglef) هيكل . |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | يقوم بتحديث هذا[`Region`](../region) لاتحاد نفسه والمحددة[`Region`](../region) . |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | يقوم بتحديث هذا[`Region`](../region) إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | يقوم بتحديث هذا[`Region`](../region) إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد[`Rectangle`](../rectangle) هيكل . |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | يقوم بتحديث هذا[`Region`](../region) إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد[`RectangleF`](../rectanglef) هيكل . |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | يقوم بتحديث هذا[`Region`](../region) إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد[`Region`](../region) . |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
