---
title: "EmfPlusRecordType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد RecordType أنواع السجلات المستخدمة في ملفات EMF الميتا."
type: docs
weight: 45
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

تحدد تعداد RecordType أنواع السجلات المستخدمة في ملفات EMF+ الميتا.
## الحقول

| حقل | الوصف |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | يحدد هذا السجل بداية بيانات EMF+ في الملف الميتا. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | يحدد هذا السجل نهاية بيانات EMF+ في الملف الميتا. |
| [EmfPlusComment](#EmfPlusComment) | يحدد هذا السجل بيانات خاصة عشوائية. |
| [EmfPlusGetDC](#EmfPlusGetDC) | يحدد هذا السجل أنه يجب معالجة سجلات EMF اللاحقة التي يتم العثور عليها في الملف الميتا. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | هذا السجل محجوز ولا يجوز استخدامه. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | هذا السجل محجوز ولا يجوز استخدامه. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | هذا السجل محجوز ولا يجوز استخدامه. |
| [EmfPlusObject](#EmfPlusObject) | هذا السجل يحدد كائنًا للاستخدام في عمليات الرسومات. |
| [EmfPlusClear](#EmfPlusClear) | هذا السجل يمسح مساحة الإحداثيات `coordinate space` الناتجة ويُهيئها بلون خلفية محدد وشفافية. |
| [EmfPlusFillRects](#EmfPlusFillRects) | هذا السجل يحدد كيفية ملء داخليات سلسلة من المستطيلات باستخدام فرشاة محددة. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | هذا السجل يحدد خطوط القلم لرسم سلسلة من المستطيلات. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | هذا السجل يحدد البيانات لملء داخلية مضلع باستخدام فرشاة محددة. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | هذا السجل يحدد خطوط القلم لرسم سلسلة من الخطوط المتصلة. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | هذا السجل يحدد كيفية ملء داخليات إهليلج باستخدام فرشاة محددة. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | هذا السجل يحدد خطوط القلم لرسم إهليلج. |
| [EmfPlusFillPie](#EmfPlusFillPie) | هذا السجل يحدد كيفية ملء جزء من داخل إهليلج باستخدام فرشاة محددة. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | هذا السجل يحدد خطوط القلم لرسم جزء من إهليلج. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | السجل يحدد خطوط القلم لرسم قوس من إهليلج. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | هذا السجل يحدد كيفية ملء داخلية منطقة باستخدام فرشاة محددة. |
| [EmfPlusFillPath](#EmfPlusFillPath) | السجل يحدد كيفية ملء داخليات الأشكال المعرفة في مسار رسومي باستخدام فرشاة محددة. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | السجل يحدد خطوط القلم لرسم الأشكال في مسار رسومي. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | هذا السجل يحدد كيفية ملء داخلية منحنى كاردينال مغلق باستخدام فرشاة محددة. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | هذا السجل يحدد القلم والخطوط لرسم منحنى كاردينال مغلق. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | هذا السجل يحدد خطوط القلم لرسم منحنى كاردينال. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | هذا السجل يحدد خطوط القلم لرسم منحنى بيزيه. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | هذا السجل يحدد كائن [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) مقاس (القسم 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | هذا السجل يحدد كائن EmfPlusImage مقاس داخل متوازي أضلاع. |
| [EmfPlusDrawString](#EmfPlusDrawString) | هذا السجل يحدد سلسلة نصية بناءً على خط، ومستطيل تخطيط، وتنسيق. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | هذا السجل يحدد أصل العرض إلى الإحداثيات الأفقية والرأسية المحددة. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | هذا السجل يحدد ما إذا كان سيتم تمكين أو تعطيل تنعيم النص. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | هذا السجل يحدد العملية المستخدمة لعرض النص. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | هذا السجل يضبط تباين النص وفقًا لقيمة غاما النص المحددة. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | تحدد هذه السجل وضع الاستيفاء لكائن وفقًا لنوع تصفية الصورة المحدد. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | تحدد هذه السجل وضع إزاحة البكسل وفقًا لقيمة تمركز البكسل المحددة. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | تحدد هذه السجل وضع التركيب وفقًا لحالة المزج ألفا، الذي يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | تحدد هذه السجل جودة التركيب، التي تصف مستوى الجودة المطلوب لإنشاء صور مركبة من عدة كائنات. |
| [EmfPlusSave](#EmfPlusSave) | تحفظ هذه السجل حالة الرسومات، المحددة بواسطة فهرس محدد، على مكدس من حالات الرسومات المحفوظة. |
| [EmfPlusRestore](#EmfPlusRestore) | تستعيد هذه السجل حالة الرسومات، المحددة بواسطة فهرس محدد، من مكدس حالات الرسومات المحفوظة. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | يفتح هذه السجل حاوية حالة رسومات جديدة ويحدد تحويلًا لها. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | يفتح هذه السجل حاوية حالة رسومات جديدة. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | يغلق هذه السجل حاوية حالة رسومات تم فتحها مسبقًا بواسطة عملية بدء الحاوية. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | تحدد هذه السجل تحويل الفضاء العالمي الحالي في playback device\_context، وفقًا لمصفوفة تحويل محددة. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | تعيد هذه السجل ضبط تحويل الفضاء العالمي الحالي إلى مصفوفة الهوية. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | تضرب هذه السجل الفضاء العالمي الحالي بمصفوفة تحويل محددة. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | تطبق هذه السجل تحويل إزاحة على الفضاء العالمي الحالي بمسافات أفقية ورأسية محددة. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | تطبق هذه السجل تحويل تكبير على الفضاء العالمي الحالي بعوامل تكبير أفقية ورأسية محددة. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | تدور هذه السجل الفضاء العالمي الحالي بزاوية محددة. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | تحدد هذه السجل عوامل تكبير إضافية لتحويل الفضاء العالمي الحالي. |
| [EmfPlusResetClip](#EmfPlusResetClip) | تعيد هذه السجل ضبط منطقة القص الحالية للفضاء العالمي إلى ما لا نهاية. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | تدمج هذه السجل منطقة القص الحالية مع مستطيل. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | تدمج هذه السجل منطقة القص الحالية مع مسار رسومي. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | تدمج هذه السجل منطقة القص الحالية مع منطقة رسومية أخرى. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | تطبق هذه السجل تحويل إزاحة على منطقة القص الحالية للفضاء العالمي. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | تحدد هذه السجل إخراج النص مع مواضع الأحرف. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | هذا السجل يغلق أي أشكال مفتوحة في مسار، ويرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | تحدد هذه السجل كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | تحدد هذه السجل حالة سياق جهاز الرسومات لخادم طرفي. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | تحدد هذه السجل مناطق القص في سياق جهاز الرسومات لخادم طرفي. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


هذا السجل يحدد بداية بيانات EMF+ في ملف التعريف. يجب أن يكون مدمجًا في السجل EMF الأول بعد سجل [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) ([MS-EMF] القسم 2.3.4.2).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


يحدد هذا السجل نهاية بيانات EMF+ في الملف الميتا.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


يحدد هذا السجل بيانات خاصة عشوائية.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


هذا السجل يحدد أنه يجب معالجة سجلات EMF اللاحقة التي تُعثر عليها في ملف التعريف. تتوقف معالجة سجلات EMF عندما يُعثر على سجل EMF+ التالي.

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


هذا السجل يمسح مساحة الإحداثيات `coordinate space` الناتجة ويُهيئها بلون خلفية محدد وشفافية.

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


هذا السجل يحدد كيفية ملء جزء من داخل إهليلج باستخدام فرشاة محددة.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


هذا السجل يحدد خطوط القلم لرسم جزء من إهليلج.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


السجل يحدد خطوط القلم لرسم قوس من إهليلج.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


هذا السجل يحدد كيفية ملء داخلية منطقة باستخدام فرشاة محددة.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


السجل يحدد كيفية ملء داخل الأشكال المعرفة في مسار رسومي بفرشاة محددة. المسار هو كائن يعرّف تسلسلًا عشوائيًا من الخطوط والمنحنيات والأشكال.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


السجل يحدد ضربات القلم لرسم الأشكال في مسار رسومي. المسار هو كائن يعرّف تسلسلًا عشوائيًا من الخطوط والمنحنيات والأشكال.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


هذا السجل يحدد كيفية ملء داخلية منحنى كاردينال مغلق باستخدام فرشاة محددة.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


هذا السجل يحدد القلم والخطوط لرسم منحنى كاردينال مغلق.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


هذا السجل يحدد خطوط القلم لرسم منحنى كاردينال.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


هذا السجل يحدد خطوط القلم لرسم منحنى بيزيه.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


هذا السجل يحدد كائن [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) مُقاس (القسم 2.2.1.4). يمكن أن تتكون الصورة إما من بيانات bitmap أو بيانات ملف تعريف.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


هذا السجل يحدد كائن EmfPlusImage مُقاس داخل متوازي أضلاع. يمكن أن تتكون الصورة إما من بيانات bitmap أو بيانات ملف تعريف.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


هذا السجل يحدد سلسلة نصية بناءً على خط، ومستطيل تخطيط، وتنسيق.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


هذا السجل يحدد أصل العرض إلى الإحداثيات الأفقية والرأسية المحددة. ينطبق ذلك على فرشاة التهشير وعلى أنماط التمويه 8 و 16 بت لكل بكسل.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


هذا السجل يحدد ما إذا كان سيتم تمكين أو تعطيل تنعيم النص. تنعيم النص هو طريقة لجعل خطوط وحواف رموز الأحرف تبدو أكثر سلاسة عند رسمها على سطح الإخراج.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


هذا السجل يحدد العملية المستخدمة لعرض النص.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


هذا السجل يضبط تباين النص وفقًا لقيمة غاما النص المحددة.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


هذا السجل يحدد وضع الاستيفاء لكائن وفقًا لنوع تصفية الصورة المحدد. يؤثر وضع الاستيفاء على كيفية تنفيذ التحجيم (التمدد والتقليص).

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


تحدد هذه السجل وضع إزاحة البكسل وفقًا لقيمة تمركز البكسل المحددة.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


تحدد هذه السجل وضع التركيب وفقًا لحالة المزج ألفا، الذي يحدد كيفية دمج ألوان المصدر مع ألوان الخلفية.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


تحدد هذه السجل جودة التركيب، التي تصف مستوى الجودة المطلوب لإنشاء صور مركبة من عدة كائنات.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


هذا السجل يحفظ حالة الرسومات، المحددة بواسطة فهرس معين، على مكدس من حالات الرسومات المحفوظة. كل فهرس في المكدس مرتبط بحالة محفوظة معينة، ويُستخدم الفهرس من قبل سجل [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) (القسم 2.3.7.4) لاستعادة الحالة.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


هذا السجل يستعيد حالة الرسومات، المحددة بواسطة فهرس معين، من مكدس حالات الرسومات المحفوظة. كل فهرس في المكدس مرتبط بحالة محفوظة معينة، ويُحدد الفهرس بواسطة سجل [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) (القسم 2.3.7.5) لحفظ الحالة.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


هذا السجل يفتح حاوية حالة رسومات جديدة ويحدد تحويلًا لها. تُستخدم حاويات الرسومات للاحتفاظ بعناصر حالة الرسومات.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


يفتح هذه السجل حاوية حالة رسومات جديدة.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


يغلق هذه السجل حاوية حالة رسومات تم فتحها مسبقًا بواسطة عملية بدء الحاوية.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


تحدد هذه السجل تحويل الفضاء العالمي الحالي في playback device\_context، وفقًا لمصفوفة تحويل محددة.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


تعيد هذه السجل ضبط تحويل الفضاء العالمي الحالي إلى مصفوفة الهوية.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


تضرب هذه السجل الفضاء العالمي الحالي بمصفوفة تحويل محددة.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


تطبق هذه السجل تحويل إزاحة على الفضاء العالمي الحالي بمسافات أفقية ورأسية محددة.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


تطبق هذه السجل تحويل تكبير على الفضاء العالمي الحالي بعوامل تكبير أفقية ورأسية محددة.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


تدور هذه السجل الفضاء العالمي الحالي بزاوية محددة.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


تحدد هذه السجل عوامل تكبير إضافية لتحويل الفضاء العالمي الحالي.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


تعيد هذه السجل ضبط منطقة القص الحالية للفضاء العالمي إلى ما لا نهاية.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


تدمج هذه السجل منطقة القص الحالية مع مستطيل.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


تدمج هذه السجل منطقة القص الحالية مع مسار رسومي.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


تدمج هذه السجل منطقة القص الحالية مع منطقة رسومية أخرى.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


تطبق هذه السجل تحويل إزاحة على منطقة القص الحالية للفضاء العالمي.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


تحدد هذه السجل إخراج النص مع مواضع الأحرف.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


هذا السجل يغلق أي أشكال مفتوحة في مسار، ويرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


تحدد هذه السجل كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


تحدد هذه السجل حالة سياق جهاز الرسومات لخادم طرفي.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


تحدد هذه السجل مناطق القص في سياق جهاز الرسومات لخادم طرفي.

