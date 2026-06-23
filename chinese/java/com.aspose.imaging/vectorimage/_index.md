---
title: "VectorImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "矢量图像是所有类型矢量图像的基类。"
type: docs
weight: 117
url: /zh/java/com.aspose.imaging/vectorimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.interfaces.IObjectWithSizeF](../../com.aspose.imaging.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

矢量图像是所有类型矢量图像的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整为指定的新宽度。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 使用扩展选项调整图像大小。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 旋转、翻转，或同时旋转和翻转图像。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 裁剪指定的矩形。 |
| [rotate(float angle)](#rotate-float-) | 围绕中心旋转图像。 |
| [getSizeF()](#getSizeF--) | 获取对象的尺寸（英寸）。 |
| [getWidthF()](#getWidthF--) | 获取对象的宽度（英寸）。 |
| [getHeightF()](#getHeightF--) | 获取对象的高度，单位为英寸。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 获取默认图像选项。 |
| [getEmbeddedImages()](#getEmbeddedImages--) | 获取嵌入的图像。 |
| [removeBackground()](#removeBackground--) | 移除背景。 |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | 移除背景。 |

## Example: The following example shows how to export a multipage vector image to another format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\java\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页
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


调整为指定的新宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整的类型。 |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


使用扩展选项调整图像大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 调整大小的设置。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


旋转、翻转，或同时旋转和翻转图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转和翻转的类型。 |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


裁剪指定的矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


围绕中心旋转图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


获取对象的尺寸（英寸）。

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the object size, in inches.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


获取对象的宽度（英寸）。

**Returns:**
float - 对象的宽度，单位为英寸。
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


获取对象的高度，单位为英寸。

**Returns:**
float - 对象的高度，单位为英寸。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

**Returns:**
int - 图像宽度。
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

**Returns:**
int - 图像高度。
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


获取默认图像选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | java.lang.Object[] | 参数。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The default image options.
### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


获取嵌入的图像。

**Returns:**
com.aspose.imaging.EmbeddedImage[] - 图像数组

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


移除背景。

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


移除背景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | 设置。 |

