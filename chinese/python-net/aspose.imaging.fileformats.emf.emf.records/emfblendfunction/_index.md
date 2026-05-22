---
title: "EmfBlendFunction 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | 初始化一个新的 EmfBlendFunction 类实例 |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | 初始化一个新的 [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | 获取一个结构，指定源像素和目标像素在 alpha 透明度方面的<br/>            解释方式。 |
| blend_flags | System.Byte | r | 获取混合标志。<br/>            此值必须为 0x00 且必须被忽略。 |
| blend_operation | System.Byte | r | 获取混合操作代码。<br/>            唯一已定义的源和目标<br/>            混合操作是 0x00，它指定源位图<br/>            必须根据源像素的 alpha 透明度值与目标位图进行合并。有关详细信息，请参见以下公式。 |
| src_constant_alpha | System.Byte | r | 获取一个 8 位无符号整数，指定 alpha 透明度，<br/>            该值决定源位图和目标位图的混合方式。此值必须在整个源位图上使用。最小的 alpha 透明度值为 0，<br/>            表示完全透明，最大值 0xFF 表示完全不透明。实际上，值为 0xFF 时，表示每像素的 alpha 值<br/>            决定源位图和目标位图的混合。有关详细信息，请参见本节后面的公式。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [to_int()](#to_int__1) | 将数字的字符串表示转换为整数。 |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

初始化一个新的 EmfBlendFunction 类实例

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

初始化一个新的 [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dword_data | int | DWORD 数据。 |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

将数字的字符串表示转换为整数。

**Returns**

| Type | Description |
| :- | :- |
| int | 结构的 DWORD 值。 |


