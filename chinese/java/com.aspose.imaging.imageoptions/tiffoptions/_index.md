---
title: "TiffOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "tiff 文件格式选项。"
type: docs
weight: 48
url: /zh/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

tiff 文件格式选项。请注意，宽度和高度标签将在图像创建时被宽度和高度参数覆盖，因此无需直接指定它们。另请注意，许多选项返回默认值，但这并不意味着该选项已显式设置为标签值。要验证标签是否存在，请使用 Tags 属性或相应的 IsTagPresent 方法。

` 警告！在保存期间切勿修改 tiff 选项，因为这可能导致副作用和难以发现的错误。以下行被特意保留为注释，因为它导致数据起始位置判断错误。传入的选项未包含 spp（虽然在这种情况下选项不正确，但仍会导致错误），下一行导致添加了 +spp 标签和 +bpp 标签，并且在数据完全写入后写入选项时，它们会覆盖未压缩编解码器的数据起始位置！！！请参阅 TiffUncompressedCodec.Encode。this.Options.SamplesPerPixel = 3; `
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | 初始化 `TiffOptions` 类的新实例。 |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | 初始化 `TiffOptions` 类的新实例。 |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | 初始化 `TiffOptions` 类的新实例。 |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 初始化 `TiffOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 获取有效标签的计数。 |
| [getTagCount()](#getTagCount--) | 获取标签计数。 |
| [getFileStandard()](#getFileStandard--) | 获取或设置 TIFF 文件标准。 |
| [setFileStandard(int value)](#setFileStandard-int-) | 获取或设置 TIFF 文件标准。 |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | 获取或设置默认内存分配限制。 |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | 获取或设置默认内存分配限制。 |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | 获取或设置指示组件是否必须预乘的值。 |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 获取或设置指示组件是否必须预乘的值。 |
| [isValid()](#isValid--) | 获取指示 `TiffOptions` 是否已正确配置的值。 |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | 获取或设置 YCbCr 颜色空间的子采样因子。 |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | 获取或设置 YCbCr 颜色空间的子采样因子。 |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | 获取或设置 YCbCrCoefficients。 |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置 YCbCrCoefficients。 |
| [isTiled()](#isTiled--) | 获取指示图像是否为平铺的值。 |
| [getArtist()](#getArtist--) | 获取或设置艺术家。 |
| [setArtist(String value)](#setArtist-java.lang.String-) | 获取或设置艺术家。 |
| [isTagPresent(int tag)](#isTagPresent-int-) | 确定标签是否存在于选项中。 |
| [getByteOrder()](#getByteOrder--) | 获取或设置指示 tiff 字节顺序的值。 |
| [setByteOrder(int value)](#setByteOrder-int-) | 获取或设置指示 tiff 字节顺序的值。 |
| [getIccProfile()](#getIccProfile--) | 获取 icc 配置文件流。 |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | 设置 icc 配置文件流。 |
| [isDisableIccExport()](#isDisableIccExport--) | 获取指示是否禁用 ICC 配置文件导出的值（ICC 配置文件会预先应用于源像素）。 |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | 设置指示是否禁用 ICC 配置文件导出的值（ICC 配置文件会预先应用于源像素）。 |
| [getBitsPerSample()](#getBitsPerSample--) | 获取每个样本的位数。 |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | 设置每个样本的位数。 |
| [getExtraSamples()](#getExtraSamples--) | 获取额外样本的值。 |
| [getCompression()](#getCompression--) | 获取压缩。 |
| [setCompression(int value)](#setCompression-int-) | 设置压缩。 |
| [getCompressedQuality()](#getCompressedQuality--) | 获取压缩图像质量。 |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | 设置压缩图像质量。 |
| [getCopyright()](#getCopyright--) | 获取版权信息。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 设置版权信息。 |
| [getColorMap()](#getColorMap--) | 获取或设置颜色映射。 |
| [setColorMap(int[] value)](#setColorMap-int---) | 获取或设置颜色映射。 |
| [getPalette()](#getPalette--) | 获取或设置颜色调色板。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | 获取或设置颜色调色板。 |
| [getDateTime()](#getDateTime--) | 获取或设置日期和时间。 |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | 获取或设置日期和时间。 |
| [getDocumentName()](#getDocumentName--) | 获取或设置文档名称。 |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | 获取或设置文档名称。 |
| [getAlphaStorage()](#getAlphaStorage--) | 获取或设置 Alpha 存储选项。 |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | 获取或设置 Alpha 存储选项。 |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | 获取一个值，指示是否存在额外样本。 |
| [getFillOrder()](#getFillOrder--) | 获取或设置字节位填充顺序。 |
| [setFillOrder(int value)](#setFillOrder-int-) | 获取或设置字节位填充顺序。 |
| [getHalfToneHints()](#getHalfToneHints--) | 获取或设置半色调提示。 |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | 获取或设置半色调提示。 |
| [getImageDescription()](#getImageDescription--) | 获取或设置图像描述。 |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | 获取或设置图像描述。 |
| [getInkNames()](#getInkNames--) | 获取或设置墨水名称。 |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | 获取或设置墨水名称。 |
| [getScannerManufacturer()](#getScannerManufacturer--) | 获取或设置扫描仪制造商。 |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | 获取或设置扫描仪制造商。 |
| [getMaxSampleValue()](#getMaxSampleValue--) | 获取或设置最大样本值。 |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | 获取或设置最大样本值。 |
| [getMinSampleValue()](#getMinSampleValue--) | 获取或设置最小样本值。 |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | 获取或设置最小样本值。 |
| [getScannerModel()](#getScannerModel--) | 获取或设置扫描仪型号。 |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | 获取或设置扫描仪型号。 |
| [getOrientation()](#getOrientation--) | 获取或设置方向。 |
| [setOrientation(int value)](#setOrientation-int-) | 获取或设置方向。 |
| [getPageName()](#getPageName--) | 获取或设置页面名称。 |
| [setPageName(String value)](#setPageName-java.lang.String-) | 获取或设置页面名称。 |
| [getPageNumber()](#getPageNumber--) | 获取或设置页码标签。 |
| [setPageNumber(int[] value)](#setPageNumber-int---) | 获取或设置页码标签。 |
| [getPhotometric()](#getPhotometric--) | 获取或设置光度信息。 |
| [setPhotometric(int value)](#setPhotometric-int-) | 获取或设置光度信息。 |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 获取或设置平面配置。 |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | 获取或设置平面配置。 |
| [getResolutionUnit()](#getResolutionUnit--) | 获取或设置分辨率单位。 |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 获取或设置分辨率单位。 |
| [getRowsPerStrip()](#getRowsPerStrip--) | 获取或设置每条带的行数。 |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | 获取或设置每条带的行数。 |
| [getTileWidth()](#getTileWidth--) | 获取或设置瓦片宽度。 |
| [setTileWidth(long value)](#setTileWidth-long-) | 获取或设置瓦片宽度。 |
| [getTileLength()](#getTileLength--) | 获取或设置瓦片长度。 |
| [setTileLength(long value)](#setTileLength-long-) | 获取或设置瓦片长度。 |
| [getSampleFormat()](#getSampleFormat--) | 获取或设置样本格式。 |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | 获取或设置样本格式。 |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | 获取每像素的样本数。 |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | 获取或设置最大样本值。 |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | 获取或设置最大样本值。 |
| [getSminSampleValue()](#getSminSampleValue--) | 获取或设置最小样本值。 |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | 获取或设置最小样本值。 |
| [getSoftwareType()](#getSoftwareType--) | 获取或设置软件类型。 |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | 获取或设置软件类型。 |
| [getStripByteCounts()](#getStripByteCounts--) | 获取或设置条带字节计数。 |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | 获取或设置条带字节计数。 |
| [getStripOffsets()](#getStripOffsets--) | 获取或设置条带偏移量。 |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | 获取或设置条带偏移量。 |
| [getTileByteCounts()](#getTileByteCounts--) | 获取或设置瓦片字节计数。 |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | 获取或设置瓦片字节计数。 |
| [getTileOffsets()](#getTileOffsets--) | 获取或设置瓦片偏移量。 |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | 获取或设置瓦片偏移量。 |
| [getSubFileType()](#getSubFileType--) | 获取或设置此子文件中包含的数据类型的一般指示。 |
| [setSubFileType(long value)](#setSubFileType-long-) | 获取或设置此子文件中包含的数据类型的一般指示。 |
| [getTargetPrinter()](#getTargetPrinter--) | 获取或设置目标打印机。 |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | 获取或设置目标打印机。 |
| [getThreshholding()](#getThreshholding--) | 获取或设置阈值处理。 |
| [setThreshholding(int value)](#setThreshholding-int-) | 获取或设置阈值处理。 |
| [getTotalPages()](#getTotalPages--) | 获取总页数。 |
| [getXposition()](#getXposition--) | 获取或设置 X 位置。 |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 X 位置。 |
| [getResolutionSettings()](#getResolutionSettings--) | 获取或设置分辨率设置。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | 获取或设置分辨率设置。 |
| [getXresolution()](#getXresolution--) | 获取或设置 X 分辨率。 |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 X 分辨率。 |
| [getYposition()](#getYposition--) | 获取或设置 Y 位置。 |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 Y 位置。 |
| [getYresolution()](#getYresolution--) | 获取或设置 Y 分辨率。 |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 Y 分辨率。 |
| [getFaxT4Options()](#getFaxT4Options--) | 获取或设置传真 T4 选项。 |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | 获取或设置传真 T4 选项。 |
| [getPredictor()](#getPredictor--) | 获取或设置 LZW 压缩的预测器。 |
| [setPredictor(int value)](#setPredictor-int-) | 获取或设置 LZW 压缩的预测器。 |
| [getImageLength()](#getImageLength--) | 获取或设置图像长度。 |
| [setImageLength(long value)](#setImageLength-long-) | 获取或设置图像长度。 |
| [getImageWidth()](#getImageWidth--) | 获取或设置图像宽度。 |
| [setImageWidth(long value)](#setImageWidth-long-) | 获取或设置图像宽度。 |
| [getExifIfd()](#getExifIfd--) | 获取或设置指向 EXIF IFD 的指针。 |
| [getTags()](#getTags--) | 获取或设置标签。 |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 获取或设置标签。 |
| [getValidTagCount()](#getValidTagCount--) | 获取有效标签计数。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取每像素位数。 |
| [getXPTitle()](#getXPTitle--) | 获取 Windows Explorer 使用的图像信息。 |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | 设置 Windows Explorer 使用的图像信息。 |
| [getXPComment()](#getXPComment--) | 获取 Windows Explorer 使用的图像注释。 |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | 设置 Windows Explorer 使用的图像注释。 |
| [getXPAuthor()](#getXPAuthor--) | 获取 Windows Explorer 使用的图像作者。 |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | 设置 Windows Explorer 使用的图像作者。 |
| [getXPKeywords()](#getXPKeywords--) | 获取 Windows Explorer 使用的图像主题。 |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | 设置 Windows Explorer 使用的图像主题。 |
| [getXPSubject()](#getXPSubject--) | 获取 Windows Explorer 使用的图像信息。 |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | 设置 Windows Explorer 使用的图像信息。 |
| [getExifData()](#getExifData--) | 获取 Exif 数据。 |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | 设置 Exif 数据。 |
| [removeTag(int tag)](#removeTag-int-) | 移除标签。 |
| [removeTags(int[] tags)](#removeTags-int...-) | 移除标签。 |
| [validate()](#validate--) | 验证选项是否具有有效的标签组合 |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 添加标签。 |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | 添加新标签。 |
| [getTagByType(int tagKey)](#getTagByType-int-) | 按类型获取标签实例。 |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
此示例演示了在导出场景中使用 SaveOptions 命名空间中的不同类。将类型为 Gif 的图像加载到 Image 实例中，然后导出为多种格式。
``` java
String dir = "c:\\temp\\";

