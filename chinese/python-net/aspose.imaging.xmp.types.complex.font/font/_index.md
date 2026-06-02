---
title: "字体类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.types.complex.font/font/
---

**Summary:** Represents XMP Font.

**Module:** [aspose.imaging.xmp.types.complex.font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/)

**Full Name:** aspose.imaging.xmp.types.complex.font.Font

**Inheritance:** IXmpType, ComplexTypeBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Font()](#Font__1) | 初始化 [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/) 类的新实例。 |
| [Font(font_family)](#Font_font_family_2) | 初始化 [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| child_font_files | string[] | r/w | 获取或设置组成复合字体的字体文件名数组。 |
| font_face | string | r/w | 获取或设置字体面。 |
| font_family | string | r/w | 获取或设置字体族。 |
| font_file_name | string | r/w | 获取或设置不含完整路径的字体文件名。 |
| font_name | string | r/w | 获取或设置 PostScript 字体名称。 |
| font_type | string | r/w | 获取或设置字体类型。 |
| is_composite | bool | r/w | 获取或设置一个值，指示此字体是否为复合字体。 |
| namespace_uri | string | r | 获取默认命名空间 URI。 |
| prefix | string | r | 获取前缀。 |
| 版本 | string | r/w | 获取或设置字体版本。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [get_xmp_representation()](#get_xmp_representation__2) | 获取 XMP 格式中包含的字符串值。 |


### Constructor: Font() {#Font__1}


```
 Font() 
```

初始化 [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/) 类的新实例。

### Constructor: Font(font_family) {#Font_font_family_2}


```
 Font(font_family) 
```

初始化 [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_family | string | 字体族。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| Type | Description |
| :- | :- |
| System.Object | 成员逐个克隆。 |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

获取 XMP 格式中包含的字符串值。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回 XMP 格式中包含的字符串值。 |


