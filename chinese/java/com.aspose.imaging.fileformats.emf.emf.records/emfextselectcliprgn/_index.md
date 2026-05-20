---
title: "EmfExtSelectClipRgn"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_EXTSELECTCLIPRGN 记录使用指定模式将指定区域与当前剪裁区域合并。"
type: docs
weight: 55
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

EMR\_EXTSELECTCLIPRGN 记录使用指定模式将指定区域与当前剪裁区域合并。注意，本节未描述的字段在第 2.3.2 节中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfExtSelectClipRgn` 类的新实例。 |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | 初始化 `EmfExtSelectClipRgn` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | 获取或设置指定区域数据大小（以字节为单位）的 32 位无符号整数。 |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | 获取或设置指定区域数据大小（以字节为单位）的 32 位无符号整数。 |
| [getRegionMode()](#getRegionMode--) | 获取或设置指定区域使用方式的 32 位无符号整数。 |
| [setRegionMode(int value)](#setRegionMode-int-) | 获取或设置指定区域使用方式的 32 位无符号整数。 |
| [getRgnData()](#getRgnData--) | 获取或设置长度为 RgnDataSize 的字节数组，以逻辑单位指定 RegionData 对象。 |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | 获取或设置长度为 RgnDataSize 的字节数组，以逻辑单位指定 RegionData 对象。 |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


初始化 `EmfExtSelectClipRgn` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


初始化 `EmfExtSelectClipRgn` 类的新实例。

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


获取或设置指定区域数据大小（以字节为单位）的 32 位无符号整数。

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


获取或设置指定区域数据大小（以字节为单位）的 32 位无符号整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


获取或设置指定区域使用方式的 32 位无符号整数。该值必须属于 RegionMode（第 2.1.29 节）枚举。

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


获取或设置指定区域使用方式的 32 位无符号整数。该值必须属于 RegionMode（第 2.1.29 节）枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


获取或设置长度为 RgnDataSize 的字节数组，以逻辑单位指定 RegionData 对象。如果 RegionMode 为 RGN\_COPY，则可以省略此数据，剪裁区域应设置为默认（NULL）剪裁区域。

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


获取或设置长度为 RgnDataSize 的字节数组，以逻辑单位指定 RegionData 对象。如果 RegionMode 为 RGN\_COPY，则可以省略此数据，剪裁区域应设置为默认（NULL）剪裁区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

