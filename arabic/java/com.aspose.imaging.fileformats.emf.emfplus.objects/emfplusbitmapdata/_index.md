---
title: "EmfPlusBitmapData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusBitmapData يحدد صورة bitmap ببيانات بكسل."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

كائن EmfPlusBitmapData يحدد صورة bitmap ببيانات بكسل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColors()](#getColors--) | يحصل أو يضبط ألوان اللوحة Colors (متغير): كائن `EmfPlusPalette` اختياري (القسم 2.2.2.28)، الذي يحدد لوحة الألوان المستخدمة في بيانات البكسل. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | يحصل أو يضبط ألوان اللوحة Colors (متغير): كائن `EmfPlusPalette` اختياري (القسم 2.2.2.28)، الذي يحدد لوحة الألوان المستخدمة في بيانات البكسل. |
| [getPixelData()](#getPixelData--) | يحصل أو يضبط بيانات البكسل PixelData (متغير): مصفوفة من البايتات التي تحدد بيانات البكسل. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | يحصل أو يضبط بيانات البكسل PixelData (متغير): مصفوفة من البايتات التي تحدد بيانات البكسل. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


يحصل أو يضبط ألوان اللوحة Colors (متغير): كائن `EmfPlusPalette` اختياري (القسم 2.2.2.28)، الذي يحدد لوحة الألوان المستخدمة في بيانات البكسل. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم I في حقل PixelFormat لكائن `EmfPlusBitmap`.

القيمة: الألوان.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


يحصل أو يضبط ألوان اللوحة Colors (متغير): كائن `EmfPlusPalette` اختياري (القسم 2.2.2.28)، الذي يحدد لوحة الألوان المستخدمة في بيانات البكسل. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم I في حقل PixelFormat لكائن `EmfPlusBitmap`.

القيمة: الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


يحصل أو يضبط بيانات البكسل PixelData (متغير): مصفوفة من البايتات التي تحدد بيانات البكسل. يمكن حساب حجم وشكل هذه البيانات من الحقول في كائن EmfPlusBitmap، بما في ذلك تنسيق البكسل من تعداد `Consts.EmfPlusPixelFormat` (القسم 2.1.1.25).

القيمة: بيانات البكسل.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


يحصل أو يضبط بيانات البكسل PixelData (متغير): مصفوفة من البايتات التي تحدد بيانات البكسل. يمكن حساب حجم وشكل هذه البيانات من الحقول في كائن EmfPlusBitmap، بما في ذلك تنسيق البكسل من تعداد `Consts.EmfPlusPixelFormat` (القسم 2.1.1.25).

القيمة: بيانات البكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

