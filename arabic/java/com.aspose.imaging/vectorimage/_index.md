---
title: "VectorImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الصورة المتجهية هي الفئة الأساسية لجميع أنواع الصور المتجهية."
type: docs
weight: 117
url: /ar/java/com.aspose.imaging/vectorimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.interfaces.IObjectWithSizeF](../../com.aspose.imaging.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

الصورة المتجهية هي الفئة الأساسية لجميع أنواع الصور المتجهية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يعيد تحجيم العرض الجديد المحدد. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | يدور، يقلب، أو يدور ويقلب الصورة. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص المستطيل المحدد. |
| [rotate(float angle)](#rotate-float-) | دوّر الصورة حول المركز. |
| [getSizeF()](#getSizeF--) | يحصل على حجم الكائن، بالبوصة. |
| [getWidthF()](#getWidthF--) | يحصل على عرض الكائن، بالبوصة. |
| [getHeightF()](#getHeightF--) | يحصل على ارتفاع الكائن، بالبوصة. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على خيارات الصورة الافتراضية. |
| [getEmbeddedImages()](#getEmbeddedImages--) | يحصل على الصور المضمنة. |
| [removeBackground()](#removeBackground--) | يزيل الخلفية. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | يزيل الخلفية. |

## Example: The following example shows how to export a multipage vector image to another format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\java\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليتين فقط
    com.aspose.imaging.IMultipageImage multipageImage = image instanceof com.aspose.imaging.IMultipageImage ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


يعيد تحجيم العرض الجديد المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


يعيد تحجيم الصورة باستخدام خيارات موسعة.

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

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


يقص المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


دوّر الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |

### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


يحصل على حجم الكائن، بالبوصة.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the object size, in inches.
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

**Returns:**
int - عرض الصورة.
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


يحصل على خيارات الصورة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعلمات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The default image options.
### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


يحصل على الصور المضمنة.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - مصفوفة من الصور

**Example: Support extracting embedded raster images from a vector image**

``` java
String inputFileName = "test.cdr";
try (Image image = com.aspose.imaging.Image.load(inputFileName))
{
    com.aspose.imaging.VectorImage vectorImage = ((com.aspose.imaging.VectorImage) image);
    EmbeddedImage[] images = vectorImage.getEmbeddedImages();
    for (int i = 0; i < images.length; i++)
    {
        String outFileName = String.format("image%d.png", i++);
        try
        {
            images[i].getImage().save(outFileName, new PngOptions());
        }
        finally
        {
            images[i].close();
        }
    }
}
```

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


يزيل الخلفية.

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


يزيل الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | الإعدادات. |

