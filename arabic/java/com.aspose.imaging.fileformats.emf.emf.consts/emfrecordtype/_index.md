---
title: "EmfRecordType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد RecordType القيم التي تحدد هوية سجلات EMF بشكل فريد."
type: docs
weight: 38
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

تُعرّف تعداد RecordType القيم التي تُحدد سجلات EMF بشكل فريد. تُقدم هذه القيم في حقل Type لكل سجل.
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | يحدد هذا السجل بداية ملف الميتا ويُحدد خصائصه؛ محتوياته، بما في ذلك أبعاد الصورة المضمنة؛ عدد السجلات في ملف الميتا؛ ودقة الجهاز الذي تم إنشاء الصورة المضمنة عليه. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | يحدد هذا السجل منحنى أو أكثر من منحنيات بيزيير. |
| [EMR_POLYGON](#EMR-POLYGON) | يحدد هذا السجل مضلعًا يتكون من رأسين أو أكثر متصلة بخطوط مستقيمة. |
| [EMR_POLYLINE](#EMR-POLYLINE) | يحدد هذا السجل سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | يحدد هذا السجل منحنى أو أكثر من منحنيات بيزيير بناءً على الموقع الحالي. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | يحدد هذا السجل خطًا أو أكثر مستقيمًا بناءً على الموقع الحالي. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | يحدد هذا السجل سلاسل متعددة من مقاطع الخط المتصلة. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | يحدد هذا السجل سلسلة من المضلعات المغلقة. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | يحدد هذا السجل مدى النافذة. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | يحدد هذا السجل أصل النافذة. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | يحدد هذا السجل مدى منطقة العرض. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | يحدد هذا السجل أصل منطقة العرض. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | يحدد هذا السجل أصل الفرشاة الحالية. |
| [EMR_EOF](#EMR-EOF) | يشير هذا السجل إلى نهاية ملف الميتا. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | يحدد هذا السجل لون البكسل عند الإحداثيات المنطقية المحددة. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | يحدد هذا السجل معلمات عملية مطابقة الخطوط المنطقية مع الخطوط الفعلية، والتي يتم تنفيذها بواسطة مُطابق الخطوط. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | يحدد هذا السجل وضع التخطيط لسياق جهاز التشغيل. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | يحدد هذا السجل وضع خلط الخلفية لسياق جهاز التشغيل. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | يحدد هذا السجل وضع تعبئة المضلع. |
| [EMR_SETROP2](#EMR-SETROP2) | يحدد هذا السجل وضع عملية الرستر الثنائية. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | هذا السجل يحدد وضع تمديد البت ماب. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | هذا السجل يحدد محاذاة النص. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | هذا السجل يحدد قيم تعديل اللون لسياق جهاز التشغيل باستخدام القيم المحددة. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | هذا السجل يحدد لون النص الحالي. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | هذا السجل يحدد لون الخلفية. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | هذا السجل يعيد تعريف منطقة القص لسياق جهاز التشغيل باستخدام الإزاحات المحددة. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | هذا السجل يحدد إحداثيات الموضع الحالي الجديد، بوحدات منطقية. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | هذا السجل يتقاطع مع منطقة القص الحالية لسياق جهاز التشغيل مع المنطقة التعريفية الحالية ويحفظ المنطقة المدمجة كمنطقة تعريفية جديدة. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | هذا السجل يحدد منطقة قص جديدة تتكون من منطقة القص الحالية مطروحًا منها المستطيل المحدد. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | هذا السجل يحدد منطقة قص جديدة من تقاطع منطقة القص الحالية والمستطيل المحدد. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | هذا السجل يعيد تعريف نافذة العرض لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | هذا السجل يعيد تعريف النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة. |
| [EMR_SAVEDC](#EMR-SAVEDC) | هذا السجل يحفظ الحالة الحالية لسياق جهاز التشغيل عن طريق نسخ البيانات التي تصف الكائنات المختارة وأنماط الرسوم\u2014بما في ذلك البت ماب، الفرشاة، اللوحة، الخط، القلم، المنطقة، وضع الرسم، ووضع التخطيط\u2014إلى مكدس من سياقات الأجهزة المحفوظة. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | هذا السجل يعيد سياق جهاز التشغيل إلى الحالة المحفوظة المحددة. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | هذا السجل يحدد تحويلًا خطيًا ثنائي الأبعاد بين الفضاء العالمي وفضاء الصفحة (لمزيد من المعلومات، راجع [MSDN-WRLDPGSPC]) لسياق جهاز التشغيل. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | هذا السجل يعيد تعريف التحويل العالمي لسياق جهاز التشغيل باستخدام الوضع المحدد. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | هذا السجل يضيف كائنًا إلى سياق جهاز التشغيل، معرّفًا إياه بواسطة فهرسه في جدول كائنات EMF (القسم 3.1.1.1). |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | هذا السجل يحدد قلمًا منطقيًا له النمط والعرض واللون المحددين. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | هذا السجل يحدد فرشاة منطقية لتعبئة الأشكال في عمليات الرسوميات. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | هذا السجل يحذف كائنًا رسوميًا، ويزيل فهرسه في جدول كائنات EMF. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | هذا السجل يحدد قطعة خطية من قوس. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | هذا السجل يحدد إهليلجًا. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | هذا السجل يحدد مستطيلًا. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | هذا السجل يحدد مستطيلًا بزوايا مستديرة. |
| [EMR_ARC](#EMR-ARC) | هذا السجل يحدد قوسًا إهليلجيًا. |
| [EMR_CHORD](#EMR-CHORD) | هذا السجل يعرّف الوتر (منطقة محصورة بتقاطع إهليلج وقطعة خطية، تُسمى مقطعا). |
| [EMR_PIE](#EMR-PIE) | هذا السجل يعرّف قطاعًا على شكل فطيرة محصورًا بتقاطع إهليلج وشعاعين. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | هذا السجل يضيف كائن LogPalette (القسم 2.2.17) إلى سياق جهاز التشغيل، مع تحديده بواسطة فهرسه في جدول كائنات EMF. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | هذا السجل يعرّف كائن LogPalette. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | هذا السجل يعرّف قيم ألوان RGB (أحمر-أخضر-أزرق) في نطاق من الإدخالات داخل كائن LogPalette. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | هذا السجل يزيد أو يقلل حجم لوحة ألوان منطقية. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | هذا السجل يطابق الإدخالات من لوحة الألوان المنطقية الحالية إلى لوحة الألوان النظامية. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | هذا السجل يملأ مساحة من سطح العرض بالفرشاة الحالية. |
| [EMR_LINETO](#EMR-LINETO) | هذا السجل يعرّف خطًا من الموضع الحالي حتى، ولكن دون تضمين، النقطة المحددة. |
| [EMR_ARCTO](#EMR-ARCTO) | هذا السجل يحدد قوسًا إهليلجيًا. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | هذا السجل يعرّف مجموعة من قطع الخطوط ومنحنيات بيزيه. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | هذا السجل يعرّف اتجاه الرسم الذي سيُستخدم لعمليات القوس والمستطيل. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | هذا السجل يعرّف الحد الأقصى لطول وصلات القطع المثلثية (miter) في سياق جهاز التشغيل. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | هذا السجل يفتح قوس مسار في سياق جهاز التشغيل. |
| [EMR_ENDPATH](#EMR-ENDPATH) | هذا السجل يغلق قوس المسار ويختار المسار المحدد بالقوس في سياق جهاز التشغيل. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | هذا السجل يغلق شكلًا مفتوحًا في مسار. |
| [EMR_FILLPATH](#EMR-FILLPATH) | هذا السجل يغلق أي أشكال مفتوحة في المسار الحالي ويملأ داخل المسار باستخدام الفرشاة الحالية ووضع ملء المضلع. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | هذا السجل يغلق أي أشكال مفتوحة في مسار، يرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | هذا السجل يرسم المسار المحدد باستخدام القلم الحالي. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | هذا السجل يحوّل أي منحنى في المسار المحدد إلى سياق جهاز التشغيل، مُحوّلاً كل منحنى إلى سلسلة من الخطوط. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | هذا السجل يعيد تعريف المسار الحالي كمنطقة ستُرسم إذا تم تتبع المسار باستخدام القلم المحدد حاليًا في سياق جهاز التشغيل. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | هذا السجل يعرّف المسار الحالي كمنطقة قص لسياق جهاز التشغيل، مدمجًا المنطقة الجديدة مع أي منطقة قص موجودة باستخدام الوضع المحدد. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | هذا السجل يلغي قوس المسار أو يتخلص من المسار من قوس مسار مغلق. |
| [EMR_COMMENT](#EMR-COMMENT) | هذا السجل يحدد بيانات خاصة عشوائية. |
| [EMR_FILLRGN](#EMR-FILLRGN) | هذا السجل يملأ المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | هذا السجل يرسم حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | هذا السجل يعكس الألوان في المنطقة المحددة. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | هذا السجل يطلي المنطقة المحددة باستخدام الفرشاة المحددة حاليًا في سياق جهاز التشغيل. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | هذا السجل يجمع المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد. |
| [EMR_BITBLT](#EMR-BITBLT) | هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الهدف إذا لزم الأمر. |
| [EMR_MASKBLT](#EMR-MASKBLT) | هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة ومع تطبيق صورة قناع لوني، وفقًا لعمليات نقطية محددة للواجهة الأمامية والخلفية. |
| [EMR_PLGBLT](#EMR-PLGBLT) | هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى متوازي أضلاع هدف، مع تطبيق صورة قناع لوني. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | هذا السجل يحدد نقل كتلة من البكسلات من خطوط مسح محددة في صورة نقطية مصدر إلى مستطيل هدف. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الهدف إذا لزم الأمر. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | هذا السجل يعرّف خطًا منطقيًا يمتلك الخصائص المحددة. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | هذا السجل يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص. ملاحظة: يجب محاكاة EMR\_EXTTEXTOUTA باستخدام سجل EMR\_EXTTEXTOUTW (القسم 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | هذا السجل يرسم سلسلة نصية Unicode باستخدام الخط الحالي وألوان النص. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | يحدد هذا السجل منحنى أو أكثر من منحنيات بيزيير. |
| [EMR_POLYGON16](#EMR-POLYGON16) | يحدد هذا السجل مضلعًا يتكون من رأسين أو أكثر متصلة بخطوط مستقيمة. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | يحدد هذا السجل سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | هذا السجل يعرّف منحنى بيزيير واحد أو أكثر بناءً على الموضع الحالي. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | يحدد هذا السجل خطًا أو أكثر مستقيمًا بناءً على الموقع الحالي. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | يحدد هذا السجل سلاسل متعددة من مقاطع الخط المتصلة. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | يحدد هذا السجل سلسلة من المضلعات المغلقة. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | هذا السجل يعرّف مجموعة من قطع الخطوط ومنحنيات بيزيه. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | هذا السجل يعرّف فرشاة منطقية بنمط صورة نقطية محدد. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | هذا السجل يعرّف فرشاة منطقية لها النمط المحدد بواسطة DIB. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | هذا السجل يعرّف قلمًا تجميليًا أو هندسيًا منطقيًا يمتلك النمط والعرض وخصائص الفرشاة المحددة. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | هذا السجل يرسم سلسلة نصية ASCII واحدة أو أكثر باستخدام الخط الحالي وألوان النص. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | هذا السجل يرسم سلسلة نصية Unicode واحدة أو أكثر باستخدام الخط الحالي وألوان النص. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | هذا السجل يحدد وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | هذا السجل ينشئ كائن مساحة ألوان منطقي من ملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف ASCII. |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | هذا السجل يعرّف كائن مساحة الألوان المنطقي الحالي لعمليات الرسومات. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | هذا السجل يحذف كائن مساحة ألوان منطقي. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | هذا السجل يحدد دالة OpenGL. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | هذا السجل يحدد دالة OpenGL مع مستطيل حد للإخراج. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | هذا السجل يحدد تنسيق البكسل المستخدم لعمليات الرسومات. |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | هذا السجل يمرّر معلومات عشوائية إلى برنامج التشغيل. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | هذا السجل يمرّر معلومات عشوائية إلى برنامج التشغيل. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | هذا السجل يخرج سلسلة نصية. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | هذا السجل يجبر مخطط الخطوط على مطابقة الخطوط بناءً على UniversalFontId بدلاً من معلومات LogFont. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | هذا السجل يمرّر معلومات عشوائية إلى برنامج التشغيل المسمى المحدد. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | تحدد هذه السجيلة كيفية تصحيح إدخالات كائن لوحة ألوان منطقية باستخدام قيم نظام ألوان ويندوز (WCS) 1.0 |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | تحدد هذه السجيلة ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف ASCII، لإخراج الرسومات. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | تحدد هذه السجيلة ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف Unicode، لإخراج الرسومات. |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | تحدد هذه السجيلة نقل كتلة من البكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، بما في ذلك بيانات الشفافية ألفا، وفقًا لعملية دمج محددة. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | تحدد هذه السجيلة الترتيب الذي يتم فيه رسم النص والرسومات. |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | تحدد هذه السجيلة نقل كتلة من البكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، مع اعتبار لون محدد شفافًا، وتمديد أو ضغط الإخراج ليتناسب مع أبعاد الوجهة إذا لزم الأمر. |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | تحدد هذه السجيلة ملء المستطيلات أو المثلثات بتدرجات لونية. |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | تحدد هذه السجيلة معرفات الخطوط العالمية (UniversalFontIds) للخطوط المرتبطة لاستخدامها أثناء البحث عن الأحرف. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | تحدد هذه السجيلة مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لأغراض الضبط. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | تحدد هذه السجيلة ما إذا كان سيتم إجراء مطابقة ألوان باستخدام ملف تعريف ألوان محدد في ملف يحمل اسمًا مكوّنًا من أحرف Unicode. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | تنشئ هذه السجيلة كائن مساحة ألوان منطقية من ملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف Unicode. |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


تحدد هذه السجيلة بداية ملف الميتا وتحدد خصائصه؛ محتوياته، بما في ذلك أبعاد الصورة المدمجة؛ عدد السجلات في ملف الميتا؛ ودقة الجهاز الذي تم إنشاء الصورة المدمجة عليه. تجعل هذه القيم ملف الميتا مستقلاً عن الجهاز.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


تحدد هذه السجيلة منحنى أو أكثر من منحنيات بيزيه. يتم تعريف منحنيات بيزيه المكعبة باستخدام نقاط النهاية ونقاط التحكم المحددة، وتُرسم باستخدام القلم الحالي.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


تحدد هذه السجيلة مضلعًا يتكوّن من نقطتين أو أكثر متصلة بخطوط مستقيمة. يُحدّد حدود المضلع باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يُغلق المضلع تلقائيًا برسم خط من آخر نقطة إلى الأولى.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


يحدد هذا السجل سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


يحدد هذا السجل منحنى أو أكثر من منحنيات بيزيير بناءً على الموقع الحالي.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


تحدد هذه السجيلة خطًا أو أكثر مستقيمًا استنادًا إلى الموضع الحالي. يُرسم خط من الموضع الحالي إلى أول نقطة محددة في حقل النقاط باستخدام القلم الحالي. لكل خط إضافي، يتم الرسم من نقطة نهاية الخط السابق إلى النقطة التالية المحددة في النقاط.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


تحدد هذه السجيلة سلاسل متعددة من مقاطع الخط المتصلة. تُرسم مقاطع الخط باستخدام القلم الحالي. لا يتم تعبئة الأشكال التي تُكوّنها المقاطع. لا يُستخدم الموضع الحالي ولا يُحدّثه هذا السجل.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


تحدد هذه السجيلة سلسلة من المضلعات المغلقة. يُحدّد حدود كل مضلع باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يمكن للمضلعات المحددة بهذه السجيلة أن تتداخل.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


يحدد هذا السجل مدى النافذة.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


يحدد هذا السجل أصل النافذة.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


يحدد هذا السجل مدى منطقة العرض.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


يحدد هذا السجل أصل منطقة العرض.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


يحدد هذا السجل أصل الفرشاة الحالية.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


يشير هذا السجل إلى نهاية ملف الميتا.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


يحدد هذا السجل لون البكسل عند الإحداثيات المنطقية المحددة.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


يحدد هذا السجل معلمات عملية مطابقة الخطوط المنطقية مع الخطوط الفعلية، والتي يتم تنفيذها بواسطة مُطابق الخطوط.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


تحدد هذه السجيلة وضعية التحويل (mapping mode) لسياق جهاز التشغيل. تُعرّف وضعية التحويل وحدة القياس المستخدمة لتحويل وحدات مساحة الصفحة إلى وحدات مساحة الجهاز، وتحدد أيضًا اتجاه محور x ومحور y للجهاز.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


تحدد هذه السجيلة وضعية خلط الخلفية لسياق جهاز التشغيل. تُستخدم وضعية خلط الخلفية مع النص، والفرش الممهدة، وأنماط الأقلام التي ليست خطوطًا صلبة.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


يحدد هذا السجل وضع تعبئة المضلع.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


يحدد هذا السجل وضع عملية الرستر الثنائية.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


هذا السجل يحدد وضع تمديد البت ماب.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


هذا السجل يحدد محاذاة النص.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


هذا السجل يحدد قيم تعديل اللون لسياق جهاز التشغيل باستخدام القيم المحددة.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


هذا السجل يحدد لون النص الحالي.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


هذا السجل يحدد لون الخلفية.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


هذا السجل يعيد تعريف منطقة القص لسياق جهاز التشغيل باستخدام الإزاحات المحددة.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


هذا السجل يحدد إحداثيات الموضع الحالي الجديد، بوحدات منطقية.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


تقاطع هذه السجيلة منطقة القص الحالية لسياق جهاز التشغيل مع المنطقة الميتا الحالية وتحفظ المنطقة المدمجة كمنطقة ميتا جديدة. تُعاد منطقة القص إلى منطقة فارغة.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


هذا السجل يحدد منطقة قص جديدة تتكون من منطقة القص الحالية مطروحًا منها المستطيل المحدد.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


هذا السجل يحدد منطقة قص جديدة من تقاطع منطقة القص الحالية والمستطيل المحدد.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


هذا السجل يعيد تعريف نافذة العرض لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


هذا السجل يعيد تعريف النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


هذا السجل يحفظ الحالة الحالية لسياق جهاز التشغيل عن طريق نسخ البيانات التي تصف الكائنات المختارة وأنماط الرسوم\u2014بما في ذلك البت ماب، الفرشاة، اللوحة، الخط، القلم، المنطقة، وضع الرسم، ووضع التخطيط\u2014إلى مكدس من سياقات الأجهزة المحفوظة.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


تستعيد هذه السجيلة سياق جهاز التشغيل إلى الحالة المحفوظة المحددة. يُستعاد سياق جهاز التشغيل عن طريق إزالة معلومات الحالة من مكدس سياقات الأجهزة المحفوظة التي أنشأتها سجلات EMR\_SAVEDC السابقة (القسم 2.3.11).

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


تحدد هذه السجيلة تحويلًا خطيًا ثنائي الأبعاد بين مساحة العالم ومساحة الصفحة (لمزيد من المعلومات، راجع [MSDN-WRLDPGSPC]) لسياق جهاز التشغيل. يمكن استخدام هذا التحويل لتكبير أو تصغير، أو تدوير، أو قص، أو إزاحة إخراج الرسومات.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


هذا السجل يعيد تعريف التحويل العالمي لسياق جهاز التشغيل باستخدام الوضع المحدد.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


هذا السجل يضيف كائنًا إلى سياق جهاز التشغيل، معرّفًا إياه بواسطة فهرسه في جدول كائنات EMF (القسم 3.1.1.1).

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


تحدد هذه السجيلة قلمًا منطقيًا له النمط والعرض واللون المحددين. يمكن بعد ذلك اختيار القلم في سياق جهاز التشغيل واستخدامه لرسم الخطوط والمنحنيات.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


هذا السجل يحدد فرشاة منطقية لتعبئة الأشكال في عمليات الرسوميات.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


تحذف هذه السجيلة كائنًا رسوميًا، وتُمسح فهرسه في جدول كائنات EMF. إذا تم اختيار الكائن المحذوف في سياق جهاز التشغيل، يجب استعادة الكائن الافتراضي لتلك الخاصية في السياق.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


تحدد هذه السجيلة مقطع خط لقوس. يُرسم مقطع الخط من الموضع الحالي إلى بداية القوس. يُرسم القوس على محيط دائرة ذات نصف قطر ومركز محددين. يُحدد طول القوس بزاويتي البداية والامتداد المحددتين.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


هذا السجل يحدد قطعًا بيضاويًا. مركز القطع البيضاوي هو مركز المستطيل المحدد المحيط. يتم تحديد حدود القطع البيضاوي باستخدام القلم الحالي ويتم تعبئته باستخدام الفرشاة الحالية.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


هذا السجل يحدد مستطيلًا. يتم تحديد حدود المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


هذا السجل يحدد مستطيلًا بزوايا مستديرة. يتم تحديد حدود المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


هذا السجل يحدد قوسًا إهليلجيًا.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


هذا السجل يحدد وترًا (منطقة محصورة بتقاطع قطع بيضاوي ومقطع خطي يُسمى القاطع). يتم تحديد حدود الوتر باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


هذا السجل يحدد شريحة على شكل فطيرة محصورة بتقاطع قطع بيضاوي وشعاعين. يتم تحديد حدود الفطيرة باستخدام القلم الحالي وتعبئتها باستخدام الفرشاة الحالية.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


هذا السجل يضيف كائن LogPalette (القسم 2.2.17) إلى سياق جهاز التشغيل، مع تحديده بواسطة فهرسه في جدول كائنات EMF.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


هذا السجل يعرّف كائن LogPalette.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


هذا السجل يعرّف قيم ألوان RGB (أحمر-أخضر-أزرق) في نطاق من الإدخالات داخل كائن LogPalette.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


هذا السجل يزيد أو يقلل حجم لوحة ألوان منطقية.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


هذا السجل يطابق الإدخالات من لوحة الألوان المنطقية الحالية إلى لوحة الألوان النظامية.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


هذا السجل يملأ مساحة من سطح العرض بالفرشاة الحالية.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


هذا السجل يحدد خطًا من الموضع الحالي حتى النقطة المحددة دون تضمينها. يعيد تعيين الموضع الحالي إلى النقطة المحددة.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


هذا السجل يحدد قوسًا بيضاويًا. يعيد تعيين الموضع الحالي إلى نقطة النهاية للقوس.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


هذا السجل يعرّف مجموعة من قطع الخطوط ومنحنيات بيزيه.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


هذا السجل يعرّف اتجاه الرسم الذي سيُستخدم لعمليات القوس والمستطيل.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


هذا السجل يعرّف الحد الأقصى لطول وصلات القطع المثلثية (miter) في سياق جهاز التشغيل.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


هذا السجل يفتح قوس مسار في سياق جهاز التشغيل.

--------------------

بعد فتح قوس مسار، يمكن للتطبيق بدء معالجة السجلات لتحديد النقاط التي تقع في المسار. يجب على التطبيق إغلاق قوس المسار المفتوح بمعالجة سجل EMR\_ENDPATH. عند معالجة التطبيق لسجل EMR\_BEGINPATH، يجب تجاهل جميع المسارات السابقة من سياق جهاز التشغيل.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


هذا السجل يغلق قوس المسار ويختار المسار المحدد بالقوس في سياق جهاز التشغيل.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


هذا السجل يغلق شكلًا مفتوحًا في مسار.

--------------------

معالجة سجل EMR\_CLOSEFIGURE يجب أن تغلق الشكل عن طريق رسم خط من الموضع الحالي إلى أول نقطة في الشكل، ثم يجب أن تربط الخطوط باستخدام نمط وصل الخط. إذا تم إغلاق الشكل بمعالجة سجل EMR\_LINETO بدلاً من سجل EMR\_CLOSEFIGURE، تُستخدم نهايات الخط لإنشاء الزاوية بدلاً من الوصل. يتم تحديد EMR\_LINETO في القسم 2.3.5.13. يجب استخدام سجل EMR\_CLOSEFIGURE فقط إذا كان هناك قوس مسار مفتوح في سياق جهاز التشغيل. يكون الشكل في مسار مفتوحًا ما لم يتم إغلاقه صراحةً بمعالجة هذا السجل. ملاحظة: يمكن أن يكون الشكل مفتوحًا حتى إذا كانت النقطة الحالية ونقطة بدء الشكل هي نفسها. بعد معالجة سجل EMR\_CLOSEFIGURE، يجب أن يبدأ إضافة خط أو منحنى إلى المسار شكلًا جديدًا.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


هذا السجل يغلق أي أشكال مفتوحة في المسار الحالي ويملأ داخل المسار باستخدام الفرشاة الحالية ووضع ملء المضلع.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


هذا السجل يغلق أي أشكال مفتوحة في مسار، يرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


هذا السجل يرسم المسار المحدد باستخدام القلم الحالي.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


هذا السجل يحوّل أي منحنى في المسار المحدد إلى سياق جهاز التشغيل، مُحوّلاً كل منحنى إلى سلسلة من الخطوط.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


هذا السجل يعيد تعريف المسار الحالي كمنطقة ستُرسم إذا تم تتبع المسار باستخدام القلم المحدد حاليًا في سياق جهاز التشغيل.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


هذا السجل يعرّف المسار الحالي كمنطقة قص لسياق جهاز التشغيل، مدمجًا المنطقة الجديدة مع أي منطقة قص موجودة باستخدام الوضع المحدد.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


هذا السجل يلغي قوس المسار أو يتخلص من المسار من قوس مسار مغلق.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


هذا السجل يحدد بيانات خاصة عشوائية.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


هذا السجل يملأ المنطقة المحددة باستخدام الفرشاة المحددة.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


هذا السجل يرسم حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


هذا السجل يعكس الألوان في المنطقة المحددة.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


هذا السجل يطلي المنطقة المحددة باستخدام الفرشاة المحددة حاليًا في سياق جهاز التشغيل.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


هذا السجل يجمع المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الهدف إذا لزم الأمر.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة ومع تطبيق صورة قناع لوني، وفقًا لعمليات نقطية محددة للواجهة الأمامية والخلفية.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى متوازي أضلاع هدف، مع تطبيق صورة قناع لوني.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


هذا السجل يحدد نقل كتلة من البكسلات من خطوط مسح محددة في صورة نقطية مصدر إلى مستطيل هدف.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


هذا السجل يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الهدف إذا لزم الأمر.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


هذا السجل يحدد خطًا منطقيًا يمتلك الخصائص المحددة. يمكن لاحقًا اختيار الخط كخط حالي لسياق جهاز التشغيل.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


هذا السجل يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص. ملاحظة يجب محاكاة EMR\_EXTTEXTOUTA بسجل EMR\_EXTTEXTOUTW (القسم 2.3.5.8). يتطلب ذلك تحويل سلسلة النص ASCII في كائن EmrText إلى ترميز Unicode UTF16-LE.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


هذا السجل يرسم سلسلة نصية Unicode باستخدام الخط الحالي وألوان النص.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


هذا السجل يحدد منحنى (أو أكثر) بيزيه. يتم رسم المنحنيات باستخدام القلم الحالي.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


تحدد هذه السجيلة مضلعًا يتكوّن من نقطتين أو أكثر متصلة بخطوط مستقيمة. يُحدّد حدود المضلع باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يُغلق المضلع تلقائيًا برسم خط من آخر نقطة إلى الأولى.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


يحدد هذا السجل سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


هذا السجل يعرّف منحنى بيزيير واحد أو أكثر بناءً على الموضع الحالي.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


هذا السجل يحدد خطًا (أو أكثر) مستقيمًا استنادًا إلى الموضع الحالي. يتم رسم خط من الموضع الحالي إلى أول نقطة محددة في حقل Points باستخدام القلم الحالي. لكل خط إضافي، يتم الرسم من نقطة نهاية الخط السابق إلى النقطة التالية المحددة في Points.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


يحدد هذا السجل سلاسل متعددة من مقاطع الخط المتصلة.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


هذا السجل يحدد سلسلة من المضلعات المغلقة. يتم تحديد حدود كل مضلع باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يمكن أن تتداخل المضلعات المحددة بهذا السجل.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


هذا السجل يعرّف مجموعة من قطع الخطوط ومنحنيات بيزيه.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


هذا السجل يحدد فرشاة منطقية بالنمط البت ماب المحدد. يمكن أن يكون البت ماب قسمًا من نوع bitmap مستقل عن الجهاز (DIB) أو يمكن أن يكون bitmap تابعًا للجهاز.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


هذا السجل يعرّف فرشاة منطقية لها النمط المحدد بواسطة DIB.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


هذا السجل يعرّف قلمًا تجميليًا أو هندسيًا منطقيًا يمتلك النمط والعرض وخصائص الفرشاة المحددة.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


هذا السجل يرسم سلسلة نصية ASCII (واحدة أو أكثر) باستخدام الخط الحالي وألوان النص. ملاحظة يجب محاكاة EMR\_POLYTEXTOUTA بسلسلة من سجلات EMR\_EXTTEXTOUTW، واحدة لكل سلسلة.

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


هذا السجل يرسم سلسلة نصية Unicode (واحدة أو أكثر) باستخدام الخط الحالي وألوان النص. ملاحظة يجب محاكاة EMR\_POLYTEXTOUTW بسلسلة من سجلات EMR\_EXTTEXTOUTW، واحدة لكل سلسلة.

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


هذا السجل يحدد وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


هذا السجل ينشئ كائن مساحة ألوان منطقي من ملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف ASCII.

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


هذا السجل يعرّف كائن مساحة الألوان المنطقي الحالي لعمليات الرسومات.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


هذا السجل يحذف كائن مساحة لون منطقية. ملاحظة يجب استخدام سجل EMR\_DELETEOBJECT بدلاً من EMR\_DELETECOLORSPACE لحذف كائن مساحة لون منطقية.

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


هذا السجل يحدد دالة OpenGL.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


هذا السجل يحدد دالة OpenGL مع مستطيل حد للإخراج.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


هذا السجل يحدد تنسيق البكسل المستخدم لعمليات الرسومات.

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


هذا السجل يمرر معلومات عشوائية إلى برنامج التشغيل. الهدف هو أن تؤدي المعلومات إلى تنفيذ الرسم.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


هذا السجل يمرر معلومات عشوائية إلى برنامج التشغيل. الهدف هو أن لا تؤدي المعلومات إلى تنفيذ الرسم.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


هذا السجل يخرج سلسلة نصية.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


هذا السجل يجبر مخطط الخطوط على مطابقة الخطوط بناءً على UniversalFontId بدلاً من معلومات LogFont.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


هذا السجل يمرّر معلومات عشوائية إلى برنامج التشغيل المسمى المحدد.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


تحدد هذه السجيلة كيفية تصحيح إدخالات كائن لوحة ألوان منطقية باستخدام قيم نظام ألوان ويندوز (WCS) 1.0

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


تحدد هذه السجيلة ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف ASCII، لإخراج الرسومات.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


تحدد هذه السجيلة ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف Unicode، لإخراج الرسومات.

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


تحدد هذه السجيلة نقل كتلة من البكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، بما في ذلك بيانات الشفافية ألفا، وفقًا لعملية دمج محددة.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


تحدد هذه السجيلة الترتيب الذي يتم فيه رسم النص والرسومات.

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


تحدد هذه السجيلة نقل كتلة من البكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، مع اعتبار لون محدد شفافًا، وتمديد أو ضغط الإخراج ليتناسب مع أبعاد الوجهة إذا لزم الأمر.

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


تحدد هذه السجيلة ملء المستطيلات أو المثلثات بتدرجات لونية.

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


تحدد هذه السجيلة معرفات الخطوط العالمية (UniversalFontIds) للخطوط المرتبطة لاستخدامها أثناء البحث عن الأحرف.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


تحدد هذه السجيلة مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لأغراض الضبط.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


تحدد هذه السجيلة ما إذا كان سيتم إجراء مطابقة ألوان باستخدام ملف تعريف ألوان محدد في ملف يحمل اسمًا مكوّنًا من أحرف Unicode.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


تنشئ هذه السجيلة كائن مساحة ألوان منطقية من ملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف Unicode.

