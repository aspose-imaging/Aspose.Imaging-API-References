---
title: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records"
second_title: "Aspose.Imaging for .NET API Reference"
description: "المساحة الاسمية تحتوي على الأنواع MSEMFPLUS Enhanced Metafile Format Plus Extensions 2.3 EMF Records"
type: docs
weight: 430
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/
---
مساحة الأسماء تحتوي على الأنواع [MS-EMFPLUS]: Enhanced Metafile Format Plus Extensions 2.3 EMF+ Records

## الفئات

| الفئة | الوصف |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer/) | سجل EmfPlusBeginContainer يفتح حاوية حالة رسومية جديدة ويحدد تحويلًا لها. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams/) | سجل EmfPlusBeginContainerNoParams يفتح حاوية حالة رسومية جديدة. |
| [EmfPlusClear](./emfplusclear/) | سجل EmfPlusClear يمسح مساحة الإحداثيات الناتجة ويهيئها بلون خلفية وشفافية. |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype/) | أنواع سجلات القص تحدد مناطق القص والعمليات. |
| [EmfPlusComment](./emfpluscomment/) | سجل EmfPlusComment يحدد بيانات خاصة عشوائية. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype/) | أنواع سجلات التحكم تحدد المعلمات العامة لمعالجة ملفات EMF+ الوصفية. |
| [EmfPlusDrawArc](./emfplusdrawarc/) | سجل EmfPlusDrawArc يحدد رسم قوس من إهليلج. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers/) | سجل EmfPlusDrawBeziers يحدد رسم تسلسل من المنحنيات البيزية المتصلة. ترتيب نقاط بيانات البيزية هو نقطة البداية، نقطة التحكم الأولى، نقطة التحكم الثانية ونقطة النهاية. لمزيد من المعلومات راجع [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve/) | سجل EmfPlusDrawClosedCurve يحدد رسم منحنى كاردينال مغلق. |
| [EmfPlusDrawCurve](./emfplusdrawcurve/) | سجل EmfPlusDrawCurve يحدد رسم منحنى كاردينال. ملاحظة: ObjectID (بايت واحد): فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring/) | سجل EmfPlusDrawDriverString يحدد إخراج النص مع مواضع الأحرف. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse/) | سجل EmfPlusDrawEllipse يحدد رسم إهليلج. |
| [EmfPlusDrawImage](./emfplusdrawimage/) | سجل EmfPlusDrawImage يحدد رسم صورة مُقاسة. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints/) | سجل EmfPlusDrawImagePoints يحدد رسم صورة مُقاسة داخل متوازي أضلاع. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype/) | أنواع سجلات الرسم تحدد مخرجات الرسومات. |
| [EmfPlusDrawLines](./emfplusdrawlines/) | سجل EmfPlusDrawlLines يحدد رسم سلسلة من الخطوط المتصلة. |
| [EmfPlusDrawPath](./emfplusdrawpath/) | سجل EmfPlusDrawPath يحدد رسم مسار رسومي. |
| [EmfPlusDrawPie](./emfplusdrawpie/) | سجل EmfPlusDrawPie يحدد رسم جزء من داخل إهليلج. |
| [EmfPlusDrawRects](./emfplusdrawrects/) | سجل EmfPlusDrawRects يحدد رسم سلسلة من المستطيلات. |
| [EmfPlusDrawString](./emfplusdrawstring/) | سجل EmfPlusDrawString يحدد إخراج النص مع تنسيق السلسلة. |
| [EmfPlusEndContainer](./emfplusendcontainer/) | سجل EmfPlusEndContainer يغلق حاوية حالة رسومية تم فتحها مسبقًا بواسطة عملية بدء الحاوية. |
| [EmfPlusEndOfFile](./emfplusendoffile/) | سجل EmfPlusEndOfFile يحدد نهاية بيانات EMF+ في الملف الوصفي. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve/) | سجل EmfPlusFillClosedCurve يحدد تعبئة داخل منحنى كاردينال مغلق. |
| [EmfPlusFillEllipse](./emfplusfillellipse/) | سجل EmfPlusFillEllipse يحدد تعبئة داخل إهليلج. |
| [EmfPlusFillPath](./emfplusfillpath/) | سجل تعبئة المسار FLAGS: عدد صحيح غير موقع 16-بت يوفر معلومات حول كيفية تنفيذ العملية، وعن بنية السجل. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X &#x7C; ObjectId &#x7C; S (بت واحد): هذه البت تشير إلى نوع البيانات في حقل BrushId. إذا تم تعيينها، فإن BrushId يحدد لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا كانت غير مفعلة، فإن BrushId يحتوي على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. X (بت واحد): محجوز ويجب تجاهله. ObjectId (بايت واحد): فهرس كائن EmfPlusPath (القسم 2.2.1.6) للتعبئة، في جدول كائنات EMF+. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| [EmfPlusFillPie](./emfplusfillpie/) | سجل EmfPlusFillPie يحدد تعبئة جزء من داخل إهليلج. |
| [EmfPlusFillPolygon](./emfplusfillpolygon/) | السجل EmfPlusFillPolygon يحدد تعبئة داخل مضلع. |
| [EmfPlusFillRects](./emfplusfillrects/) | السجل EmfPlusFillRects يحدد تعبئة داخل مجموعة من المستطيلات. |
| [EmfPlusFillRegion](./emfplusfillregion/) | السجل EmfPlusFillRegion يحدد تعبئة داخل منطقة رسومية. |
| [EmfPlusGetDc](./emfplusgetdc/) | السجل EmfPlusGetDC يحدد أنه يجب معالجة سجلات EMF اللاحقة التي تُعثر عليها في ملف التعريف. |
| [EmfPlusHeader](./emfplusheader/) | السجل EmfPlusHeader يحدد بداية بيانات EMF+ في ملف التعريف. يجب أن يكون السجل EmfPlusHeader مضمنًا في سجل EMF EMR_COMMENT_EMFPLUS، والذي يجب أن يكون السجل التالي مباشرةً بعد رأس EMF في ملف التعريف. يتم تحديد سجل EMR_COMMENT_EMFPLUS في القسم 2.3.3.2 من [MS-EMF]. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform/) | السجل EmfPlusMultiplyWorldTransform يضرب التحويل الحالي للفضاء العالمي بمصفوفة تحويل محددة. |
| [EmfPlusObject](./emfplusobject/) | السجل EmfPlusObject يحدد كائنًا للاستخدام في عمليات الرسوميات. يمكن أن تمتد تعريفات الكائن عبر سجلات متعددة، وهو ما يُشير إليه قيمة حقل Flags. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype/) | أنواع سجلات الكائن تُعرّف كائنات رسومية قابلة لإعادة الاستخدام. |
| [EmfPlusOffsetClip](./emfplusoffsetclip/) | السجل EmfPlusOffsetClip يطبق تحويل إزاحة على منطقة القص الحالية للفضاء العالمي. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة تحويل الإزاحة. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype/) | أنواع سجلات الخصائص تحدد خصائص سياق جهاز التشغيل. |
| [EmfPlusRecord](./emfplusrecord/) | نوع السجل الأساسي Emf+. |
| [EmfPlusResetClip](./emfplusresetclip/) | السجل EmfPlusResetClip يعيد تعيين منطقة القص الحالية للفضاء العالمي إلى اللانهاية. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform/) | السجل EmfPlusResetWorldTransform يعيد تعيين التحويل الحالي للفضاء العالمي إلى مصفوفة الهوية. |
| [EmfPlusRestore](./emfplusrestore/) | السجل EmfPlusRestore يستعيد حالة الرسوميات، المحددة بواسطة فهرس معين، من مكدس حالات الرسوميات المحفوظة. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform/) | السجل EmfPlusRotateWorldTransform يُجري دورانًا على التحويل الحالي للفضاء العالمي. |
| [EmfPlusSave](./emfplussave/) | السجل EmfPlusSave يحفظ حالة الرسوميات، المحددة بواسطة فهرس معين، على مكدس حالات الرسوميات المحفوظة. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform/) | السجل EmfPlusScaleWorldTransform يُجري تحجيمًا على التحويل الحالي للفضاء العالمي. |
| [EmfPlusSerializableObject](./emfplusserializableobject/) | السجل EmfPlusSerializableObject يعرّف كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode/) | السجل EmfPlusSetAntiAliasMode يحدد وضع مكافحة التعرجات لإخراج النص. |
| [EmfPlusSetClipPath](./emfplussetclippath/) | السجل EmfPlusSetClipPath يجمع منطقة القص الحالية مع مسار رسومي. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة عملية CombineMode. |
| [EmfPlusSetClipRect](./emfplussetcliprect/) | السجل EmfPlusSetClipRect يجمع منطقة القص الحالية مع مستطيل. |
| [EmfPlusSetClipRegion](./emfplussetclipregion/) | السجل EmfPlusSetClipRegion يجمع منطقة القص الحالية مع منطقة رسومية أخرى. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة عملية CombineMode على منطقة القص الحالية السابقة والكائن EmfPlusRegion المحدد. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode/) | السجل EmfPlusSetCompositingMode يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality/) | السجل EmfPlusSetCompositingQuality يحدد مستوى الجودة المطلوب لإنشاء صور مركبة من كائنات متعددة. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode/) | السجل EmfPlusSetInterpolationMode يحدد كيفية تنفيذ تحجيم الصورة، بما في ذلك التمدد والتقليص. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform/) | سجل EmfPlusSetPageTransform يحدد عوامل التحجيم والوحدات لتحويل إحداثيات مساحة الصفحة إلى إحداثيات مساحة الجهاز. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode/) | سجل EmfPlusSetPixelOffsetMode يحدد كيفية تمركز البكسلات بالنسبة لإحداثيات سطح الرسم. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin/) | سجل EmfPlusSetRenderingOrigin يحدد أصل العرض لإخراج الرسومات. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast/) | سجل EmfPlusSetTextContrast يحدد تباين النص وفقًا لقيمة تصحيح غاما. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint/) | سجل EmfPlusSetTextRenderingHint يحدد جودة عرض النص، بما في ذلك نوع مضاد التعرجات. |
| [EmfPlusSetTsClip](./emfplussettsclip/) | سجل EmfPlusSetTSClip يحدد مناطق القص في سياق جهاز الرسومات لخادم الطرفية. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics/) | سجل EmfPlusSetTSGraphics يحدد حالة سياق جهاز الرسومات لخادم الطرفية. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform/) | سجل EmfPlusSetWorldTransform يضبط تحويل العالم وفقًا للقيم الموجودة في مصفوفة التحويل المحددة. |
| [EmfPlusStateRecordType](./emfplusstaterecordtype/) | أنواع سجلات الحالة تحدد العمليات على حالة سياق جهاز التشغيل. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype/) | أنواع سجلات خادم الطرفية تحدد معالجة الرسومات على خادم الطرفية. الأنواع التالية هي سجلات خادم الطرفية EMF+. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype/) | أنواع سجلات التحويل تحدد الخصائص والتحويلات على مساحات الإحداثيات. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform/) | سجل EmfPlusTranslateWorldTransform ينفذ ترجمة على تحويل مساحة العالم الحالية. |


