---
title: "RasterCachedImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示支持光栅图形操作的光栅图像。"
type: docs
weight: 89
url: /zh/java/com.aspose.imaging/rastercachedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

表示支持光栅图形操作的光栅图像。需要时此图像会缓存像素数据。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isCached()](#isCached--) | 获取一个指示图像数据当前是否已缓存的值。 |
| [cacheData()](#cacheData--) | 缓存数据，并确保不会从底层 `DataStreamSupporter.DataStreamContainer` 再进行额外的数据加载。 |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | 将此图像实例与 `overlay` 图像混合。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 调整图像大小。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 旋转、翻转，或同时旋转和翻转图像。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | 围绕中心旋转图像。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 裁剪图像。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | 对当前图像执行抖动处理。 |
| [grayscale()](#grayscale--) | 将图像转换为灰度表示 |
| [normalizeHistogram()](#normalizeHistogram--) | 归一化图像直方图 \\u2014 调整像素值以使用全部可用范围。 |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | 对整幅图像执行自动自适应亮度和对比度归一化。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义阈值对图像进行二值化 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值法对图像进行二值化 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化 |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | 使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 调整图像的亮度。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 图像对比度增强 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 对图像进行伽马校正。 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 对图像进行伽马校正。 |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | 使用隐写技术将基于提供的密码的数字签名嵌入图像中。 |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | 计算提取数据与原始密码之间的相似度百分比。 |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | 使用提供的密码和阈值快速检查图像是否已进行数字签名。 |

## Example: The following example transforms a colored raster cached image to its grayscale representation.
以下示例将彩色栅格缓存图像转换为灰度表示。灰度图像仅由灰色阴影组成，只携带强度信息。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### isCached() {#isCached--}
```
public boolean isCached()
```


获取一个指示图像数据当前是否已缓存的值。

**Returns:**
布尔值 - 如果图像数据已缓存则为 `true`；否则为 `false`。
### cacheData() {#cacheData--}
```
public void cacheData()
```


缓存数据，并确保不会从底层 `DataStreamSupporter.DataStreamContainer` 再进行额外的数据加载。


**Example: The following example shows how raster image caching affects performance.**
以下示例展示了栅格图像缓存如何影响性能。一般情况下，读取缓存数据比读取未缓存数据更快。
``` java
String dir = "c:\\temp\\";

// 从 PNG 文件加载图像。
com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // 缓存所有像素数据，以免从底层数据流进行额外的数据加载
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // 读取所有像素相当快。
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// 从 PNG 文件加载图像
image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // 读取所有像素的速度不如缓存时快
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// 输出可能如下所示：
//读取所有缓存像素耗时 2923 毫秒。
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:54)
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


将此图像实例与 `overlay` 图像混合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | 背景图像混合的原点。 |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | 覆盖图像。 |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | 覆盖区域。 |
| overlayAlpha | byte | 覆盖透明度。 |

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


**Example: This example loads a raster cached image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

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


**Example: This example loads a raster cached image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// 基于加权和混合有理函数以及 lanczos3 插值的自适应算法。
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// 小矩形滤波器
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// 调色板中的颜色数量。
resizeSettings.setEntriesCount(256);

// 未使用颜色量化
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// 欧几里得方法
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // 使用自适应重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


旋转、翻转，或同时旋转和翻转图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |


**Example: This example loads a raster cached image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// 这是一个帮助类。
class LocalHelper {
    // 获取旋转翻转类型的字符串表示。
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// 以下是主要示例
int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

LocalHelper localHelper = new LocalHelper();
for (int rotateFlipType : rotateFlipTypes) {
    // 旋转、翻转并保存到输出文件。
    com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + localHelper.rotateFlipTypeToString(rotateFlipType) + ".bmp");
    } finally {
        image.dispose();
    }
}
```

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


围绕中心旋转图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度，以度为单位。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


裁剪图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |


**Example: The following example crops a raster cached image.**
以下示例裁剪栅格缓存图像。裁剪区域通过 com.aspose.imaging.Rectangle 指定。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 裁剪图像。裁剪区域是图像的中心矩形区域。
    int width = rasterImage.getWidth();
    int height = rasterImage.getHeight();
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(width / 4, height / 4, width / 2, height / 2);
    rasterImage.crop(area);

    // 将裁剪后的图像保存为 PNG
    rasterImage.save(dir + "sample.Crop.png");
} finally {
    image.dispose();
}
```

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


**Example: The following example transforms a colored raster cached image to its grayscale representation.**
以下示例将彩色栅格缓存图像转换为灰度表示。灰度图像仅由灰色阴影组成，只携带强度信息。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


对整幅图像执行自动自适应亮度和对比度归一化。

--------------------

> ```
> // Example usage in image pre-processing:
>  image.AutoBrightnessContrast();
> ```

--------------------

此方法应用一系列高级自适应滤镜（CLAHE、自适应白色拉伸和自动白平衡）管线，以通过增强对比度、局部亮度和色彩保真度来提升图像的视觉质量。

`**过滤管线:**`

1.  对比度受限自适应直方图均衡 (CLAHE) – 提高局部对比度并增强细微细节。
2.  自适应白色拉伸 – 在保护暗部特征的同时提升有效白色水平。
3.  自动白平衡 – 通过平衡通道直方图校正颜色偏差。

`**注意:**`

 *  
 *  

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


使用预定义阈值对图像进行二值化

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。若像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |


**Example: The following example binarizes a raster cached image with the predefined threshold.**
以下示例使用预定义阈值对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为 255，否则为 0。
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


**Example: The following example binarizes a raster cached image with Otsu thresholding.**
以下示例使用 Otsu 阈值法对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 使用 Otsu 阈值法对图像进行二值化。
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


使用 Bradley 的自适应阈值算法（基于积分图像阈值）对图像进行二值化

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素的亮度差是该像素与以其为中心的 s × s 窗口像素平均值之间的差异。 |
| windowSize | int | 以该像素为中心的 s × s 窗口的大小 |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size.**
以下示例使用 Bradley 自适应阈值算法并指定窗口大小，对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 使用亮度差为 5 对图像进行二值化。
    // 亮度是该像素与以其为中心的 10 × 10 窗口像素平均值之间的差异。
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
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
| brightnessDifference | double | 像素的亮度差是该像素与以其为中心的 s × s 窗口像素平均值之间的差异。 |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm.**
以下示例使用 Bradley 自适应阈值算法对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 使用亮度差为 5 对图像进行二值化。
    // 亮度是该像素与以其为中心的 s × s 窗口像素平均值之间的差异。
    // 窗口大小将自动校准。
    rasterImage.binarizeBradley(5);
    rasterImage.save(dir + "sample.BinarizeBradley5.png");
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


调整图像的亮度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |


**Example: The following example performs brightness correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


**Example: The following example performs contrast correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 设置对比度值。对比度的可接受范围为 [-100f, 100f]。
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

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
| gammaBlue | float | 蓝色通道系数的 Gamma |


**Example: The following example performs gamma-correction of a raster cached image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 为红色、绿色和蓝色通道设置各自的 Gamma 系数。
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
| 伽马 | float | 红色、绿色和蓝色通道系数的 Gamma |


**Example: The following example performs gamma-correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // 为红色、绿色和蓝色通道设置 Gamma 系数。
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
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
| 密码 | java.lang.String | 用于生成数字签名数据的密码（最少 4 个字符） |


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
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


使用提供的密码和阈值快速检查图像是否已进行数字签名。

--------------------

此方法通过利用 `GetSignPercentage` 提供最快的检测。一旦提取的数据达到指定阈值，后续旨在提高检测准确性的提取步骤将被跳过。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 用于检查签名的密码。 |
| percentageThreshold | int | 阈值（百分比）[0-100] 用于确定图像是否被视为已签名。如果未指定，将使用默认阈值（`75`）。 |

**Returns:**
boolean - 如果图像已签名则为 true，否则为 false。
