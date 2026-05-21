---
title: "فئة Matrix"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Matrix. تستبدل فئة GDI Matrix."
type: docs
weight: 11100
url: /ar/net/aspose.imaging/matrix/
---
## Matrix class

يستبدل مصفوفة GDI+.

```csharp
public class Matrix
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Matrix](matrix/#constructor)() | يُهيئ نسخة جديدة من فئة Matrix كمصفوفة هوية. |
| [Matrix](matrix/#constructor_1)(Matrix) | ينشئ نسخة من فئة `Matrix`. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | يُهيئ نسخة جديدة من فئة `Matrix` إلى التحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | يُهيئ نسخة جديدة من فئة `Matrix` إلى التحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | يُهيئ نسخة جديدة من فئة `Matrix`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements/) { get; } | يحصل على مصفوفة من القيم العشرية التي تمثل عناصر هذا `Matrix`. |
| [M11](../../aspose.imaging/matrix/m11/) { get; } | يحصل على عنصر المصفوفة في الصف الأول والعمود الأول. يمثل المقياس على محور X. |
| [M12](../../aspose.imaging/matrix/m12/) { get; } | يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. يمثل القص على المحور Y. |
| [M21](../../aspose.imaging/matrix/m21/) { get; } | يحصل على عنصر المصفوفة في الصف الثاني والعمود الأول. يمثل القص على المحور X. |
| [M22](../../aspose.imaging/matrix/m22/) { get; } | يحصل على عنصر المصفوفة في الصف الثاني والعمود الثاني. يمثل التحجيم على المحور Y. |
| [M31](../../aspose.imaging/matrix/m31/) { get; } | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور X. |
| [M32](../../aspose.imaging/matrix/m32/) { get; } | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور Y. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals/)(object) | يحدد ما إذا كان الـ Object المحدد يساوي هذه المثيلة. |
| [GetElements](../../aspose.imaging/matrix/getelements/)() | يحصل على نسخة من عناصر المصفوفة. |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode/)() | يرجع رمز تجزئة لهذه المثيلة. |
| [Multiply](../../aspose.imaging/matrix/multiply/#multiply)(Matrix) | يضرب هذه Matrix بالمصفوفة المحددة في معامل matrix باستخدام ترتيب (Prepend) الافتراضي. |
| [Multiply](../../aspose.imaging/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | يضرب هذه Matrix بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order. |
| [Reset](../../aspose.imaging/matrix/reset/)() | يعيد ضبط هذه Matrix لتحتوي على عناصر المصفوفة الهوية. |
| [Rotate](../../aspose.imaging/matrix/rotate/#rotate)(float) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذه Matrix بالترتيب الافتراضي (Prepend). |
| [Rotate](../../aspose.imaging/matrix/rotate/#rotate_1)(float, MatrixOrder) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y صفر) لهذه Matrix بالترتيب المحدد. |
| [RotateAt](../../aspose.imaging/matrix/rotateat/#rotateat)(float, PointF) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب الافتراضي (Prepend). |
| [RotateAt](../../aspose.imaging/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب المحدد. |
| [Scale](../../aspose.imaging/matrix/scale/#scale)(float, float) | يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه Matrix باستخدام ترتيب (Prepend) الافتراضي. |
| [Scale](../../aspose.imaging/matrix/scale/#scale_1)(float, float, MatrixOrder) | يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه `Matrix` باستخدام الترتيب المحدد. |
| override [ToString](../../aspose.imaging/matrix/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints/)(PointF[]) | يطبق التحويل الهندسي الممثّل بهذه `Matrix` على مصفوفة محددة من النقاط. |
| [Translate](../../aspose.imaging/matrix/translate/#translate)(float, float) | يطبق متجه الإزاحة المحدد على هذه `Matrix` باستخدام ترتيب (Prepend) الافتراضي. |
| [Translate](../../aspose.imaging/matrix/translate/#translate_1)(float, float, MatrixOrder) | يطبق متجه الإزاحة المحدد على هذه Matrix بالترتيب المحدد. |
| static [Equals](../../aspose.imaging/matrix/equals/)(Matrix, Matrix) | يحدد ما إذا كان مصفوفتان متساويتان. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip/) | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بقلب صورة مرآة حول محور ما، مما يغيّر نظام الإحداثيات الأيمن التقليدي إلى نظام أيسر بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى. نظام الإحداثيات الأيمن هو الذي يدور فيه المحور X الموجب عكس اتجاه عقارب الساعة ليطابق المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليمنى عندما تنظر إلى إبهامك من الطرف. نظام الإحداثيات الأيسر هو الذي يدور فيه المحور X الموجب مع اتجاه عقارب الساعة ليطابق المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليسرى. لا توجد طريقة رياضية لتحديد زاوية القلب أو التحويل الأصلي لأن جميع زوايا القلب تكون متطابقة عند تطبيق دوران تعديل مناسب. ملاحظة: تم إضافة TypeFlip بعد أن كان GENERAL_TRANSFORM متاحًا للجمهور ولم يعد من الممكن إعادة ترقيم بتات flag بسهولة دون إدخال عدم توافق ثنائي في الشيفرة الخارجية. |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation/) | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران بزاوية عشوائية بالإضافة إلى التحويلات المشار إليها ببتات flag الأخرى. يغيّر الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذه البتة flag متعارضة مع الـ |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale/) | يقوم التحجيم العام بضرب طول المتجهات بمقادير مختلفة في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة. هذه البتة flag متعارضة مع علم TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform/) | تشير هذه الثابتة إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بتحويل عشوائي لإحداثيات الإدخال. إذا كان يمكن تصنيف هذا التحويل بأحد الثوابت المذكورة أعلاه، فسيكون النوع إما الثابت TypeIdentity أو مزيجًا من بتات flag المناسبة لمختلف تحويلات الإحداثيات التي يقوم بها هذا التحويل. |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity/) | التحويل الهوية هو التحويل الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال. إذا كان هذا التحويل غير التحويل الهوية، فسيكون النوع إما الثابت GENERAL_TRANSFORM أو مزيجًا من بتات flag المناسبة لمختلف تحويلات الإحداثيات التي يقوم بها هذا التحويل. |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation/) | هذه الثابتة هي قناع بت لأي من بتات flag الخاصة بالدوران. |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale/) | هذا الثابت هو قناع بت لأي من بتات علم المقياس. |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation/) | هذا بت العلم يشير إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران ربعي بضعف من 90 درجة بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. الدوران يغيّر زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذا بت العلم غير متوافق مع علم TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation/) | التحويل يحرّك الإحداثيات بمقدار ثابت في x و y دون تغيير طول أو زاوية المتجهات. |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale/) | المقياس المتساوي يضاعف طول المتجهات بنفس المقدار في كل من اتجاهي x و y دون تغيير الزاوية بين المتجهات. هذا بت العلم غير متوافق مع علم TypeGeneralScale. |

## ملاحظات

معظم الخوارزميات مأخوذة من AffineTransform.java الخاص بـ Sun. أسماء Java لعناصر المصفوفة المستخدمة داخليًا. خريطة أسماء Java إلى نظيرات .net مع الوصف: m00 M11 مقياس X m10 M12 قص Y m01 M21 قص X m11 M22 مقياس Y m02 M31 ترجمة X m12 M32 ترجمة Y

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


