---
title: "EmfUniversalFontId"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن UniversalFontId يعرّف آلية لتحديد الخطوط في ملفات ميتافايل EMF."
type: docs
weight: 37
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

كائن UniversalFontId يعرّف آلية لتحديد الخطوط في ملفات ميتافايل EMF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getChecksum()](#getChecksum--) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل المجموع الاختباري للخط. |
| [setChecksum(int value)](#setChecksum-int-) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل المجموع الاختباري للخط. |
| [getIndex()](#getIndex--) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل فهرسًا مرتبطًا بكائن الخط. |
| [setIndex(int value)](#setIndex-int-) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل فهرسًا مرتبطًا بكائن الخط. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل المجموع الاختباري للخط. لقيمة المجموع الاختباري المعاني التالية. 0x00000000 الكائن هو خط جهاز. 0x00000001 الكائن هو خط Type 1 تم تثبيته على جهاز العميل ويتم تعدادُه بواسطة برنامج تشغيل طابعة PostScript كخط جهاز. 0x00000002 الكائن ليس خطًا بل هو rasterizer من النوع Type 1. 3 \\u2264 value الكائن هو صورة نقطية أو متجهة أو خط TrueType، أو خط Type 1 rasterized تم إنشاؤه بواسطة rasterizer من النوع Type 1.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل المجموع الاختباري للخط. لقيمة المجموع الاختباري المعاني التالية. 0x00000000 الكائن هو خط جهاز. 0x00000001 الكائن هو خط Type 1 تم تثبيته على جهاز العميل ويتم تعدادُه بواسطة برنامج تشغيل طابعة PostScript كخط جهاز. 0x00000002 الكائن ليس خطًا بل هو rasterizer من النوع Type 1. 3 \\u2264 value الكائن هو صورة نقطية أو متجهة أو خط TrueType، أو خط Type 1 rasterized تم إنشاؤه بواسطة rasterizer من النوع Type 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل فهرسًا مرتبطًا بكائن الخط. يتم تحديد معنى هذا الحقل بناءً على نوع الخط.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يمثل فهرسًا مرتبطًا بكائن الخط. يتم تحديد معنى هذا الحقل بناءً على نوع الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

