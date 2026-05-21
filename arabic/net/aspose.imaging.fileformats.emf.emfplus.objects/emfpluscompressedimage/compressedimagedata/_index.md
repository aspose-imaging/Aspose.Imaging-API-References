---
title: "EmfPlusCompressedImage.CompressedImageData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfPlusCompressedImage. يحصل أو يعيّن مصفوفة من البايتات التي تحدد الصورة المضغوطة. يجب تحديد نوع الضغط من البيانات نفسها."
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/compressedimagedata/
---
## EmfPlusCompressedImage.CompressedImageData property

يحصل أو يضبط مصفوفة من البايتات التي تحدد الصورة المضغوطة. يجب تحديد نوع الضغط من البيانات نفسها.

```csharp
public byte[] CompressedImageData { get; set; }
```

## ملاحظات

يتم تحديد الصور النقطية (Bitmaps) بواسطة كائنات EmfPlusBitmap (القسم 2.2.2.2). يجب أن يكون كائن EmfPlusCompressedImage موجودًا في حقل BitmapData لكائن EmfPlusBitmap إذا تم تحديد BitmapDataTypeCompressed في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات المضغوطة، بما في ذلك: • تنسيق ملف الصورة القابلة للتبادل (EXIF)، كما هو محدد في [EXIF]; • تنسيق تبادل الرسومات (GIF)، كما هو محدد في [GIF]; • مجموعة خبراء الصور المشتركة (JPEG)، كما هو محدد في [JFIF]; • رسومات الشبكة المحمولة (PNG)، كما هو محدد في [RFC2083] و[W3C - PNG]; و • تنسيق ملف صورة العلامة (TIFF)، كما هو محدد في [RFC3302] و[TIFF].

### انظر أيضًا

* class [EmfPlusCompressedImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluscompressedimage/)
* assembly [Aspose.Imaging](../../../)


