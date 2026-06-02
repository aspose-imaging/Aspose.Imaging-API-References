---
title: "EmfPlusCompressedImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusCompressedImage يحدد صورة ذات بيانات مضغوطة."
type: docs
weight: 31
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
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

يتم تحديد البت ماب بواسطة كائنات EmfPlusBitmap (القسم 2.2.2.2). يجب أن يكون كائن EmfPlusCompressedImage موجودًا في حقل BitmapData لكائن EmfPlusBitmap إذا تم تحديد BitmapDataTypeCompressed في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات المضغوطة، بما في ذلك: \\uf0a7 Exchangeable Image File Format (EXIF)، كما هو محدد في [EXIF]; \\uf0a7 Graphics Interchange Format (GIF)، كما هو محدد في [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG)، كما هو محدد في [JFIF]; \\uf0a7 Portable Network Graphics (PNG)، كما هو محدد في [RFC2083] و[W3C - PNG]; و \\uf0a7 Tag Image File Format (TIFF)، كما هو محدد في [RFC3302] و[TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


يحصل أو يعيّن مصفوفة من البايتات التي تحدد الصورة المضغوطة. يجب تحديد نوع الضغط من البيانات نفسها.

يتم تحديد البت ماب بواسطة كائنات EmfPlusBitmap (القسم 2.2.2.2). يجب أن يكون كائن EmfPlusCompressedImage موجودًا في حقل BitmapData لكائن EmfPlusBitmap إذا تم تحديد BitmapDataTypeCompressed في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات المضغوطة، بما في ذلك: \\uf0a7 Exchangeable Image File Format (EXIF)، كما هو محدد في [EXIF]; \\uf0a7 Graphics Interchange Format (GIF)، كما هو محدد في [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG)، كما هو محدد في [JFIF]; \\uf0a7 Portable Network Graphics (PNG)، كما هو محدد في [RFC2083] و[W3C - PNG]; و \\uf0a7 Tag Image File Format (TIFF)، كما هو محدد في [RFC3302] و[TIFF].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

