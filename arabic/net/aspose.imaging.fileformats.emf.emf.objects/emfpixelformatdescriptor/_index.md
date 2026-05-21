---
title: "الفئة EmfPixelFormatDescriptor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfPixelFormatDescriptor. يمكن استخدام كائن PixelFormatDescriptor في سجلات EMR_HEADER القسم 2.3.4.2 لتحديد تنسيق البكسل لسطح الإخراج لسياق جهاز التشغيل."
type: docs
weight: 3210
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

يمكن استخدام كائن PixelFormatDescriptor في سجلات EMR_HEADER (القسم 2.3.4.2) لتحديد تنسيق البكسل للسطح الخارجي في سياق جهاز التشغيل.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved/) { get; set; } | يحصل أو يعيّن يحدد عدد مستويات التراكب والطبقة السفلية. تحدد البتات 0 إلى 3 ما يصل إلى 15 مستوى تراكب وتحدد البتات 4 إلى 7 ما يصل إلى 15 مستوى سفلي. |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits/) { get; set; } | يحصل أو يعيّن يحدد عدد طبقات البت ألفا في مخزن التجميع. |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits/) { get; set; } | يحصل أو يعيّن يحدد العدد الإجمالي لطبقات البت في مخزن التجميع. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits/) { get; set; } | يحصل أو يعيّن يحدد عدد طبقات البت الزرقاء في مخزن التجميع. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits/) { get; set; } | يحصل أو يعيّن يحدد عدد طبقات البت الخضراء في التجميع |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits/) { get; set; } | يحصل أو يعيّن يحدد عدد طبقات البت الحمراء في مخزن التجميع. |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits/) { get; set; } | يحصل أو يعيّن يحدد عدد طبقات البت ألفا في كل مخزن ألوان RGBA. |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift/) { get; set; } | يحصل أو يعيّن يحدد عدد إزاحة طبقات البت ألفا في كل مخزن ألوان RGBA. |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers/) { get; set; } | يحصل أو يعيّن يحدد عدد المخازن المساعدة. المخازن المساعدة غير مدعومة |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits/) { get; set; } | يحصل أو يعيّن يحدد عدد طبقات البت الزرقاء في كل مخزن ألوان RGBA. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift/) { get; set; } | يحصل أو يعيّن يحدد عدد إزاحة طبقات البت الزرقاء في كل مخزن ألوان RGBA. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits/) { get; set; } | يحصل أو يعيّن عدد البتات لكل بكسل لأنواع بكسل RGBA، باستثناء طبقات البت ألفا. بالنسبة لبكسلات جدول الألوان، فهو حجم كل فهرس في جدول الألوان. |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits/) { get; set; } | يحصل أو يعيّن يحدد عمق مخزن العمق (محور z). |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits/) { get; set; } | يحصل أو يعيّن يحدد عدد طبقات البت الخضراء في كل مخزن ألوان RGBA |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift/) { get; set; } | الحصول أو الضبط يحدد عدد الإزاحات لطبقات البت الخضراء في كل مخزن ألوان RGBA. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits/) { get; set; } | الحصول أو الضبط يحدد عدد طبقات البت الحمراء في كل مخزن ألوان RGBA |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift/) { get; set; } | الحصول أو الضبط يحدد عدد الإزاحات بالبتات لطبقات البت الحمراء في كل مخزن ألوان RGBA. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits/) { get; set; } | الحصول أو الضبط يحدد عمق مخزن القالب. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask/) { get; set; } | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags/) { get; set; } | الحصول أو الضبط علامات البت التي تحدد خصائص مخزن البكسل المستخدم للإخراج إلى سطح الرسم. هذه الخصائص ليست جميعها متعارضة؛ يُسمح بدمج العلامات، باستثناء ما هو مذكور خلاف ذلك. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask/) { get; set; } | الحصول أو الضبط قد يتم تجاهل هذا الحقل. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask/) { get; set; } | الحصول أو الضبط يحدد اللون الشفاف أو الفهرس لطائرة تحتية. عندما يكون نوع البكسل RGBA، يكون dwVisibleMask قيمة لون RGB شفافة. عندما يكون نوع البكسل فهرس ألوان، يكون قيمة فهرس شفافة. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype/) { get; set; } | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype/) { get; set; } | الحصول أو الضبط يحدد نوع بيانات البكسل PFD_TYPE_RGBA 0x00 تنسيق البكسل هو RGBA. PFD_TYPE_COLORINDEX 0x01 كل بكسل هو فهرس في جدول الألوان. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize/) { get; set; } | الحصول أو الضبط عدد صحيح 16‑بت يحدد حجم هذه البنية البياناتية بالبايت. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion/) { get; set; } | الحصول أو الضبط عدد صحيح 16‑بت يجب أن يُعيّن إلى 0x0001. |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


