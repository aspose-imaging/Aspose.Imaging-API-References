---
title: "VectorMultipageImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الصورة المتجهية متعددة الصفحات"
type: docs
weight: 118
url: /ar/java/com.aspose.imaging/vectormultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class VectorMultipageImage extends VectorImage implements IMultipageImage
```

الصورة المتجهية متعددة الصفحات
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VectorMultipageImage()](#VectorMultipageImage--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getDefaultPage()](#getDefaultPage--) | يحصل على الصفحة الافتراضية. |
| [getPageExportingAction()](#getPageExportingAction--) | يحصل على إجراء تصدير الصفحة. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | يضبط إجراء تصدير الصفحة. |
| [getMetadata()](#getMetadata--) | يحصل على بيانات تعريف الصورة. |
| [cacheData()](#cacheData--) | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص المستطيل المحدد. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يُعيد تحجيم الصورة. |
| [rotate(float angle)](#rotate-float-) | دوّر الصورة حول المركز. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يُعيد تحجيم الصورة. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | يدور، يقلب، أو يدور ويقلب الصورة. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | يزيل الخلفية. |
| [removeBackground()](#removeBackground--) | يزيل الخلفية. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
| [getEmbeddedImages()](#getEmbeddedImages--) | يحصل على الصور المضمنة. |
### VectorMultipageImage() {#VectorMultipageImage--}
```
public VectorMultipageImage()
```


### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات.

القيمة: `true` إذا تم تخزين بيانات الكائن مؤقتًا؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

القيمة: عدد البتات لكل بكسل في الصورة.

**Returns:**
int - عدد البتات لكل بكسل في الصورة.
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
### getDefaultPage() {#getDefaultPage--}
```
public abstract Image getDefaultPage()
```


يحصل على الصفحة الافتراضية.

القيمة: الصفحة الافتراضية.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


يحصل على إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرة قبل حفظ كل صفحة.

القيمة: إجراء تصدير الصفحة.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


يضبط إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرة قبل حفظ كل صفحة.

القيمة: إجراء تصدير الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | إجراء تصدير الصفحة. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


يحصل على بيانات تعريف الصورة.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### cacheData() {#cacheData--}
```
public void cacheData()
```


يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


يقص المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


يُعيد تحجيم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


دوّر الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


يُعيد تحجيم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع الدوران والقلب. |

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


يزيل الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | الإعدادات. |

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


يزيل الخلفية.

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

### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


يحصل على الصور المضمنة.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - مصفوفة من الصور
