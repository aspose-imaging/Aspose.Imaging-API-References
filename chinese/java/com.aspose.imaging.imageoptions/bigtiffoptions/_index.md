---
title: "BigTiffOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "BigTIFF 栅格图像格式创建的 API 专为满足使用扫描仪的大规模成像数据的应用程序的独特需求而设计。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

用于创建 BigTIFF 栅格图像格式的 API 专门设计以满足使用扫描仪的大规模成像数据的应用程序的独特需求。该 API 促进了 BigTIFF 格式的无缝生成，该格式将多个 TIFF 图像合并为单个完整的图像。它确保对大量图像数据的高效处理，为开发者提供了一个强大的工具，用于创建和操作高分辨率的多图像格式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | 初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。 |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | 初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。 |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。 |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | 初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆此实例。 |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。默认使用小端字节序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expectedFormat | int | 预期的 Tiff 文件格式。 |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | 选项来源。 |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 用于选项初始化的标签。 |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


初始化 [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expectedFormat | int | 预期的 Tiff 文件格式。 |
| byteOrder | int | 要使用的 tiff 文件格式字节序。 |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


克隆此实例。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
