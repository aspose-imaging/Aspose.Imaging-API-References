---
title: "EmfPlusCompressedImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusCompressedImage يحدد صورة ذات بيانات مضغوطة."
type: docs
weight: 31
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

كائن EmfPlusCompressedImage يحدد صورة ذات بيانات مضغوطة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | يحصل أو يعيّن مصفوفة من البايتات التي تحدد الصورة المضغوطة. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | يحصل أو يعيّن مصفوفة من البايتات التي تحدد الصورة المضغوطة. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


يحصل أو يعيّن مصفوفة من البايتات التي تحدد الصورة المضغوطة. يجب تحديد نوع الضغط من البيانات نفسها.

يتم تحديد الصور النقطية بواسطة كائنات EmfPlusBitmap (القسم 2.2.2.2). يجب أن يكون كائن EmfPlusCompressedImage موجودًا في حقل BitmapData لكائن EmfPlusBitmap إذا تم تحديد BitmapDataTypeCompressed في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات المضغوطة، بما في ذلك: \\uf0a7 تنسيق ملف الصورة القابلة للتبادل (EXIF)، كما هو موضح في [EXIF]; \\uf0a7 تنسيق تبادل الرسومات (GIF)، كما هو موضح في [GIF]; \\uf0a7 مجموعة الخبراء المشتركة للصور (JPEG)، كما هو موضح في [JFIF]; \\uf0a7 الرسوميات الشبكية القابلة للنقل (PNG)، كما هو موضح في [RFC2083] و[W3C - PNG]; و \\uf0a7 تنسيق ملف صورة العلامة (TIFF)، كما هو موضح في [RFC3302] و[TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


يحصل أو يعيّن مصفوفة من البايتات التي تحدد الصورة المضغوطة. يجب تحديد نوع الضغط من البيانات نفسها.

يتم تحديد الصور النقطية بواسطة كائنات EmfPlusBitmap (القسم 2.2.2.2). يجب أن يكون كائن EmfPlusCompressedImage موجودًا في حقل BitmapData لكائن EmfPlusBitmap إذا تم تحديد BitmapDataTypeCompressed في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات المضغوطة، بما في ذلك: \\uf0a7 تنسيق ملف الصورة القابلة للتبادل (EXIF)، كما هو موضح في [EXIF]; \\uf0a7 تنسيق تبادل الرسومات (GIF)، كما هو موضح في [GIF]; \\uf0a7 مجموعة الخبراء المشتركة للصور (JPEG)، كما هو موضح في [JFIF]; \\uf0a7 الرسوميات الشبكية القابلة للنقل (PNG)، كما هو موضح في [RFC2083] و[W3C - PNG]; و \\uf0a7 تنسيق ملف صورة العلامة (TIFF)، كما هو موضح في [RFC3302] و[TIFF].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

