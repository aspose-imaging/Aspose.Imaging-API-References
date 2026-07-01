---
title: "ImageOptionsBase"
second_title: "Aspose.Imaging for Java API 参考"
description: "Image 基础选项。"
type: docs
weight: 62
url: /zh/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Image 基础选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | 获取一个值，以指示在导出时是否保留原始图像元数据。 |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | 一个值，以指示在导出时是否保留原始图像元数据。 |
| [getXmpData()](#getXmpData--) | 获取 XMP 元数据容器。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | 设置 XMP 元数据容器。 |
| [getExifData()](#getExifData--) | 获取 Exif 数据。 |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | 设置 Exif 数据。 |
| [getSource()](#getSource--) | 获取创建图像的来源。 |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | 获取或设置创建图像的来源。 |
| [getPalette()](#getPalette--) | 获取颜色调色板。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | 设置颜色调色板。 |
| [getResolutionSettings()](#getResolutionSettings--) | 获取分辨率设置。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | 设置分辨率设置。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 获取矢量光栅化选项。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | 设置矢量光栅化选项。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | 多页选项 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | 多页选项 |
| [getFullFrame()](#getFullFrame--) | 获取一个值，以指示是否为 [full frame]。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 设置一个值，以指示是否为 [full frame]。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取进度事件处理程序。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | 设置进度事件处理程序。 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | 尝试设置一个 `metadata` 实例，如果此 [Image](../../com.aspose.imaging/image) 实例支持并实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例。 |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


获取一个值，以指示在导出时是否保留原始图像元数据。

**Returns:**
布尔型 - 一个值，以指示在导出时是否保留原始图像元数据。
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


一个值，以指示在导出时是否保留原始图像元数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 一个值，以指示在导出时是否保留原始图像元数据。 |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


获取 XMP 元数据容器。

值：XMP 数据容器。

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


设置 XMP 元数据容器。

值：XMP 数据容器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | XMP 元数据容器。 |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


获取 Exif 数据。

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


设置 Exif 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif 数据。 |

### getSource() {#getSource--}
```
public Source getSource()
```


获取创建图像的来源。

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


获取或设置创建图像的来源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | 创建图像的来源。 |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


获取颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


设置颜色调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// 创建一个 100 x 100 像素的 BMP 图像。
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // 图像左上角到右下角的线性渐变。
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // 使用线性渐变画笔填充整个图像。
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // 获取最接近的 8 位颜色调色板，以覆盖尽可能多的像素，从而得到调色板图像
    // 几乎在视觉上与非调色的图像没有区别。
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // 8 位调色板最多包含 256 种颜色。
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// 输出如下：
// 调色后的图像大小为 11078 字节。
// 非调色的图像大小为 40054 字节。
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


获取分辨率设置。

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


设置分辨率设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// 从文件加载 BMP 图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // 进行一些图像处理。

    // 使用其他选项来指定所需的图像参数。
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // 每个通道的位数为 8。
    // 使用调色板时，颜色索引存储在图像数据中，而不是存储颜色本身。
    saveOptions.setBitsPerChannel((byte) 8);

    // 设置渐进式压缩类型。
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // 设置图像质量。取值范围为 1 到 100。
    saveOptions.setQuality(100);

    // 将水平/垂直分辨率设置为每英寸 96 点。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // 如果源图像是彩色的，它将被转换为灰度图像。
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // 使用调色板来减小输出大小。
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


获取矢量光栅化选项。

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


设置矢量光栅化选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | 向量光栅化选项。 |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Returns:**
int - 为所有内部缓冲区定义的最大允许大小的缓冲区大小提示。
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 缓冲区大小提示，为所有内部缓冲区定义的最大允许大小。 |

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


多页选项

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


多页选项

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


获取一个值，以指示是否为 [full frame]。

值：如果是 [full frame] 则为 `true`；否则为 `false`。

**Returns:**
布尔值 - 表示是否为 [full frame] 的值。
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


设置一个值，以指示是否为 [full frame]。

值：如果是 [full frame] 则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示是否为 [full frame] 的值。 |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


获取进度事件处理程序。

值：进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


设置进度事件处理程序。

值：进度事件处理程序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | 进度事件处理程序。 |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// 示例：在加载/导出操作中使用单独的操作进度事件处理程序
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// STDOUT 日志可能如下所示：
//        加载事件 初始化 : 1/4
//        加载事件 预处理 : 2/4
//        加载事件 处理 : 3/4
//        加载事件 完成 : 4/4
//        导出事件 初始化 : 1/4
//        导出事件 预处理 : 2/4
//        导出事件 处理 : 3/4
//        导出事件 相对进度 : 1/1
//        加载事件 相对进度 : 1/1
//        导出事件 完成 : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


克隆此实例。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


尝试设置一个 `metadata` 实例，如果此 [Image](../../com.aspose.imaging/image) 实例支持并实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | 元数据。 |

**Returns:**
布尔值 - 如果 [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) 实例支持和/或实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例，则为 True；否则为 false。
