---
title: "EmfRop4 类"
type: docs
weight: 1010
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/
---

**Summary:** A quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRop4

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfRop4(dword_data)](#EmfRop4_dword_data_1) | 初始化 [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| background_rop3 | System.Byte | r | 获取背景 ROP3。<br/>            该值是来自 WMF 三元光栅操作枚举 ([MS-WMF] 第 2.1.1.31 节) 的 24 位三元光栅操作值的最高有效 8 位无符号整数。此代码定义了如何将源和目标位图以及画笔图案的背景颜色数据进行组合。 |
| foreground_rop3 | System.Byte | r | 获取前景 ROP3。<br/>            该值是来自 WMF 三元光栅操作枚举的 24 位三元光栅操作值的最高有效 8 位无符号整数。此代码定义了如何将源和目标位图以及画笔图案的前景颜色数据进行组合。 |


### Constructor: EmfRop4(dword_data) {#EmfRop4_dword_data_1}


```
 EmfRop4(dword_data) 
```

初始化 [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dword_data | int | DWORD 数据。 |