//在 Image 类的实例中加载已有的图像（类型为 Gif）
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //使用默认选项导出为 BMP 文件格式
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //使用默认选项导出为 JPEG 文件格式
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //使用默认选项导出为 PNG 文件格式
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //使用默认选项导出为 TIFF 文件格式
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。这些页面将在输出的 TIFF 中作为帧呈现。
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
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

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


初始化 `TiffOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expectedFormat | int | 预期的 TIFF 文件格式。 |
| byteOrder | int | TIFF 文件格式的字节顺序。 |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


初始化 `TiffOptions` 类的新实例。默认使用小端字节序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expectedFormat | int | 预期的 TIFF 文件格式。 |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


初始化 `TiffOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | 要复制的选项。 |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


初始化 `TiffOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 用于初始化选项的标签。 |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


获取有效标签的计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 要验证的标签。 |

**Returns:**
int - 有效标签计数。
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


获取标签计数。

**Returns:**
int - 标签计数。
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


获取或设置 TIFF 文件标准。

**Returns:**
int - TIFF 文件标准。
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


获取或设置 TIFF 文件标准。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | TIFF 文件标准。 |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


获取或设置默认内存分配限制。

**Returns:**
int - 默认内存分配限制。
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


获取或设置默认内存分配限制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 默认内存分配限制。 |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


获取或设置指示组件是否必须预乘的值。

**Returns:**
boolean - 如果组件必须预乘则为 `true`；否则为 `false`。
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


获取或设置指示组件是否必须预乘的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 表示组件必须预乘；否则为 `false`。 |

### isValid() {#isValid--}
```
public boolean isValid()
```


获取一个值，指示 `TiffOptions` 是否已正确配置。使用 Validate 方法来查找失败原因。

**Returns:**
boolean - 如果 TiffOptions 已正确配置则为 `true`；否则为 `false`。
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


获取或设置 YCbCr 颜色空间的子采样因子。

**Returns:**
int[] - YCbCr 颜色空间的子采样因子。
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


获取或设置 YCbCr 颜色空间的子采样因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | YCbCr 颜色空间的子采样因子。 |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// 设置大端字节序（Motorola）
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// 设置 LZW 压缩。
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// 允许减小连续色调图像的大小。
// 当前此字段仅在 LZW 编码下使用，因为 LZW 可能是唯一的 TIFF 编码方案。
// 它从预测步骤中显著受益。
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// 设置 RGB 颜色模型。
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// 对于 YCbCr，您可以使用以下选项之一：
// YCbCrSubSampling 字段   JPEG 采样因子
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(默认值)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// 所有颜色分量将存储在单个平面中。
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 创建一个 100x100 像素的 TIFF 帧。
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // 用蓝黄渐变填充整个图像。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


获取或设置 YCbCrCoefficients。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - YCbCr 系数。
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


获取或设置 YCbCrCoefficients。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | YCbCr 系数。 |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


获取指示图像是否为平铺的值。

**Returns:**
boolean - 如果图像为平铺则为 `true`；否则为 `false`。
### getArtist() {#getArtist--}
```
public String getArtist()
```


获取或设置艺术家。

**Returns:**
java.lang.String - 艺术家。
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


获取或设置艺术家。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 艺术家。 |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


确定标签是否存在于选项中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标签 | int | 要检查的标签 ID。 |

**Returns:**
boolean - 如果标签存在则为 `true`；否则为 `false`。
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


获取或设置指示 tiff 字节顺序的值。

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


获取或设置指示 tiff 字节顺序的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// 设置大端字节序（Motorola）
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// 设置 LZW 压缩。
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// 允许减小连续色调图像的大小。
// 当前此字段仅在 LZW 编码下使用，因为 LZW 可能是唯一的 TIFF 编码方案。
// 它从预测步骤中显著受益。
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// 设置 RGB 颜色模型。
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// 对于 YCbCr，您可以使用以下选项之一：
// YCbCrSubSampling 字段   JPEG 采样因子
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(默认值)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// 所有颜色分量将存储在单个平面中。
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 创建一个 100x100 像素的 TIFF 帧。
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // 用蓝黄渐变填充整个图像。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


获取 icc 配置文件流。

**Returns:**
byte[] - ICC 配置文件。
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


设置 icc 配置文件流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] | 此 ICC 配置文件。 |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


获取指示是否禁用 ICC 配置文件导出的值（ICC 配置文件会预先应用于源像素）。

**Returns:**
boolean - 表示是否禁用 ICC 配置文件导出的值（ICC 配置文件会预先应用于源像素）。
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


设置指示是否禁用 ICC 配置文件导出的值（ICC 配置文件会预先应用于源像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 表示是否禁用 ICC 配置文件导出的值（ICC 配置文件会预先应用于源像素）。 |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


获取每个样本的位数。

**Returns:**
int[] - 每个样本的位数值。

设置此值时请记住，它还会将 SamplesPerPixel 的值设为数组长度。这两个属性紧密耦合，因而只能一起设置。
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


设置每个样本的位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 每个样本的位数值。 |

设置此值时请记住，它还会将 SamplesPerPixel 的值设为数组长度。这两个属性紧密耦合，因而只能一起设置。 |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 创建一个永久的（而非临时的）文件源。
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // 图像左上角到右下角的线性渐变。
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // 使用线性渐变画刷填充活动帧。
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // 灰度选项
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // 创建活动帧的灰度副本。
    // 像素数据被保留，但会转换为所需的格式。
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // 将新创建的帧添加到 TIFF 图像中。
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


获取额外样本的值。

值：额外样本的值。

**Returns:**
int[] - 额外样本的值。
### getCompression() {#getCompression--}
```
public int getCompression()
```


获取压缩。

**Returns:**
int - 压缩方式。
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


设置压缩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 压缩方式。 |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// 第一帧的选项
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// 设置大端字节序（Motorola）
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// 设置 LZW 压缩。
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// 设置 RGB 颜色模型。
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// 所有颜色分量将存储在单个平面中。
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 创建第一帧 100x100 像素的 TIFF。
// 请注意，如果帧已包含在 TiffImage 中，则无需显式释放帧。
// 当容器被释放时，所有帧将自动被释放。
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// 用蓝黄渐变填充第一帧。
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// 第一帧的选项
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 为黑白图像设置每像素 1 位。
createOptions2.setBitsPerSample(new int[]{1});

// 设置小端字节序（Intel）
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// 设置 CCITT Group 3 传真压缩。
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// 设置黑白颜色模型，其中 0 为黑色，1 为白色。
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// 创建第二帧 200x200 像素的 TIFF。
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// 用蓝黄渐变填充第二帧。
// 由于帧的相应设置，它将自动转换为黑白格式。
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// 创建 TIFF 图像。
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


获取压缩图像质量。与 JPEG 压缩一起使用。

**Returns:**
int - 压缩图像质量。
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


设置压缩图像质量。与 JPEG 压缩一起使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 压缩图像质量。 |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // 设置 RGB 颜色模型。
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // 设置 JPEG 压缩。
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // 为每个颜色分量设置 8 位。
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


获取版权信息。

**Returns:**
java.lang.String - 版权信息。
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


设置版权信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 版权。 |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


获取或设置颜色映射。

**Returns:**
int[] - 颜色映射。
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


获取或设置颜色映射。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 颜色映射。 |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


获取或设置颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


获取或设置颜色调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


获取或设置日期和时间。

**Returns:**
java.lang.String - 日期和时间。
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


获取或设置日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 日期和时间。 |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


获取或设置文档名称。

**Returns:**
java.lang.String - 文档名称。
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


获取或设置文档名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 文档名称。 |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


获取或设置 alpha 存储选项。当定义了超过 3 个 `SamplesPerPixel` 时，使用除 `TiffAlphaStorage.Unspecified` 之外的选项。

**Returns:**
int - alpha 存储选项。
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


获取或设置 alpha 存储选项。当定义了超过 3 个 `SamplesPerPixel` 时，使用除 `TiffAlphaStorage.Unspecified` 之外的选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | alpha 存储选项。 |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


获取一个值，指示是否存在额外样本。

**Returns:**
boolean - 如果存在额外样本则为 `true`；否则为 `false`。
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


获取或设置字节位填充顺序。

**Returns:**
int - 字节位填充顺序。
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


获取或设置字节位填充顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 字节位填充顺序。 |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


获取或设置半色调提示。

**Returns:**
int[] - 半色调提示。
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


获取或设置半色调提示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 半色调提示。 |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


获取或设置图像描述。

**Returns:**
java.lang.String - 图像描述。
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


获取或设置图像描述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像描述。 |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


获取或设置墨水名称。

**Returns:**
java.lang.String - 墨水名称。
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


获取或设置墨水名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 墨水名称。 |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


获取或设置扫描仪制造商。

**Returns:**
java.lang.String - 扫描仪制造商。
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


获取或设置扫描仪制造商。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 扫描仪制造商。 |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


获取或设置最大样本值。

**Returns:**
int[] - 最大样本值。
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


获取或设置最大样本值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 最大样本值。 |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


获取或设置最小样本值。

**Returns:**
int[] - 最小样本值。
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


获取或设置最小样本值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 最小样本值。 |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


获取或设置扫描仪型号。

**Returns:**
java.lang.String - 扫描仪型号。
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


获取或设置扫描仪型号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 扫描仪型号。 |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


获取或设置方向。

**Returns:**
int - 方向 [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations)。
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


获取或设置方向。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 方向 [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations)。 |

### getPageName() {#getPageName--}
```
public String getPageName()
```


获取或设置页面名称。

**Returns:**
java.lang.String - 页面名称。
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


获取或设置页面名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 页面名称。 |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


获取或设置页码标签。

**Returns:**
int[] - 页面编号标签。
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


获取或设置页码标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 页面编号标签。 |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


获取或设置光度信息。

**Returns:**
int - 光度。
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


获取或设置光度信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 光度。 |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 创建一个永久的（而非临时的）文件源。
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // 图像左上角到右下角的线性渐变。
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // 使用线性渐变画刷填充活动帧。
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // 灰度选项
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // 创建活动帧的灰度副本。
    // 像素数据被保留，但会转换为所需的格式。
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // 将新创建的帧添加到 TIFF 图像中。
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


获取或设置平面配置。

**Returns:**
int - 平面配置。
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


获取或设置平面配置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 平面配置。 |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// 设置大端字节序（Motorola）
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// 设置 LZW 压缩。
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// 设置 RGB 颜色模型。
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// 所有颜色分量将存储在单个平面中。
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 创建一个 100x100 像素的 TIFF 帧。
// 请注意，如果帧已包含在 TiffImage 中，则无需显式释放该帧。
// 当容器被释放时，所有帧将自动被释放。
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// 用蓝黄渐变填充整个帧。
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// 创建 TIFF 图像。
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


获取或设置分辨率单位。

**Returns:**
int - 分辨率单位。
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


获取或设置分辨率单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 分辨率单位。 |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


获取或设置每条带的行数。

**Returns:**
long - 每条带的行数。
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


获取或设置每条带的行数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 每条带的行数。 |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


获取或设置瓦片宽度。

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


获取或设置瓦片宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


获取或设置瓦片长度。

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


获取或设置瓦片长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


获取或设置样本格式。

**Returns:**
int[] - 采样格式。
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


获取或设置样本格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 采样格式。 |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


获取每像素的采样数。要更改此属性值，请使用 `BitsPerSample` 属性设置器。

**Returns:**
int - 每像素的采样数。
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


获取或设置最大采样值。该值具有最匹配采样数据的字段类型（Byte、Short 或 Long 类型）。

**Returns:**
long[] - 最大采样值。
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


获取或设置最大采样值。该值具有最匹配采样数据的字段类型（Byte、Short 或 Long 类型）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long[] | 最大样本值。 |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


获取或设置最小采样值。该值具有最匹配采样数据的字段类型（Byte、Short 或 Long 类型）。

**Returns:**
long[] - 最小采样值。
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


获取或设置最小采样值。该值具有最匹配采样数据的字段类型（Byte、Short 或 Long 类型）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long[] | 最小样本值。 |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


获取或设置软件类型。

**Returns:**
java.lang.String - 软件类型。
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


获取或设置软件类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 软件类型。 |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


获取或设置条带字节计数。

**Returns:**
long[] - 条带字节计数。
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


获取或设置条带字节计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long[] | 条带字节计数。 |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


获取或设置条带偏移量。

**Returns:**
long[] - 条带偏移量。
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


获取或设置条带偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long[] | 条带偏移量。 |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


获取或设置瓦片字节计数。

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


获取或设置瓦片字节计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


获取或设置瓦片偏移量。

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


获取或设置瓦片偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


获取或设置此子文件中包含的数据类型的一般指示。

**Returns:**
long - 对此子文件中包含的数据类型的一般指示。
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


获取或设置此子文件中包含的数据类型的一般指示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 对该子文件中包含的数据类型的一般指示。 |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


获取或设置目标打印机。

**Returns:**
java.lang.String - 目标打印机。
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


获取或设置目标打印机。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 目标打印机。 |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


获取或设置阈值处理。

**Returns:**
int - 阈值处理。
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


获取或设置阈值处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 阈值处理。 |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


获取总页数。

**Returns:**
int - 总页数。
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


获取或设置 X 位置。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


获取或设置 X 位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | X 位置。 |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


获取或设置分辨率设置。

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


获取或设置分辨率设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


获取或设置 X 分辨率。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


获取或设置 X 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | X 分辨率。 |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


获取或设置 Y 位置。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


获取或设置 Y 位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Y 位置。 |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


获取或设置 Y 分辨率。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


获取或设置 Y 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Y 分辨率。 |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


获取或设置传真 T4 选项。

**Returns:**
long - 传真 T4 选项。
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


获取或设置传真 T4 选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 传真 T4 选项。 |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


获取或设置 LZW 压缩的预测器。

**Returns:**
int - 预测器类型。
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


获取或设置 LZW 压缩的预测器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 预测器类型。 |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// 设置大端字节序（Motorola）
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// 设置 LZW 压缩。
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// 允许减小连续色调图像的大小。
// 当前此字段仅在 LZW 编码下使用，因为 LZW 可能是唯一的 TIFF 编码方案。
// 它从预测步骤中显著受益。
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// 设置 RGB 颜色模型。
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// 对于 YCbCr，您可以使用以下选项之一：
// YCbCrSubSampling 字段   JPEG 采样因子
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(默认值)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// 所有颜色分量将存储在单个平面中。
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 创建一个 100x100 像素的 TIFF 帧。
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // 用蓝黄渐变填充整个图像。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


获取或设置图像长度。

**Returns:**
long - 图像长度。
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


获取或设置图像长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 图像长度。 |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


获取或设置图像宽度。

**Returns:**
long - 图像宽度。
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


获取或设置图像宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 图像宽度。 |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


获取或设置指向 EXIF IFD 的指针。

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


获取或设置标签。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - 标签。
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


获取或设置标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 标签。 |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


获取有效标签的数量。这不是标签的总数，而是可能被保留的标签数量。

**Returns:**
int - 有效标签的数量。
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取每像素位数。

**Returns:**
int - 每像素的位数。
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


获取 Windows Explorer 使用的图像信息。

值：关于图像的信息，由 Windows Explorer 使用。如果存在 `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) 标签，则 Windows Explorer 会忽略 `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String))。

**Returns:**
java.lang.String - 关于图像的信息，由 Windows Explorer 使用。
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


设置 Windows Explorer 使用的图像信息。

值：关于图像的信息，由 Windows Explorer 使用。如果存在 `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) 标签，则 Windows Explorer 会忽略 `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 关于图像的信息，由 Windows Explorer 使用。 |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


获取 Windows Explorer 使用的图像注释。

值：图像的注释，由 Windows Explorer 使用。

**Returns:**
java.lang.String - 图像的注释，由 Windows Explorer 使用。
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


设置 Windows Explorer 使用的图像注释。

值：图像的注释，由 Windows Explorer 使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像的注释，由 Windows Explorer 使用。 |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


获取 Windows Explorer 使用的图像作者。

值：图像作者，由 Windows Explorer 使用。如果存在 `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) 标签，则 Windows Explorer 会忽略 `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String))。

**Returns:**
java.lang.String - 图像作者，由 Windows Explorer 使用。
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


设置 Windows Explorer 使用的图像作者。

值：图像作者，由 Windows Explorer 使用。如果存在 `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) 标签，则 Windows Explorer 会忽略 `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像作者，由 Windows Explorer 使用。 |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


获取 Windows Explorer 使用的图像主题。

值：图像主题，由 Windows Explorer 使用。

**Returns:**
java.lang.String - 图像主题，由 Windows Explorer 使用。
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


设置 Windows Explorer 使用的图像主题。

值：图像主题，由 Windows Explorer 使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像主题，由 Windows Explorer 使用。 |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


获取 Windows Explorer 使用的图像信息。

值：关于图像的信息，由 Windows Explorer 使用。

**Returns:**
java.lang.String - 关于图像的信息，由 Windows Explorer 使用。
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


设置 Windows Explorer 使用的图像信息。

值：关于图像的信息，由 Windows Explorer 使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 关于图像的信息，由 Windows Explorer 使用。 |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


获取 Exif 数据。

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


设置 Exif 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif 数据。 |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


移除标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标签 | int | 要移除的标签。 |

**Returns:**
boolean - 如果成功移除则为 true
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


移除标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标签 | int[] | 要移除的标签集合。 |

**Returns:**
boolean - `` 如果标签集合大小已更改。
### validate() {#validate--}
```
public void validate()
```


验证选项是否具有有效的标签组合

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


添加标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 要添加的标签。 |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


添加新标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 要添加的标签。 |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


按类型获取标签实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagKey | int | 标签键。 |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
