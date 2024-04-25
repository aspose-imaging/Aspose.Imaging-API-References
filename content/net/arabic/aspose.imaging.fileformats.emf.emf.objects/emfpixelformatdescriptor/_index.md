---
title: EmfPixelFormatDescriptor
second_title: Aspose.Imaging لمرجع NET API
description: يمكن استخدام كائن PixelFormatDescriptor في سجلات EMR_HEADER القسم 2.3.4.2 لتحديد تنسيق البكسل لسطح الإخراج لسياق جهاز التشغيل.
type: docs
weight: 3120
url: /ar/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

يمكن استخدام كائن PixelFormatDescriptor في سجلات EMR_HEADER (القسم 2.3.4.2) لتحديد تنسيق البكسل لسطح الإخراج لسياق جهاز التشغيل.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved) { get; set; } | Gets أو المجموعات تحدد عدد مستويات التراكب والطبقات التي تقوم عليها. تحدد البتات من 0 إلى 3 ما يصل إلى 15 مستوى من طبقات التراكب والبتات من 4 إلى 7 تحدد ما يصل إلى 15 طائرة سفلية |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits) { get; set; } | Gets or Sets يحدد عدد طائرات alpha bitplanes في المخزن المؤقت للتراكم |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits) { get; set; } | Gets أو المجموعات تحدد العدد الإجمالي للطائرات النقطية في المخزن المؤقت للتراكم. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits) { get; set; } | Gets or مجموعات تحدد عدد الطائرات الزرقاء في المخزن المؤقت للتراكم. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits) { get; set; } | Gets or مجموعات تحدد عدد طائرات البت الخضراء في التراكم |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits) { get; set; } | Gets or مجموعات تحدد عدد الطائرات النقطية الحمراء في المخزن المؤقت للتراكم |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits) { get; set; } | Gets or Sets يحدد عدد طائرات alpha bitplan في كل مخزن ألوان RGBA |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift) { get; set; } | Gets or Sets يحدد عدد الإزاحة لطائرات ألفا النقطية في كل مخزن ألوان RGBA |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers) { get; set; } | Gets أو المجموعات تحدد عدد المخازن المؤقتة المساعدة. المخازن المؤقتة المساعدة غير مدعومة |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits) { get; set; } | الحصول أو المجموعات يحدد عدد الطائرات النقطية الزرقاء في كل مخزن ألوان RGBA . |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift) { get; set; } | الحصول أو المجموعات يحدد عدد الإزاحة للطبقات النقطية الزرقاء في كل مخزن ألوان RGBA . |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits) { get; set; } | الحصول على أو تحديد عدد وحدات البت لكل بكسل لأنواع RGBA البكسل ، باستثناء طائرات alpha bitplanes. بالنسبة لبكسل جدول الألوان ، يكون حجم كل جدول ألوان index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits) { get; set; } | الحصول أو المجموعات تحدد عمق المخزن المؤقت للعمق (المحور z) . |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits) { get; set; } | الحصول على أو المجموعات تحديد عدد الطائرات النقطية الخضراء في كل مخزن ألوان RGBA |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift) { get; set; } | الحصول أو المجموعات يحدد عدد الإزاحة للطائرات النقطية الخضراء في كل مخزن ألوان RGBA . |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits) { get; set; } | الحصول أو المجموعات يحدد عدد الطائرات النقطية الحمراء في كل مخزن ألوان RGBA |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift) { get; set; } | الحصول أو المجموعات يحدد عدد الإزاحة بالبتات للطائرات النقطية الحمراء في كل مخزن ألوان RGBA . |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits) { get; set; } | الحصول أو المجموعات تحدد عمق المخزن المؤقت للاستنسل. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask) { get; set; } | الحصول على هذا الحقل أو تعيينه قد يتم تجاهله |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags) { get; set; } | الحصول على أو تعيين إشارات البت التي تحدد خصائص المخزن المؤقت للبكسل المستخدم للإخراج إلى سطح الرسم. هذه الخصائص ليست كلها متبادلة ؛ يُسمح بمجموعات من الأعلام ، ما لم يُذكر خلاف ذلك. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask) { get; set; } | الحصول على هذا الحقل أو تعيينه قد يتم تجاهله. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask) { get; set; } | Gets or Sets يحدد اللون الشفاف أو الفهرس لمستوى تحتي. عندما يكون نوع البكسل هو RGBA ، فإن dwVisibleMask هو قيمة ألوان RGB شفافة. عندما يكون نوع البكسل هو مؤشر اللون ، فهو قيمة فهرس شفافة. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype) { get; set; } | الحصول على هذا الحقل أو تعيينه قد يتم تجاهله |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype) { get; set; } | الحصول على أو تعيين نوع بيانات البكسل PFD_TYPE_RGBA 0x00 تنسيق البكسل هو RGBA. PFD_TYPE_COLORINDEX 0x01 كل بكسل عبارة عن فهرس في جدول ألوان. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize) { get; set; } | الحصول على أو تعيين عدد صحيح 16 بت يحدد الحجم بالبايت لهيكل البيانات. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion) { get; set; } | الحصول على أو تعيين عدد صحيح 16 بت يجب تعيينه على 0x0001. |

### أنظر أيضا

* class [EmfObject](../emfobject)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
