---
title: "EmfRegionDataHeader 类"
type: docs
weight: 250
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | 初始化 EmfRegionDataHeader 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），用于指定 <br/>            区域的边界。 |
| count_rects | int | r/w | 获取或设置一个 32 位无符号整数，用于指定此区域中的矩形数量。 |
| rgn_size | int | r/w | 获取或设置一个 32 位无符号整数，用于指定矩形缓冲区的大小（字节）。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，用于指定此对象的大小（字节）。该值必须为 0x00000020。 |
| type | int | r/w | 获取或设置一个 32 位无符号整数，用于指定区域类型。该值应为 <br/>            RDH_RECTANGLES (0x00000001)。 |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

初始化 EmfRegionDataHeader 类的新实例

