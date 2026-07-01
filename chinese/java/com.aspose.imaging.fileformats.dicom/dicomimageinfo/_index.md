---
title: "DicomImageInfo"
second_title: "Aspose.Imaging for Java API 参考"
description: "包含来自 Dicom 文件头的所有元信息。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

包含来自 Dicom 文件头的所有元信息。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | 获取以字节形式的 DICOM 头信息。 |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 获取平面配置。 |
| [getSignedImage()](#getSignedImage--) | 获取指示是否为 "signedImage" 的值。 |
| [getDicomInfo()](#getDicomInfo--) | 获取 DICOM 文件的头信息。 |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | 获取 "samplesPerPixel" 的值。 |
| [getBitsAllocated()](#getBitsAllocated--) | 获取 "bitsAllocated" 的值。 |
| [getBitsStored()](#getBitsStored--) | 获取存储位的数量。 |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | 获取 "PhotoInterpretation" 的值。 |
| [getWidth()](#getWidth--) | 获取宽度。 |
| [getHeight()](#getHeight--) | 获取高度。 |
| [getWindowCentre()](#getWindowCentre--) | 获取窗口中心。 |
| [getWindowWidth()](#getWindowWidth--) | 获取窗口宽度。 |
| [getPixelRepresentation()](#getPixelRepresentation--) | 获取像素 "pixelRepresentation" 的值。 |
| [getRescaleIntercept()](#getRescaleIntercept--) | 获取 "rescaleIntercept" 的值。 |
| [getRescaleSlope()](#getRescaleSlope--) | 获取 "rescaleSlope" 的值。 |
| [getNumberOfFrames()](#getNumberOfFrames--) | 获取帧数。 |
| [isLittleEndian()](#isLittleEndian--) | 获取指示此实例是否为小端序的值。 |
| [getReds()](#getReds--) | 获取红色的颜色数组 |
| [getGreens()](#getGreens--) | 获取绿色的颜色数组。 |
| [getBlues()](#getBlues--) | 获取蓝色的颜色数组。 |
| [getOffset()](#getOffset--) | 获取偏移量。 |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | 添加新的 Dicom 标记。 |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | 添加新的 Dicom 标记。 |
| [removeTagAt(int index)](#removeTagAt-int-) | 移除已有的标记。 |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | 移除已有的标记。 |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | 更新已有的标记。 |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | 更新已有的标记。 |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


获取以字节形式的 DICOM 头信息。

值：按字节的 dicom 头信息。

**Returns:**
byte[] - 按字节的 dicom 头信息。
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


获取平面配置。

值：平面配置。

**Returns:**
int - 平面配置。
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


获取指示是否为 "signedImage" 的值。

**Returns:**
boolean - 指示是否为 "signedImage" 的值。
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


获取 DICOM 文件的头信息。

**Returns:**
java.util.List<java.lang.String> - DICOM 文件的头信息。

**Example: The following example shows how to read the header information of a DICOM image.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1489\\";
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "ttfm.dcm");
try {
    for (String s : image.getFileInfo().getDicomInfo()) {
        System.out.println(s);
    }
}
finally {
    image.close();
}

// STDOUT:
//媒体存储 Sop 类 Uid：1.2.840.10008.5.1.4.1.1.3.1
//媒体存储 Sop 实例 Uid：2.16.840.1.114488.0.4.123489834087.1330071425.2
//传输语法 Uid：1.2.840.10008.1.2.4.70
//实现类 Uid：1.2.840.114236
//特定字符集：ISO_IR 100
//图像类型：\SECONDARY\INTRAOPERATIVE
//Sop 类 Uid：1.2.840.10008.5.1.4.1.1.3.1
//Sop 实例 Uid：2.16.840.1.114488.0.4.123489834087.1330071425.2
//研究日期：20110824
//序列日期：20110824
//内容日期：20110824
//研究时间：094836.214743984
//序列时间：094836.214743984
//内容时间：100451.214743816
//模态：US
//制造商: Medistim
//机构名称: Hospital Name
//机构地址: Hospital Address or Department
//站点名称: VERIQ
//执行医师姓名: CA Prof. Debus
//制造商型号名称: VeriQ C
//推荐显示帧率: 1
//患者姓名: Femoral trombenarterectomy^Case Report:
//患者ID: Case Report 1
//患者性别: M
//患者尺寸: 0
//患者体重: 0
//患者备注: See case report on www.medistim.com
//Cine 速率: 1
//有效持续时间: 1
//设备序列号: 0
//软件版本: 3.3.0 RC0 built 02 / 23 / 12  09:50:45
//帧时间: 1000
//研究实例 UID: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//序列实例 UID: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//序列号: 1
//实例号: 1
//每像素样本数: 3
//光度解释: RGB
//平面配置: 0
//帧数: 1
//帧增量指针:
//行: 768
//列: 1024
//已分配位数: 8
//存储的位数: 8
//高位: 7
//像素表示: 0
//有损图像压缩: 00
//像素数据: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


获取 "samplesPerPixel" 的值。

值: "samplesPerPixel" 的值。

**Returns:**
int - "samplesPerPixel" 的一个值。
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


获取 "bitsAllocated" 的值。

值: "bitsAllocated" 的值。

**Returns:**
int - "bitsAllocated" 的一个值。
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


获取存储位的数量。

**Returns:**
int - 已存储位的数量。
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


获取 "PhotoInterpretation" 的值。

**Returns:**
java.lang.String - "PhotoInterpretation" 的一个值。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取宽度。

值: 宽度的值。

**Returns:**
int - 宽度。
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取高度。

值: 高度的值。

**Returns:**
int - 高度。
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


获取窗口中心。

值: 窗口中心的值。

**Returns:**
double - 窗口中心。
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


获取窗口宽度。

值: 窗口的宽度。

**Returns:**
double - 窗口的宽度。
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


获取像素 "pixelRepresentation" 的值。

值: "pixelRepresentation" 的值。

**Returns:**
int - 像素 "pixelRepresentation" 的一个值。
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


获取 "rescaleIntercept" 的值。

值: "rescaleIntercept" 的值。

**Returns:**
double - \"rescaleIntercept\" 的值。
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


获取 "rescaleSlope" 的值。

值：\"rescaleSlope\" 的值。

**Returns:**
double - \"rescaleSlope\" 的值。
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


获取帧数。

值：帧的数量。

**Returns:**
int - 帧的数量。
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


获取指示此实例是否为小端序的值。

值：如果此实例是小端序则为 `true`；否则为 `false`。

**Returns:**
boolean - 表示此实例是否为小端序的值。
### getReds() {#getReds--}
```
public byte[] getReds()
```


获取红色的颜色数组

值：红色。

**Returns:**
byte[] - 红色的颜色数组
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


获取绿色的颜色数组。

值：红色的颜色。

**Returns:**
byte[] - 绿色的颜色数组
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


获取蓝色的颜色数组。

值：蓝色。

**Returns:**
byte[] - 蓝色的颜色数组
### getOffset() {#getOffset--}
```
public int getOffset()
```


获取偏移量。

值：偏移量的值。

**Returns:**
int - 偏移量。
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


添加新的 Dicom 标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagDescription | java.lang.String | 标签描述。不能为空或仅包含空白。 |
| 值 | java.lang.Object | 标签值。不能为空。 |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


添加新的 Dicom 标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagDescription | java.lang.String | 标签描述。不能为空或仅包含空白。 |
| 值 | java.lang.Object | 标签值。不能为空。 |

**Returns:**
boolean - 操作结果。
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


移除已有的标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要更新的标签索引。 |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


移除已有的标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要更新的标签索引。 |

**Returns:**
boolean - 操作结果。
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


更新已有的标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要更新的标签索引。 |
| newValue | java.lang.Object | 标签值。不能为空。 |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


更新已有的标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要更新的标签索引。 |
| newValue | java.lang.Object | 标签值。不能为空。 |

**Returns:**
boolean - 操作结果。
