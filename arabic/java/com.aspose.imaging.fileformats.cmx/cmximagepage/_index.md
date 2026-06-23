---
title: "CmxImagePage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "صورة صفحة CMX"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

صورة صفحة CMX
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | يُنشئ مثلاً جديدًا من الفئة [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | يُنشئ مثلاً جديدًا من الفئة [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | يحصل على صفحة CMX. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| [getWidthF()](#getWidthF--) | يحصل على عرض الكائن، بالبوصة. |
| [getHeightF()](#getHeightF--) | يحصل على ارتفاع الكائن، بالبوصة. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [cacheData()](#cacheData--) | لا يمكن استخدام الذاكرة المؤقتة. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


يُنشئ مثلاً جديدًا من الفئة [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | صفحة CMX. |
| container | [Image](../../com.aspose.imaging/image) | الحاوية. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


يُنشئ مثلاً جديدًا من الفئة [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | صفحة CMX. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


يحصل على صفحة CMX.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يحصل على قيمة تنسيق الملف

**Returns:**
long - قيمة تنسيق الملف
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

**Returns:**
int - عدد البتات لكل بكسل في الصورة.
### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات.

القيمة: `true` إذا تم تخزين بيانات الكائن مؤقتًا؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


يحصل على عرض الكائن، بالبوصة.

**Returns:**
float - عرض الكائن، بالبوصة.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


يحصل على ارتفاع الكائن، بالبوصة.

**Returns:**
float - ارتفاع الكائن، بالبوصة.
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

القيمة: عرض الصورة.

**Returns:**
int - عرض الصورة.
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

القيمة: ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


يحصل على الخيارات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعاملات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


لا يمكن استخدام الذاكرة المؤقتة.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة من ملف CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // هذه العملية تخزن مؤقتًا الصفحة الافتراضية فقط.
    image.cacheData();

    // قم بتخزين جميع الصفحات مؤقتًا حتى لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

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

