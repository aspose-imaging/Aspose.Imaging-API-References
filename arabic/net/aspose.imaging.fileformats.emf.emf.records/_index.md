---
title: "Aspose.Imaging.FileFormats.Emf.Emf.Records"
second_title: "Aspose.Imaging for .NET API Reference"
description: "مساحة الأسماء تحتوي على الأنواع MSEMF تنسيق ميتافايل محسن. سجلات EMF 2.3."
type: docs
weight: 400
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/
---
مساحة الأسماء تحتوي على الأنواع [MS-EMF]: Enhanced Metafile Format. 2.3 EMF Records

## الفئات

| الفئة | الوصف |
| --- | --- |
| [EmfAbortPath](./emfabortpath/) | يسجل هذا السجل إلغاء قوس مسار أو حذف المسار من قوس مسار مغلق. |
| [EmfAlphaBlend](./emfalphablend/) | يسجل EMR_ALPHABLEND عملية نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، بما في ذلك بيانات الشفافية ألفا، وفقًا لعملية دمج محددة. |
| [EmfAngleArc](./emfanglearc/) | يسجل EMR_ANGLEARC مقطع خط لقوس. يُرسم مقطع الخط من الموضع الحالي إلى بداية القوس. يُرسم القوس على محيط دائرة ذات نصف قطر ومركز محددين. يُحدد طول القوس بزاوية البدء وزاوية المسح المحددتين. |
| [EmfArc](./emfarc/) | يسجل EMR_ARC قوسًا إهليلجيًا. |
| [EmfArcTo](./emfarcto/) | يسجل EMR_ARCTO قوسًا إهليلجيًا. يعيد تعيين الموضع الحالي إلى نقطة النهاية للقوس. |
| [EmfBeginPath](./emfbeginpath/) | يفتح هذا السجل قوس مسار في سياق جهاز التشغيل الحالي. بعد فتح قوس المسار، يمكن للتطبيق بدء معالجة السجلات لتحديد النقاط الموجودة في المسار. يجب على التطبيق إغلاق قوس مسار مفتوح بمعالجة سجل EMR_ENDPATH. عند معالجة التطبيق لسجل EMR_BEGINPATH، يجب إلغاء جميع المسارات السابقة من سياق جهاز التشغيل. |
| [EmfBitBlt](./emfbitblt/) | يسجل EMR_BITBLT عملية نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة. |
| [EmfBitmapRecordType](./emfbitmaprecordtype/) | أنواع سجلات الصورة النقطية تقوم بنقل كتل من صور نقطية. |
| [EmfBoundedRecord](./emfboundedrecord/) | فئة متعددة الأشكال الأساسية EMF. |
| [EmfChord](./emfchord/) | يسجل EMR_CHORD وترًا، وهو منطقة محصورة بتقاطع إهليلج وخط مقطع يُسمى قاطع. يُرسم حدود الوتر باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية. |
| [EmfClippingRecordType](./emfclippingrecordtype/) | أنواع سجلات القص تحدد وتدير مناطق القص. ملاحظة: سجل EMR_SETMETARGN لا يحدد معلمات. |
| [EmfCloseFigure](./emfclosefigure/) | يغلق هذا السجل شكلًا مفتوحًا في مسار. يجب أن يغلق سجل EMR_CLOSEFIGURE الشكل عن طريق رسم خط من الموضع الحالي إلى أول نقطة في الشكل، ثم يجب ربط الخطوط باستخدام نمط وصل الخط. إذا تم إغلاق الشكل بمعالجة سجل EMR_LINETO بدلاً من سجل EMR_CLOSEFIGURE، تُستخدم نهايات الخط لإنشاء الزاوية بدلاً من الوصل. يُحدد EMR_LINETO في القسم 2.3.5.13. يجب استخدام سجل EMR_CLOSEFIGURE فقط إذا كان هناك قوس مسار مفتوح في سياق جهاز التشغيل. يظل الشكل في المسار مفتوحًا ما لم يتم إغلاقه صراحةً بمعالجة هذا السجل. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette/) | يسجل EMR_COLORCORRECTPALETTE كيفية تصحيح مدخلات كائن لوحة ألوان منطقية باستخدام قيم WCS 1.0. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw/) | يسجل EMR_COLORMATCHTOTargetW ما إذا كان يجب إجراء مطابقة ألوان باستخدام ملف تعريف ألوان محدد في ملف يحمل اسمًا مكوّنًا من أحرف Unicode. |
| [EmfComment](./emfcomment/) | سجل EMR_COMMENT يحتوي على بيانات خاصة عشوائية. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3. |
| [EmfCommentBeginGroup](./emfcommentbegingroup/) | سجل EMR_COMMENT_BEGINGROUP يحدد بداية مجموعة من سجلات الرسم. |
| [EmfCommentEmfPlus](./emfcommentemfplus/) | سجل EMR_COMMENT_EMFPLUS يحتوي على سجلات EMF+ مدمجة. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3. |
| [EmfCommentEmfSpool](./emfcommentemfspool/) | سجل EMR_COMMENT_EMFSPOOL يحتوي على سجلات EMFSPOOL مدمجة. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3. |
| [EmfCommentEndGroup](./emfcommentendgroup/) | سجل EMR_COMMENT_ENDGROUP يحدد نهاية مجموعة من سجلات الرسم. |
| [EmfCommentMultiFormats](./emfcommentmultiformats/) | سجل EMR_COMMENT_MULTIFORMATS يحدد صورة بأكثر من تنسيق رسومي. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype/) | أنواع سجلات EMR_COMMENT_PUBLIC تحدد امتدادات لمعالجة EMF. |
| [EmfCommentRecordType](./emfcommentrecordtype/) | أنواع سجلات التعليق تعرف صيغًا لتحديد بيانات خاصة عشوائية، ودمج السجلات في صيغ ملفات ميتا أخرى، وإضافة أوامر جديدة أو ذات غرض خاص. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile/) | سجل EMR_COMMENT_WINDOWS_METAFILE يحدد صورة في ملف ميتا WMF مدمج. |
| [EmfControlRecordType](./emfcontrolrecordtype/) | أنواع سجلات التحكم تعرف بداية ونهاية ملف ميتا EMF وخصائص الملف. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect/) | سجل EMR_CREATEBRUSHINDIRECT يعرف فرشاة منطقية لعمليات الرسوم. |
| [EmfCreateColorSpace](./emfcreatecolorspace/) | سجل EMR_CREATECOLORSPACE ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف ASCII. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew/) | سجل EMR_CREATECOLORSPACEW ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف Unicode. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt/) | سجل EMR_CREATEDIBPATTERNBRUSHPT يعرف فرشاة نمطية لعمليات الرسوم. النمط محدد بواسطة DIB. |
| [EmfCreateMonoBrush](./emfcreatemonobrush/) | سجل EMR_CREATEMONOBRUSH يعرف فرشاة نمط أحادية اللون لعمليات الرسوم. النمط محدد بواسطة DIB أحادي اللون. |
| [EmfCreatePalette](./emfcreatepalette/) | سجل EMR_CREATEPALETTE يعرف لوحة ألوان منطقية لعمليات الرسوم. |
| [EmfCreatePen](./emfcreatepen/) | سجل EMR_CREATEPEN يعرف قلمًا منطقيًا لعمليات الرسوم. |
| [EmfDeleteColorSpace](./emfdeletecolorspace/) | سجل EMR_DELETECOLORSPACE يحذف كائن مساحة لون منطقية. |
| [EmfDeleteObject](./emfdeleteobject/) | سجل EMR_DELETEOBJECT يحذف كائن رسومي، يتم تحديده بواسطة فهرسه في جدول كائنات EMF (القسم 3.1.1.1). |
| [EmfDrawEscape](./emfdrawescape/) | سجل EMR_DRAWESCAPE يمرر معلومات عشوائية إلى برنامج تشغيل الطابعة. الهدف هو أن تؤدي هذه المعلومات إلى تنفيذ الرسم. |
| [EmfDrawingRecordType](./emfdrawingrecordtype/) | أنواع سجلات الرسم تقوم بتنفيذ رسومات الرسوميات. |
| [EmfEllipse](./emfellipse/) | سجل EMR_ELLIPSE يحدد إهليلجًا. مركز الإهليلج هو مركز المستطيل المحدد كحدود. يتم تحديد حدود الإهليلج باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية. |
| [EmfEndPath](./emfendpath/) | هذا السجل يغلق قوس مسار ويختار المسار المحدد بواسطة القوس إلى سياق جهاز التشغيل. |
| [EmfEof](./emfeof/) | سجل EMR_EOF يشير إلى نهاية ملف الميتا ويحدد لوحة ألوان. |
| [EmfEscapeRecordType](./emfescaperecordtype/) | أنواع سجلات الهروب تنفذ وظائف برنامج تشغيل الطابعة. |
| [EmfExcludeClipRect](./emfexcludecliprect/) | سجل EMR_EXCLUDECLIPRECT يحدد منطقة قص جديدة تتكون من منطقة القص الحالية مطروحًا منها المستطيل المحدد. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw/) | سجل EMR_EXTCREATEFONTINDIRECTW يعرّف خطًا منطقيًا لعمليات الرسومات. |
| [EmfExtCreatePen](./emfextcreatepen/) | سجل EMR_EXTCREATEPEN يعرّف قلمًا منطقيًا ممتدًا لعمليات الرسومات. يمكن تحديد DIB اختياري لاستخدامه كنمط للخط. |
| [EmfExtEscape](./emfextescape/) | سجل EMR_EXTESCAPE يمرّر معلومات عشوائية إلى برنامج تشغيل الطابعة. الهدف هو أن لا تؤدي هذه المعلومات إلى تنفيذ أي رسم. |
| [EmfExtFloodFill](./emfextfloodfill/) | سجل EMR_EXTFLOODFILL يملأ مساحة من سطح العرض بالفرشاة الحالية |
| [EmfExtSelectClipRgn](./emfextselectcliprgn/) | سجل EMR_EXTSELECTCLIPRGN يجمع المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2. |
| [EmfExtTextOutA](./emfexttextouta/) | سجل EMR_EXTTEXTOUTA يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص. |
| [EmfExtTextOutW](./emfexttextoutw/) | سجل EMR_EXTTEXTOUTW يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص. |
| [EmfFillPath](./emffillpath/) | سجل EMR_FILLPATH يغلق أي أشكال مفتوحة في المسار الحالي ويملأ داخل المسار باستخدام الفرشاة الحالية ووضع ملء المضلع. |
| [EmfFillRgn](./emffillrgn/) | سجل EMR_FILLRGN يملأ المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EmfFlatternPath](./emfflatternpath/) | هذا السجل يحوّل أي منحنيات في المسار المحدد إلى سياق جهاز التشغيل؛ يجب تحويل كل منحنى إلى سلسلة من الخطوط. |
| [EmfForceUfiMapping](./emfforceufimapping/) | سجل EMR_FORCEUFIMAPPING يجبر مُطابق الخطوط على مطابقة الخطوط بناءً على UniversalFontId بدلاً من معلومات LogFont (القسم 2.2.13). |
| [EmfFrameRgn](./emfframergn/) | سجل EMR_FRAMERGN يرسم إطارًا حول المنطقة المحددة باستخدام الفرشاة المحددة. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord/) | سجل EMR_GLSBOUNDEDRECORD يحدد دالة OpenGL مع مستطيل حدود للإخراج. |
| [EmfGlsRecord](./emfglsrecord/) | سجل EMR_GLSRECORD يحدد دالة OpenGL. |
| [EmfGradientFill](./emfgradientfill/) | سجل EMR_GRADIENTFILL يحدد ملء المستطيلات أو المثلثات بتدرجات اللون. |
| [EmfIntersectClipRect](./emfintersectcliprect/) | سجل EMR_INTERSECTCLIPRECT يحدد منطقة قص جديدة من تقاطع منطقة القص الحالية والمستطيل المحدد. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2. |
| [EmfInvertRgn](./emfinvertrgn/) | سجل EMR_INVERTRGN يعكس الألوان في المنطقة المحددة. |
| [EmfLineTo](./emflineto/) | سجل EMR_LINETO يحدد خطًا من الموضع الحالي حتى، ولكن لا يشمل، النقطة المحددة. يعيد ضبط الموضع الحالي إلى النقطة المحددة. |
| [EmfMaskBlt](./emfmaskblt/) | سجل EMR_MASKBLT يحدد نقلًا كتليًا للبكسلات من صورة مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة وتطبيق صورة قناع لون، وفقًا لعمليات الراستر المحددة للأمام والخلف. |
| [EmfMetafileHeader](./emfmetafileheader/) | أنواع سجلات EMR_HEADER تحدد نقاط البداية لملفات EMF الوصفية وتحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل الملف الوصفي. تجعل المعلومات في سجل الرأس ملفات EMF مستقلة عن أي جهاز إخراج محدد. يمكن استخدام قيمة حقل Size للتمييز بين أنواع سجلات EMR_HEADER المختلفة المذكورة سابقًا في هذا القسم. هناك ثلاثة رؤوس محتملة: الرأس الأساسي، وهو سجل EmfMetafileHeader. الجزء ثابت الحجم من هذا الرأس هو 88 بايت، ويحتوي على كائن Header. رأس الامتداد الأول، وهو سجل EmfMetafileHeaderExtension1. الجزء ثابت الحجم من هذا الرأس هو 100 بايت، ويحتوي على كائن Header وكائن HeaderExtension1 (القسم 2.2.10). رأس الامتداد الثاني، وهو سجل EmfMetafileHeaderExtension2. الجزء ثابت الحجم من هذا الرأس هو 108 بايت، ويحتوي على كائن Header، وكائن HeaderExtension1، وكائن HeaderExtension2 (القسم 2.2.11). |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1/) | سجل EmfMetafileHeaderExtension1 هو سجل الرأس المستخدم في الامتداد الأول لملفات EMF الوصفية. بعد حقل EmfHeaderExtension1، تكون الحقول المتبقية اختيارية ويمكن أن تظهر بأي ترتيب. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2/) | سجل EmfMetafileHeaderExtension2 هو سجل الرأس المستخدم في الامتداد الثاني لملفات EMF الوصفية. بعد حقل EmfHeaderExtension2، تكون الحقول المتبقية اختيارية ويمكن أن تظهر بأي ترتيب. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform/) | سجل EMR_MODIFYWORLDTRANSFORM يغيّر تحويل الفضاء العالمي الحالي إلى فضاء الصفحة في سياق جهاز التشغيل. |
| [EmfMoveToEx](./emfmovetoex/) | سجل EMR_MOVETOEX يحدد إحداثيات الموضع الحالي الجديد، بوحدات منطقية. |
| [EmfNamedEscape](./emfnamedescape/) | يسلم سجل MR_NAMEDESCAPE معلومات عشوائية إلى برنامج تشغيل طابعة محدد. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype/) | أنواع سجلات إنشاء الكائنات تنشئ كائنات رسومية. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype/) | أنواع سجلات معالجة الكائنات تدير وتعدل الكائنات الرسومية. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn/) | يقوم سجل EMR_OFFSETCLIPRGN بنقل منطقة القص الحالية في سياق جهاز التشغيل وفقًا للإزاحات المحددة. |
| [EmfOpenGlRecordType](./emfopenglrecordtype/) | أنواع سجلات OpenGL تحدد وظائف OpenGL. |
| [EmfPaintRgn](./emfpaintrgn/) | سجل EMR_PAINTRGN يرسم المنطقة المحددة باستخدام الفرشاة المختارة حاليًا في سياق جهاز التشغيل. |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype/) | أنواع سجلات قوس المسار تحدد وتتحكم في المسارات داخل أقواس المسار. ملاحظة: لا تحدد أي من سجلات قوس المسار معلمات. |
| [EmfPie](./emfpie/) | سجل EMR_PIE يحدد شريحة على شكل فطيرة محاطة بتقاطع إهليلج وشعاعين. يتم تحديد حدود الفطيرة باستخدام القلم الحالي وتملأ باستخدام الفرشاة الحالية. |
| [EmfPixelFormat](./emfpixelformat/) | سجل EMR_PIXELFORMAT يحدد تنسيق البكسل المستخدم في عمليات الرسومات. |
| [EmfPlgBlt](./emfplgblt/) | سجل EMR_PLGBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى متوازي أضلاع هدف، مع تطبيق صورة قناع لوني. |
| [EmfPolyBezier](./emfpolybezier/) | سجل EMR_POLYBEZIER يحدد منحنى بيزيه واحد أو أكثر. |
| [EmfPolyBezier16](./emfpolybezier16/) | سجل EMR_POLYBEZIER16 يحدد منحنى بيزيه واحد أو أكثر. تُرسم المنحنيات باستخدام القلم الحالي. |
| [EmfPolyBezierTo](./emfpolybezierto/) | سجل EMR_POLYBEZIERTO يحدد منحنى بيزيه واحد أو أكثر بناءً على الموضع الحالي. |
| [EmfPolyBezierTo16](./emfpolybezierto16/) | سجل EMR_POLYBEZIERTO16 يحدد منحنى بيزيه واحد أو أكثر بناءً على الموضع الحالي. |
| [EmfPolyDraw](./emfpolydraw/) | سجل EMR_POLYDRAW يحدد مجموعة من مقاطع الخطوط ومنحنيات بيزيه. |
| [EmfPolyDraw16](./emfpolydraw16/) | سجل EMR_POLYDRAW16 يحدد مجموعة من مقاطع الخطوط ومنحنيات بيزيه. |
| [EmfPolygon](./emfpolygon/) | سجل EMR_POLYGON يحدد مضلعًا يتكون من نقطتين أو أكثر متصلة بخطوط مستقيمة. |
| [EmfPolygon16](./emfpolygon16/) | سجل EMR_POLYGON16 يحدد مضلعًا يتكون من نقطتين أو أكثر متصلة بخطوط مستقيمة. يتم تحديد حدود المضلع باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يُغلق المضلع تلقائيًا برسم خط من آخر نقطة إلى الأولى. |
| [EmfPolyline](./emfpolyline/) | سجل EMR_POLYLINE يحدد سلسلة من مقاطع الخطوط بربط النقاط في المصفوفة المحددة. |
| [EmfPolyline16](./emfpolyline16/) | سجل EMR_POLYLINE16 يحدد سلسلة من مقاطع الخطوط بربط النقاط في المصفوفة المحددة. |
| [EmfPolylineTo](./emfpolylineto/) | سجل EMR_POLYLINETO يحدد خطًا مستقيمًا واحدًا أو أكثر بناءً على الموضع الحالي. |
| [EmfPolylineTo16](./emfpolylineto16/) | سجل EMR_POLYLINETO16 يحدد خطًا مستقيمًا واحدًا أو أكثر بناءً على الموضع الحالي. يتم رسم خط من الموضع الحالي إلى أول نقطة محددة في حقل aPoints باستخدام القلم الحالي. لكل خط إضافي، يتم الرسم من نقطة نهاية الخط السابق إلى النقطة التالية المحددة في aPoints. |
| [EmfPolyPolygon](./emfpolypolygon/) | سجل EMR_POLYPOLYGON يحدد سلسلة من المضلعات المغلقة. |
| [EmfPolyPolygon16](./emfpolypolygon16/) | سجل EMR_POLYPOLYGON16 يحدد سلسلة من المضلعات المغلقة. كل مضلع يُحدَّد حدوده باستخدام القلم الحالي، ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يمكن أن تتداخل المضلعات المرسومة بواسطة هذا السجل. |
| [EmfPolyPolyline](./emfpolypolyline/) | سجل EMR_POLYPOLYLINE يحدد سلاسل متعددة من مقاطع الخطوط المتصلة. |
| [EmfPolyPolyline16](./emfpolypolyline16/) | سجل EMR_POLYPOLYLINE16 يحدد سلاسل متعددة من المقاطع الخطية المتصلة. |
| [EmfPolyPolyShape](./emfpolypolyshape/) | فئة قاعدة EMF poly polyshape. |
| [EmfPolyShape](./emfpolyshape/) | فئة متعددة الأشكال الأساسية EMF. |
| [EmfPolyTextOutA](./emfpolytextouta/) | سجل EMR_POLYTEXTOUTA يرسم سلسلة نصية واحدة أو أكثر من نوع ASCII باستخدام الخط الحالي وألوان النص. |
| [EmfPolyTextOutW](./emfpolytextoutw/) | سجل EMR_POLYTEXTOUTW يرسم سلسلة نصية واحدة أو أكثر من نوع Unicode باستخدام الخط الحالي وألوان النص. |
| [EmfRealizePalette](./emfrealizepalette/) | هذا السجل يطابق مداخل لوحة الألوان من كائن LogPalette الحالي (القسم 2.2.17) إلى system_palette. لا يحدد هذا السجل EMF أي معلمات. |
| [EmfRecord](./emfrecord/) | الفئة الأساسية لسجلات EMF. يجب أن يكون لجميع سجلات EMF طول يساوي مضاعفًا ل 4 بايت. يتم توضيح ذلك في الهياكل العامة لأنواع سجلات EMF السابقة عن طريق تضمين حقول AlignmentPadding حيثما كان ذلك مناسبًا في نهايات هذه الهياكل. يجب دائمًا تجاهل محتويات حقول AlignmentPadding. للتبسيط، لا تُظهر هذه الحقول في كل تعريف فردي لسجل EMF. |
| [EmfRectangle](./emfrectangle/) | سجل EMR_RECTANGLE يرسم مستطيلًا. يتم تحديد حدود المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية. |
| [EmfResizePalette](./emfresizepalette/) | سجل EMR_RESIZEPALETTE يزيد أو يقلل حجم كائن LogPalette الموجود (القسم 2.2.17). |
| [EmfRestoreDc](./emfrestoredc/) | سجل EMR_RESTOREDC يعيد سياق جهاز التشغيل إلى الحالة المحددة. يتم استعادة سياق جهاز التشغيل عن طريق إلغاء معلومات الحالة من المكدس الذي تم إنشاؤه بواسطة سجلات EMR_SAVEDC السابقة (القسم 2.3.11). |
| [EmfRop4](./emfrop4/) | عملية نقطية رباعية، تحدد عمليات نقطية ثلاثية للألوان الأمامية والخلفية لصور البت. تُعرّف هذه القيم كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الوجهة. |
| [EmfRoundRect](./emfroundrect/) | سجل EMR_ROUNDRECT يحدد مستطيلًا بزوايا مستديرة. يتم تحديد حدود المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية. |
| [EmfSaveDc](./emfsavedc/) | يحفظ الحالة الحالية لسياق جهاز التشغيل على مكدس الحالات التي حفظتها سجلات EMR_SAVEDDC السابقة، إن وجدت. تتكون الحالة من خصائص ورسومات كائنات، بما في ذلك صورة البت، الفرشاة، لوحة الألوان، الخط، القلم، والمنطقة المحددة حاليًا. يُستخدم سجل EMR_RESTOREDC لاستعادة الحالة. لا يحدد هذا السجل EMF أي معلمات. |
| [EmfScaleViewportExtex](./emfscaleviewportextex/) | سجل EMR_SCALEVIEWPORTEXTEX يعيد تحديد نافذة العرض لسياق الجهاز باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة. |
| [EmfScaleWindowExtex](./emfscalewindowextex/) | سجل EMR_SCALEWINDOWEXTEX يعيد تحديد النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة. |
| [EmfSelectClipPath](./emfselectclippath/) | سجل EMR_SELECTCLIPPATH يحدد المسار الحالي كمنطقة قص لسياق جهاز التشغيل، ويجمع المنطقة الجديدة مع أي منطقة قص موجودة باستخدام الوضع المحدد. |
| [EmfSelectObject](./emfselectobject/) | سجل EMR_SELECTOBJECT يضيف كائن رسومي إلى سياق جهاز تشغيل ملف الميتا الحالي. يُحدد الكائن إما بواسطة فهرسه في جدول كائنات EMF (القسم 3.1.1.1) أو بقيمته من تعداد StockObject (القسم 2.1.31). |
| [EmfSelectPalette](./emfselectpalette/) | سجل EMR_SELECTPALETTE يحدد لوحة ألوان منطقية لسياق جهاز التشغيل. |
| [EmfSetArcDirection](./emfsetarcdirection/) | سجل EMR_SETARCDIRECTION يحدد اتجاه الرسم المستخدم لإخراج الأقواس والمستطيلات. |
| [EmfSetBkColor](./emfsetbkcolor/) | سجل EMR_SETBKCOLOR يحدد لون الخلفية. |
| [EmfSetBkMode](./emfsetbkmode/) | سجل EMR_SETBKMODE يحدد وضع خلط الخلفية لسياق جهاز التشغيل. يُستخدم وضع خلط الخلفية مع النص، والفرش المخططة، وأنماط الأقلام التي ليست خطوطًا صلبة. |
| [EmfSetBrushOrgEx](./emfsetbrushorgex/) | سجل EMR_SETBRUSHORGEX يحدد أصل الفرشاة الحالية. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment/) | سجل EMR_SETCOLORADJUSTMENT يحدد خصائص تعديل اللون في سياق جهاز التشغيل. |
| [EmfSetColorSpace](./emfsetcolorspace/) | سجل EMR_SETCOLORSPACE يعرّف كائن مساحة اللون المنطقية الحالية لعمليات الرسومات. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice/) | سجل EMR_SETDIBITSTODEVICE يحدد نقل كتلة من البكسلات من خطوط المسح المحددة لصورة البت المصدر إلى المستطيل الوجهة. |
| [EmfSetIcmMode](./emfseticmmode/) | سجل EMR_SETICMMODE يحدد وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات. |
| [EmfSetIcmProfileA](./emfseticmprofilea/) | سجل EMR_SETICMPROFILEA يحدد ملف تعريف لون في ملف يحمل اسماً مكوّناً من أحرف ASCII، لإخراج الرسومات. |
| [EmfSetIcmProfileW](./emfseticmprofilew/) | سجل EMR_SETICMPROFILEW يحدد ملف تعريف لون في ملف يحمل اسماً مكوّناً من أحرف Unicode، لإخراج الرسومات. |
| [EmfSetLayout](./emfsetlayout/) | سجل EMR_SETLAYOUT يحدد الترتيب الذي تُرسم به النصوص والرسومات. |
| [EmfSetLinkedUfis](./emfsetlinkedufis/) | سجل EMR_SETLINKEDUFIS يضبط UniversalFontIds (القسم 2.2.27) للخطوط المرتبطة لاستخدامها أثناء البحث عن الأحرف. |
| [EmfSetMapMode](./emfsetmapmode/) | سجل EMR_SETMAPMODE يحدد وضعية التخطيط لسياق جهاز التشغيل. وضعية التخطيط تحدد وحدة القياس المستخدمة لتحويل وحدات مساحة الصفحة إلى وحدات مساحة الجهاز، وتحدد أيضاً اتجاه محور x ومحور y للجهاز. |
| [EmfSetMapperFlags](./emfsetmapperflags/) | سجل EMR_SETMAPPERFLAGS يحدد معلمات عملية مطابقة الخطوط المنطقية مع الخطوط الفعلية، التي يقوم بها مُطابق الخطوط. |
| [EmfSetMetaRgn](./emfsetmetargn/) | Inter يضبط المنطقة الوصفية الحالية مع منطقة القص الحالية لتشكيل منطقة وصفية جديدة لسياق جهاز التشغيل. يجب إعادة تعيين منطقة القص الحالية إلى null. لا يحدد سجل EMF هذا أي معلمات. |
| [EmfSetMiterLimit](./emfsetmiterlimit/) | سجل EMR_SETMITERLIMIT يحدد الحد لطول وصلات الميتر في سياق جهاز التشغيل. |
| [EmfSetPaletteEntries](./emfsetpaletteentries/) | سجل EMR_SETPALETTEENTRIES يعرّف قيم ألوان RGB في نطاق من الإدخالات لكائن LogPalette الموجود (القسم 2.2.17). |
| [EmfSetPixelV](./emfsetpixelv/) | سجل EMR_SETPIXELV يعرّف لون البكسل عند الإحداثيات المنطقية المحددة. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode/) | سجل EMR_SETPOLYFILLMODE يعرّف وضعية تعبئة المضلع. |
| [EmfSetRop2](./emfsetrop2/) | سجل EMR_SETROP2 يعرّف وضعية عملية نقطية ثنائية. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode/) | سجل EMR_SETSTRETCHBLTMODE يحدد وضعية تمديد الصورة النقطية. |
| [EmfSetTextAlign](./emfsettextalign/) | سجل EMR_SETTEXTALIGN يحدد محاذاة النص. |
| [EmfSetTextColor](./emfsettextcolor/) | سجل EMR_SETTEXTCOLOR يعرّف لون النص الحالي. |
| [EmfSetTextJustification](./emfsettextjustification/) | سجل EMR_SETTEXTJUSTIFICATION يحدد مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لتبرير النص. |
| [EmfSetViewportExtEx](./emfsetviewportextex/) | سجل EMR_SETVIEWPORTEXTEX يعرّف امتداد مساحة العرض. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex/) | سجل EMR_SETVIEWPORTORGEX يعرّف أصل مساحة العرض. |
| [EmfSetWindowExtEx](./emfsetwindowextex/) | سجل EMR_SETWINDOWEXTEX يعرّف امتداد النافذة. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex/) | سجل EMR_SETWINDOWORGEX يعرّف أصل النافذة. |
| [EmfSetWorldTransform](./emfsetworldtransform/) | سجل EMR_SETWORLDTRANSFORM يحدد تحويلًا من مساحة العالم الحالية إلى تحويل مساحة الصفحة في سياق جهاز التشغيل. |
| [EmfSmallTextOut](./emfsmalltextout/) | سجل EMR_SMALLTEXTOUT يخرج سلسلة نصية. |
| [EmfStateRecordType](./emfstaterecordtype/) | أنواع سجلات الحالة تحدد وتدير خصائص الرسومات التي تُعرّف حالة سياق جهاز التشغيل. |
| [EmfStretchBlt](./emfstretchblt/) | سجل EMR_STRETCHBLT يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفق عملية نقطية محددة، مع تمديد أو ضغط المخرجات لتناسب أبعاد الهدف إذا لزم الأمر. |
| [EmfStretchDiBits](./emfstretchdibits/) | سجل EMR_STRETCHDIBITS يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفق عملية نقطية محددة، مع تمديد أو ضغط المخرجات لتناسب أبعاد الهدف إذا لزم الأمر. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath/) | يقوم سجل EMR_STROKEANDFILLPATH بإغلاق أي أشكال مفتوحة في مسار، ويرسم حدود المسار باستخدام القلم الحالي، ويملأ داخله باستخدام الفرشاة الحالية. |
| [EmfStrokePath](./emfstrokepath/) | فئة EMR_STROKEPATH |
| [EmfTransformRecordType](./emftransformrecordtype/) | تحدد أنواع سجلات التحويل وتعدل تحويلات الفضاء العالمي إلى الفضاء الصفحي. |
| [EmfTransparentBlt](./emftransparentblt/) | سجل EMR_TRANSPARENTBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى مستطيل هدف، مع معالجة لون محدد كشفاف، وتمديد أو ضغط الناتج ليتناسب مع أبعاد الهدف إذا لزم الأمر. |
| [EmfVertexData](./emfvertexdata/) | الكائنات التي تحدد رؤوس المستطيلات أو المثلثات والألوان المقابلة لها. |
| [EmfWidenPath](./emfwidenpath/) | يعيد هذا السجل تعريف المسار الحالي كالمساحة التي سيتم طلاءها إذا تم رسم المسار باستخدام القلم المحدد حاليًا في سياق جهاز التشغيل. |
## Structures

| بنية | الوصف |
| --- | --- |
| [EmfBlendFunction](./emfblendfunction/) | هيكل يحدد عمليات المزج لصور المصدر والوجهة. |


