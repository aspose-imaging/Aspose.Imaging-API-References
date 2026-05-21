---
title: "RasterImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示支持光栅图形操作的光栅图像。"
type: docs
weight: 91
url: /zh/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

表示支持光栅图形操作的光栅图像。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | 获取或设置一个值，指示图像组件是否必须进行预乘。 |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 获取或设置一个值，指示图像组件是否必须进行预乘。 |
| [getUseRawData()](#getUseRawData--) | 获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。 |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | 获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。 |
| [getUpdateXmpData()](#getUpdateXmpData--) | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | 获取或设置索引颜色转换器 |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | 获取或设置索引颜色转换器 |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | 获取或设置自定义颜色转换器 |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | 获取或设置自定义颜色转换器 |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | 获取或设置在调色板索引超出范围时使用的回退索引 |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | 获取或设置在调色板索引超出范围时使用的回退索引 |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | 获取指示是否使用图像调色板的值。 |
| [getRawDataFormat()](#getRawDataFormat--) | 获取原始数据格式。 |
| [getRawLineSize()](#getRawLineSize--) | 获取原始行大小（字节）。 |
| [isRawDataAvailable()](#isRawDataAvailable--) | 获取一个值，指示原始数据加载是否可用。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 获取或设置此 `RasterImage` 的水平分辨率（每英寸像素数）。 |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 获取或设置此 `RasterImage` 的水平分辨率（每英寸像素数）。 |
| [getVerticalResolution()](#getVerticalResolution--) | 获取或设置此 `RasterImage` 的垂直分辨率（每英寸像素数）。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 获取或设置此 `RasterImage` 的垂直分辨率（每英寸像素数）。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示此 [RasterImage](../../com.aspose.imaging/rasterimage) 实例是否具有透明颜色。 |
| [hasAlpha()](#hasAlpha--) | 获取一个值，指示此实例是否具有 alpha 通道。 |
| [getTransparentColor()](#getTransparentColor--) | 获取图像的透明颜色。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 设置一个值，指示此 [RasterImage](../../com.aspose.imaging/rasterimage) 实例是否具有透明颜色。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | 获取图像的透明颜色。 |
| [getImageOpacity()](#getImageOpacity--) | 获取此图像的不透明度。 |
| [removeMetadata()](#removeMetadata--) | 通过将此 `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) 的值设为 `null`，移除此图像实例的元数据。 |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | 检索资源图像最近一次修改的日期和时间。 |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | 对当前图像执行抖动处理。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | 对当前图像执行抖动处理。 |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | 使用部分像素加载器获取默认像素数组。 |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | 使用部分像素加载器获取默认原始数据数组。 |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | 获取默认的 32 位 ARGB 像素数组。 |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | 获取默认的原始数据数组。 |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | 获取图像的 32 位 ARGB 像素。 |
| [getPixel(int x, int y)](#getPixel-int-int-) | 获取图像像素。 |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | 为指定位置设置图像像素。 |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | 按指定的扫描线索引读取整条扫描线。 |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | 按指定的扫描线索引读取整条扫描线。 |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | 将整条扫描线写入指定的扫描线索引。 |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | 将整条扫描线写入指定的扫描线索引。 |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | 按包部分加载 32 位 ARGB 像素。 |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | 按包部分加载像素。 |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | 加载 32 位 ARGB 像素。 |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | 加载 64 位 ARGB 像素。 |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | 按包部分加载 64 位 ARGB 像素。 |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | 加载像素。 |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | 以 CMYK 格式加载像素。 |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | 以 CMYK 格式加载像素。 |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | 使用部分处理机制加载原始图像数据。 |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | 加载原始数据。 |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | 保存原始数据。 |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | 保存 32 位 ARGB 像素。 |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | 保存像素。 |
| [toBitmap()](#toBitmap--) | 将光栅图像转换为位图。 |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | 保存像素。 |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | 保存像素。 |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | 为此 `RasterImage` 设置分辨率。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 设置图像调色板。 |
| [autoRotate()](#autoRotate--) | 自动根据从 Exif 元数据提取的方向数据旋转图像。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 使用扩展选项调整图像大小。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | 围绕中心旋转图像。 |
| [rotate(float angle)](#rotate-float-) | 围绕中心旋转图像。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义阈值对图像进行二值化 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值法对图像进行二值化 |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | 使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化 |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | 将此图像实例与 `overlay` 图像混合。 |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | 将此图像实例与 `overlay` 图像混合。 |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | 将此图像实例与 `overlay` 进行混合，alpha == 255。 |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | 将此图像实例与 `overlay` 进行混合。 |
| [grayscale()](#grayscale--) | 将图像转换为灰度表示 |
| [normalizeHistogram()](#normalizeHistogram--) | 归一化图像直方图 \\u2014 调整像素值以使用全部可用范围。 |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | 对整幅图像进行自动自适应亮度和对比度归一化。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 调整图像的亮度。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 图像对比度增强 |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | 使用隐写技术将基于提供的密码的数字签名嵌入图像中。 |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | 计算提取数据与原始密码之间的相似度百分比。 |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | 使用提供的密码和阈值快速检查图像是否已数字签名。 |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | 使用提供的密码和阈值快速检查图像是否已数字签名。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 对图像进行伽马校正。 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 对图像进行伽马校正。 |
| [getSkewAngle()](#getSkewAngle--) | 获取倾斜角度。 |
| [normalizeAngle()](#normalizeAngle--) | 归一化角度。 |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | 归一化角度。 |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | 过滤指定的矩形。 |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | 将一种颜色替换为另一种颜色（允许差异），并保留原始 alpha 值以保持平滑边缘。 |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | 将一种颜色替换为另一种颜色（允许差异），并保留原始 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。 |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// 创建 GifOptions 的实例并设置其各种属性，包括 Source 属性。
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// 创建 Image 的实例
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // 通过将区域指定为图像边界来获取图像的像素。
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // 遍历数组并设置交替索引像素的颜色。
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // 将索引像素颜色设置为黄色。
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // 将索引像素颜色设置为蓝色。
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // 将像素更改应用于图像。
    image.savePixels(image.getBounds(), pixels);

    // 保存所有更改。
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


获取或设置一个值，指示图像组件是否必须进行预乘。

**Returns:**
布尔值 - 如果图像组件必须预乘则为 `true`；否则为 `false`。
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


获取或设置一个值，指示图像组件是否必须进行预乘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | `true` 表示图像组件必须预乘；否则为 `false`。 |


**Example: The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 保存整幅图像的像素。
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // 像素以非预乘形式存储在原始图像中。
    // 需要显式指定相应的选项以获取预乘颜色分量。
    // 预乘颜色分量通过以下公式计算：
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    rasterImage.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = rasterImage.loadPixels(rasterImage.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}
```

### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。

**Returns:**
布尔值 - 如果在原始数据加载可用时使用原始数据加载则为 `true`；否则为 `false`。
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | `true` 表示在原始数据加载可用时使用原始数据加载；否则为 `false`。 |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


获取或设置一个值，指示是否更新 XMP 元数据。

**Returns:**
布尔值 - 如果更新 XMP 元数据则为 `true`；否则为 `false`。
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


获取或设置一个值，指示是否更新 XMP 元数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | `true` 表示更新 XMP 元数据；否则为 `false`。 |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


获取或设置索引颜色转换器

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


获取或设置索引颜色转换器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | 索引颜色转换器 |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


获取或设置自定义颜色转换器

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


获取或设置自定义颜色转换器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | 自定义颜色转换器 |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


获取或设置在调色板索引超出范围时使用的回退索引

**Returns:**
int - 当调色板索引超出范围时使用的回退索引
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


获取或设置在调色板索引超出范围时使用的回退索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 当调色板索引超出范围时使用的回退索引 |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


获取当前原始数据设置。注意，使用这些设置时数据将直接加载而不进行转换。

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


获取指示是否使用图像调色板的值。

值：`true` 表示在图像中使用调色板；否则为 `false`。

**Returns:**
boolean - 表示是否使用图像调色板的值。
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


获取原始数据格式。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// 要加载的图像文件。
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// 输出可能如下所示：
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


获取原始行大小（字节）。

**Returns:**
int - 原始行大小（字节）。
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


获取一个值，指示原始数据加载是否可用。

**Returns:**
布尔值 - 如果此原始数据加载可用则为 `true`；否则为 `false`。
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


获取或设置此 `RasterImage` 的水平分辨率（每英寸像素数）。

**Returns:**
double - 水平分辨率。

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 获取图像的水平和垂直分辨率
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // 输出可能如下所示：
    // 水平分辨率（每英寸像素数）：300.0
    // 垂直分辨率（每英寸像素数）：300.0
    // 将分辨率设置为 96 dpi
    // 水平分辨率（每英寸像素数）：96.0
    // 垂直分辨率（每英寸像素数）：96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


获取或设置此 `RasterImage` 的水平分辨率（每英寸像素数）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 水平分辨率。 |

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。 |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


获取或设置此 `RasterImage` 的垂直分辨率（每英寸像素数）。

**Returns:**
double - 垂直分辨率。

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 获取图像的水平和垂直分辨率
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // 输出可能如下所示：
    // 水平分辨率（每英寸像素数）：300.0
    // 垂直分辨率（每英寸像素数）：300.0
    // 将分辨率设置为 96 dpi
    // 水平分辨率（每英寸像素数）：96.0
    // 垂直分辨率（每英寸像素数）：96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


获取或设置此 `RasterImage` 的垂直分辨率（每英寸像素数）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 垂直分辨率。 |

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。 |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


获取一个值，指示此 [RasterImage](../../com.aspose.imaging/rasterimage) 实例是否具有透明颜色。

--------------------

基类实现如果未在支持此功能的特定实现中被覆盖，则会返回 ``。此属性主要被 [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) 使用，以在图像不支持通过 alpha 通道的透明度时设置透明颜色。

**Returns:**
boolean - 一个值，指示此 [RasterImage](../../com.aspose.imaging/rasterimage) 实例是否具有透明颜色。
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


获取一个值，指示此实例是否具有 alpha 通道。

**Returns:**
boolean - 如果此实例具有 alpha，则为 `true`；否则为 `false`。

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// 要加载的图像文件。
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// 输出可能如下所示：
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


获取图像的透明颜色。

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


设置一个值，指示此 [RasterImage](../../com.aspose.imaging/rasterimage) 实例是否具有透明颜色。

--------------------

基类实现如果未在支持此功能的特定实现中被覆盖，则会返回 ``。此属性主要被 [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) 使用，以在图像不支持通过 alpha 通道的透明度时设置透明颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 一个值，指示此 [RasterImage](../../com.aspose.imaging/rasterimage) 实例是否具有透明颜色。 |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


获取图像的透明颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


获取此图像的不透明度。

**Returns:**
float - 不透明度值，介于 0.0（完全透明）和 1.0（完全不透明）之间。
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


通过将此 `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) 的值设为 `null`，移除此图像实例的元数据。

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


检索资源图像最近一次修改的日期和时间。此方法提供有价值的元数据，使用户能够有效跟踪和管理图像文件的更新。通过访问此信息，用户可以确保其图像资产的完整性和时效性，从而在图像使用和维护方面做出明智的决策。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| useDefault | boolean | 如果设置为 `true`，则使用来自 FileInfo 的信息作为默认值。 |

**Returns:**
java.util.Date - 资源图像上次修改的日期和时间。
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


对当前图像执行抖动处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 使用包含 16 种颜色的 4 位色彩调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 使用仅包含 2 种颜色（黑色和白色）的 1 位色彩调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


对当前图像执行抖动处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 抖动的自定义调色板。 |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


使用部分像素加载器获取默认像素数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于获取像素的矩形。 |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | 部分像素加载器。 |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


使用部分像素加载器获取默认原始数据数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于获取像素的矩形。 |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | 部分原始数据加载器。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | 原始数据设置。 |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


获取默认的 32 位 ARGB 像素数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于获取像素的矩形。 |

**Returns:**
int[] - 默认像素数组。
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


获取默认的原始数据数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于获取原始数据的矩形。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | 原始数据设置。 |

**Returns:**
byte[] - 默认的原始数据数组。
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


获取图像的 32 位 ARGB 像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标位置。 |
| y | int | 像素的 y 坐标位置。 |

**Returns:**
int - 指定位置的 32 位 ARGB 像素。

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 获取图像左上像素颜色的整数表示。
    int color = rasterImage.getArgb32Pixel(0, 0);

    // 要获取各个颜色分量的值，需要将颜色值按相应的位数进行移位。
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 像素 (0,0) 的颜色为 A=255,R=0,G=0,B=0
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


获取图像像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标位置。 |
| y | int | 像素的 y 坐标位置。 |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 获取图像左上像素的颜色。
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // 获取各个颜色分量的值
    int alpha = color.getA();
    int red = color.getR();
    int green = color.getG();
    int blue = color.getB();

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}
```

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


为指定位置设置图像的 32 位 ARGB 像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标位置。 |
| y | int | 像素的 y 坐标位置。 |
| argb32Color | int | 指定位置的 32 位 ARGB 像素。 |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 设置左上像素的颜色。
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // 另一种方式是直接传递 com.aspose.imaging.Color 的实例
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


为指定位置设置图像像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标位置。 |
| y | int | 像素的 y 坐标位置。 |
| color | [Color](../../com.aspose.imaging/color) | 指定位置的像素颜色。 |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 设置左上像素的颜色。
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // 另一种方式是直接传递 com.aspose.imaging.Color 的实例
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


按指定的扫描线索引读取整条扫描线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |

**Returns:**
com.aspose.imaging.Color[] - 扫描线像素颜色值数组。
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


按指定的扫描线索引读取整条扫描线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |

**Returns:**
int[] - 扫描线 32 位 ARGB 颜色值数组。
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


将整条扫描线写入指定的扫描线索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | 待写入的像素颜色数组。 |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


将整条扫描线写入指定的扫描线索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |
| argb32Pixels | int[] | 待写入的 32 位 ARGB 颜色数组。 |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


按包部分加载 32 位 ARGB 像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 所需的矩形。 |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | 32 位 ARGB 像素加载器。 |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
以下示例演示如何使用您自己的部分处理器加载和处理栅格图像的像素。例如，考虑统计图像中完全透明像素的问题。为了使用部分加载机制统计透明像素，介绍了一个实现 com.aspose.imaging.IPartialArgb32PixelLoader 的单独类 TransparentArgb32PixelCounter。
``` java

// 首先，实现 com.aspose.imaging.IPartialArgb32PixelLoader 来计数所有完全透明的像素。
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentArgb32PixelCounter implements com.aspose.imaging.IPartialArgb32PixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>                 *
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, int[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (int pixel : pixels) {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0) {
                this.count++;
            }
        }
    }
}

// 下面是使用计数器的示例。
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 创建 com.aspose.imaging.IPartialArgb32PixelLoader 的实例并将其传递给 com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 com.aspose.imaging.RasterImage.loadPartialArgb32Pixels 方法的第一个参数指定。
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 完全透明像素的数量为 55157
// 像素的总数为 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


按包部分加载像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 所需的矩形。 |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | 像素加载器。 |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
下面的示例展示了如何使用您自己的部分处理器加载和处理光栅图像的像素。例如，考虑一个统计图像中完全透明像素的问题。为了使用部分加载机制计数透明像素，引入了实现 com.aspose.imaging.IPartialPixelLoader 的单独类 TransparentPixelCounter。
``` java

// 首先，实现 com.aspose.imaging.IPartialPixelLoader 来计数所有完全透明的像素。
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelCounter implements com.aspose.imaging.IPartialPixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, com.aspose.imaging.Color[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (com.aspose.imaging.Color pixel : pixels) {
            if (pixel.getA() == 0) {
                this.count++;
            }
        }
    }
}

// 下面是使用计数器的示例。
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 创建 com.aspose.imaging.IPartialPixelLoader 的实例并将其传递给 com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 com.aspose.imaging.RasterImage.loadPartialPixels 方法的第一个参数指定。
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 完全透明像素的数量为 55157
// 像素的总数为 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


加载 32 位 ARGB 像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要从中加载像素的矩形。 |

**Returns:**
int[] - 已加载的 32 位 ARGB 像素数组。

**Example: The following example shows how to load and process pixels of a raster image.**
下面的示例展示了如何加载和处理光栅图像的像素。像素以 32 位整数值表示。例如，考虑一个统计图像中完全透明像素的问题。
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 com.aspose.imaging.RasterImage.loadArgb32Pixels 方法的参数指定。
    int[] pixels = rasterImage.loadArgb32Pixels(rasterImage.getBounds());

    int count = 0;
    for (int pixel : pixels) {
        int alpha = (pixel >> 24) & 0xff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.imaging.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


加载 64 位 ARGB 像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要从中加载像素的矩形。 |

**Returns:**
long[] - 已加载的 64 位 ARGB 像素数组。

**Example: The following example shows how to load and process pixels of a raster image.**
下面的示例展示了如何加载和处理光栅图像的像素。像素以 64 位整数值表示。例如，考虑一个统计图像中完全透明像素的问题。
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 com.aspose.imaging.RasterImage.loadArgb64Pixels 方法的参数指定。
    // 请注意，图像本身必须是每个样本 16 位，因为 com.aspose.imaging.RasterImage.loadArgb64Pixels 不支持每个样本 8 位。
    // 若要使用每个样本 8 位，请使用老牌的 com.aspose.imaging.RasterImage.loadArgb32Pixels 方法。
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // 请注意，所有颜色分量（包括 alpha）均以 16 位值表示，因此其允许的取值范围为 [0, 63535]。
        long alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader) {#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-}
```
public final void loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)
```


按包部分加载 64 位 ARGB 像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 所需的矩形。 |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | 64 位 ARGB 像素加载器。 |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


加载像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要从中加载像素的矩形。 |

**Returns:**
com.aspose.imaging.Color[] - 已加载的像素数组。

**Example: The following example shows how to load and process pixels of a raster image.**
下面的示例展示了如何加载和处理光栅图像的像素。例如，考虑一个统计图像中完全透明像素的问题。
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 Aspose.Imaging.RasterImage.LoadPixels 方法的参数指定。
    com.aspose.imaging.Color[] pixels = rasterImage.loadPixels(rasterImage.getBounds());

    int count = 0;
    for (com.aspose.imaging.Color pixel : pixels) {
        if (pixel.getA() == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.imaging.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


以 CMYK 格式加载像素。此方法已弃用。请改用更高效的 `loadCmyk32Pixels(Rectangle)` 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要从中加载像素的矩形。 |

**Returns:**
com.aspose.imaging.CmykColor[] - 已加载的 CMYK 像素数组。
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


以 CMYK 格式加载像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要从中加载像素的矩形。 |

**Returns:**
int[] - 已加载的 CMYK 像素以 32 位整数值的形式呈现。
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


使用部分处理机制加载原始图像数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要从中加载数据的图像的目标矩形区域。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | 原始数据设置。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | 原始数据加载器。 |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
以下示例展示了如何使用 RawDataSettings 从原始图像数据中提取像素。例如，考虑统计图像中完全透明像素的问题。
``` java

// 首先，实现一个计数器。对于原始数据，计数器可能如下所示：
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelRawDataCounter implements com.aspose.imaging.IPartialRawDataLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * The raw data settings of the loaded image.
     */
    private com.aspose.imaging.RawDataSettings rawDataSettings;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Initializes a new instance of the <see TransparentPixelRawDataCounter /> class.</p>
     *
     * @param settings The raw data settings allow to extract color components from raw data.
     */
    public TransparentPixelRawDataCounter(com.aspose.imaging.RawDataSettings settings) {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end)// throws java.lang.Exception
    {
        int[] channelBits = this.rawDataSettings.getPixelDataFormat().getChannelBits();

        // 此处仅考虑简单格式，以简化代码。
        // 我们仅考虑每个样本为 8 位的图像。
        for (int i = 0; i < channelBits.length; i++) {
            if (channelBits[i] != 8) {
                throw new java.lang.UnsupportedOperationException();
            }
        }

        switch (this.rawDataSettings.getPixelDataFormat().getPixelFormat()) {
            case com.aspose.imaging.PixelFormat.Rgb:
            case com.aspose.imaging.PixelFormat.Bgr: {
                if (channelBits.length == 4) {
                    // ARGB
                    for (int i = 0; i < data.length; i += 4) {
                        // Alpha 通道存储在最后，位于颜色分量之后。
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // 灰度 Alpha
                    for (int i = 0; i < data.length; i += 2) {
                        // Alpha 通道存储在最后，位于颜色分量之后。
                        if (data[i + 1] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            default:
                throw new java.lang.IllegalArgumentException("PixelFormat");
        }
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>                 *
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     * @param loadOptions   The load options.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end, com.aspose.imaging.LoadOptions loadOptions) {
        this.process(dataRectangle, data, start, end);
    }
}

// 以下是使用计数器的主要示例
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // 加载整幅图像的像素。图像的任意矩形部分都可以作为 Aspose.Imaging.RasterImage.LoadRawData 方法的参数指定。
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 完全透明像素的数量为 55157
// 像素的总数为 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


加载原始数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于加载原始数据的矩形。 |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | 目标图像的边界。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | 用于已加载数据的原始数据设置。请注意，如果数据不是指定的格式，则会执行数据转换。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | 原始数据加载器。 |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


保存原始数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 原始数据。 |
| dataOffset | int | 起始原始数据偏移量。 |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 原始数据矩形。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | 数据所在的原始数据设置。 |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


保存 32 位 ARGB 像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于保存像素的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素数组。 |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
以下示例使用 com.aspose.imaging.RasterImage.saveArgb32Pixels 方法将栅格图像的中心区域填充为黑色像素。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 黑色方块
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // 在图像中心绘制黑色方块。
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveArgb32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveArgb32Pixels.png");
} finally {
    image.dispose();
}
```

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


保存像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于保存像素的矩形。 |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | 像素数组。 |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
以下示例使用 com.aspose.imaging.RasterImage.savePixels 方法填充光栅图像的中心区域为黑色像素。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 黑色方块
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // 在图像中心绘制黑色方块。
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.savePixels(area, pixels);

    rasterImage.save(dir + "sample.SavePixels.png");
} finally {
    image.dispose();
}
```

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


将光栅图像转换为位图。

**Returns:**
java.awt.image.BufferedImage - 位图

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // 处理本机 Java 位图。
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


保存像素。此方法已弃用。请使用更有效的 `saveCmyk32Pixels(Rectangle, int[])` 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于保存像素的矩形。 |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK 像素数组。 |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


保存像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 用于保存像素的矩形。 |
| 像素 | int[] | CMYK 像素以 32 位整数值的形式呈现。 |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
以下示例使用 com.aspose.imaging.RasterImage.saveCmyk32Pixels 方法填充光栅图像的中心区域为黑色像素。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 获取 CMYK 颜色空间中黑色的整数表示。
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // 黑色方块。
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // 在图像中心绘制黑色方块。
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveCmyk32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveCmyk32Pixels.png");
} finally {
    image.dispose();
}
```

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


为此 `RasterImage` 设置分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | double | `RasterImage` 的水平分辨率（每英寸点数）。 |
| dpiY | double | `RasterImage` 的垂直分辨率（每英寸点数）。 |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 获取图像的水平和垂直分辨率
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // 输出可能如下所示：
    // 水平分辨率（每英寸像素数）：300.0
    // 垂直分辨率（每英寸像素数）：300.0
    // 将分辨率设置为 96 dpi
    // 水平分辨率（每英寸像素数）：96.0
    // 垂直分辨率（每英寸像素数）：96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


设置图像调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供在不同平台和设备上无缝的观看体验。此自动旋转过程简化了图像处理并提高整体可用性，尤其在处理具有不同方向的大批量图像时。

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

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


围绕中心旋转图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


围绕中心旋转图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


使用预定义阈值对图像进行二值化

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。若像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |


**Example: The following example binarizes a raster image with the predefined threshold.**
以下示例使用预定义阈值对光栅图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为 255；否则为 0。
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


使用 Otsu 阈值法对图像进行二值化


**Example: The following example binarizes a raster image with Otsu thresholding.**
以下示例使用 Otsu 阈值法对光栅图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 使用 Otsu 阈值法对图像进行二值化。
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素与以该像素为中心的 s × s 窗口像素平均值之间的亮度差。 |

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


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
以下示例使用 Bradley 自适应阈值算法（指定窗口大小）对光栅图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 使用亮度差 5 对图像进行二值化。亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-}
```
public final void blend(Point origin, RasterImage overlay, Rectangle overlayArea)
```


将此图像实例与 `overlay` 图像混合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | 背景图像混合的起点。 |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | 覆盖图像。 |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | 覆盖区域。 |

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

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


将此图像实例与 `overlay` 进行混合，alpha == 255。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | 背景图像混合的起点。 |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | 覆盖层。 |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


将此图像实例与 `overlay` 进行混合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | 背景图像混合的起点。 |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | 覆盖层。 |
| overlayAlpha | byte | 覆盖透明度。 |

### grayscale() {#grayscale--}
```
public void grayscale()
```


将图像转换为灰度表示


**Example: The following example transforms a colored raster image to its grayscale representation.**
以下示例将彩色光栅图像转换为其灰度表示。灰度图像仅由灰色阴影组成，只包含强度信息。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


归一化图像直方图 \\u2014 调整像素值以使用全部可用范围。

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


对整幅图像进行自动自适应亮度和对比度归一化。

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


调整图像的亮度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 设置亮度值。亮度的可接受范围为 [-255, 255]。
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


图像对比度增强

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | float | 对比度值（范围为 [-100; 100]） |


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 设置对比度值。对比度的可接受范围为 [-100f, 100f]。
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


使用隐写技术将基于提供的密码的数字签名嵌入图像中。

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

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 用于提取嵌入数据的密码。 |

**Returns:**
int - 百分比相似度值。
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


使用提供的密码和阈值快速检查图像是否已数字签名。

--------------------

此方法通过利用 `GetSignPercentage` 提供最快的检测。一旦提取的数据达到指定阈值，旨在提高检测准确性的后续提取步骤将被跳过。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 用于检查签名的密码。 |

**Returns:**
boolean - 如果图像已签名则为 True，否则为 false。
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


使用提供的密码和阈值快速检查图像是否已数字签名。

--------------------

此方法通过利用 `GetSignPercentage` 提供最快的检测。一旦提取的数据达到指定阈值，旨在提高检测准确性的后续提取步骤将被跳过。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 用于检查签名的密码。 |
| percentageThreshold | int | 阈值（百分比）[0-100] 用于确定图像是否被视为已签名。如果未指定，将使用默认阈值（`75`）。 |

**Returns:**
boolean - 如果图像已签名则为 True，否则为 false。
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


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 为红色、绿色和蓝色通道设置各自的伽马系数。
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


对图像进行伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 伽马 | float | 红色、绿色和蓝色通道的伽马系数 |


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 为红色、绿色和蓝色通道设置伽马系数。
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。

**Returns:**
float - 倾斜角度（单位：度）。
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


标准化角度。此方法适用于扫描的文本文件，以消除倾斜的扫描。此方法使用 \#getSkewAngle.getSkewAngle 和 [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-) 方法。

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


标准化角度。此方法适用于扫描的文本文件，以消除倾斜的扫描。此方法使用 \#rotate(float, boolean, Color).rotate(float, boolean, Color) 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
倾斜是文档扫描过程中可能出现的伪影，当文档的文字/图像略微旋转时会产生。它可能由多种原因导致，但最常见的是扫描时纸张位置偏移。因此，去倾斜是对扫描文件（即位图）进行检测并修复此问题的过程，使去倾斜后的文档文字/图像能够正确且水平地显示。
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// 使用默认参数消除倾斜的扫描
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(inputFilePath);
try {
    // 去倾斜
    image.normalizeAngle(false /*do not resize*/, com.aspose.imaging.Color.getLightGray() /*background color*/);
    image.save(outputFilePath);
} finally {
    image.close();
}
```

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


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用矩形大小为 5 的中值滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用核大小为 5 的双边平滑滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用半径为 5、sigma 值为 4.0 的高斯模糊滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用核大小为 5、sigma 值为 4.0 的锐化滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


将一种颜色替换为另一种颜色（允许差异），并保留原始 alpha 值以保持平滑边缘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | 待替换的旧颜色。 |
| oldColorDiff | byte | 允许的旧颜色差异，以便能够扩大替换后的颜色色调。 |
| newColor | [Color](../../com.aspose.imaging/color) | 用于替换旧颜色的新颜色。 |

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

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | 用于替换非透明颜色的新颜色。 |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorArgb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

