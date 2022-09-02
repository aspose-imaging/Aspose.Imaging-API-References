---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Aspose.Imaging لمرجع NET API
description: تحتوي مساحة الاسم على أنواع MS-EMF تنسيق ملف التعريف المحسن. 2.3 سجلات EMF
type: docs
weight: 360
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/
---
تحتوي مساحة الاسم على أنواع [MS-EMF]: تنسيق ملف التعريف المحسن. 2.3 سجلات EMF

## الطبقات

| فصل | وصف |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | هذا السجل يحبط قوس مسار أو يتجاهل المسار من قوس مسار مغلق. |
| [EmfAlphaBlend](./emfalphablend) | يحدد سجل EMR_ALPHABLEND كتلة نقل وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة ، بما في ذلك بيانات الشفافية ألفا ، وفقًا لعملية مزج محددة . |
| [EmfAngleArc](./emfanglearc) | يحدد سجل EMR_ANGLEARC مقطع خط من قوس. يتم رسم قطعة الخط من الموضع الحالي إلى بداية القوس. يرسم القوس على طول محيط الدائرة مع إعطاء نصف قطر ومركز . يتم تحديد طول القوس من خلال زوايا البداية والكنس المعطاة |
| [EmfArc](./emfarc) | يحدد سجل EMR_ARC قوسًا بيضاويًا. |
| [EmfArcTo](./emfarcto) | يحدد سجل EMR_ARCTO قوسًا بيضاويًا. يعيد تعيين الوضع الحالي إلى نقطة نهاية القوس. |
| [EmfBeginPath](./emfbeginpath) | يفتح هذا السجل قوس مسار في سياق جهاز التشغيل الحالي. بعد فتح قوس المسار ، يمكن للتطبيق بدء معالجة السجلات لتعريف النقاط التي تقع في المسار. يجب على التطبيق إغلاق قوس مسار مفتوح بواسطة معالجة EMR_ENDPATH سجل . عندما يعالج أحد التطبيقات سجل EMR_BEGINPATH ، يجب تجاهل جميع المسارات السابقة من سياق جهاز التشغيل. |
| [EmfBitBlt](./emfbitblt) | يحدد سجل EMR_BITBLT كتلة نقل وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة ، اختياريًا بالاقتران مع نمط الفرشاة ، وفقًا لعملية البيانات النقطية المحددة. |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | تقوم أنواع سجلات الصور النقطية بإجراء عمليات نقل كتلة للصور النقطية. |
| [EmfChord](./emfchord) | يحدد سجل EMR_CHORD الوتر ، وهو منطقة يحدها تقاطع قطع ناقص ومقطع خط ، يسمى القاطع. تم تحديد الوتر باستخدام القلم الحالي وتم تعبئته باستخدام الفرشاة الحالية. |
| [EmfClippingRecordType](./emfclippingrecordtype) | تحدد أنواع سجلات القطع مناطق القطع وتديرها. ملاحظة لا يحدد سجل EMR_SETMETARGN معلمات. |
| [EmfCloseFigure](./emfclosefigure) | هذا السجل يغلق رقمًا مفتوحًا في مسار. يجب أن تغلق معالجة سجل EMR_CLOSEFIGURE الشكل عن طريق رسم line من الموضع الحالي إلى النقطة الأولى من الشكل ، ثم يجب توصيل الخطوط باستخدام نمط ربط السطر. إذا تم إغلاق الرقم عن طريق معالجة سجل EMR_LINETO بدلاً من سجل EMR_CLOSEFIGURE ، فإن قبعات النهاية هي تُستخدم لإنشاء الزاوية بدلاً من الصلة. تم تحديد EMR_LINETO في section 2.3.5.13. يجب استخدام سجل EMR_CLOSEFIGURE فقط إذا كان هناك افتح path bracket في سياق جهاز التشغيل. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | يحدد سجل EMR_COLORCORRECTPALETTE كيفية تصحيح إدخالات كائن palette المنطقي باستخدام قيم WCS 1.0. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | يحدد سجل EMR_COLORMATCHTOTargetW ما إذا كان سيتم إجراء مطابقة اللون مع ملف تعريف color المحدد في ملف باسم يتكون من أحرف Unicode. |
| [EmfComment](./emfcomment) | يحتوي سجل EMR_COMMENT على بيانات خاصة عشوائية. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3. |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | يحدد سجل EMR_COMMENT_BEGINGROUP بداية مجموعة من سجلات الرسم. |
| [EmfCommentEmfPlus](./emfcommentemfplus) | يحتوي سجل EMR_COMMENT_EMFPLUS على سجلات EMF + مضمنة. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3. |
| [EmfCommentEmfSpool](./emfcommentemfspool) | يحتوي سجل EMR_COMMENT_EMFSPOOL على سجلات EMFSPOOL مضمنة. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3. |
| [EmfCommentEndGroup](./emfcommentendgroup) | يحدد سجل EMR_COMMENT_ENDGROUP نهاية مجموعة سجلات الرسم. |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | يحدد سجل EMR_COMMENT_MULTIFORMATS صورة بتنسيقات رسومات متعددة. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | تحدد أنواع سجلات EMR_COMMENT_PUBLIC امتدادات لمعالجة EMF. |
| [EmfCommentRecordType](./emfcommentrecordtype) | تحدد أنواع سجلات التعليقات تنسيقات لتحديد البيانات الخاصة التعسفية ، وتضمين السجلات في تنسيقات ملفات التعريف الأخرى ، وإضافة أوامر جديدة أو ذات غرض خاص. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | يحدد سجل EMR_COMMENT_WINDOWS_METAFILE صورة في ملف تعريف WMF مضمن. |
| [EmfControlRecordType](./emfcontrolrecordtype) | تحدد أنواع سجلات التحكم بداية ونهاية ملف تعريف EMF وخصائص ملف التعريف. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | يحدد سجل EMR_CREATEBRUSHINDIRECT فرشاة منطقية لعمليات الرسومات. |
| [EmfCreateColorSpace](./emfcreatecolorspace) | يُنشئ سجل EMR_CREATECOLORSPACE كائن مساحة لونية منطقية من ملف تعريف لون باسم a يتكون من أحرف ASCII. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | يقوم سجل EMR_CREATECOLORSPACEW بإنشاء كائن مساحة لونية منطقية من ملف تعريف اللون مع اسم يتكون من أحرف Unicode. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | يحدد سجل EMR_CREATEDIBPATTERNBRUSHPT فرشاة نمط لعمليات الرسومات. يتم تحديد نمط بواسطة DIB. |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | يحدد سجل EMR_CREATEMONOBRUSH فرشاة نمط أحادية اللون لعمليات الرسومات . يتم تحديد النمط بواسطة DIB أحادي اللون. |
| [EmfCreatePalette](./emfcreatepalette) | يحدد سجل EMR_CREATEPALETTE لوحة منطقية لعمليات الرسومات. |
| [EmfCreatePen](./emfcreatepen) | يحدد سجل EMR_CREATEPEN قلمًا منطقيًا لعمليات الرسومات. |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | يحذف سجل EMR_DELETECOLORSPACE كائن مساحة لونية منطقية. |
| [EmfDeleteObject](./emfdeleteobject) | يحذف سجل EMR_DELETEOBJECT كائنًا رسوميًا محددًا بواسطة الفهرس الخاص به في جدول كائن EMF (القسم 3.1.1.1) . |
| [EmfDrawEscape](./emfdrawescape) | يمرر سجل EMR_DRAWESCAPE معلومات عشوائية إلى برنامج تشغيل الطابعة. القصد هو أن المعلومات ستؤدي إلى إتمام الرسم. |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | تقوم أنواع سجلات الرسم برسم الرسومات . |
| [EmfEllipse](./emfellipse) | يحدد سجل EMR_ELLIPSE القطع الناقص. مركز القطع الناقص هو مركز المستطيل المحيط المحدد . يتم تحديد القطع الناقص باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية. |
| [EmfEndPath](./emfendpath) | هذا السجل يغلق قوس المسار ويختار المسار المحدد بواسطة القوس في سياق جهاز التشغيل. |
| [EmfEof](./emfeof) | يشير سجل EMR_EOF إلى نهاية ملف التعريف ويحدد لوحًا. |
| [EmfEscapeRecordType](./emfescaperecordtype) | تقوم أنواع سجلات الهروب بتنفيذ وظائف برنامج تشغيل الطابعة. |
| [EmfExcludeClipRect](./emfexcludecliprect) | يحدد سجل EMR_EXCLUDECLIPRECT منطقة لقطة جديدة تتكون من منطقة القطع الحالية مطروحًا منها المستطيل المحدد. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | يحدد سجل EMR_EXTCREATEFONTINDIRECTW خطًا منطقيًا لعمليات الرسومات. |
| [EmfExtCreatePen](./emfextcreatepen) | يعرّف سجل EMR_EXTCREATEPEN قلمًا منطقيًا موسعًا لعمليات الرسومات. يمكن تحديد An DIB الاختياري لاستخدامه كنمط الخط. |
| [EmfExtEscape](./emfextescape) | يمرر سجل EMR_EXTESCAPE معلومات عشوائية إلى برنامج تشغيل الطابعة. القصد هو أن المعلومات لن تؤدي إلى إتمام الرسم. |
| [EmfExtFloodFill](./emfextfloodfill) | يملأ سجل EMR_EXTFLOODFILL مساحة من سطح العرض بالفرشاة الحالية |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | يدمج سجل EMR_EXTSELECTCLIPRGN المنطقة المحددة مع منطقة القصاصة الحالية باستخدام الوضع المحدد. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2. |
| [EmfExtTextOutA](./emfexttextouta) | يرسم سجل EMR_EXTTEXTOUTA سلسلة نص ASCII باستخدام الخط وألوان النص الحالية. |
| [EmfExtTextOutW](./emfexttextoutw) | يرسم سجل EMR_EXTTEXTOUTW سلسلة نص ASCII باستخدام الخط وألوان النص الحالية. |
| [EmfFillPath](./emffillpath) | يغلق سجل EMR_FILLPATH أي أرقام مفتوحة في المسار الحالي ويملأ الجزء الداخلي للمسار بواسطة باستخدام الفرشاة الحالية ووضع ملء المضلع . |
| [EmfFillRgn](./emffillrgn) | يملأ سجل EMR_FILLRGN المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EmfFlatternPath](./emfflatternpath) | يحول هذا السجل أي منحنيات في المسار المحدد إلى سياق تشغيل device ؛ يجب تحويل كل منحنى إلى سلسلة من الخطوط. |
| [EmfForceUfiMapping](./emfforceufimapping) | يفرض سجل EMR_FORCEUFIMAPPING على مخطط الخط أن يطابق الخطوط بناءً على تفضيلهم UniversalFontId على معلومات LogFont (القسم 2.2.13) . |
| [EmfFrameRgn](./emfframergn) | يرسم سجل EMR_FRAMERGN حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | يحدد سجل EMR_GLSBOUNDEDRECORD دالة OpenGL مع مستطيل إحاطة للإخراج. |
| [EmfGlsRecord](./emfglsrecord) | يحدد سجل EMR_GLSRECORD دالة OpenGL. |
| [EmfGradientFill](./emfgradientfill) | يحدد سجل EMR_GRADIENTFILL تعبئة المستطيلات أو المثلثات بتدرجات اللون. |
| [EmfIntersectClipRect](./emfintersectcliprect) | يحدد سجل EMR_INTERSECTCLIPRECT منطقة لقطة جديدة من تقاطع منطقة القطع الحالية والمستطيل المحدد. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2. |
| [EmfInvertRgn](./emfinvertrgn) | سجل EMR_INVERTRGN يعكس الألوان في المنطقة المحددة. |
| [EmfLineTo](./emflineto) | يحدد سجل EMR_LINETO سطرًا من الموضع الحالي حتى النقطة المحددة ولكن لا يشملها. ويعيد تعيين الموضع الحالي إلى النقطة المحددة. |
| [EmfMaskBlt](./emfmaskblt) | يحدد سجل EMR_MASKBLT نقل كتلة وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة ، اختياريًا بالاقتران مع نمط الفرشاة وتطبيق قناع اللون الصورة النقطية ، وفقًا لعمليات المسح النقطية الأمامية والخلفية المحددة. |
| [EmfMetafileHeader](./emfmetafileheader) | تحدد أنواع سجلات EMR_HEADER نقاط البداية لملفات تعريف EMF وتحدد خصائص الجهاز الذي تم إنشاء الصورة في ملف التعريف عليه. تتيح المعلومات الموجودة في سجل الرأس إمكانية أن تكون ملفات تعريف EMF مستقلة عن أي جهاز إخراج محدد. headers: رأس القاعدة ، وهو سجل EmfMetafileHeader . الجزء ذو الحجم الثابت من هذا الرأس هو 88 بايت ، ويحتوي على كائن Header . رأس الامتداد الأول ، وهو سجل EmfMetafileHeaderExtension1 . الحجم الثابت جزء من هذا الرأس هو 100 بايت ، ويحتوي على كائن Header وكائن HeaderExtension1 (القسم 2.2.10) . رأس التمديد الثاني ، وهو سجل EmfMetafileHeaderExtension2 . الجزء ذي الحجم الثابت من هذا الرأس هو 108 بايت ، ويحتوي على كائن رأس ، كائن HeaderExtension1 ، وكائن HeaderExtension2 (القسم 2.2.11) . |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | سجل EmfMetafileHeaderExtension1 هو سجل الرأس المستخدم في الامتداد الأول لملفات تعريف EMF . بعد حقل EmfHeaderExtension1 ، تكون الحقول المتبقية اختيارية ويمكن أن تكون موجودة بأي ترتيب. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | سجل EmfMetafileHeaderExtension2 هو سجل الرأس المستخدم في الملحق الثاني لملفات التعريف EMF . بعد حقل EmfHeaderExtension2 ، تكون الحقول المتبقية اختيارية ويمكن أن تكون موجودة بأي ترتيب. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | يعدل سجل EMR_MODIFYWORLDTRANSFORM مساحة العالم الحالية لتحويل مساحة الصفحة في سياق جهاز التشغيل. |
| [EmfMoveToEx](./emfmovetoex) | يحدد سجل EMR_MOVETOEX إحداثيات الموضع الحالي الجديد بالوحدات المنطقية. |
| [EmfNamedEscape](./emfnamedescape) | يمرر سجل MR_NAMATESCAPE معلومات عشوائية إلى برنامج تشغيل طابعة محدد. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | تقوم أنواع سجلات إنشاء الكائن بإنشاء كائنات رسومية. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | تقوم أنواع سجلات معالجة الكائن بإدارة وتعديل كائنات الرسومات. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | ينقل سجل EMR_OFFSETCLIPRGN منطقة القطع الحالية في سياق جهاز التشغيل بواسطة الإزاحات المحددة. |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | تحدد أنواع سجلات OpenGL وظائف OpenGL. |
| [EmfPaintRgn](./emfpaintrgn) | يرسم سجل EMR_PAINTRGN المنطقة المحددة باستخدام الفرشاة المحددة حاليًا في سياق جهاز التشغيل . |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | تحدد أنواع سجلات قوس المسار المسارات وتعالجها في أقواس المسار . ملاحظة: لا تحدد أي من سجلات قوس المسار المعلمات. |
| [EmfPie](./emfpie) | يحدد سجل EMR_PIE إسفينًا دائري الشكل يحده تقاطع قطع ناقص وشعاعين . يتم تحديد الدائرة باستخدام القلم الحالي وتعبئتها باستخدام الفرشاة الحالية. |
| [EmfPixelFormat](./emfpixelformat) | يحدد سجل EMR_PIXELFORMAT تنسيق البكسل لاستخدامه في عمليات الرسومات. |
| [EmfPlgBlt](./emfplgblt) | يحدد سجل EMR_PLGBLT كتلة نقل وحدات البكسل من الصورة النقطية المصدر إلى الوجهة متوازي الأضلاع ، مع تطبيق صورة نقطية لقناع اللون. |
| [EmfPolyBezier](./emfpolybezier) | يحدد سجل EMR_POLYBEZIER واحدًا أو أكثر من منحنيات Bezier . |
| [EmfPolyBezier16](./emfpolybezier16) | يحدد سجل EMR_POLYBEZIER16 واحدًا أو أكثر من منحنيات Bezier. يتم رسم المنحنيات باستخدام القلم الحالي. |
| [EmfPolyBezierTo](./emfpolybezierto) | يحدد سجل EMR_POLYBEZIERTO واحدًا أو أكثر من منحنيات Bezier بناءً على الموضع الحالي. |
| [EmfPolyBezierTo16](./emfpolybezierto16) | يحدد سجل EMR_POLYBEZIERTO16 واحدًا أو أكثر من منحنيات بيزير بناءً على الوضع الحالي. |
| [EmfPolyDraw](./emfpolydraw) | يحدد سجل EMR_POLYDRAW مجموعة من مقاطع الخطوط ومنحنيات بيزير. |
| [EmfPolyDraw16](./emfpolydraw16) | يحدد سجل EMR_POLYDRAW16 مجموعة من مقاطع الخطوط ومنحنيات بيزير. |
| [EmfPolygon](./emfpolygon) | يحدد سجل EMR_POLYGON مضلعًا يتكون من رأسين أو أكثر متصلين بخطوط مستقيمة . |
| [EmfPolygon16](./emfpolygon16) | يحدد السجل EMR_POLYGON16 مضلعًا يتكون من رأسين أو أكثر متصلين بخطوط مستقيمة . يتم تحديد المضلع باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يتم إغلاق المضلع تلقائيًا عن طريق رسم خط من الرأس الأخير إلى الأول. |
| [EmfPolyline](./emfpolyline) | يحدد سجل EMR_POLYLINE سلسلة من مقاطع الخطوط عن طريق توصيل النقاط في المصفوفة المحددة . |
| [EmfPolyline16](./emfpolyline16) | يحدد سجل EMR_POLYLINE16 سلسلة من مقاطع الخطوط عن طريق توصيل النقاط في المصفوفة المحددة . |
| [EmfPolylineTo](./emfpolylineto) | يحدد سجل EMR_POLYLINETO خطًا مستقيمًا واحدًا أو أكثر بناءً على الموضع الحالي. |
| [EmfPolylineTo16](./emfpolylineto16) | يحدد سجل EMR_POLYLINETO16 خطًا مستقيمًا واحدًا أو أكثر بناءً على الموضع الحالي. يتم رسم خط من الموضع الحالي إلى النقطة الأولى المحددة بواسطة حقل aPoints باستخدام القلم الحالي . لكل سطر إضافي ، يتم الرسم من نقطة نهاية السطر السابق إلى النقطة التالية المحددة بواسطة النقاط. |
| [EmfPolyPolygon](./emfpolypolygon) | يحدد سجل EMR_POLYPOLYGON سلسلة من المضلعات المغلقة. |
| [EmfPolyPolygon16](./emfpolypolygon16) | يحدد سجل EMR_POLYPOLYGON16 سلسلة من المضلعات المغلقة. يتم تحديد كل مضلع باستخدام القلم الحالي ، ويتم تعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يمكن أن تتداخل المضلعات المرسومة بواسطة هذا السجل. |
| [EmfPolyPolyline](./emfpolypolyline) | يحدد سجل EMR_POLYPOLYLINE سلاسل متعددة من مقاطع الخطوط المتصلة. |
| [EmfPolyPolyline16](./emfpolypolyline16) | يحدد سجل EMR_POLYPOLYLINE16 سلاسل متعددة من مقاطع الخط المتصلة. |
| [EmfPolyTextOutA](./emfpolytextouta) | يرسم سجل EMR_POLYTEXTOUTA واحدًا أو أكثر من سلاسل نص ASCII باستخدام الخط الحالي وألوان النص. |
| [EmfPolyTextOutW](./emfpolytextoutw) | يرسم سجل EMR_POLYTEXTOUTW واحدًا أو أكثر من سلاسل نص Unicode باستخدام الخط الحالي وألوان النص. |
| [EmfRealizePalette](./emfrealizepalette) | يقوم هذا السجل بتعيين إدخالات اللوحة من كائن LogPalette الحالي (القسم 2.2.17) إلى لوحة system_palette. لا يحدد سجل EMF هذا أي معلمات. |
| [EmfRecord](./emfrecord) | الفئة الأساسية لسجلات EMF يجب أن يكون طول كافة سجلات EMF مضاعف 4 بايت. تم توضيح ذلك في الهياكل العامة لأنواع سجلات EMF السابقة من خلال تضمين حقول AlignmentPadding حيثما كان ذلك مناسبًا في نهايات هذه الهياكل. محتويات حقول AlignmentPadding يجب دائمًا تجاهلها. للإيجاز ، لا تظهر هذه الحقول في كل تعريف سجل EMF فردي. |
| [EmfRectangle](./emfrectangle) | يرسم سجل EMR_RECTANGLE مستطيلاً. تم تحديد المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية. |
| [EmfResizePalette](./emfresizepalette) | يزيد سجل EMR_RESIZEPALETTE أو ينقص حجم كائن LogPalette الموجود (القسم 2.2.17) . |
| [EmfRestoreDc](./emfrestoredc) | يستعيد سجل EMR_RESTOREDC سياق جهاز التشغيل إلى الحالة المحددة. تتم استعادة سياق جهاز التشغيل عن طريق إظهار معلومات الحالة من مكدس تم إنشاؤه بواسطة سجلات EMR_SAVEDC السابقة (القسم 2.3.11) . |
| [EmfRop4](./emfrop4) | عملية نقطية رباعية تحدد العمليات النقطية الثلاثية لـ ألوان المقدمة والخلفية للصورة النقطية. تحدد هذه القيم كيفية دمج بيانات اللون الخاصة بالمستطيل المصدر مع بيانات لون المستطيل الوجهة. |
| [EmfRoundRect](./emfroundrect) | يحدد السجل EMR_ROUNDRECT مستطيلاً بزوايا دائرية. تم تحديد المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية. |
| [EmfSaveDc](./emfsavedc) | يحفظ الحالة الحالية لسياق جهاز التشغيل على a كومة من الحالات المحفوظة بواسطة سجلات EMR_SAVEDC السابقة ، إن وجدت. تتكون الحالة من خصائص الرسومات والكائنات ، بما في ذلك الصورة النقطية المحددة حاليًا والفرشاة واللوحة والخط والقلم والمنطقة المحددة حاليًا. يتم استخدام سجل An EMR_RESTOREDC لاستعادة الحالة . لا يحدد سجل EMF هذا أي معلمات. |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | يقوم سجل EMR_SCALEVIEWPORTEXTEX بإعادة تحديد منفذ العرض لسياق الجهاز باستخدام نسب التي تم تكوينها بواسطة المضاعفات والمقسومات المحددة. |
| [EmfScaleWindowExtex](./emfscalewindowextex) | يعيد سجل EMR_SCALEWINDOWEXTEX تحديد النافذة الخاصة بسياق جهاز التشغيل بواسطة باستخدام النسب التي شكلتها المضاعفات والمقسومات المحددة. |
| [EmfSelectClipPath](./emfselectclippath) | يحدد سجل EMR_SELECTCLIPPATH المسار الحالي كمنطقة لقطة لسياق جهاز التشغيل ، مع دمج المنطقة الجديدة مع أي منطقة قطع موجودة باستخدام الوضع المحدد. |
| [EmfSelectObject](./emfselectobject) | يضيف السجل EMR_SELECTOBJECT كائنًا رسوميًا إلى سياق تشغيل ملف التعريف الحالي device . يتم تحديد الكائن إما عن طريق الفهرس الخاص به في جدول كائن EMF (القسم 3.1.1.1) أو من خلال قيمته من تعداد StockObject (القسم 2.1.31) . |
| [EmfSelectPalette](./emfselectpalette) | يحدد سجل EMR_SELECTPALETTE لوحة منطقية لسياق جهاز التشغيل. |
| [EmfSetArcDirection](./emfsetarcdirection) | يحدد سجل EMR_SETARCDIRECTION اتجاه الرسم الذي سيتم استخدامه لإخراج القوس والمستطيل. |
| [EmfSetBkColor](./emfsetbkcolor) | يحدد سجل EMR_SETBKCOLOR لون الخلفية. |
| [EmfSetBkMode](./emfsetbkmode) | يحدد سجل EMR_SETBKMODE وضع مزج الخلفية لسياق جهاز التشغيل. يتم استخدام وضع مزيج الخلفية مع النص ، والفرش المتدرجة ، وأنماط القلم التي ليست خطوطًا صلبة . |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | يحدد سجل EMR_SETBRUSHORGEX أصل الفرشاة الحالية. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | يحدد سجل EMR_SETCOLORADJUSTMENT خصائص ضبط اللون في سياق التشغيل للجهاز. |
| [EmfSetColorSpace](./emfsetcolorspace) | يحدد سجل EMR_SETCOLORSPACE كائن مساحة اللون المنطقي الحالي لعمليات الرسومات. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | يحدد سجل EMR_SETDIBITSTODEVICE نقل كتلة البكسل من خطوط المسح المحددة من صورة نقطية المصدر إلى مستطيل الوجهة. |
| [EmfSetIcmMode](./emfseticmmode) | يحدد سجل EMR_SETICMMODE وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات. |
| [EmfSetIcmProfileA](./emfseticmprofilea) | يحدد سجل EMR_SETICMPROFILEA ملف تعريف اللون في ملف باسم يتكون من أحرف ASCII ، لإخراج الرسومات. |
| [EmfSetIcmProfileW](./emfseticmprofilew) | يحدد سجل EMR_SETICMPROFILEW ملف تعريف اللون في ملف باسم يتألف من أحرف Unicode ، لإخراج الرسومات. |
| [EmfSetLayout](./emfsetlayout) | يحدد سجل EMR_SETLAYOUT الترتيب الذي يتم به رسم النص والرسومات. |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | يعيّن سجل EMR_SETLINKEDUFIS UniversalFontIds (القسم 2.2.27) للخطوط المرتبطة لاستخدامها أثناء البحث عن الأحرف. |
| [EmfSetMapMode](./emfsetmapmode) | يحدد سجل EMR_SETMAPMODE وضع التعيين لسياق جهاز التشغيل. يحدد وضع التعيين وحدة القياس المستخدمة لتحويل وحدات مساحة الصفحة إلى وحدات مساحة الجهاز ، كما يحدد اتجاه المحور السيني والمحور الصادي للجهاز. |
| [EmfSetMapperFlags](./emfsetmapperflags) | يحدد سجل EMR_SETMAPPERFLAGS معلمات عملية مطابقة الخطوط المنطقية إلى الخطوط الفعلية ، والتي يتم تنفيذها بواسطة مخطط الخط. |
| [EmfSetMetaRgn](./emfsetmetargn) | يعيّن Inter منطقة التعريف الحالية مع منطقة القطع الحالية لتشكيل منطقة تعريف جديدة لسياق جهاز التشغيل. يجب إعادة تعيين منطقة القطع الحالية إلى خالية. لا يحدد سجل EMF هذا أي معلمات. |
| [EmfSetMiterLimit](./emfsetmiterlimit) | يحدد سجل EMR_SETMITERLIMIT الحد الأقصى لطول وصلات ميتري لسياق جهاز التشغيل. |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | يحدد سجل EMR_SETPALETTEENTRIES قيم ألوان RGB في نطاق من الإدخالات لكائن لوح ألوان موجود (القسم 2.2.17). |
| [EmfSetPixelV](./emfsetpixelv) | يحدد سجل EMR_SETPIXELV لون البكسل في الإحداثيات المنطقية المحددة. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | يحدد سجل EMR_SETPOLYFILLMODE وضع تعبئة المضلع. |
| [EmfSetRop2](./emfsetrop2) | يحدد سجل EMR_SETROP2 وضع عملية البيانات النقطية الثنائية. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | يحدد سجل EMR_SETSTRETCHBLTMODE وضع امتداد الصورة النقطية. |
| [EmfSetTextAlign](./emfsettextalign) | يحدد سجل EMR_SETTEXTALIGN محاذاة النص. |
| [EmfSetTextColor](./emfsettextcolor) | يحدد سجل EMR_SETTEXTCOLOR لون النص الحالي. |
| [EmfSetTextJustification](./emfsettextjustification) | يحدد سجل EMR_SETTEXTJUSTIFICATION مقدار المساحة الإضافية لإضافتها إلى break الأحرف لضبط النص. |
| [EmfSetViewportExtEx](./emfsetviewportextex) | يحدد سجل EMR_SETVIEWPORTEXTEX مدى منفذ العرض. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | يحدد سجل EMR_SETVIEWPORTORGEX أصل منفذ العرض. |
| [EmfSetWindowExtEx](./emfsetwindowextex) | يحدد سجل EMR_SETWINDOWEXTEX مدى النافذة. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | يحدد سجل EMR_SETWINDOWORGEX أصل النافذة. |
| [EmfSetWorldTransform](./emfsetworldtransform) | يحدد سجل EMR_SETWORLDTRANSFORM تحويلاً لفضاء العالم الحالي إلى مساحة الصفحة في سياق جهاز التشغيل. |
| [EmfSmallTextOut](./emfsmalltextout) | ينتج عن سجل EMR_SMALLTEXTOUT سلسلة. |
| [EmfStateRecordType](./emfstaterecordtype) | تحدد أنواع سجلات الحالة وتدير خصائص الرسومات التي تحدد حالة سياق جهاز التشغيل. |
| [EmfStretchBlt](./emfstretchblt) | يحدد سجل EMR_STRETCHBLT نقل كتلة وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة ، اختياريًا بالاقتران مع نمط الفرشاة ، وفقًا لعملية raster المحددة ، أو تمديد أو ضغط الإخراج لملاءمة أبعاد الوجهة ، إذا لزم الأمر . |
| [EmfStretchDiBits](./emfstretchdibits) | يحدد سجل EMR_STRETCHDIBITS كتلة نقل وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة ، اختياريًا بالاقتران مع نمط الفرشاة ، وفقًا لعملية تحديد نقطية ، أو تمديد أو ضغط الإخراج لملاءمة أبعاد الوجهة ، إذا من الضروري. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | يغلق سجل EMR_STROKEANDFILLPATH أي أرقام مفتوحة في المسار ، ويضرب مخطط مسار باستخدام القلم الحالي ، ويملأ الجزء الداخلي باستخدام الفرشاة الحالية. |
| [EmfStrokePath](./emfstrokepath) | EMR_STROKEPATH class |
| [EmfTransformRecordType](./emftransformrecordtype) | تحدد أنواع سجلات التحويل وتعديل مساحة العالم لتحويل مساحة الصفحة. |
| [EmfTransparentBlt](./emftransparentblt) | يحدد سجل EMR_TRANSPARENTBLT نقل كتلة وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة ، مع معاملة اللون المحدد على أنه شفاف ، أو تمديد أو ضغط الإخراج لملاءمة أبعاد الوجهة ، إذا لزم الأمر |
| [EmfVertexData](./emfvertexdata) | كائنات تحدد رؤوس المستطيلات أو المثلثات و الألوان التي تتوافق معها. |
| [EmfWidenPath](./emfwidenpath) | يعيد هذا السجل تحديد المسار الحالي على أنه المنطقة التي سيتم رسمها إذا تم رسم المسار باستخدام القلم المحدد حاليًا في سياق جهاز التشغيل. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
