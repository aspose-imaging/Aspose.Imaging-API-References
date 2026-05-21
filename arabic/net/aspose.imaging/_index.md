---
title: "Aspose.Imaging"
second_title: "Aspose.Imaging for .NET API Reference"
description: "المجال هو الأساس للمجالات المتداخلة وأبسط الكائنات المستخدمة في معالجة Aspose.Imaging"
type: docs
weight: 10
url: /ar/net/aspose.imaging/
---
مساحة الاسم هي النواة للمساحات المتداخلة وأبسط الكائنات المستخدمة في معالجة Aspose.Imaging.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [AggregateException](./aggregateexception/) | يجمع استثناءات متعددة. |
| [Blend](./blend/) | يحدد نمط المزج. لا يمكن وراثة هذه الفئة. |
| [Brush](./brush/) | فئة الفرشاة الأساسية. |
| [BuildVersionInfo](./buildversioninfo/) | يحتوي على معلومات إصدار البناء الحالي. |
| [Cache](./cache/) | يحتوي على إعدادات الذاكرة المؤقتة. |
| [CmykColorHelper](./cmykcolorhelper/) | طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح موقعة 32‑بت. يوفر واجهة برمجة تطبيقات مشابهة للهيكل [`CmykColor`](../aspose.imaging/cmykcolor/). إنه أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الثابتة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل المهمل [`CmykColor`](../aspose.imaging/cmykcolor/). |
| [ColorBlend](./colorblend/) | يحدد مصفوفات من الألوان والمواقع المستخدمة في استيفاء مزج الألوان في تدرج متعدد الألوان. لا يمكن وراثة هذه الفئة. |
| [ColorMap](./colormap/) | يحدد خريطة لتحويل الألوان. عدة طرق في فئة [`ImageAttributes`](../aspose.imaging/imageattributes/) تعدل ألوان الصورة باستخدام جدول إعادة تعيين الألوان، وهو مصفوفة من هياكل [`ColorMap`](../aspose.imaging/colormap/). لا يمكن وراثتها. |
| [ColorMatrix](./colormatrix/) | يحدد مصفوفة 5 × 5 تحتوي على إحداثيات مساحة RGBA. عدة طرق في فئة [`ImageAttributes`](../aspose.imaging/imageattributes/) تعدل ألوان الصورة باستخدام مصفوفة ألوان. لا يمكن وراثة هذه الفئة. |
| [ColorPalette](./colorpalette/) | يحدد مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32‑بت. لا يمكن وراثتها. |
| [ColorPaletteHelper](./colorpalettehelper/) | فئة مساعدة لتلاعب لوحات الألوان. |
| [ColorTranslator](./colortranslator/) | يترجم الألوان إلى ومن هياكل GDI+ Color. لا يمكن وراثة هذه الفئة. |
| [CompositeException](./compositeexception/) | الاستثناء المركب |
| [CustomFontSource](./customfontsource/) | دالة موفر مصدر الخط المخصص |
| [CustomLineCap](./customlinecap/) | يحتوي على غطاء خط مخصص يحدده المستخدم. |
| [DataStreamSupporter](./datastreamsupporter/) | حاوية تدفق البيانات. |
| [DisposableObject](./disposableobject/) | يمثل كائنًا قابلًا للتصرف. |
| [EmbeddedImage](./embeddedimage/) | فئة الصورة المضمنة |
| [Figure](./figure/) | الشكل. حاوية للأشكال. |
| [FileStreamContainer](./filestreamcontainer/) | مساعدة لمعالجة تدفق الملفات. |
| [Font](./font/) | يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط. لا يمكن وراثة هذه الفئة. |
| [FontSettings](./fontsettings/) | إعدادات خط عارض صيغ المتجهات العامة للتصوير. |
| [Graphics](./graphics/) | يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي. |
| [GraphicsPath](./graphicspath/) | يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن وراثة هذه الفئة. |
| [Image](./image/) | الصورة هي الفئة الأساسية لجميع أنواع الصور. |
| [ImageAttributes](./imageattributes/) | كائن [`ImageAttributes`](../aspose.imaging/imageattributes/) يحتوي على معلومات حول كيفية تعديل ألوان البت ماب وملف الميتا خلال عملية التصيير. كائن [`ImageAttributes`](../aspose.imaging/imageattributes/) يحافظ على عدة إعدادات لتعديل الألوان، بما في ذلك مصفوفات تعديل اللون، مصفوفات تعديل التدرج الرمادي، قيم تصحيح غاما، جداول خريطة الألوان، وقيم عتبة اللون. خلال عملية التصيير، يمكن تصحيح الألوان، تعتيمها، إضاءتها، وإزالتها. لتطبيق هذه التعديلات، قم بتهيئة كائن [`ImageAttributes`](../aspose.imaging/imageattributes/) ومرّر مسار ذلك الكائن (إلى جانب مسار كائن [`Image`](../aspose.imaging/image/)) إلى طريقة DrawImage method. |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | يمثل سجل منشئي الصور. |
| [ImageExportersRegistry](./imageexportersregistry/) | يمثل سجل مصدري الصور. |
| [ImageLoadersRegistry](./imageloadersregistry/) | يمثل سجل محمّلي الصور. |
| [ImageOptionsBase](./imageoptionsbase/) | خيارات قاعدة الصورة. |
| [ImageResizeSettings](./imageresizesettings/) | فئة إعدادات تغيير حجم الصورة |
| [IntRange](./intrange/) | فئة لتمثيل تسلسل العناصر |
| [License](./license/) | يوفر طرقًا لترخيص المكوّن. |
| [LoadOptions](./loadoptions/) | يمثل خيارات التحميل. |
| [Matrix](./matrix/) | يستبدل مصفوفة GDI+. |
| [Metered](./metered/) | يوفر طرقًا محسوبة للتكامل |
| [NonGenericDictionary](./nongenericdictionary/) | يمثل قاموسًا غير عام. |
| [NonGenericList](./nongenericlist/) | قائمة غير عامة من الكائنات |
| [ObjectWithBounds](./objectwithbounds/) | الكائن الذي له حدود. |
| [OpenTypeFontsCache](./opentypefontscache/) | ذاكرة مخبأة لخطوط OpenType المثبتة في النظام. |
| [PageExportingAction](./pageexportingaction/) | مندوب لإطلاق الحدث قبل تصدير الصفحة |
| [Pen](./pen/) | يحدد كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال. |
| [PixelDataFormat](./pixeldataformat/) | تنسيق بيانات البكسل. هذا كائن غير قابل للتغيير. |
| [ProgressEventHandler](./progresseventhandler/) | مرجع دالة معالج حدث التقدم |
| [RasterCachedImage](./rastercachedimage/) | يمثل صورة نقطية تدعم عمليات الرسومات النقطية. تقوم هذه الصورة بتخزين بيانات البكسل في الذاكرة المؤقتة عند الحاجة. |
| [RasterCachedMultipageImage](./rastercachedmultipageimage/) | صورة نقطية متعددة الصفحات |
| [RasterImage](./rasterimage/) | يمثل صورة نقطية تدعم عمليات الرسومات النقطية. |
| [RawDataSettings](./rawdatasettings/) | إعدادات البيانات الخام |
| [Region](./region/) | يصف الجزء الداخلي لشكل رسومي مكوّن من مستطيلات ومسارات. لا يمكن وراثة هذه الفئة. |
| [RemoveBackgroundSettings](./removebackgroundsettings/) | إعدادات إزالة الخلفية |
| [ResolutionSetting](./resolutionsetting/) | إعداد الدقة لخيارات حفظ الصورة. |
| [Shape](./shape/) | الشكل. مجموعة مستمرة من النقاط متصلة باستخدام قاعدة محددة. |
| [ShapeSegment](./shapesegment/) | يمثل مقطع الشكل. المقطع هو خط أو منحنى يربط نقطتين. |
| [Source](./source/) | المصدر يُستخدم لاحتواء جميع المعلومات ذات الصلة لأنبوب الكائن. |
| [SplitStreamContainer](./splitstreamcontainer/) | يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق. |
| [StreamContainer](./streamcontainer/) | يمثل حاوية تدفق تحتوي على التدفق وتوفر روتينات معالجة التدفق. |
| [StringFormat](./stringformat/) | يحتوي على معلومات تخطيط النص (مثل المحاذاة، الاتجاه وإيقافات الجدولة) وتعديلات العرض (مثل إدراج الحذف الثلاثي واستبدال الأرقام الوطنية) وميزات OpenType. لا يمكن وراثة هذه الفئة. |
| [TransparencySupporter](./transparencysupporter/) | الكائن الذي يدعم الشفافية. |
| [VectorImage](./vectorimage/) | الصورة المتجهة هي الفئة الأساسية لجميع أنواع الصور المتجهة. |
| [VectorMultipageImage](./vectormultipageimage/) | صورة المتجه متعددة الصفحات |
## Structures

