---
title: "LoadOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示加载选项。"
type: docs
weight: 70
url: /zh/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

表示加载选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | 获取数据恢复模式。 |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | 设置数据恢复模式。 |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | 获取 `Image` 背景 `Color`。 |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | 设置 `Image` 背景 `Color`。 |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | 获取一个值，指示是否应应用 ICC 配置文件转换。 |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | 设置一个值，指示是否应应用 ICC 配置文件转换。 |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | 添加自定义字体源以提供特定于图像的字体。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | 获取一个值，指示是否启用 [concurrent image processing]。 |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | 设置一个值，指示是否启用 [concurrent image processing]。 |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | 获取进度事件处理程序。 |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | 设置进度事件处理程序。 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


获取数据恢复模式。

**Returns:**
int - 数据恢复模式。
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


设置数据恢复模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 数据恢复模式。 |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


获取 `Image` 背景 `Color`。

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

通常在由于数据损坏导致像素值无法恢复时设置背景颜色。
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


设置 `Image` 背景 `Color`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | 背景颜色。 |

通常在由于数据损坏导致像素值无法恢复时设置背景颜色。 |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


获取一个值，指示是否应应用 ICC 配置文件转换。

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


设置一个值，指示是否应应用 ICC 配置文件转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


添加自定义字体源以提供特定于图像的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | 自定义字体源提供程序函数。 |
| args | java.lang.Object[] | 参数。 |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示（单位：兆字节）。非正值表示内部缓冲区没有内存限制

**Returns:**
int - 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示（单位：兆字节）。非正值表示内部缓冲区没有内存限制

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。 |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
以下示例展示了在加载 JPEG 图像时如何设置内存限制。内存限制是所有内部缓冲区允许的最大大小（以兆字节为单位）。
``` java
String workDir = "c:\\temp\\";
// 为目标加载的图像设置 50 兆字节的内存限制
com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
loadOptions.setBufferSizeHint(50);
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(workDir + "inputFile.jpg", loadOptions);
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Baseline);
    jpegOptions.setQuality(100);
    image.save(workDir + "outputFile_Baseline.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);
    image.save(workDir + "outputFile_Progressive.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Lossless);
    jpegOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);
    jpegOptions.setBitsPerChannel((byte) 4);
    image.save(workDir + "outputFile_Lossless.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.JpegLs);
    jpegOptions.setJpegLsInterleaveMode(com.aspose.imaging.fileformats.jpeg.JpegLsInterleaveMode.None);
    jpegOptions.setJpegLsAllowedLossyError(3);
    jpegOptions.setJpegLsPreset(null);
    image.save(workDir + "outputFile_JpegLs.jpg", jpegOptions);
} finally {
    image.close();
}
```

### getConcurrentImageProcessing() {#getConcurrentImageProcessing--}
```
public final boolean getConcurrentImageProcessing()
```


获取一个值，指示是否启用 [concurrent image processing]。

值：如果 [concurrent image processing] 为 `true`；否则为 `false`。

**Returns:**
布尔 - 一个指示是否启用 [concurrent image processing] 的值。
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


设置一个值，指示是否启用 [concurrent image processing]。

值：如果 [concurrent image processing] 为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 一个指示是否进行[concurrent image processing]的值。 |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


获取进度事件处理程序。

值：进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


设置进度事件处理程序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | 进度事件处理程序。 |

