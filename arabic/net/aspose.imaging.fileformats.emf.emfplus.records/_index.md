---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Aspose.Imaging لمرجع NET API
description: تحتوي مساحة الاسم على أنواع MS-EMFPLUS تنسيق ملف تعريف محسّن بالإضافة إلى الامتدادات 2.3 EMF  Records
type: docs
weight: 390
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/
---
تحتوي مساحة الاسم على أنواع [MS-EMFPLUS]: تنسيق ملف تعريف محسّن بالإضافة إلى الامتدادات 2.3 EMF + Records

## الطبقات

| فصل | وصف |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | يفتح سجل EmfPlusBeginContainer حاوية حالة رسومات جديدة ويحدد تحويلاً لها. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | يفتح سجل EmfPlusBeginContainerNoParams حاوية حالة رسومات جديدة. |
| [EmfPlusClear](./emfplusclear) | يمسح سجل EmfPlusClear مساحة إحداثيات الإخراج ويهيئها بلون الخلفية والشفافية |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | تحدد أنواع سجلات القطع مناطق وعمليات القطع. |
| [EmfPlusComment](./emfpluscomment) | يحدد سجل EmfPlusComment البيانات الخاصة التعسفية. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | تحدد أنواع سجلات التحكم المعلمات العامة لمعالجة ملف تعريف EMF +. |
| [EmfPlusDrawArc](./emfplusdrawarc) | يحدد سجل EmfPlusDrawArc رسم قوس القطع الناقص. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | يحدد سجل EmfPlusDrawBeziers رسم تسلسل منحنيات Bezier المتصلة. ترتيب نقاط بيانات Bezier هو نقطة البداية ونقطة التحكم 1 و نقطة التحكم 2 ونقطة النهاية. لمزيد من المعلومات ، راجع [MSDN-DrawBeziers] . |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | يحدد سجل EmfPlusDrawClosedCurve رسم شريحة أساسية مغلقة |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | يحدد سجل EmfPlusDrawCurve رسم شريحة أساسية ملاحظة: معرف الكائن (1 بايت): فهرس كائن EmfPlusPen (القسم 2.2.1.7) في EMF + Object Table لرسم المنحنى. يجب أن تكون القيمة من صفر إلى 63 ، شاملة . |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | يحدد سجل EmfPlusDrawDriverString إخراج النص بمواضع الأحرف. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | يحدد سجل EmfPlusDrawEllipse رسم قطع ناقص. |
| [EmfPlusDrawImage](./emfplusdrawimage) | يحدد سجل EmfPlusDrawImage رسم صورة بحجم. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | يحدد سجل EmfPlusDrawImagePoints رسم صورة تم قياسها داخل متوازي أضلاع. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | تحدد أنواع سجلات الرسم إخراج الرسومات. |
| [EmfPlusDrawLines](./emfplusdrawlines) | يحدد سجل EmfPlusDrawlLines رسم سلسلة من الخطوط المتصلة |
| [EmfPlusDrawPath](./emfplusdrawpath) | يحدد سجل EmfPlusDrawPath رسم مسار رسومي. |
| [EmfPlusDrawPie](./emfplusdrawpie) | يحدد سجل EmfPlusDrawPie رسم قسم من الجزء الداخلي من القطع الناقص. |
| [EmfPlusDrawRects](./emfplusdrawrects) | يحدد سجل EmfPlusDrawRects رسم سلسلة من المستطيلات |
| [EmfPlusDrawString](./emfplusdrawstring) | يحدد سجل EmfPlusDrawString إخراج النص بتنسيق السلسلة |
| [EmfPlusEndContainer](./emfplusendcontainer) | يغلق سجل EmfPlusEndContainer حاوية حالة رسومات تم فتحها مسبقًا بواسطة عملية حاوية بدء. |
| [EmfPlusEndOfFile](./emfplusendoffile) | يحدد سجل EmfPlusEndOfFile نهاية بيانات EMF + في ملف التعريف. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | يحدد سجل EmfPlusFillClosedCurve ملء الجزء الداخلي من شريحة أساسية مغلقة |
| [EmfPlusFillEllipse](./emfplusfillellipse) | يحدد سجل EmfPlusFillEllipse ملء الجزء الداخلي من القطع الناقص |
| [EmfPlusFillPath](./emfplusfillpath) | Fill path record FLAGS: عدد صحيح بدون إشارة 16 بت يوفر معلومات حول كيفية تنفيذ العملية ، وحول بنية السجل. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 بت): يشير هذا البت إلى نوع البيانات في حقل BrushId . إذا تم تعيينه ، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا تم مسحه ، فإن BrushId يحتوي على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في EMF + Object Table. X (1 بت): محجوز ويجب تجاهله. ObjectId (1 بايت): فهرس كائن EmfPlusPath ( القسم 2.2.1.6) لملء EMF + Object Table. يجب أن تكون القيمة من صفر إلى 63 ، شاملة . |
| [EmfPlusFillPie](./emfplusfillpie) | يحدد سجل EmfPlusFillPie ملء قسم من الجزء الداخلي من القطع الناقص |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | يحدد سجل EmfPlusFillPolygon تعبئة الجزء الداخلي من المضلع. |
| [EmfPlusFillRects](./emfplusfillrects) | يحدد سجل EmfPlusFillRects ملء الأجزاء الداخلية لسلسلة من المستطيلات |
| [EmfPlusFillRegion](./emfplusfillregion) | يحدد سجل EmfPlusFillRegion تعبئة الجزء الداخلي لمنطقة الرسومات |
| [EmfPlusGetDc](./emfplusgetdc) | يحدد سجل EmfPlusGetDC أنه يجب معالجة سجلات EMF اللاحقة التي تمت مواجهتها في ملف التعريف. |
| [EmfPlusHeader](./emfplusheader) | يحدد سجل EmfPlusHeader بداية بيانات EMF + في ملف التعريف. يجب تضمين سجل EmfPlusHeader في سجل EMF EMR_COMMENT_EMFPLUS ، الذي يجب أن يكون السجل الذي يلي مباشرةً رأس EMF في ملف التعريف. تم تحديد سجل EMR_COMMENT_EMFPLUS في قسم [MS-EMF] 2.3.3.2. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | يضاعف سجل EmfPlusMultiplyWorldTransform تحويل الفضاء العالمي الحالي بمصفوفة تحويل محددة. |
| [EmfPlusObject](./emfplusobject) | يحدد سجل EmfPlusObject كائنًا لاستخدامه في عمليات الرسومات. يمكن أن يمتد تعريف الكائن إلى سجلات متعددة ، والتي يشار إليها بقيمة حقل الإشارات. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | تعرف أنواع سجلات الكائن الكائنات الرسومية التي يمكن إعادة استخدامها. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | يطبق سجل EmfPlusOffsetClip تحويل ترجمة على منطقة القطع الحالية لمساحة العالم. يتم تعيين منطقة القطع الحالية الجديدة على نتيجة تحويل الترجمة. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | تحدد أنواع سجلات الخاصية خصائص سياق جهاز التشغيل. |
| [EmfPlusRecord](./emfplusrecord) | نوع السجل الأساسي Emf + . |
| [EmfPlusResetClip](./emfplusresetclip) | يعيد سجل EmfPlusResetClip تعيين منطقة القطع الحالية لمساحة العالم إلى ما لا نهاية. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | يقوم سجل EmfPlusResetWorldTransform بإعادة تعيين تحويل الفضاء العالمي الحالي إلى مصفوفة التعريف. |
| [EmfPlusRestore](./emfplusrestore) | يستعيد سجل EmfPlusRestore حالة الرسومات ، التي تم تحديدها بواسطة فهرس محدد ، من مجموعة من حالات الرسومات المحفوظة. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | يقوم سجل EmfPlusRotateWorldTransform بإجراء دوران على تحويل الفضاء العالمي الحالي. |
| [EmfPlusSave](./emfplussave) | يحفظ سجل EmfPlusSave حالة الرسومات ، التي تم تحديدها بواسطة فهرس محدد ، على مجموعة من حالات الرسومات المحفوظة. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | يقوم سجل EmfPlusScaleWorldTransform بإجراء قياس على تحويل الفضاء العالمي الحالي. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | يحدد سجل EmfPlusSerializableObject كتلة معلمة تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات مؤقت. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | يحدد سجل EmfPlusSetAntiAliasMode وضع الصقل لإخراج النص. |
| [EmfPlusSetClipPath](./emfplussetclippath) | يدمج سجل EmfPlusSetClipPath منطقة القطع الحالية مع مسار الرسوم . تم تعيين منطقة القطع الحالية الجديدة على نتيجة عملية CombineMode. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | يدمج سجل EmfPlusSetClipRect منطقة القطع الحالية مع مستطيل. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | يدمج سجل EmfPlusSetClipRegion منطقة القطع الحالية مع منطقة رسومات أخرى . تم تعيين منطقة القطع الحالية الجديدة على نتيجة تنفيذ عملية CombineMode on منطقة القطع الحالية السابقة وكائن EmfPlusRegion المحدد. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | يحدد سجل EmfPlusSetCompositingMode كيفية دمج ألوان المصدر مع ألوان الخلفية. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | يحدد سجل EmfPlusSetCompositingQuality مستوى الجودة المطلوب لإنشاء صور مركبة من كائنات متعددة. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | يحدد سجل EmfPlusSetInterpolationMode كيفية إجراء قياس الصورة ، بما في ذلك التمدد والانكماش. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | يحدد سجل EmfPlusSetPageTransform عوامل القياس والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | يحدد سجل EmfPlusSetPixelOffsetMode كيفية توسيط البكسل فيما يتعلق بإحداثيات سطح الرسم. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | يحدد سجل EmfPlusSetRenderingOrigin أصل العرض لإخراج الرسومات. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | يحدد سجل EmfPlusSetTextContrast تباين النص وفقًا لقيمة تصحيح جاما. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | يحدد سجل EmfPlusSetTextRenderingHint جودة عرض النص ، بما في ذلك نوع الصقل. |
| [EmfPlusSetTsClip](./emfplussettsclip) | يحدد سجل EmfPlusSetTSClip مناطق القطع في سياق جهاز الرسومات لوحدة خدمة المحطة الطرفية. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | يحدد سجل EmfPlusSetTSGraphics حالة سياق جهاز الرسومات لوحدة خدمة المحطة الطرفية. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | يحدد سجل EmfPlusSetWorldTransform تحويل العالم وفقًا للقيم الموجودة في مصفوفة التحويل المحددة. |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | تحدد أنواع سجلات الحالة العمليات على حالة سياق جهاز التشغيل. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | تحدد أنواع سجلات الخادم الطرفي معالجة الرسومات على خادم طرفي. التالية هي أنواع سجلات خادم المحطة الطرفية + EMF. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | تحدد أنواع سجلات التحويل الخصائص والتحويلات على مسافات الإحداثيات. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | يقوم سجل EmfPlusTranslateWorldTransform بترجمة تحويل الفضاء العالمي الحالي. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
