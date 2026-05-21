---
title: "RasterCachedMultipageImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "光栅多页图像"
type: docs
weight: 90
url: /zh/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

光栅多页图像
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [isCached()](#isCached--) | 获取一个值，指示图像数据当前是否已缓存。 |
| [hasAlpha()](#hasAlpha--) | 获取一个值，指示此实例是否具有 alpha 通道。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示图像是否具有透明颜色。 |
| [getImageOpacity()](#getImageOpacity--) | 获取此图像的不透明度。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色的值。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 设置背景颜色的值。 |
| [getMetadata()](#getMetadata--) | 获取帧的 XMP 数据。 |
| [getPageExportingAction()](#getPageExportingAction--) | 获取页面导出操作。 |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | 设置页面导出操作。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 调整图像的 `brightness`。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) 对比 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 对图像进行伽马校正。 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 对图像进行伽马校正。 |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | 将此图像实例与 `overlay` 图像混合。 |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | 将基于提供的密码的数字签名嵌入图像的每一页。 |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | 计算提取数据与原始密码之间的相似度百分比。 |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | 使用提供的密码和阈值快速检查图像是否已数字签名。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义阈值对图像进行二值化 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化 |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | 使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值法对图像进行二值化 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 裁剪图像。 |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | 使用位移裁剪图像。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | 对当前图像执行抖动处理。 |
| [grayscale()](#grayscale--) | 将图像转换为灰度表示 |
| [normalizeHistogram()](#normalizeHistogram--) | 归一化图像直方图 \\u2014 调整像素值以使用全部可用范围。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` 图像围绕中心旋转。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 旋转、翻转或旋转并翻转所有页面。 |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | 旋转并翻转全部。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 调整图像大小。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 按比例调整宽度。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 按比例调整宽度。 |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | 将一种颜色替换为另一种颜色（允许差异），并保留原始 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | 过滤指定的矩形。 |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | 归一化角度。 |
| [cacheData()](#cacheData--) | 私有缓存数据。 |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//已实现保存（导出）Tiff 图像前的批量转换功能。

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // 为页面设置批量操作。
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // 触发垃圾回收，以避免前一页的多余垃圾存储。
            System.gc();

            ((com.aspose.imaging.RasterImage) page).rotate(90);
        }
    });

    tiffImage.save(outputFileNameTif);

    /* Attention! In batch mode all pages will be released in this line!
     If you want to further perform operations on the original image, you should reload it from the source to another instance. */
}
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

值：图像高度。

**Returns:**
int - 图像高度。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

值：图像宽度。

**Returns:**
int - 图像宽度。
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

值：图像每像素位数。

**Returns:**
int - 图像每像素位数。
### isCached() {#isCached--}
```
public boolean isCached()
```


获取一个值，指示图像数据当前是否已缓存。

值：如果图像数据已缓存，则为 `true`；否则为 `false`。

**Returns:**
boolean - 表示当前图像数据是否已缓存的值。
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


获取一个值，指示此实例是否具有 alpha 通道。

值：如果此实例具有 alpha，则为 `true`；否则为 `false`。

**Returns:**
boolean - 表示此实例是否具有 alpha 的值。
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


获取一个值，指示图像是否具有透明颜色。

--------------------

此实现检查 `RasterImage.HasTransparentColor`（[RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) 的 `DefaultPage`（\#getDefaultPage\_internalized.getDefaultPage\_internalized）值。

**Returns:**
boolean - 表示图像是否具有透明颜色的值。
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


获取此图像的不透明度。

值：介于 0.0（完全透明）和 1.0（完全不透明）之间的不透明度值。

**Returns:**
float - 此图像的不透明度。
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色的值。

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


设置背景颜色的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 背景颜色的值。 |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


获取帧的 XMP 数据。

值：XMP 数据包包装器

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


获取页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。该操作将在每个页面保存之前执行。

值：页面导出操作。

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。该操作将在每个页面保存之前执行。

值：页面导出操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | 页面导出操作。 |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


调整图像的 `brightness`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | float | 对比度值（范围为 [-100; 100]） |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


对图像进行伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | float | 红色通道的伽马系数 |
| gammaGreen | float | 绿色通道的伽马系数 |
| gammaBlue | float | 蓝色通道的伽马系数 |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


对图像进行伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | float | 红色、绿色和蓝色通道的伽马系数 |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


将此图像实例与 `overlay` 图像混合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | 背景图像混合的起点。 |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | 覆盖图像。 |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | 覆盖区域。 |
| overlayAlpha | byte | 覆盖透明度。 |

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


将基于提供的密码的数字签名嵌入图像的每一页。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 用于生成数字签名数据的密码 |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


计算提取数据与原始密码之间的相似度百分比。

--------------------

由于多页图像，结果表示计算得到的 `MIDDLE AVERAGED signing percentage`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 用于提取嵌入数据的密码。 |

**Returns:**
int - 百分比相似度值。
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


使用提供的密码和阈值快速检查图像是否已数字签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 用于检查签名的密码。 |
|  | percentageThreshold | int | 阈值（百分比）[0-100] 用于确定图像是否被视为已签名。如果未指定，将使用默认阈值（`75`）。 |

--------------------

此方法通过利用 `GetSignPercentage` 提供最快的检测。一旦提取的数据达到指定阈值，旨在提高检测准确性的后续提取步骤将被跳过。

仅当多页图像中的所有页面被识别为已签名时，结果才为 `true`；否则，图像被视为未签名。 |

**Returns:**
boolean - 如果图像已签名则为 True，否则为 false。
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


使用预定义阈值对图像进行二值化

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。若像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素与以该像素为中心的 s × s 窗口像素平均值之间的亮度差。 |
| windowSize | int | 以该像素为中心的 s × s 窗口像素的大小 |

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素与以该像素为中心的 s × s 窗口像素平均值之间的亮度差。 |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


使用 Otsu 阈值法对图像进行二值化

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


裁剪图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


使用位移裁剪图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | int | 左位移。 |
| rightShift | int | 右位移。 |
| topShift | int | 上位移。 |
| bottomShift | int | 下位移。 |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


对当前图像执行抖动处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 抖动的自定义调色板。 |

### grayscale() {#grayscale--}
```
public void grayscale()
```


将图像转换为灰度表示

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


归一化图像直方图 \\u2014 调整像素值以使用全部可用范围。

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` 图像围绕中心旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度，以度为单位。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅 `` 图像内容被旋转。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


旋转、翻转或旋转并翻转所有页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


旋转并翻转全部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlip | int | 旋转翻转。 |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


调整图像大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


调整图像大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 调整大小的设置。 |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


按比例调整宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| resizeType | int | 调整的类型。 |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


按比例调整宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整的类型。 |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


将一种颜色替换为另一种颜色（允许差异），并保留原始 alpha 值以保持平滑边缘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldColorArgb | int | 要替换的旧颜色 ARGB 值。 |
| oldColorDiff | byte | 允许的旧颜色差异，以便能够扩大替换后的颜色色调。 |
| newColorArgb | int | 用于替换旧颜色的新颜色 ARGB 值。 |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorArgb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


过滤指定的矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | 选项。 |

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


标准化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用 [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) 和 [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

### cacheData() {#cacheData--}
```
public void cacheData()
```


私有缓存数据。

