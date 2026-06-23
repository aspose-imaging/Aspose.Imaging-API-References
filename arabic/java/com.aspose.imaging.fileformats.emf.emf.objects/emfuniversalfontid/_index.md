---
title: "EmfUniversalFontId"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن UniversalFontId يعرّف آلية لتحديد الخطوط في ملفات الميتافايل EMF."
type: docs
weight: 37
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

كائن UniversalFontId يعرّف آلية لتحديد الخطوط في ملفات الميتافايل EMF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getChecksum()](#getChecksum--) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يمثل قيمة التحقق (checksum) للخط. |
| [setChecksum(int value)](#setChecksum-int-) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يمثل قيمة التحقق (checksum) للخط. |
| [getIndex()](#getIndex--) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يمثل فهرسًا مرتبطًا بكائن الخط. |
| [setIndex(int value)](#setIndex-int-) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يمثل فهرسًا مرتبطًا بكائن الخط. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يمثل قيمة التحقق (checksum) للخط. قيمة التحقق لها المعاني التالية. 0x00000000 الكائن هو خط جهاز. 0x00000001 الكائن هو خط Type 1 تم تثبيته على جهاز العميل ويتم تعدادها بواسطة برنامج تشغيل طابعة PostScript كخط جهاز. 0x00000002 الكائن ليس خطًا بل هو Rasterizer من النوع Type 1. 3 \\u2264 value الكائن هو صورة نقطية (bitmap)، أو متجه، أو خط TrueType، أو خط Type 1 مُرصّص تم إنشاؤه بواسطة Rasterizer من النوع Type 1.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يمثل قيمة التحقق (checksum) للخط. قيمة التحقق لها المعاني التالية. 0x00000000 الكائن هو خط جهاز. 0x00000001 الكائن هو خط Type 1 تم تثبيته على جهاز العميل ويتم تعدادها بواسطة برنامج تشغيل طابعة PostScript كخط جهاز. 0x00000002 الكائن ليس خطًا بل هو Rasterizer من النوع Type 1. 3 \\u2264 value الكائن هو صورة نقطية (bitmap)، أو متجه، أو خط TrueType، أو خط Type 1 مُرصّص تم إنشاؤه بواسطة Rasterizer من النوع Type 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يكون فهرسًا مرتبطًا بكائن الخط. يتم تحديد معنى هذا الحقل بناءً على نوع الخط.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يكون فهرسًا مرتبطًا بكائن الخط. يتم تحديد معنى هذا الحقل بناءً على نوع الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

