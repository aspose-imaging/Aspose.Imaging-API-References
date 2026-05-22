---
title: "ColorantCmyk 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | 初始化 [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) 类的新实例。 |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | 初始化 [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [静态] | float | r | CMYK 色剂中的颜色最大值。 |
| COLOR_VALUE_MIN [静态] | float | r | CMYK 色剂中的颜色最小值。 |
| 黑色 | float | r/w | 获取或设置黑色分量的值。 |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | 获取或设置颜色的类型。 |
| 青色 | float | r/w | 获取或设置青色分量的值。 |
| 品红色 | float | r/w | 获取或设置品红色分量的值。 |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | 获取 [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/)。 |
| namespace_uri | string | r | 获取默认命名空间 URI。 |
| prefix | string | r | 获取前缀。 |
| swatch_name | string | r/w | 获取或设置样本的名称。 |
| 黄色 | float | r/w | 获取或设置黄色分量的值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [get_xmp_representation()](#get_xmp_representation__2) | 获取 XMP 格式中包含的字符串值。 |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

初始化 [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) 类的新实例。

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

初始化 [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 黑色 | float | 黑色分量值。 |
| 青色 | float | 青色分量的值。 |
| 品红色 | float | 品红色分量值。 |
| 黄色 | float | 黄色分量的值。 |

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


