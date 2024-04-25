---
title: Graphics
second_title: Aspose.Imaging لمرجع NET API
description: يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي.
type: docs
weight: 9360
url: /ar/aspose.imaging/graphics/
---
## Graphics class

يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي.

```csharp
public sealed class Graphics
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Graphics](graphics)(Image) | يقوم بتهيئة مثيل جديد لملف[`Graphics`](../graphics) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | الحصول على منطقة المقطع أو تعيينها . |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | الحصول على جودة التركيب أو تعيينها. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | الحصول على الدقة الأفقية لهذا الغرض. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | الحصول على الدقة الرأسية لهذا الغرض. |
| [Image](../../aspose.imaging/graphics/image) { get; } | يحصل على الصورة . |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | الحصول على أو تحديد وضع الاستيفاء. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء بدء التحديث. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | الحصول على أو تعيين القياس بين وحدات العالم ووحدات الصفحة لهذا الغرض. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | الحصول على أو تعيين وحدة القياس المستخدمة لإحداثيات الصفحة في هذا الغرض. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | الحصول على أو تحديد وضع التجانس . |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | الحصول على تلميح عرض النص أو تعيينه. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | الحصول على أو تعيين نسخة من تحويل العالم الهندسي لهذا الغرض[`Graphics`](../graphics) . |

## طُرق

| اسم | وصف |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | يبدأ التخزين المؤقت لعمليات الرسومات التالية. لن يتم تطبيق تأثيرات الرسومات المطبقة بعد ذلك على الفور بدلاً من أن يتسبب EndUpdate في تطبيق جميع التأثيرات مرة واحدة. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | مسح سطح الرسومات باستخدام اللون المحدد. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة أ[`Rectangle`](../rectangle) هيكل . |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة أ[`RectangleF`](../rectanglef) هيكل . |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | يرسم شريحة بيزير محددة بأربعة[`Point`](../point) الهياكل . |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | يرسم شريحة بيزير محددة بأربعة[`PointF`](../pointf) الهياكل . |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | يرسم شريحة بيزير محددة بأربعة أزواج مرتبة من الإحداثيات التي تمثل النقاط. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | رسم سلسلة من شرائح بيزيير من مصفوفة[`PointF`](../pointf) الهياكل . |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | رسم سلسلة من شرائح بيزيير من مصفوفة[`Point`](../point) الهياكل . |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`PointF`](../pointf) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`Point`](../point) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`PointF`](../pointf) الهياكل التي تستخدم توترًا محددًا. تستخدم هذه الطريقة افتراضيًاAlternate وضع الملء . |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`Point`](../point) الهياكل التي تستخدم توترًا محددًا. تستخدم هذه الطريقة افتراضيًاAlternate وضع الملء . |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf) الهياكل. تستخدم هذه الطريقة معدل توتر افتراضي 0.5 . |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../point) الهياكل . |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf) الهياكل باستخدام التوتر المحدد. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../point) الهياكل باستخدام التوتر المحدد. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf) الهياكل. يبدأ الرسم في الإزاحة من بداية المصفوفة . تستخدم هذه الطريقة شد افتراضي 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf)الهياكل التي تستخدم توترًا محددًا. يبدأ الرسم في الإزاحة من بداية المصفوفة. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../point) الهياكل باستخدام التوتر المحدد. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | رسم قطع ناقص محدد بإحاطة[`Rectangle`](../rectangle) هيكل . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | رسم قطع ناقص معرّف بحدود[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | رسم شكل بيضاوي محدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات وارتفاع وعرض . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | رسم شكل بيضاوي محدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات وارتفاع وعرض . |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | رسم ملف[`Image`](./image) ، باستخدام حجمه الفعلي الأصلي ، في الموقع المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | رسم ملف[`Image`](./image) ، باستخدام حجمه الفعلي الأصلي ، في الموقع المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | رسم ملف[`Image`](./image) ، باستخدام حجمه الفعلي الأصلي ، في الموقع المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | يرسم الصورة المحددة ، باستخدام حجمها المادي الأصلي ، في الموقع المحدد بواسطة زوج إحداثيات . |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image) في الموقع المحدد وبالحجم المحدد. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | رسم صورة محددة باستخدام حجمها الفعلي الأصلي في مكان محدد. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | رسم صورة محددة باستخدام حجمها الفعلي الأصلي في مكان محدد. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | يرسم الصورة المحددة باستخدام حجمها المادي الأصلي في الموقع المحدد بواسطة زوج إحداثيات . |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | رسم صورة محددة باستخدام حجمها الفعلي الأصلي في مكان محدد. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | يرسم الصورة المحددة دون تغيير الحجم ويقطعها ، إذا لزم الأمر ، لتلائم المستطيل المحدد. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | يرسم خطًا يربط بين اثنين[`Point`](../point) الهياكل . |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | يرسم خطًا يربط بين اثنين[`PointF`](../pointf) الهياكل . |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | يرسم خطًا يربط بين النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | يرسم خطًا يربط بين النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | يرسم سلسلة من مقاطع الخطوط التي تصل صفيف من ملفات[`PointF`](../pointf) الهياكل . |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | يرسم سلسلة من مقاطع الخطوط التي تصل صفيف من ملفات[`Point`](../point) الهياكل . |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | رسم أ[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | يرسم شكل دائري معرف بقطع ناقص محدد بواسطة[`Rectangle`](../rectangle) هيكل وخطين شعاعي. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | يرسم شكل دائري معرف بقطع ناقص محدد بواسطة[`RectangleF`](../rectanglef) هيكل وخطين شعاعي. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | يرسم شكل دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج إحداثيات ، وعرض ، وارتفاع ، وخطين نصف قطريين. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | يرسم شكل دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج إحداثيات ، وعرض ، وارتفاع ، وخطين نصف قطريين. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | يرسم مضلعًا محددًا بمصفوفة من[`PointF`](../pointf) الهياكل . |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | يرسم مضلعًا محددًا بمصفوفة من[`Point`](../point) الهياكل . |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | يرسم مستطيلاً محدداً ب[`Rectangle`](../rectangle) هيكل . |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | يرسم مستطيلاً محدداً ب[`RectangleF`](../rectanglef) هيكل . |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | رسم مستطيل محدد بواسطة زوج إحداثيات وعرض وارتفاع. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | رسم مستطيل محدد بواسطة زوج إحداثيات وعرض وارتفاع. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | يرسم سلسلة من المستطيلات المحددة بواسطة[`RectangleF`](../rectanglef) الهياكل . |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | يرسم سلسلة من المستطيلات المحددة بواسطة[`Rectangle`](../rectangle) الهياكل . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush) و[`Font`](../font) الكائنات . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../brush) و[`Font`](../font) الكائنات . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush) و[`Font`](../font) الكائنات . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush) و[`Font`](../font) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../brush) و[`Font`](../font) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush) و[`Font`](../font) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | يبدأ التخزين المؤقت لعمليات الرسومات بعد استدعاء BeginUpdate. سيتم تطبيق عمليات الرسومات السابقة مرة واحدة عند استدعاء هذه الطريقة. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`PointF`](../pointf) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`Point`](../point) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`PointF`](../pointf) الهياكل باستخدام وضع التعبئة المحدد. تستخدم هذه الطريقة معدل توتر افتراضي 0.5 . |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`Point`](../point) الهياكل باستخدام وضع التعبئة المحدد. تستخدم هذه الطريقة معدل توتر افتراضي 0.5 . |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`PointF`](../pointf) الهياكل باستخدام وضع التعبئة والتوتر المحدد. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`Point`](../point) الهياكل باستخدام وضع التعبئة والتوتر المحدد. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة[`Rectangle`](../rectangle) هيكل . |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة[`RectangleF`](../rectanglef) هيكل . |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | يملأ الجزء الداخلي من أ[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة[`RectangleF`](../rectanglef) هيكل وخطين شعاعي. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة[`RectangleF`](../rectanglef) هيكل وخطين شعاعي. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج من الإحداثيات والعرض والارتفاع وخطين نصف قطريين. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج من الإحداثيات والعرض والارتفاع وخطين نصف قطريين. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`PointF`](../pointf) الهياكل وAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`Point`](../point) الهياكل وAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`PointF`](../pointf) الهياكل باستخدام وضع التعبئة المحدد. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`Point`](../point) الهياكل باستخدام وضع التعبئة المحدد. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة أ[`Rectangle`](../rectangle) هيكل . |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة أ[`RectangleF`](../rectanglef) هيكل . |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع . |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع . |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | يملأ الأجزاء الداخلية لسلسلة من المستطيلات المحددة بواسطة[`RectangleF`](../rectanglef) الهياكل . |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | يملأ الأجزاء الداخلية لسلسلة من المستطيلات المحددة بواسطة[`Rectangle`](../rectangle) الهياكل . |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | يملأ الجزء الداخلي من أ[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | يقيس السلسلة النصية المحددة بمعلمات محددة |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | يضاعف[`Matrix`](../matrix) التي تمثل التحويل الهندسي المحلي لهذا[`Graphics`](../graphics) حسب المحدد[`Matrix`](../matrix) عن طريق إضافة الملف المحدد مسبقًا[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | يضاعف[`Matrix`](../matrix) التي تمثل التحويل الهندسي المحلي لهذا[`Graphics`](../graphics) حسب المحدد[`Matrix`](../matrix) بالترتيب المحدد. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | يعيد تعيين ملف[`Transform`](./transform) الخاصية للهوية . |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | مقياس التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | مقياس التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### أمثلة

يستخدم هذا المثال فئة الرسومات لإنشاء أشكال بدائية على سطح الصورة. لتوضيح العملية ، يقوم المثال بإنشاء صورة جديدة بتنسيق PNG ورسم أشكال بدائية على سطح الصورة باستخدام طرق الرسم المكشوفة بواسطة فئة الرسومات

```csharp
[C#]

// ينشئ مثيلاً من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    // قم بإنشاء مثيل لـ PngOptions وقم بتعيين خصائصه المختلفة
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // تعيين المصدر لخيارات PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        // إنشاء وتهيئة مثيل لفئة الرسومات
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        // مسح سطح الرسومات
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // ارسم قوسًا بتحديد كائن القلم ذي اللون الأسود ، 
        // أ مستطيل يحيط بالقوس وزاوية البدء وزاوية المسح
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        // ارسم بيزير عن طريق تحديد كائن القلم ذي اللون الأزرق ونقاط التنسيق.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        // ارسم منحنى عن طريق تحديد كائن القلم ذي اللون الأخضر ومجموعة من النقاط
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        // ارسم شكل بيضاوي باستخدام كائن القلم والمستطيل المحيط
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //ارسم خطا 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        // ارسم مقطع دائري
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        // ارسم مضلعًا بتحديد كائن القلم ذي اللون الأحمر ومجموعة من النقاط
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        // ارسم مستطيلاً
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        // إنشاء كائن SolidBrush وضبط خصائصه المختلفة
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        // ارسم سلسلة باستخدام كائن SolidBrush والخط ، عند نقطة معينة
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
