---
title: "CdrImagePage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "صفحة صورة Cdr"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

صفحة صورة Cdr
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getParentImage()](#getParentImage--) | يحصل على الصورة الأصلية. |
| [getPageNumber()](#getPageNumber--) | يحصل على رقم الصفحة. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |
| [getCdrDocument()](#getCdrDocument--) | يحصل على مستند CDR. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [cacheData()](#cacheData--) | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` الأساسي. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


يحصل على الصورة الأصلية.

القيمة: الصورة الأصلية.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


يحصل على رقم الصفحة.

القيمة: رقم الصفحة.

**Returns:**
int - رقم الصفحة.
### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

**Returns:**
int - عدد البتات لكل بكسل في الصورة.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يحصل على قيمة تنسيق الملف

**Returns:**
long - قيمة تنسيق الملف
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


يحصل على مستند CDR.

القيمة: مستند CDR.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


يحصل على الخيارات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعلمات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public synchronized void cacheData()
```


يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` الأساسي.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


يضبط لوحة ألوان الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