| بنية | الوصف |
| --- | --- |
| [CmykColor](./cmykcolor/) | لون CMYK للبكسل. |
| [Color](./color/) | لون البكسل. |
| [Point](./point/) | يمثل زوجًا مرتبًا من إحداثيات x و y صحيحة يحدد نقطة في مستوى ثنائي الأبعاد. |
| [PointF](./pointf/) | يمثل زوجًا مرتبًا من إحداثيات x و y عائمة يحدد نقطة في مستوى ثنائي الأبعاد. |
| [Rectangle](./rectangle/) | يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل. |
| [RectangleF](./rectanglef/) | يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل. |
| [Size](./size/) | يمثل الحجم. |
| [SizeF](./sizef/) | يخزن زوجًا مرتبًا من الأعداد العائمة، عادةً العرض والارتفاع للمستطيل. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | معالج المخزن المؤقت المتقدم. |
| [IAnimationFrame](./ianimationframe/) | إطار الرسوم المتحركة |
| [IBufferProcessor](./ibufferprocessor/) | معالج المخزن المؤقت. |
| [IColorConverter](./icolorconverter/) | محول اللون. |
| [IColorPalette](./icolorpalette/) | واجهة لوحة الألوان. |
| [IHasMetadata](./ihasmetadata/) | واجهة بيانات تعريف الصورة. |
| [IImageCreator](./iimagecreator/) | منشئ الصورة. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | وصف منشئ الصورة الذي يحدد خصائص المنشئ. يُستخدم وصف المنشئ لتجاوز الحاجة إلى احتواء كل مثال لمنشئ الصورة في الذاكرة ومشكلات تعدد الخيوط. |
| [IImageDescriptor](./iimagedescriptor/) | وصف الصورة. يحتوي على الخصائص والطرق الأساسية لجميع أنواع أوصاف الصور الأخرى. |
| [IImageExporter](./iimageexporter/) | مُصدّر الصورة. يمكنه تصدير البيانات من تنسيق Aspose.Imaging الداخلي إلى تنسيق بيانات محدد. |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | يمثّل وصف مُصدّر الصورة. يُستخدم وصف المُصدّر لتجاوز الحاجة إلى احتواء كل مثال للمُصدّر في الذاكرة ومشكلات تعدد الخيوط. |
| [IImageLoader](./iimageloader/) | محمل الصورة. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | وصف محمل الصورة الذي يحدد خصائص المحمل. يُستخدم وصف المحمل لتجاوز الحاجة إلى احتواء كل مثال لمحمل الصورة في الذاكرة ومشكلات تعدد الخيوط. |
| [IIndexedColorConverter](./iindexedcolorconverter/) | محول الألوان لتنسيقات الصور المفهرسة. |
| [IMetadataContainer](./imetadatacontainer/) | واجهة حاوية بيانات تعريف الصورة. |
| [IMultipageImage](./imultipageimage/) | واجهة الصورة متعددة الصفحات |
| [IMultipageImageExt](./imultipageimageext/) | واجهة الصورة متعددة الصفحات الموسعة |
| [IObjectWithBounds](./iobjectwithbounds/) | يمثّل كائنًا بحدوده. |
| [IOrderedShape](./iorderedshape/) | يمثّل شكلًا مرتبًا. الشكل المرتب هو مجموعة مستمرة من النقاط لها نقطة بداية ونقطة نهاية. المجموعة المستمرة من النقاط متصلة باستخدام قاعدة محددة. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | يتوافق مع بكسلات ARGB 32‑بت التي تم تحميلها جزئيًا. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | محمل بكسلات ARGB 64‑بت. |
| [IPartialPixelLoader](./ipartialpixelloader/) | يتوافق مع البكسلات التي تم تحميلها جزئيًا. |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | محمل البيانات الجزئي. |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | محمل بكسل ARGB 32‑بت للصورة النقطية. |
| [IRasterImageArgb64PixelLoader](./irasterimageargb64pixelloader/) | محمل بكسل ARGB 64‑بت للصورة النقطية. |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | محمل بكسل الصورة النقطية. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | محمل البيانات الخام للصورة النقطية. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [AnimationDisposalMethods](./animationdisposalmethods/) | يشير إلى الطريقة التي يجب معالجة الرسمة بها بعد عرضها. |
| [CacheType](./cachetype/) | يحدد نوع الذاكرة المؤقتة المراد استخدامها. |
| [CharacterSet](./characterset/) | يمثل مجموعة الأحرف المستخدمة. |
| [ColorAdjustType](./coloradjusttype/) | يحدد أي الكائنات تستخدم معلومات تعديل اللون. |
| [ColorChannelFlag](./colorchannelflag/) | يحدد القنوات الفردية في مساحة اللون CMYK (سماوي، أرجواني، أصفر، أسود). تُستخدم هذه التعدادات بواسطة طرق SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod/) | طريقة مقارنة اللون لضبط إلى أقرب جار |
| [ColorMatrixFlag](./colormatrixflag/) | يحدد أنواع الصور والألوان التي سيتأثر بها إعدادات تعديل اللون وتدرج الرمادي لكائن [`ImageAttributes`](../aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](./colorquantizationmethod/) | طرق تقليل ألوان |
| [CompositingQuality](./compositingquality/) | يحدد مستوى الجودة المستخدم أثناء التركيب. |
| [DashCap](./dashcap/) | يحدد نوع الشكل الرسومي المستخدم على كلا طرفي كل شَرطَة في خط متقطع. |
| [DashStyle](./dashstyle/) | يحدد نمط الخطوط المتقطعة المرسومة باستخدام كائن [`Pen`](../aspose.imaging/pen/). |
| [DataRecoveryMode](./datarecoverymode/) | وضع استعادة البيانات. |
| [DitheringMethod](./ditheringmethod/) | طريقة التمويه. |
| [DitheringMethods](./ditheringmethods/) | طرق التمويه المستخدمة للتحكم في تحويل اللون. |
| [FileFormat](./fileformat/) | أحد صيغ ملفات التصوير المدعومة. |
| [FillMode](./fillmode/) | يحدد كيفية ملء داخل مسار مغلق. |
| [FontStyle](./fontstyle/) | يحدد معلومات النمط المطبقة على النص. |
| [GraphicsUnit](./graphicsunit/) | يحدد وحدة القياس للبيانات المعطاة. |
| [HatchStyle](./hatchstyle/) | يحدد الأنماط المختلفة المتاحة لكائنات [`HatchBrush`](../aspose.imaging.brushes/hatchbrush/). |
| [HotkeyPrefix](./hotkeyprefix/) | يحدد نوع العرض للبادئات الخاصة بمفاتيح الاختصار المتعلقة بالنص. |
| [ImageFilterType](./imagefiltertype/) | مرشحات الصورة للاستخدام |
| [InterpolationMode](./interpolationmode/) | تحدد تعداد [`InterpolationMode`](../aspose.imaging/interpolationmode/) الخوارزمية المستخدمة عند تحجيم أو تدوير الصور. |
| [KnownColor](./knowncolor/) | يحدد ألوان النظام المعروفة. |
| [LineCap](./linecap/) | يحدد أنماط القمة المتاحة التي يمكن لكائن [`Pen`](../aspose.imaging/pen/) إنهاء الخط بها. |
| [LineJoin](./linejoin/) | يحدد كيفية ربط مقاطع الخط أو المنحنى المتتالية في شكل (مسار فرعي) موجود داخل كائن [`GraphicsPath`](../aspose.imaging/graphicspath/). |
| [MatrixOrder](./matrixorder/) | يحدد ترتيب عمليات تحويل المصفوفة. |
| [PaletteMiningMethod](./paletteminingmethod/) | طريقة استخراج لوحة ألوان الصورة |
| [PdfComplianceVersion](./pdfcomplianceversion/) | يحدد مستوى توافق PDF لملف الإخراج. |
| [PenAlignment](./penalignment/) | يحدد محاذاة كائن [`Pen`](../aspose.imaging/pen/) بالنسبة إلى الخط النظري ذي العرض الصفري. |
| [PenType](./pentype/) | يحدد نوع التعبئة التي يستخدمها كائن [`Pen`](../aspose.imaging/pen/) لملء الخطوط. |
| [PixelFormat](./pixelformat/) | المعنى الفعلي لتنسيق بيانات البكسل. |
| [ProcessingType](./processingtype/) | نوع المعالجة. |
| [ResizeType](./resizetype/) | يحدد نوع تغيير الحجم. |
| [ResolutionUnit](./resolutionunit/) | تعداد وحدة الدقة. |
| [RotateFlipType](./rotatefliptype/) | يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة. |
| [SeekOrigin](./seekorigin/) | يوفر الحقول التي تمثل نقاط المرجع في [`StreamContainer`](../aspose.imaging/streamcontainer/) للبحث. |
| [SmoothingMode](./smoothingmode/) | يحدد ما إذا كان يتم تطبيق التنعيم (مضاد التعرج) على الخطوط والمنحنيات وحواف المناطق المملوءة. |
| [StringAlignment](./stringalignment/) | يحدد محاذاة سلسلة النص بالنسبة إلى مستطيل التخطيط الخاص بها. |
| [StringDigitSubstitute](./stringdigitsubstitute/) | التعداد يحدد كيفية استبدال الأرقام في سلسلة وفقًا لإعدادات المستخدم الإقليمية أو اللغة. |
| [StringFormatFlags](./stringformatflags/) | يحدد معلومات العرض والتخطيط لسلاسل النص. |
| [StringTrimming](./stringtrimming/) | يحدد كيفية قص الأحرف من سلسلة لا تتناسب بالكامل مع شكل التخطيط. |
| [TextRenderingHint](./textrenderinghint/) | يحدد جودة عرض النص. |
| [WarpMode](./warpmode/) | يحدد نوع تحويل الالتواء المطبق. |
| [WrapMode](./wrapmode/) | يحدد كيفية تجانب النسيج أو التدرج عندما يكون أصغر من المنطقة التي يتم ملئها. |


