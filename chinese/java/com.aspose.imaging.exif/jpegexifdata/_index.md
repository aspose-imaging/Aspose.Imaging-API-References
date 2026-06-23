---
title: "JpegExifData"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于 jpeg 文件的 EXIF 数据容器。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

用于 jpeg 文件的 EXIF 数据容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | 初始化 `JpegExifData` 类的新实例。 |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 使用数组中的数据初始化 `JpegExifData` 类的新实例。 |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | 使用数组中的数据初始化 `JpegExifData` 类的新实例。 |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | 使用数组中的数据初始化 [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | 允许的最大 EXIF 段大小（字节）。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArtist()](#getArtist--) | 获取或设置艺术家。 |
| [setArtist(String value)](#setArtist-java.lang.String-) | 获取或设置艺术家。 |
| [getBitsPerSample()](#getBitsPerSample--) | 获取或设置每个样本的位数。 |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | 获取或设置每个样本的位数。 |
| [getCompression()](#getCompression--) | 获取或设置压缩方式。 |
| [setCompression(int value)](#setCompression-int-) | 获取或设置压缩方式。 |
| [getCopyright()](#getCopyright--) | 获取或设置版权信息。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 获取或设置版权信息。 |
| [getDateTime()](#getDateTime--) | 获取或设置日期时间。 |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | 获取或设置日期时间。 |
| [getImageDescription()](#getImageDescription--) | 获取或设置图像描述。 |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | 获取或设置图像描述。 |
| [getImageLength()](#getImageLength--) | 获取或设置图像长度。 |
| [setImageLength(long value)](#setImageLength-long-) | 获取或设置图像长度。 |
| [getImageWidth()](#getImageWidth--) | 获取或设置图像宽度。 |
| [setImageWidth(long value)](#setImageWidth-long-) | 获取或设置图像宽度。 |
| [getModel()](#getModel--) | 获取或设置型号。 |
| [setModel(String value)](#setModel-java.lang.String-) | 获取或设置型号。 |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | 获取或设置光度解释。 |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | 获取或设置光度解释。 |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 获取或设置平面配置。 |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | 获取或设置平面配置。 |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | 获取或设置图像三原色的色度。 |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置图像三原色的色度。 |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | 获取或设置参考黑白。 |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置参考黑白。 |
| [getResolutionUnit()](#getResolutionUnit--) | 获取或设置分辨率单位。 |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 获取或设置分辨率单位。 |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | 获取或设置每像素样本数。 |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | 获取或设置每像素样本数。 |
| [getSoftware()](#getSoftware--) | 获取或设置软件信息。 |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | 获取或设置软件信息。 |
| [getTransferFunction()](#getTransferFunction--) | 获取或设置传输函数。 |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | 获取或设置传输函数。 |
| [getXResolution()](#getXResolution--) | 获取或设置 X 分辨率。 |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 X 分辨率。 |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | 获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | 获取或设置色度分量相对于亮度分量的位置。 |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | 获取或设置色度分量相对于亮度分量的位置。 |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | 获取或设置色度分量相对于亮度分量的采样比例。 |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | 获取或设置色度分量相对于亮度分量的采样比例。 |
| [getYResolution()](#getYResolution--) | 获取或设置 Y 分辨率。 |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 Y 分辨率。 |
| [serializeExifData()](#serializeExifData--) | 序列化 EXIF 数据。 |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


初始化 `JpegExifData` 类的新实例。

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


使用数组中的数据初始化 `JpegExifData` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 包含公共和 GPS 标签的 EXIF 标签数组。 |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


使用数组中的数据初始化 `JpegExifData` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 公共标签。 |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | EXIF 标签。 |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | GPS 标签。 |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


使用数组中的数据初始化 [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | 包含公共和 GPS 标签的 EXIF 标签数组。 |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


允许的最大 EXIF 段大小（字节）。

### getArtist() {#getArtist--}
```
public String getArtist()
```


获取或设置艺术家。

值：艺术家。

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


获取或设置艺术家。

值：艺术家。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


获取或设置每个样本的位数。

值：每个样本的位数。

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


获取或设置每个样本的位数。

值：每个样本的位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


获取或设置压缩方式。

值：压缩。

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


获取或设置压缩方式。

值：压缩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


获取或设置版权信息。

值：版权信息。

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


获取或设置版权信息。

值：版权信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


获取或设置日期时间。

值：日期时间。

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


获取或设置日期时间。

值：日期时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


获取或设置图像描述。

值：图像描述。

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


获取或设置图像描述。

值：图像描述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


获取或设置图像长度。

值：图像长度。

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


获取或设置图像长度。

值：图像长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


获取或设置图像宽度。

值：图像宽度。

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


获取或设置图像宽度。

值：图像宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


获取或设置型号。

值：型号。

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


获取或设置型号。

值：型号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


获取或设置光度解释。

值：光度解释。

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


获取或设置光度解释。

值：光度解释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


获取或设置平面配置。

值：平面配置。

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


获取或设置平面配置。

值：平面配置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


获取或设置图像三原色的色度。

值：图像三原色的色度。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


获取或设置图像三原色的色度。

值：图像三原色的色度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


获取或设置参考黑白。

值：参考黑白。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


获取或设置参考黑白。

值：参考黑白。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


获取或设置分辨率单位。

值：分辨率单位。

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


获取或设置分辨率单位。

值：分辨率单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


获取或设置每像素样本数。

值：每像素的样本数。

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


获取或设置每像素样本数。

值：每像素的样本数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


获取或设置软件信息。

值：软件。

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


获取或设置软件信息。

值：软件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


获取或设置传输函数。

值：传输函数。

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


获取或设置传输函数。

值：传输函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


获取或设置 X 分辨率。

值：x 分辨率。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


获取或设置 X 分辨率。

值：x 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。

值：从 RGB 到 YCbCr 图像数据转换的矩阵系数。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。

值：从 RGB 到 YCbCr 图像数据转换的矩阵系数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


获取或设置色度分量相对于亮度分量的位置。

值：色度分量相对于亮度分量的位置。

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


获取或设置色度分量相对于亮度分量的位置。

值：色度分量相对于亮度分量的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


获取或设置色度分量相对于亮度分量的采样比例。

值：色度分量相对于亮度分量的采样比例。

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


获取或设置色度分量相对于亮度分量的采样比例。

值：色度分量相对于亮度分量的采样比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


获取或设置 Y 分辨率。

值：y 分辨率。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


获取或设置 Y 分辨率。

值：y 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


序列化 EXIF 数据。写入标签值和内容。最影响大小的标签是缩略图标签内容。

**Returns:**
byte[] - 已序列化的 EXIF 数据。

整体段大小必须小于或等于 MaxExifSegmentSize 字节，以生成正确的 jpeg 图像。提示：如果 EXIF 部分大小过大，请尝试减小缩略图尺寸或更改其压缩方式。
