---
title: "الفئة EmfPlusBitmap"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBitmap الفئة. كائن EmfPlusBitmap يحدد صورة بت ماب تحتوي على صورة رسومية."
type: docs
weight: 5290
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
## EmfPlusBitmap class

يحدد كائن EmfPlusBitmap صورة نقطية تحتوي على صورة رسومية.

```csharp
public sealed class EmfPlusBitmap : EmfPlusBaseImageData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusBitmap](emfplusbitmap/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitmapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/bitmapdata/) { get; set; } | الحصول أو تعيين بيانات البت ماب BitmapData (متغيرة): بيانات بطول متغير تُعرّف كائن بيانات البت ماب المحدد في حقل Type. يمكن أن يختلف المحتوى والتنسيق للبيانات لكل نوع بت ماب. |
| [Height](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/height/) { get; set; } | الحصول أو تعيين ارتفاع البت ماب Height (4 بايت): عدد صحيح موقع 32-بت يحدد الارتفاع بالبكسل للمساحة التي يشغلها البت ماب. إذا كانت الصورة مضغوطة، وفقاً لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |
| [PixelFormat](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/pixelformat/) { get; set; } | الحصول أو تعيين تنسيق البكسل PixelFormat (4 بايت): عدد صحيح غير موقع 32-بت يحدد تنسيق البكسلات التي تشكل صورة البت ماب. تنسيقات البكسل المدعومة محددة في تعداد [`EmfPlusPixelFormat`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (القسم 2.1.1.25). إذا كانت الصورة مضغوطة، وفقاً لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |
| [Stride](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/stride/) { get; set; } | الحصول أو تعيين خطوة الصورة Stride (4 بايت): عدد صحيح 32‑بت موقع يحدد إزاحة البايت بين بداية سطر المسح التالي. هذه القيمة هي عدد البايتات لكل بكسل، المحددة في حقل PixelFormat، مضروبًا في العرض بالبكسل المحدد في حقل Width. يجب أن تكون قيمة هذا الحقل مضاعفًا للعدد أربعة. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/type/) { get; set; } | الحصول أو تعيين نوع الصورة Type (4 بايت): عدد صحيح غير موقع 32‑بت يحدد نوع البيانات في حقل BitmapData. يجب أن تكون هذه القيمة معرفة في تعداد [`EmfPlusBitmapDataType`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) (القسم 2.1.1.2). |
| [Width](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/width/) { get; set; } | الحصول أو تعيين عرض الصورة Width (4 بايت): عدد صحيح 32‑بت موقع يحدد العرض بالبكسل للمنطقة التي يشغلها البت ماب. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها. |

### انظر أيضًا

* class [EmfPlusBaseImageData](../emfplusbaseimagedata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


