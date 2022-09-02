---
title: Matrix
second_title: Aspose.Imaging لمرجع NET API
description: يستبدل GDI  Matrix.
type: docs
weight: 10550
url: /ar/net/aspose.imaging/matrix/
---
## Matrix class

يستبدل GDI + Matrix.

```csharp
public class Matrix
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Matrix](matrix#constructor)() | تهيئة مثيل جديد لفئة Matrix كمصفوفة الهوية. |
| [Matrix](matrix#constructor_1)(Matrix) | عمل نسخة من ملف[`Matrix`](../matrix) فئة . |
| [Matrix](matrix#constructor_2)(Rectangle, Point[]) | يقوم بتهيئة مثيل جديد لملف[`Matrix`](../matrix) فئة للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومجموعة من النقاط. |
| [Matrix](matrix#constructor_3)(RectangleF, PointF[]) | يقوم بتهيئة مثيل جديد لملف[`Matrix`](../matrix) فئة للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومجموعة من النقاط. |
| [Matrix](matrix#constructor_4)(float, float, float, float, float, float) | يقوم بتهيئة مثيل جديد لملف[`Matrix`](../matrix) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements) { get; } | يحصل على مصفوفة من قيم الفاصلة العائمة التي تمثل عناصر هذا[`Matrix`](../matrix) . |
| [M11](../../aspose.imaging/matrix/m11) { get; } | يحصل على عنصر المصفوفة في العمود الأول للصف الأول. يمثل المقياس على طول المحور X. |
| [M12](../../aspose.imaging/matrix/m12) { get; } | يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. يمثل القص على طول المحور Y. |
| [M21](../../aspose.imaging/matrix/m21) { get; } | يحصل على عنصر المصفوفة في العمود الأول للصف الثاني. يمثل القص على طول المحور X. |
| [M22](../../aspose.imaging/matrix/m22) { get; } | يحصل على عنصر المصفوفة في العمود الثاني للصف الثاني. يمثل المقياس على طول المحور Y. |
| [M31](../../aspose.imaging/matrix/m31) { get; } | يحصل على عنصر المصفوفة في العمود الأول للصف الثالث. يمثل الترجمة على طول المحور X. |
| [M32](../../aspose.imaging/matrix/m32) { get; } | يحصل على عنصر المصفوفة في العمود الأول للصف الثالث. يمثل الترجمة على طول المحور ص . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals)(object) | تحديد ما إذا كان الملف المحددObject يساوي هذا المثال. |
| [GetElements](../../aspose.imaging/matrix/getelements)() | الحصول على نسخة من عناصر المصفوفة . |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode)() | إرجاع رمز تجزئة لهذا المثال. |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply)(Matrix) | ضرب هذه المصفوفة بالمصفوفة المحددة في معامل المصفوفة باستخدام (افتراضي) ترتيب الإيداع المسبق . |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply_1)(Matrix, MatrixOrder) | تضرب هذه المصفوفة بالمصفوفة المحددة في معلمة المصفوفة ، وبالترتيب المحدد في معامل الطلب. |
| [Reset](../../aspose.imaging/matrix/reset)() | يعيد تعيين هذه المصفوفة بحيث تحتوي على عناصر مصفوفة الهوية. |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate)(float) | يطبق دورانًا في اتجاه عقارب الساعة لمبلغ محدد في معامل الزاوية ، حول الأصل (إحداثيات صفر x و y) لهذه المصفوفة بالترتيب الافتراضي (الإيداع المسبق) . |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate_1)(float, MatrixOrder) | يطبق دورانًا في اتجاه عقارب الساعة لمبلغ محدد في معامل الزاوية ، حول الأصل (إحداثيات صفر x و y) لهذه المصفوفة بالترتيب المحدد . |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat)(float, PointF) | يطبق دوران في اتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب الافتراضي (الإيداع المسبق). |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat_1)(float, PointF, MatrixOrder) | يطبق دوران في اتجاه عقارب الساعة حول النقطة المحددة على هذه المصفوفة بالترتيب المحدد. |
| [Scale](../../aspose.imaging/matrix/scale#scale)(float, float) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه المصفوفة باستخدام (افتراضي) ترتيب مسبق . |
| [Scale](../../aspose.imaging/matrix/scale#scale_1)(float, float, MatrixOrder) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذا[`Matrix`](../matrix) باستخدام الأمر المحدد. |
| override [ToString](../../aspose.imaging/matrix/tostring)() | إرجاع أString الذي يمثل هذا المثال. |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints)(PointF[]) | يطبق التحويل الهندسي الذي يمثله هذا[`Matrix`](../matrix)إلى مجموعة محددة من النقاط. |
| [Translate](../../aspose.imaging/matrix/translate#translate)(float, float) | يطبق متجه الترجمة المحدد على ذلك[`Matrix`](../matrix) باستخدام (افتراضي) أمر الإيداع المسبق. |
| [Translate](../../aspose.imaging/matrix/translate#translate_1)(float, float, MatrixOrder) | يطبق متجه الترجمة المحدد على هذه المصفوفة بالترتيب المحدد. |
| static [Equals](../../aspose.imaging/matrix/equals)(Matrix, Matrix) | لتحديد ما إذا كانت مصفوفتان متساويتين. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip) | يشير بت العلم هذا إلى أن التحويل المحدد بواسطة هذا الكائن يؤدي إلى انعكاس صورة معكوسة حول بعض المحاور التي تغير نظام إحداثيات اليد اليمنى عادةً إلى نظام اليد اليسرى بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. هو واحد حيث يدور المحور X الموجب عكس اتجاه عقارب الساعة ليغلف المحور Y الموجب على غرار الاتجاه الذي تلتف فيه الأصابع على يدك اليمنى عندما تحدق بإبهامك. في اتجاه عقارب الساعة لتراكب المحور Y الموجب بشكل مشابه للاتجاه الذي تجعد فيه الأصابع الموجودة على يدك اليسرى. لا توجد طريقة رياضية لتحديد زاوية التقليب الأصلي أو التحويل الانعكاسي نظرًا لأن جميع الزوايا للقلب متطابقة مع توفير دوران ضبط مناسب. ملاحظة: تمت إضافة TypeFlip بعد GENERAL_TRANSFORM كانت قيد التداول public ولم يعد من الممكن إعادة ترقيم بتات العلم بشكل ملائم دون إدخال عدم التوافق الثنائي في الرمز outside. |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation) | يشير بت العلم هذا إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بإجراء دوران بزاوية عشوائية بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. وبدون تغيير طول المتجه. |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale) | يضاعف المقياس العام طول المتجهات بمبالغ مختلفة في اتجاهي x و y دون تغيير الزاوية بين المتجهات العمودية. |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform) | يشير هذا الثابت إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بإجراء تحويل عشوائي لإحداثيات الإدخال. بت للتحويلات الإحداثية المختلفة التي يؤديها هذا التحويل. |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity) | تحويل الهوية هو تحويل تكون فيه إحداثيات الإخراج دائمًا هي نفسها إحداثيات الإدخال. إذا كان هذا التحويل هو أي شيء آخر غير تحويل الهوية ، سيكون النوع إما تركيبة GENERAL_TRANSFORM الثابتة أو a من بتات العلم المناسبة لـ مختلف تحويلات الإحداثيات التي يؤديها هذا التحويل. |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation) | هذا الثابت هو قناع بت لأي بتات علم الدوران. |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale) | هذا الثابت هو قناع بت لأي من بتات علم المقياس. |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation) | يشير بت العلم هذا إلى أن التحويل المحدد بواسطة هذا الكائن يؤدي إلى دوران رباعي بمقدار 90 درجة في بالإضافة إلى التحويلات المشار إليها بواسطة بتات العلم الأخرى. من المتجه وبدون تغيير طول المتجه. |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation) | تنقل الترجمة الإحداثيات بمقدار ثابت في x و y دون تغيير طول أو زاوية المتجهات. |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale) | يضاعف المقياس المنتظم طول المتجهات بنفس المقدار في كلا الاتجاهين x و y بدون تغيير الزاوية بين المتجهات. هذا العلم لا يتعارض مع علامة TypeGeneralScale. |

### ملاحظات

معظم الخوارزميات مأخوذة من Sun's AffineTransform.java. أسماء Java لعناصر المصفوفة المستخدمة داخليًا. تعيين أسماء java لعناصر المصفوفة. net للوصف: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear_ M211_d_m_m01 ترجمة X m12 M32 ترجمة Y

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
