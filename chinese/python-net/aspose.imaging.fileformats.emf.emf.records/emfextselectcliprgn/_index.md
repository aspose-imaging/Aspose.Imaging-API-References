---
title: "EmfExtSelectClipRgn 类"
type: docs
weight: 460
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---

**Summary:** The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region <br/>            using the specified mode. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtSelectClipRgn

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn__1) | 初始化 [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) 类的新实例。 |
| [EmfExtSelectClipRgn(source)](#EmfExtSelectClipRgn_source_2) | 初始化 [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | 获取或设置一个 32 位无符号整数，指定区域的使用方式。该 <br/> 值必须属于 RegionMode（第 2.1.29 节）枚举。 |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | 获取或设置一个长度为 RgnDataSize 的字节数组，用于指定以逻辑单位表示的 RegionData 对象 <br/>。如果 RegionMode 为 RGN_COPY，则可以省略此数据，剪裁区域 <br/> 应设置为默认（NULL）剪裁区域。 |
| rgn_data_size | int | r/w | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfExtSelectClipRgn() {#EmfExtSelectClipRgn__1}


```
 EmfExtSelectClipRgn() 
```

初始化 [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) 类的新实例。

### Constructor: EmfExtSelectClipRgn(source) {#EmfExtSelectClipRgn_source_2}


```
 EmfExtSelectClipRgn(source) 
```

初始化 [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | 记录类型。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


