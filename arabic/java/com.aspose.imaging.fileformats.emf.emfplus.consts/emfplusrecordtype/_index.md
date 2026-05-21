---
title: "EmfPlusRecordType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد تعداد RecordType أنواع السجلات المستخدمة في ملفات EMF الوصفية."
type: docs
weight: 45
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

تحدد تعداد RecordType أنواع السجلات المستخدمة في ملفات EMF+ الوصفية.
## الحقول

| حقل | الوصف |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | هذا السجل يحدد بداية بيانات EMF+ في الملف الوصفي. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | هذا السجل يحدد نهاية بيانات EMF+ في الملف الوصفي. |
| [EmfPlusComment](#EmfPlusComment) | هذا السجل يحدد بيانات خاصة عشوائية. |
| [EmfPlusGetDC](#EmfPlusGetDC) | هذا السجل يحدد أنه يجب معالجة سجلات EMF اللاحقة التي يتم مواجهتها في الملف الوصفي. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | هذا السجل محجوز ولا يجوز استخدامه. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | هذا السجل محجوز ولا يجوز استخدامه. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | هذا السجل محجوز ولا يجوز استخدامه. |
| [EmfPlusObject](#EmfPlusObject) | هذا السجل يحدد كائنًا للاستخدام في عمليات الرسومات. |
| [EmfPlusClear](#EmfPlusClear) | هذا السجل يمسح `coordinate space` الناتج ويُهيئه بلون خلفية محدد وشفافية. |
| [EmfPlusFillRects](#EmfPlusFillRects) | هذا السجل يحدد كيفية ملء داخليات سلسلة من المستطيلات باستخدام فرشاة محددة. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | هذا السجل يحدد خطوط القلم لرسم سلسلة من المستطيلات. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | هذا السجل يحدد البيانات لملء داخلية مضلع باستخدام فرشاة محددة. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | هذا السجل يحدد خطوط القلم لرسم سلسلة من الخطوط المتصلة. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | هذا السجل يحدد كيفية ملء داخليات إهليلج باستخدام فرشاة محددة. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | هذا السجل يحدد خطوط القلم لرسم إهليلج. |
| [EmfPlusFillPie](#EmfPlusFillPie) | يحدد هذا السجل كيفية ملء جزء من قسم داخلي لبيضاوي باستخدام فرشاة محددة. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | يحدد هذا السجل ضربات القلم لرسم جزء من بيضاوي. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | يحدد السجل ضربات القلم لرسم قوس من بيضاوي. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | يحدد هذا السجل كيفية ملء داخل منطقة باستخدام فرشاة محددة. |
| [EmfPlusFillPath](#EmfPlusFillPath) | يحدد السجل كيفية ملء داخل الأشكال المعرفة في مسار رسومي باستخدام فرشاة محددة. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | يحدد السجل ضربات القلم لرسم الأشكال في مسار رسومي. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | يحدد هذا السجل كيفية ملء داخل منحنى كاردينال مغلق باستخدام فرشاة محددة. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | يحدد هذا السجل القلم والضربات لرسم منحنى كاردينال مغلق. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | يحدد هذا السجل ضربات القلم لرسم منحنى كاردينال. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | يحدد هذا السجل ضربات القلم لرسم منحنى بيزيه. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | يحدد هذا السجل كائن [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) مُقاس (القسم 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | يحدد هذا السجل كائن EmfPlusImage مُقاس داخل متوازي أضلاع. |
| [EmfPlusDrawString](#EmfPlusDrawString) | يحدد هذا السجل سلسلة نصية بناءً على خط، ومستطيل تخطيط، وتنسيق. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | يحدد هذا السجل أصل العرض إلى الإحداثيات الأفقية والعمودية المحددة. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | يحدد هذا السجل ما إذا كان سيتم تمكين أو تعطيل تنعيم النص. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | يحدد هذا السجل العملية المستخدمة لعرض النص. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | يضبط هذا السجل تباين النص وفقًا لقيمة غاما النص المحددة. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | يحدد هذا السجل وضع الاستيفاء لكائن وفقًا لنوع تصفية الصورة المحدد. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | يحدد هذا السجل وضع إزاحة البكسل وفقًا لقيمة تمركز البكسل المحددة. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | يحدد هذا السجل وضع التركيب وفقًا لحالة دمج ألفا، الذي يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | يحدد هذا السجل جودة التركيب، التي تصف المستوى المطلوب للجودة لإنشاء صور مركبة من كائنات متعددة. |
| [EmfPlusSave](#EmfPlusSave) | يحفظ هذا السجل حالة الرسومات، المحددة بواسطة فهرس معين، على مكدس من حالات الرسومات المحفوظة. |
| [EmfPlusRestore](#EmfPlusRestore) | يستعيد هذا السجل حالة الرسومات، المحددة بواسطة فهرس معين، من مكدس حالات الرسومات المحفوظة. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | يفتح هذا السجل حاوية حالة رسومات جديدة ويحدد تحويلًا لها. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | يفتح هذا السجل حاوية حالة رسومات جديدة. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | يقوم هذا السجل بإغلاق حاوية حالة الرسومات التي تم فتحها مسبقًا بواسطة عملية بدء الحاوية. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | يقوم هذا السجل بتعريف تحويل الفضاء العالمي الحالي في سياق جهاز التشغيل\_context، وفقًا لمصفوفة تحويل محددة. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | يقوم هذا السجل بإعادة تعيين تحويل الفضاء العالمي الحالي إلى مصفوفة الهوية. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | يقوم هذا السجل بضرب الفضاء العالمي الحالي في مصفوفة تحويل محددة. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | يقوم هذا السجل بتطبيق تحويل إزاحة على الفضاء العالمي الحالي بمسافات أفقية ورأسية محددة. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | يقوم هذا السجل بتطبيق تحويل تكبير/تصغير على الفضاء العالمي الحالي بعوامل مقياس أفقية ورأسية محددة. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | يقوم هذا السجل بتدوير الفضاء العالمي الحالي بزاوية محددة. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | يحدد هذا السجل عوامل تكبير إضافية لتحويل الفضاء العالمي الحالي. |
| [EmfPlusResetClip](#EmfPlusResetClip) | يقوم هذا السجل بإعادة تعيين منطقة القطع الحالية للفضاء العالمي إلى ما لا نهائي. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | يقوم هذا السجل بدمج منطقة القطع الحالية مع مستطيل. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | يقوم هذا السجل بدمج منطقة القطع الحالية مع مسار رسومي. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | يقوم هذا السجل بدمج منطقة القطع الحالية مع منطقة رسومية أخرى. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | يقوم هذا السجل بتطبيق تحويل إزاحة على منطقة القطع الحالية للفضاء العالمي. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | يحدد هذا السجل إخراج النص مع مواضع الأحرف. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | هذا السجل يغلق أي أشكال مفتوحة في مسار، يرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | يعرف هذا السجل كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | يحدد هذا السجل حالة سياق جهاز الرسومات لخادم الطرفية. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | يحدد هذا السجل مناطق القطع في سياق جهاز الرسومات لخادم الطرفية. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


يحدد هذا السجل بداية بيانات EMF+ في ملف التعريف. يجب تضمينه في أول سجل EMF بعد سجل [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) ([MS-EMF] القسم 2.3.4.2).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


هذا السجل يحدد نهاية بيانات EMF+ في الملف الوصفي.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


هذا السجل يحدد بيانات خاصة عشوائية.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


يحدد هذا السجل أن سجلات EMF اللاحقة التي يتم مواجهتها في ملف التعريف يجب معالجتها. تتوقف معالجة سجلات EMF عندما يتم العثور على سجل EMF+ التالي.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


هذا السجل محجوز ولا يجوز استخدامه.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


هذا السجل محجوز ولا يجوز استخدامه.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


هذا السجل محجوز ولا يجوز استخدامه.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


هذا السجل يحدد كائنًا للاستخدام في عمليات الرسومات.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


هذا السجل يمسح `coordinate space` الناتج ويُهيئه بلون خلفية محدد وشفافية.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


هذا السجل يحدد كيفية ملء داخليات سلسلة من المستطيلات باستخدام فرشاة محددة.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


هذا السجل يحدد خطوط القلم لرسم سلسلة من المستطيلات.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


هذا السجل يحدد البيانات لملء داخلية مضلع باستخدام فرشاة محددة.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


هذا السجل يحدد خطوط القلم لرسم سلسلة من الخطوط المتصلة.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


هذا السجل يحدد كيفية ملء داخليات إهليلج باستخدام فرشاة محددة.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


هذا السجل يحدد خطوط القلم لرسم إهليلج.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


يحدد هذا السجل كيفية ملء جزء من قسم داخلي لبيضاوي باستخدام فرشاة محددة.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


يحدد هذا السجل ضربات القلم لرسم جزء من بيضاوي.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


يحدد السجل ضربات القلم لرسم قوس من بيضاوي.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


يحدد هذا السجل كيفية ملء داخل منطقة باستخدام فرشاة محددة.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


يحدد السجل كيفية ملء داخل الأشكال المعرفة في مسار رسومي بفرشاة محددة. المسار هو كائن يحدد تسلسلًا عشوائيًا من الخطوط والمنحنيات والأشكال.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


يحدد السجل ضربات القلم لرسم الأشكال في مسار رسومي. المسار هو كائن يحدد تسلسلًا عشوائيًا من الخطوط والمنحنيات والأشكال.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


يحدد هذا السجل كيفية ملء داخل منحنى كاردينال مغلق باستخدام فرشاة محددة.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


يحدد هذا السجل القلم والضربات لرسم منحنى كاردينال مغلق.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


يحدد هذا السجل ضربات القلم لرسم منحنى كاردينال.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


يحدد هذا السجل ضربات القلم لرسم منحنى بيزيه.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


يحدد هذا السجل كائن [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) مُقاس (القسم 2.2.1.4). يمكن أن تتكون الصورة من بيانات بت ماب أو ملف تعريف.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


يحدد هذا السجل كائن EmfPlusImage مُقاس داخل متوازي أضلاع. يمكن أن تتكون الصورة من بيانات بت ماب أو ملف تعريف.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


يحدد هذا السجل سلسلة نصية بناءً على خط، ومستطيل تخطيط، وتنسيق.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


يحدد هذا السجل أصل العرض إلى الإحداثيات الأفقية والرأسية المحددة. ينطبق ذلك على فرشاة التهشير وأنماط التمويه ذات 8 و16 بت لكل بكسل.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


يحدد هذا السجل ما إذا كان سيتم تمكين أو تعطيل تنعيم النص. تنعيم النص هو طريقة لجعل خطوط وحواف رموز الأحرف تبدو أكثر سلاسة عند رسمها على سطح الإخراج.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


يحدد هذا السجل العملية المستخدمة لعرض النص.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


يضبط هذا السجل تباين النص وفقًا لقيمة غاما النص المحددة.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


تحدد هذه السجيلة وضع الاستيفاء لكائن وفقًا لنوع تصفية الصورة المحدد. يؤثر وضع الاستيفاء على كيفية تنفيذ التحجيم (التمدد والتقليص).

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


يحدد هذا السجل وضع إزاحة البكسل وفقًا لقيمة تمركز البكسل المحددة.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


يحدد هذا السجل وضع التركيب وفقًا لحالة دمج ألفا، الذي يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


يحدد هذا السجل جودة التركيب، التي تصف المستوى المطلوب للجودة لإنشاء صور مركبة من كائنات متعددة.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


تقوم هذه السجيلة بحفظ حالة الرسومات، التي يتم التعرف عليها بواسطة فهرس محدد، على مكدس من حالات الرسومات المحفوظة. كل فهرس في المكدس مرتبط بحالة محفوظة معينة، ويُستخدم الفهرس بواسطة سجل [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) (القسم 2.3.7.4) لاستعادة الحالة.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


تستعيد هذه السجيلة حالة الرسومات، التي يتم التعرف عليها بواسطة فهرس محدد، من مكدس حالات الرسومات المحفوظة. كل فهرس في المكدس مرتبط بحالة محفوظة معينة، ويُعرّف الفهرس بواسطة سجل [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) (القسم 2.3.7.5) لحفظ الحالة.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


تفتح هذه السجيلة حاوية حالة رسومات جديدة وتحدد تحويلًا لها. تُستخدم حاويات الرسومات للاحتفاظ بعناصر حالة الرسومات.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


يفتح هذا السجل حاوية حالة رسومات جديدة.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


يقوم هذا السجل بإغلاق حاوية حالة الرسومات التي تم فتحها مسبقًا بواسطة عملية بدء الحاوية.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


يقوم هذا السجل بتعريف تحويل الفضاء العالمي الحالي في سياق جهاز التشغيل\_context، وفقًا لمصفوفة تحويل محددة.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


يقوم هذا السجل بإعادة تعيين تحويل الفضاء العالمي الحالي إلى مصفوفة الهوية.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


يقوم هذا السجل بضرب الفضاء العالمي الحالي في مصفوفة تحويل محددة.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


يقوم هذا السجل بتطبيق تحويل إزاحة على الفضاء العالمي الحالي بمسافات أفقية ورأسية محددة.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


يقوم هذا السجل بتطبيق تحويل تكبير/تصغير على الفضاء العالمي الحالي بعوامل مقياس أفقية ورأسية محددة.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


يقوم هذا السجل بتدوير الفضاء العالمي الحالي بزاوية محددة.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


يحدد هذا السجل عوامل تكبير إضافية لتحويل الفضاء العالمي الحالي.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


يقوم هذا السجل بإعادة تعيين منطقة القطع الحالية للفضاء العالمي إلى ما لا نهائي.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


يقوم هذا السجل بدمج منطقة القطع الحالية مع مستطيل.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


يقوم هذا السجل بدمج منطقة القطع الحالية مع مسار رسومي.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


يقوم هذا السجل بدمج منطقة القطع الحالية مع منطقة رسومية أخرى.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


يقوم هذا السجل بتطبيق تحويل إزاحة على منطقة القطع الحالية للفضاء العالمي.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


يحدد هذا السجل إخراج النص مع مواضع الأحرف.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


هذا السجل يغلق أي أشكال مفتوحة في مسار، يرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


يعرف هذا السجل كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


يحدد هذا السجل حالة سياق جهاز الرسومات لخادم الطرفية.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


يحدد هذا السجل مناطق القطع في سياق جهاز الرسومات لخادم الطرفية.

