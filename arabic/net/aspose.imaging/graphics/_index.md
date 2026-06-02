---
title: "فئة Graphics"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Graphics. تمثّل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي."
type: docs
weight: 9540
url: /ar/net/aspose.imaging/graphics/
---
## Graphics class

يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي.

```csharp
public sealed class Graphics
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Graphics](graphics/)(Image) | يُهيئ مثيلاً جديداً لفئة `Graphics`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip/) { get; set; } | يحصل أو يعيّن منطقة القص. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality/) { get; set; } | يحصل أو يعيّن جودة التركيب. |
| [DpiX](../../aspose.imaging/graphics/dpix/) { get; } | يحصل على الدقة الأفقية لهذا Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy/) { get; } | يحصل على الدقة العمودية لهذا Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image/) { get; } | يحصل على الصورة. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode/) { get; set; } | يحصل أو يعيّن وضع الاستيفاء. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء BeginUpdate. |
| [PageScale](../../aspose.imaging/graphics/pagescale/) { get; set; } | يحصل أو يعيّن مقياس التحويل بين وحدات العالم ووحدات الصفحة لهذا Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit/) { get; set; } | يحصل أو يعيّن وحدة القياس المستخدمة لإحداثيات الصفحة في هذا Aspose.Imaging.Graphics. |
| [PaintableImageOptions](../../aspose.imaging/graphics/paintableimageoptions/) { get; set; } | يحصل أو يعيّن خيارات الصورة، المستخدمة لإنشاء صور متجهية قابلة للرسم. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode/) { get; set; } | يحصل أو يعيّن وضع التنعيم. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint/) { get; set; } | يحصل أو يعيّن تلميح عرض النص. |
| [Transform](../../aspose.imaging/graphics/transform/) { get; set; } | يحصل أو يعيّن نسخة من التحويل الهندسي للعالم لهذا `Graphics`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate/)() | يبدأ التخزين المؤقت للعمليات الرسومية التالية. لن تُطبق تأثيرات الرسومات التي تُطبق لاحقًا فورًا؛ بدلاً من ذلك سيؤدي EndUpdate إلى تطبيق جميع التأثيرات مرة واحدة. |
| [Clear](../../aspose.imaging/graphics/clear/)(Color) | يمسح سطح الرسومات باستخدام اللون المحدد. |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [`Rectangle`](../rectangle/). |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [`RectangleF`](../rectanglef/). |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | يرسم منحنى بيزيير معرف بأربع هياكل [`Point`](../point/). |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | يرسم منحنى بيزيير معرف بأربع هياكل [`PointF`](../pointf/). |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | يرسم منحنى بيزيير معرف بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | يرسم سلسلة من منحنيات بيزيير من مصفوفة هياكل [`PointF`](../pointf/). |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | يرسم سلسلة من منحنيات بيزيير من مصفوفة هياكل [`Point`](../point/). |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | يرسم منحنى كاردينال مغلق معرف بمصفوفة هياكل [`PointF`](../pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | يرسم منحنى كاردينال مغلق معرف بمصفوفة هياكل [`Point`](../point/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | يرسم منحنى كاردينال مغلق معرف بمصفوفة هياكل [`PointF`](../pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة بديل افتراضي. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | يرسم منحنى كاردينال مغلق معرف بمصفوفة هياكل [`Point`](../point/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة بديل افتراضي. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../point/). |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/) باستخدام توتر محدد. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../point/) باستخدام توتر محدد. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/). يبدأ الرسم بإزاحة من بداية المصفوفة. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/) باستخدام توتر محدد. يبدأ الرسم بإزاحة من بداية المصفوفة. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../point/) باستخدام توتر محدد. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | يرسم إهليلجًا محددًا بواسطة هيكل [`Rectangle`](../rectangle/) محيط. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | يرسم إهليلجًا معرفًا بواسطة هيكل [`RectangleF`](../rectanglef/) محيط. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | يرسم إهليلجًا معرفًا بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | يرسم إهليلجًا معرفًا بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage)(Image, Point) | يرسم [`Image`](./image/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_1)(Image, PointF) | يرسم [`Image`](./image/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_2)(Image, PointF[]) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_6)(Image, Point[]) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_10)(Image, Rectangle) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_15)(Image, RectangleF) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_22)(Image, float, float) | يرسم [`Image`](./image/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_20)(Image, int, int) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد بواسطة زوج من الإحداثيات. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | يرسم الجزء المحدد من *image* المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | يرسم [`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بواسطة زوج من الإحداثيات. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | يرسم الصورة المحددة دون تغيير الحجم ويقصها إذا لزم الأمر لتتناسب مع المستطيل المحدد. |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline)(Pen, Point, Point) | يرسم خطًا يربط بين هيكلي [`Point`](../point/). |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | يرسم خطًا يربط بين هيكلي [`PointF`](../pointf/). |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | يرسم خطًا يربط النقطتين المحددتين بأزواج الإحداثيات. |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | يرسم خطًا يربط النقطتين المحددتين بأزواج الإحداثيات. |
| [DrawLines](../../aspose.imaging/graphics/drawlines/#drawlines)(Pen, PointF[]) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هيكلي [`PointF`](../pointf/). |
| [DrawLines](../../aspose.imaging/graphics/drawlines/#drawlines_1)(Pen, Point[]) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هيكلي [`Point`](../point/). |
| [DrawPath](../../aspose.imaging/graphics/drawpath/)(Pen, GraphicsPath) | يرسم [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | يرسم شكل فطيرة معرفًا بقطع ناقص محدد بهيكل [`Rectangle`](../rectangle/) وخطين شعاعيين. |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | يرسم شكل فطيرة معرفًا بقطع ناقص محدد بهيكل [`RectangleF`](../rectanglef/) وخطين شعاعيين. |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | يرسم شكل فطيرة معرفًا بقطع ناقص محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين. |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | يرسم شكل فطيرة معرفًا بقطع ناقص محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | يرسم مضلعًا معرفًا بمصفوفة من هيكلي [`PointF`](../pointf/). |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | يرسم مضلعًا معرفًا بمصفوفة من هيكلي [`Point`](../point/). |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | يرسم مستطيلًا محددًا بهيكل [`Rectangle`](../rectangle/). |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | يرسم مستطيلًا محددًا بهيكل [`RectangleF`](../rectanglef/). |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | يرسم مستطيلًا محددًا بأزواج الإحداثيات، العرض، والارتفاع. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | يرسم مستطيلًا محددًا بأزواج الإحداثيات، العرض، والارتفاع. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | يرسم سلسلة من المستطيلات المحددة بهياكل [`RectangleF`](../rectanglef/). |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | يرسم سلسلة من المستطيلات المحددة بهياكل [`Rectangle`](../rectangle/). |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة. |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | يرسم سلسلة النص المحددة داخل المستطيل المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة. |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة. |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة وبخصائص التنسيق لكائن [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | يرسم سلسلة النص المحددة داخل المستطيل المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة وبخصائص التنسيق لكائن [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة وبخصائص التنسيق لكائن [`StringFormat`](../stringformat/). |
| [EndUpdate](../../aspose.imaging/graphics/endupdate/)() | ينهي تخزين عمليات الرسومات في الذاكرة التي بدأت بعد استدعاء BeginUpdate. سيتم تطبيق عمليات الرسومات السابقة مرة واحدة عند استدعاء هذه الطريقة. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | يملأ داخل منحنى السبلين القسري المغلق المحدد بمصفوفة من هيكلي [`PointF`](../pointf/). يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | يملأ داخل منحنى السبلين القسري المغلق المحدد بمصفوفة من هيكلي [`Point`](../point/). يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | يملأ داخل منحنى السبلين القسري المغلق المحدد بمصفوفة من هيكلي [`PointF`](../pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [`Point`](../point/) باستخدام وضع التعبئة المحدد. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [`PointF`](../pointf/) باستخدام وضع التعبئة والتوتر المحددين. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [`Point`](../point/) باستخدام وضع التعبئة والتوتر المحددين. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بهيكل [`Rectangle`](../rectangle/). |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بهيكل [`RectangleF`](../rectanglef/). |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بزوج من الإحداثيات، عرض، وارتفاع. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بزوج من الإحداثيات، عرض، وارتفاع. |
| [FillPath](../../aspose.imaging/graphics/fillpath/)(Brush, GraphicsPath) | يملأ داخل [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بهيكل [`RectangleF`](../rectanglef/) وخطين شعاعيين. |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بهيكل [`RectangleF`](../rectanglef/) وخطين شعاعيين. |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بزوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بزوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [`PointF`](../pointf/) وAlternate. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [`Point`](../point/) وAlternate. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [`PointF`](../pointf/) باستخدام وضع التعبئة المحدد. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [`Point`](../point/) باستخدام وضع التعبئة المحدد. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | يملأ داخل مستطيل محدد بهيكل [`Rectangle`](../rectangle/). |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | يملأ داخل مستطيل محدد بهيكل [`RectangleF`](../rectanglef/). |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | يملأ داخل مستطيل محدد بزوج من الإحداثيات، عرض وارتفاع. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | يملأ داخل مستطيل محدد بزوج من الإحداثيات، عرض وارتفاع. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | يملأ داخل مجموعة من المستطيلات المحددة بهياكل [`RectangleF`](../rectanglef/). |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | يملأ داخل مجموعة من المستطيلات المحددة بهياكل [`Rectangle`](../rectangle/). |
| [FillRegion](../../aspose.imaging/graphics/fillregion/)(Brush, Region) | يملأ داخل [`Region`](../region/). |
| [MeasureString](../../aspose.imaging/graphics/measurestring/)(string, Font, SizeF, StringFormat) | يقيس سلسلة النص المحددة باستخدام المعلمات المحددة |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform/#multiplytransform)(Matrix) | يضرب الـ[`Matrix`](../matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `Graphics` بالـ[`Matrix`](../matrix/) المحدد عن طريق إلحاق الـ[`Matrix`](../matrix/) المحدد في البداية. |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | يضرب الـ[`Matrix`](../matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `Graphics` بالـ[`Matrix`](../matrix/) المحدد وفقًا للترتيب المحدد. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform/)() | يعيد تعيين خاصية [`Transform`](./transform/) إلى الهوية. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform/#rotatetransform)(float) | يدور التحويل الهندسي المحلي بالمقدار المحدد. تقوم هذه الطريقة بإلحاق الدوران إلى التحويل. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform/#scaletransform)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالمقاسات المحددة. تقوم هذه الطريقة بإلحاق مصفوفة التكبير إلى التحويل. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالمقاسات المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform/#translatetransform)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تقوم هذه الطريقة بإلحاق الإزاحة إلى التحويل. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

## أمثلة

يستخدم هذا المثال فئة Graphics لإنشاء أشكال أولية على سطح Image. لتوضيح العملية، ينشئ المثال صورة جديدة بصيغة PNG ويرسم أشكالًا أولية على سطح Image باستخدام طرق Draw التي توفرها فئة Graphics.

```csharp
[C#]

//ينشئ مثيلًا من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //إنشاء مثيل من PngOptions وتعيين خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //تعيين المصدر لـ PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //إنشاء وتهيئة مثيل من فئة Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //مسح سطح Graphics
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //رسم قوس بتحديد كائن Pen الذي له اللون الأسود،
        //مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //رسم منحنى بيزيير بتحديد كائن Pen الذي له اللون الأزرق ونقاط الإحداثيات.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //رسم منحنى بتحديد كائن Pen الذي له اللون الأخضر ومصفوفة من النقاط
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //رسم إهليلج باستخدام كائن Pen ومستطيل محيط
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //رسم خط
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //رسم قطعة فطيرة
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //رسم مضلع بتحديد كائن Pen الذي له اللون الأحمر ومصفوفة من النقاط
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //رسم مستطيل
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //إنشاء كائن SolidBrush وتعيين خصائصه المتنوعة
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //رسم نص باستخدام كائن SolidBrush والخط، عند نقطة محددة
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


