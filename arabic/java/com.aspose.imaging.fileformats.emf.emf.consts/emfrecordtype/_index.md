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

تعداد RecordType يحدد القيم التي تعرّف سجلات EMF بشكل فريد. تُقدم هذه القيم في حقل Type لكل سجل.
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | هذا السجل يحدد بداية ملف الميتا ويحدد خصائصه؛ محتوياته، بما في ذلك أبعاد الصورة المدمجة؛ عدد السجلات في ملف الميتا؛ ودقة الجهاز الذي تم إنشاء الصورة المدمجة عليه. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | هذا السجل يحدد منحنى بيزيه واحد أو أكثر. |
| [EMR_POLYGON](#EMR-POLYGON) | هذا السجل يحدد مضلعًا يتكون من نقطتين أو أكثر متصلة بخطوط مستقيمة. |
| [EMR_POLYLINE](#EMR-POLYLINE) | هذا السجل يحدد سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | هذا السجل يحدد منحنى بيزيه واحد أو أكثر بناءً على الموضع الحالي. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | هذا السجل يحدد خطًا (أو أكثر) مستقيمًا بناءً على الموضع الحالي. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | هذا السجل يحدد سلاسل متعددة من مقاطع الخط المتصلة. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | هذا السجل يحدد سلسلة من المضلعات المغلقة. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | هذا السجل يحدد امتداد النافذة. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | هذا السجل يحدد أصل النافذة. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | هذا السجل يحدد امتداد منطقة العرض. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | هذا السجل يحدد أصل منطقة العرض. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | هذا السجل يحدد أصل الفرشاة الحالية. |
| [EMR_EOF](#EMR-EOF) | هذا السجل يشير إلى نهاية ملف الميتا. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | هذا السجل يحدد لون البكسل عند الإحداثيات المنطقية المحددة. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | هذا السجل يحدد معلمات عملية مطابقة الخطوط المنطقية مع الخطوط الفعلية، والتي يتم تنفيذها بواسطة مطابقة الخطوط. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | هذا السجل يحدد وضعية التخطيط لسياق جهاز التشغيل. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | هذا السجل يحدد وضعية خلط الخلفية لسياق جهاز التشغيل. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | هذا السجل يحدد وضعية تعبئة المضلع. |
| [EMR_SETROP2](#EMR-SETROP2) | هذا السجل يحدد وضعية العملية النقطية الثنائية. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | هذا السجل يحدد وضعية تمديد الصورة النقطية. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | هذا السجل يحدد محاذاة النص. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | هذا السجل يحدد قيم تعديل اللون لسياق جهاز التشغيل باستخدام القيم المحددة. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | هذا السجل يحدد لون النص الحالي. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | هذا السجل يحدد لون الخلفية. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | هذا السجل يعيد تعريف منطقة القص لسياق جهاز التشغيل باستخدام الإزاحات المحددة. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | هذا السجل يحدد إحداثيات الموضع الحالي الجديد، بوحدات منطقية. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | هذا السجل يتقاطع مع منطقة القص الحالية لسياق جهاز التشغيل مع المنطقة الميتا الحالية ويحفظ المنطقة المدمجة كمنطقة ميتا جديدة. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | هذا السجل يحدد منطقة قص جديدة تتكون من منطقة القص الحالية مطروحًا منها المستطيل المحدد. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | هذا السجل يحدد منطقة قص جديدة من تقاطع منطقة القص الحالية مع المستطيل المحدد. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | هذا السجل يعيد تعريف نافذة العرض لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والقواسم المحددة. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | هذا السجل يعيد تعريف النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والقواسم المحددة. |
| [EMR_SAVEDC](#EMR-SAVEDC) | هذا السجل يحفظ الحالة الحالية لسياق جهاز التشغيل عن طريق نسخ البيانات التي تصف الكائنات المختارة وأنماط الرسومات\u2014بما في ذلك الصورة النقطية، الفرشاة، لوحة الألوان، الخط، القلم، المنطقة، وضعية الرسم، ووضعية التخطيط\u2014إلى مكدس من سياقات الأجهزة المحفوظة. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | هذا السجل يعيد سياق جهاز التشغيل إلى الحالة المحفوظة المحددة. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | هذا السجل يحدد تحويلًا خطيًا ثنائي الأبعاد بين مساحة العالم ومساحة الصفحة (لمزيد من المعلومات، راجع [MSDN-WRLDPGSPC]) لسياق جهاز التشغيل. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | هذا السجل يعيد تعريف تحويل العالم لسياق جهاز التشغيل باستخدام الوضع المحدد. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | هذا السجل يضيف كائنًا إلى سياق جهاز التشغيل، معرّفًا إياه بواسطة فهرسه في جدول كائنات EMF (القسم 3.1.1.1). |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | هذا السجل يعرّف قلمًا منطقيًا له النمط المحدد والعرض واللون. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | هذا السجل يعرّف فرشاة منطقية لتعبئة الأشكال في عمليات الرسومات. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | هذا السجل يحذف كائنًا رسوميًا، ويزيل فهرسه في جدول كائنات EMF. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | هذا السجل يعرّف قطعة خط من قوس. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | هذا السجل يعرّف إهليلجًا. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | هذا السجل يعرّف مستطيلًا. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | هذا السجل يعرّف مستطيلًا بزوايا مستديرة. |
| [EMR_ARC](#EMR-ARC) | هذا السجل يعرّف قوسًا إهليلجيًا. |
| [EMR_CHORD](#EMR-CHORD) | هذا السجل يعرّف وترًا (منطقة محصورة بتقاطع إهليلج وخط قطعة، يُطلق عليها القاطع). |
| [EMR_PIE](#EMR-PIE) | هذا السجل يعرّف شريحة على شكل فطيرة محصورة بتقاطع إهليلج وشعاعين. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | هذا السجل يضيف كائن LogPalette (القسم 2.2.17) إلى سياق جهاز التشغيل، مع تحديده بواسطة فهرسه في جدول كائنات EMF. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | هذا السجل يعرّف كائن LogPalette. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | هذا السجل يعرّف قيم ألوان RGB (أحمر-أخضر-أزرق) في نطاق من الإدخالات داخل كائن LogPalette. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | هذا السجل يزيد أو يقلل حجم لوحة ألوان منطقية. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | هذا السجل يطابق الإدخالات من لوحة الألوان المنطقية الحالية إلى لوحة ألوان النظام. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | هذا السجل يملأ مساحة من سطح العرض بالفرشاة الحالية. |
| [EMR_LINETO](#EMR-LINETO) | هذا السجل يعرّف خطًا من الموضع الحالي حتى، دون تضمين، النقطة المحددة. |
| [EMR_ARCTO](#EMR-ARCTO) | هذا السجل يعرّف قوسًا إهليلجيًا. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | هذا السجل يعرّف مجموعة من قطع الخطوط ومنحنيات بيزيه. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | هذا السجل يعرّف اتجاه الرسم الذي سيُستخدم لعمليات القوس والمستطيل. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | هذا السجل يعرّف الحد لطول وصلات الزاوية الحادة في سياق جهاز التشغيل. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | هذا السجل يفتح قوس مسار في سياق جهاز التشغيل. |
| [EMR_ENDPATH](#EMR-ENDPATH) | هذا السجل يغلق قوس المسار ويختار المسار المحدد بالقوس في سياق جهاز التشغيل. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | هذا السجل يغلق شكلًا مفتوحًا في مسار. |
| [EMR_FILLPATH](#EMR-FILLPATH) | هذا السجل يغلق أي أشكال مفتوحة في المسار الحالي ويملأ داخل المسار باستخدام الفرشاة الحالية ووضع تعبئة المضلع. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | هذا السجل يغلق أي أشكال مفتوحة في مسار، ويرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | هذا السجل يرسم المسار المحدد باستخدام القلم الحالي. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | هذا السجل يحوّل أي منحنى في المسار المحدد إلى سياق جهاز التشغيل، مبدلًا كل منحنى إلى سلسلة من الخطوط. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | يعيد هذا السجل تعريف المسار الحالي على أنه المنطقة التي سيتم طلاءها إذا تم رسم المسار باستخدام القلم المحدد حاليًا في سياق جهاز التشغيل. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | يحدد هذا السجل المسار الحالي كمنطقة قص لسياق جهاز التشغيل، مع دمج المنطقة الجديدة مع أي منطقة قص موجودة باستخدام الوضع المحدد. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | هذا السجل يلغي قوس المسار أو يتخلص من المسار من قوس مسار مغلق. |
| [EMR_COMMENT](#EMR-COMMENT) | يحدد هذا السجل بيانات خاصة عشوائية. |
| [EMR_FILLRGN](#EMR-FILLRGN) | يقوم هذا السجل بملء المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | يرسم هذا السجل حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | يعكس هذا السجل ألوان المنطقة المحددة. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | يطلي هذا السجل المنطقة المحددة باستخدام الفرشاة المحددة حاليًا في سياق جهاز التشغيل. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | يجمع هذا السجل المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد. |
| [EMR_BITBLT](#EMR-BITBLT) | يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الوجهة إذا لزم الأمر. |
| [EMR_MASKBLT](#EMR-MASKBLT) | يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة وتطبيق صورة قناع لوني، وفقًا لعمليات نقطية محددة للواجهة الأمامية والخلفية. |
| [EMR_PLGBLT](#EMR-PLGBLT) | يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى متوازي أضلاع الوجهة، مع تطبيق صورة قناع لوني. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | يحدد هذا السجل نقلًا كتليًا للبكسلات من خطوط المسح المحددة في صورة نقطية المصدر إلى مستطيل الوجهة. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الوجهة إذا لزم الأمر. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | يعرّف هذا السجل خطًا منطقيًا يمتلك الخصائص المحددة. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | يرسم هذا السجل سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص. ملاحظة: يجب محاكاة EMR\_EXTTEXTOUTA باستخدام سجل EMR\_EXTTEXTOUTW (القسم 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | يرسم هذا السجل سلسلة نصية Unicode باستخدام الخط الحالي وألوان النص. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | هذا السجل يحدد منحنى بيزيه واحد أو أكثر. |
| [EMR_POLYGON16](#EMR-POLYGON16) | هذا السجل يحدد مضلعًا يتكون من نقطتين أو أكثر متصلة بخطوط مستقيمة. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | هذا السجل يحدد سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | يحدد هذا السجل منحنيات بيزيير واحدة أو أكثر بناءً على الموضع الحالي. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | هذا السجل يحدد خطًا (أو أكثر) مستقيمًا بناءً على الموضع الحالي. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | هذا السجل يحدد سلاسل متعددة من مقاطع الخط المتصلة. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | هذا السجل يحدد سلسلة من المضلعات المغلقة. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | هذا السجل يعرّف مجموعة من قطع الخطوط ومنحنيات بيزيه. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | يعرّف هذا السجل فرشاة منطقية بنمط الصورة النقطية المحدد. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | يعرّف هذا السجل فرشاة منطقية لها النمط المحدد بواسطة DIB. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | يعرّف هذا السجل قلمًا تجميليًا أو هندسيًا منطقيًا يمتلك النمط والعرض وخصائص الفرشاة المحددة. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | يرسم هذا السجل سلسلة (أو أكثر) من نصوص ASCII باستخدام الخط الحالي وألوان النص. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | يرسم هذا السجل سلسلة (أو أكثر) من نصوص Unicode باستخدام الخط الحالي وألوان النص. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | يحدد هذا السجل وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | ينشئ هذا السجل كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف ASCII. |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | يعرّف هذا السجل كائن مساحة اللون المنطقية الحالي لعمليات الرسومات. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | يقوم هذا السجل بحذف كائن مساحة ألوان منطقية. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | يحدد هذا السجل دالة OpenGL. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | يحدد هذا السجل دالة OpenGL مع مستطيل حدود للإخراج. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | يحدد هذا السجل تنسيق البكسل المستخدم لعمليات الرسومات |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | ينقل هذا السجل معلومات عشوائية إلى برنامج التشغيل. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | ينقل هذا السجل معلومات عشوائية إلى برنامج التشغيل. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | يقوم هذا السجل بإخراج سلسلة نصية. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | يجبر هذا السجل مخطط الخطوط على مطابقة الخطوط بناءً على UniversalFontId الخاص بها بدلاً من معلومات LogFont. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | ينقل هذا السجل معلومات عشوائية إلى برنامج التشغيل المسمى المحدد. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | يحدد هذا السجل طريقة تصحيح مدخلات كائن لوحة ألوان منطقية باستخدام قيم نظام ألوان ويندوز (WCS) 1.0 |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | يحدد هذا السجل ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف ASCII، للإخراج الرسومي. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | يحدد هذا السجل ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف Unicode، للإخراج الرسومي. |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | يحدد هذا السجل نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، بما في ذلك بيانات الشفافية ألفا، وفقًا لعملية دمج محددة. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | يحدد هذا السجل ترتيب رسم النص والرسومات. |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | يحدد هذا السجل نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، مع اعتبار لون محدد شفافًا، وتمديد أو ضغط الإخراج ليتناسب مع أبعاد الهدف إذا لزم الأمر. |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | يحدد هذا السجل تعبئة المستطيلات أو المثلثات بتدرجات لونية. |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | يضبط هذا السجل قيم UniversalFontIds للخطوط المرتبطة لاستخدامها أثناء البحث عن الأحرف. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | يحدد هذا السجل مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لأغراض الضبط. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | يحدد هذا السجل ما إذا كان سيتم إجراء مطابقة ألوان باستخدام ملف تعريف ألوان محدد في ملف يحمل اسمًا مكوّنًا من أحرف Unicode. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | ينشئ هذا السجل كائن مساحة ألوان منطقية من ملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف Unicode. |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


يحدد هذا السجل بداية ملف الميتا ويصف خصائصه؛ محتوياته، بما في ذلك أبعاد الصورة المضمنة؛ عدد السجلات في ملف الميتا؛ ودقة الجهاز الذي تم إنشاء الصورة المضمنة عليه. تجعل هذه القيم ملف الميتا مستقلاً عن الجهاز.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


يحدد هذا السجل منحنى أو أكثر من منحنيات بيزيه. تُعرّف منحنيات بيزيه المكعبة باستخدام نقاط النهاية ونقاط التحكم المحددة، وتُرسم باستخدام القلم الحالي.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


يحدد هذا السجل مضلعًا يتكوّن من نقطتين أو أكثر متصلة بخطوط مستقيمة. يُحدّد المضلع باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يُغلق المضلع تلقائيًا برسم خط من آخر نقطة إلى الأولى.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


هذا السجل يحدد سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


هذا السجل يحدد منحنى بيزيه واحد أو أكثر بناءً على الموضع الحالي.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


يحدد هذا السجل خطًا أو أكثر مستقيمًا بناءً على الموضع الحالي. يُرسم خط من الموضع الحالي إلى أول نقطة محددة في حقل النقاط باستخدام القلم الحالي. لكل خط إضافي، يتم الرسم من نقطة نهاية الخط السابق إلى النقطة التالية المحددة في النقاط.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


يحدد هذا السجل سلاسل متعددة من مقاطع الخط المتصلة. تُرسم مقاطع الخط باستخدام القلم الحالي. الأشكال التي تُكوّنها المقاطع لا تُملأ. لا يُستخدم الموضع الحالي ولا يتم تحديثه بواسطة هذا السجل.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


يحدد هذا السجل سلسلة من المضلعات المغلقة. يُحدّد كل مضلع باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يمكن للمضلعات المحددة بهذا السجل أن تتداخل.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


هذا السجل يحدد امتداد النافذة.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


هذا السجل يحدد أصل النافذة.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


هذا السجل يحدد امتداد منطقة العرض.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


هذا السجل يحدد أصل منطقة العرض.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


هذا السجل يحدد أصل الفرشاة الحالية.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


هذا السجل يشير إلى نهاية ملف الميتا.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


هذا السجل يحدد لون البكسل عند الإحداثيات المنطقية المحددة.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


هذا السجل يحدد معلمات عملية مطابقة الخطوط المنطقية مع الخطوط الفعلية، والتي يتم تنفيذها بواسطة مطابقة الخطوط.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


يسجل هذا السجل وضع التخطيط لسياق جهاز التشغيل. يحدد وضع التخطيط وحدة القياس المستخدمة لتحويل وحدات مساحة الصفحة إلى وحدات مساحة الجهاز، كما يحدد اتجاه محور x ومحور y للجهاز.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


يحدد هذا السجل وضع خلط الخلفية لسياق جهاز التشغيل. يُستخدم وضع خلط الخلفية مع النص، والفرش المخططة، وأنماط القلم التي ليست خطوطًا صلبة.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


هذا السجل يحدد وضعية تعبئة المضلع.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


هذا السجل يحدد وضعية العملية النقطية الثنائية.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


هذا السجل يحدد وضعية تمديد الصورة النقطية.

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


يقوم هذا السجل بتقاطع منطقة القص الحالية لسياق جهاز التشغيل مع المنطقة الوصفية الحالية ويحفظ المنطقة المدمجة كمنطقة وصفية جديدة. تُعاد منطقة القص إلى منطقة فارغة.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


هذا السجل يحدد منطقة قص جديدة تتكون من منطقة القص الحالية مطروحًا منها المستطيل المحدد.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


هذا السجل يحدد منطقة قص جديدة من تقاطع منطقة القص الحالية مع المستطيل المحدد.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


هذا السجل يعيد تعريف نافذة العرض لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والقواسم المحددة.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


هذا السجل يعيد تعريف النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والقواسم المحددة.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


هذا السجل يحفظ الحالة الحالية لسياق جهاز التشغيل عن طريق نسخ البيانات التي تصف الكائنات المختارة وأنماط الرسومات\u2014بما في ذلك الصورة النقطية، الفرشاة، لوحة الألوان، الخط، القلم، المنطقة، وضعية الرسم، ووضعية التخطيط\u2014إلى مكدس من سياقات الأجهزة المحفوظة.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


يستعيد هذا السجل سياق جهاز التشغيل إلى الحالة المحفوظة المحددة. يتم استعادة سياق جهاز التشغيل عن طريق إزالة معلومات الحالة من مكدس سياقات الأجهزة المحفوظة التي أنشأتها سجلات EMR\\_SAVEDC السابقة (القسم 2.3.11).

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


يحدد هذا السجل تحويلًا خطيًا ثنائي الأبعاد بين مساحة العالم ومساحة الصفحة (لمزيد من المعلومات، راجع [MSDN-WRLDPGSPC]) لسياق جهاز التشغيل. يمكن استخدام هذا التحويل لتكبير، أو تدوير، أو قص، أو إزاحة مخرجات الرسومات.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


هذا السجل يعيد تعريف تحويل العالم لسياق جهاز التشغيل باستخدام الوضع المحدد.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


هذا السجل يضيف كائنًا إلى سياق جهاز التشغيل، معرّفًا إياه بواسطة فهرسه في جدول كائنات EMF (القسم 3.1.1.1).

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


يحدد هذا السجل قلمًا منطقيًا يمتلك النمط والعرض واللون المحددين. يمكن بعد ذلك اختيار القلم في سياق جهاز التشغيل واستخدامه لرسم الخطوط والمنحنيات.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


هذا السجل يعرّف فرشاة منطقية لتعبئة الأشكال في عمليات الرسومات.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


يحذف هذا السجل كائنًا رسوميًا، ويُمسح فهرسه في جدول كائنات EMF. إذا تم اختيار الكائن المحذوف في سياق جهاز التشغيل، يجب استعادة الكائن الافتراضي لتلك الخاصية في السياق.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


يحدد هذا السجل قطعة خط من قوس. تُرسم قطعة الخط من الموضع الحالي إلى بداية القوس. يُرسم القوس على محيط دائرة ذات نصف قطر ومركز محددين. يُحدد طول القوس بواسطة زوايا البدء والامتداد المعطاة.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


يحدد هذا السجل إهليلجًا. مركز الإهليلج هو مركز المستطيل المحدد الذي يحده. يُحدّد الإهليلج باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


يحدد هذا السجل مستطيلًا. يُحدّد المستطيل باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


يحدد هذا السجل مستطيلًا بزوايا مستديرة. يُحدّد المستطيل باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


هذا السجل يعرّف قوسًا إهليلجيًا.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


يحدد هذا السجل وترًا (منطقة محصورة بتقاطع إهليلج وقطعة خط، تُسمى مقطعًا). يُحدّد الوتر باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


يحدد هذا السجل شريحة على شكل فطيرة محصورة بتقاطع إهليلج وشعاعين. تُحدّد الشريحة باستخدام القلم الحالي وتُملأ باستخدام الفرشاة الحالية.

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


هذا السجل يطابق الإدخالات من لوحة الألوان المنطقية الحالية إلى لوحة ألوان النظام.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


هذا السجل يملأ مساحة من سطح العرض بالفرشاة الحالية.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


يحدد هذا السجل خطًا من الموضع الحالي حتى، ولكن لا يشمل، النقطة المحددة. يعيد تعيين الموضع الحالي إلى النقطة المحددة.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


يحدد هذا السجل قوسًا إهليلجيًا. يعيد تعيين الموضع الحالي إلى نقطة النهاية للقوس.

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


هذا السجل يعرّف الحد لطول وصلات الزاوية الحادة في سياق جهاز التشغيل.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


هذا السجل يفتح قوس مسار في سياق جهاز التشغيل.

--------------------

بعد فتح قوس مسار، يمكن للتطبيق بدء معالجة السجلات لتحديد النقاط التي تقع في المسار. يجب على التطبيق إغلاق قوس مسار مفتوح بمعالجة سجل EMR\\_ENDPATH. عندما يعالج التطبيق سجل EMR\\_BEGINPATH، يجب تجاهل جميع المسارات السابقة من سياق جهاز التشغيل.

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

يجب أن يغلق سجل EMR\\_CLOSEFIGURE الشكل برسم خط من الموضع الحالي إلى النقطة الأولى للشكل، ثم يجب ربط الخطوط باستخدام نمط وصل الخط. إذا تم إغلاق الشكل بمعالجة سجل EMR\\_LINETO بدلاً من سجل EMR\\_CLOSEFIGURE، تُستخدم أغطية النهاية لإنشاء الزاوية بدلاً من الوصل. يُحدد EMR\\_LINETO في القسم 2.3.5.13. يجب استخدام سجل EMR\\_CLOSEFIGURE فقط إذا كان هناك قوس مسار مفتوح في سياق جهاز التشغيل. يكون الشكل في مسار مفتوحًا ما لم يتم إغلاقه صراحةً بمعالجة هذا السجل. ملاحظة: يمكن أن يكون الشكل مفتوحًا حتى إذا كانت النقطة الحالية ونقطة بدء الشكل متطابقتين. بعد معالجة سجل EMR\\_CLOSEFIGURE، يجب أن يبدأ إضافة خط أو منحنى إلى المسار شكلًا جديدًا.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


هذا السجل يغلق أي أشكال مفتوحة في المسار الحالي ويملأ داخل المسار باستخدام الفرشاة الحالية ووضع تعبئة المضلع.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


هذا السجل يغلق أي أشكال مفتوحة في مسار، ويرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


هذا السجل يرسم المسار المحدد باستخدام القلم الحالي.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


هذا السجل يحوّل أي منحنى في المسار المحدد إلى سياق جهاز التشغيل، مبدلًا كل منحنى إلى سلسلة من الخطوط.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


يعيد هذا السجل تعريف المسار الحالي على أنه المنطقة التي سيتم طلاءها إذا تم رسم المسار باستخدام القلم المحدد حاليًا في سياق جهاز التشغيل.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


يحدد هذا السجل المسار الحالي كمنطقة قص لسياق جهاز التشغيل، مع دمج المنطقة الجديدة مع أي منطقة قص موجودة باستخدام الوضع المحدد.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


هذا السجل يلغي قوس المسار أو يتخلص من المسار من قوس مسار مغلق.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


يحدد هذا السجل بيانات خاصة عشوائية.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


يقوم هذا السجل بملء المنطقة المحددة باستخدام الفرشاة المحددة.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


يرسم هذا السجل حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


يعكس هذا السجل ألوان المنطقة المحددة.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


يطلي هذا السجل المنطقة المحددة باستخدام الفرشاة المحددة حاليًا في سياق جهاز التشغيل.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


يجمع هذا السجل المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الوجهة إذا لزم الأمر.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة وتطبيق صورة قناع لوني، وفقًا لعمليات نقطية محددة للواجهة الأمامية والخلفية.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى متوازي أضلاع الوجهة، مع تطبيق صورة قناع لوني.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


يحدد هذا السجل نقلًا كتليًا للبكسلات من خطوط المسح المحددة في صورة نقطية المصدر إلى مستطيل الوجهة.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


يحدد هذا السجل نقلًا كتليًا للبكسلات من صورة نقطية المصدر إلى مستطيل الوجهة، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة، مع تمديد أو ضغط الناتج ليتناسب مع أبعاد الوجهة إذا لزم الأمر.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


يحدد هذا السجل خطًا منطقيًا يمتلك الخصائص المحددة. يمكن بعد ذلك اختيار الخط كخط الحالي لسياق جهاز التشغيل.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


يرسم هذا السجل سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص. ملاحظة: يجب محاكاة EMR\\_EXTTEXTOUTA بسجل EMR\\_EXTTEXTOUTW (القسم 2.3.5.8). يتطلب ذلك تحويل سلسلة النص ASCII في كائن EmrText إلى ترميز Unicode UTF16-LE.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


يرسم هذا السجل سلسلة نصية Unicode باستخدام الخط الحالي وألوان النص.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


يحدد هذا السجل منحنى (أو أكثر) بيزيه. تُرسم المنحنيات باستخدام القلم الحالي.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


يحدد هذا السجل مضلعًا يتكوّن من نقطتين أو أكثر متصلة بخطوط مستقيمة. يُحدّد المضلع باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يُغلق المضلع تلقائيًا برسم خط من آخر نقطة إلى الأولى.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


هذا السجل يحدد سلسلة من مقاطع الخط عن طريق ربط النقاط في المصفوفة المحددة.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


يحدد هذا السجل منحنيات بيزيير واحدة أو أكثر بناءً على الموضع الحالي.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


يحدد هذا السجل خطًا (أو أكثر) مستقيمًا استنادًا إلى الموضع الحالي. يُرسم الخط من الموضع الحالي إلى النقطة الأولى المحددة في حقل Points باستخدام القلم الحالي. لكل خط إضافي، يتم الرسم من نقطة نهاية الخط السابق إلى النقطة التالية المحددة في Points.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


هذا السجل يحدد سلاسل متعددة من مقاطع الخط المتصلة.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


يحدد هذا السجل سلسلة من المضلعات المغلقة. يُحدّد كل مضلع باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلعات. يمكن أن تتداخل المضلعات المحددة بهذا السجل.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


هذا السجل يعرّف مجموعة من قطع الخطوط ومنحنيات بيزيه.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


يحدد هذا السجل فرشاة منطقية بنمط البت ماب المحدد. يمكن أن يكون البت ماب قسمًا من نوع bitmap مستقل عن الجهاز (DIB) أو يمكن أن يكون bitmap تابعًا للجهاز.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


يعرّف هذا السجل فرشاة منطقية لها النمط المحدد بواسطة DIB.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


يعرّف هذا السجل قلمًا تجميليًا أو هندسيًا منطقيًا يمتلك النمط والعرض وخصائص الفرشاة المحددة.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


يرسم هذا السجل سلسلة نصية ASCII (واحدة أو أكثر) باستخدام الخط الحالي وألوان النص. ملاحظة: يجب محاكاة EMR\\_POLYTEXTOUTA بسلسلة من سجلات EMR\\_EXTTEXTOUTW، واحدة لكل سلسلة.

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


يرسم هذا السجل سلسلة نصية Unicode (واحدة أو أكثر) باستخدام الخط الحالي وألوان النص. ملاحظة: يجب محاكاة EMR\\_POLYTEXTOUTW بسلسلة من سجلات EMR\\_EXTTEXTOUTW، واحدة لكل سلسلة.

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


يحدد هذا السجل وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


ينشئ هذا السجل كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف ASCII.

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


يعرّف هذا السجل كائن مساحة اللون المنطقية الحالي لعمليات الرسومات.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


يقوم هذا السجل بحذف كائن مساحة لون منطقية. ملاحظة: يجب استخدام سجل EMR\_DELETEOBJECT بدلاً من EMR\_DELETECOLORSPACE لحذف كائن مساحة لون منطقية.

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


يحدد هذا السجل دالة OpenGL.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


يحدد هذا السجل دالة OpenGL مع مستطيل حدود للإخراج.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


يحدد هذا السجل تنسيق البكسل المستخدم لعمليات الرسومات

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


يقوم هذا السجل بتمرير معلومات عشوائية إلى برنامج التشغيل. النية هي أن تؤدي المعلومات إلى تنفيذ الرسم.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


يقوم هذا السجل بتمرير معلومات عشوائية إلى برنامج التشغيل. النية هي أن لا تؤدي المعلومات إلى تنفيذ الرسم.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


يقوم هذا السجل بإخراج سلسلة نصية.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


يجبر هذا السجل مخطط الخطوط على مطابقة الخطوط بناءً على UniversalFontId الخاص بها بدلاً من معلومات LogFont.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


ينقل هذا السجل معلومات عشوائية إلى برنامج التشغيل المسمى المحدد.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


يحدد هذا السجل طريقة تصحيح مدخلات كائن لوحة ألوان منطقية باستخدام قيم نظام ألوان ويندوز (WCS) 1.0

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


يحدد هذا السجل ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف ASCII، للإخراج الرسومي.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


يحدد هذا السجل ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف Unicode، للإخراج الرسومي.

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


يحدد هذا السجل نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، بما في ذلك بيانات الشفافية ألفا، وفقًا لعملية دمج محددة.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


يحدد هذا السجل ترتيب رسم النص والرسومات.

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


يحدد هذا السجل نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، مع اعتبار لون محدد شفافًا، وتمديد أو ضغط الإخراج ليتناسب مع أبعاد الهدف إذا لزم الأمر.

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


يحدد هذا السجل تعبئة المستطيلات أو المثلثات بتدرجات لونية.

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


يضبط هذا السجل قيم UniversalFontIds للخطوط المرتبطة لاستخدامها أثناء البحث عن الأحرف.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


يحدد هذا السجل مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لأغراض الضبط.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


يحدد هذا السجل ما إذا كان سيتم إجراء مطابقة ألوان باستخدام ملف تعريف ألوان محدد في ملف يحمل اسمًا مكوّنًا من أحرف Unicode.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


ينشئ هذا السجل كائن مساحة ألوان منطقية من ملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف Unicode.

