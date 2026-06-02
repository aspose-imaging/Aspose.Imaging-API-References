---
title: "ColorantLab 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/
---

**Summary:** Represents LAB Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantLab

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ColorantLab()](#ColorantLab__1) | 初始化 [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) 类的新实例。 |
| [ColorantLab(a, b, l)](#ColorantLab_a_b_l_2) | 初始化 [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| MAX_A [静态] | int | r | A 组件的最大值 |
| MAX_B [静态] | int | r | A 组件的最大值 |
| MAX_L [静态] | float | r | A 组件的最大值 |
| MIN_A [静态] | int | r | A 组件的最小值 |
| MIN_B [静态] | int | r | B 组件的最小值 |
| MIN_L [静态] | float | r | L 组件的最小值 |
| a | int | r/w | 获取或设置 A 组件。 |
| b | int | r/w | 获取或设置 B 组件。 |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | 获取或设置颜色的类型。 |
| l | float | r/w | 获取或设置 L 组件。 |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | 获取 [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/)。 |
| namespace_uri | string | r | 获取默认命名空间 URI。 |
| prefix | string | r | 获取前缀。 |
| swatch_name | string | r/w | 获取或设置样本的名称。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [get_xmp_representation()](#get_xmp_representation__2) | 获取 XMP 格式中包含的字符串值。 |


### Constructor: ColorantLab() {#ColorantLab__1}


```
 ColorantLab() 
```

初始化 [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) 类的新实例。

### Constructor: ColorantLab(a, b, l) {#ColorantLab_a_b_l_2}


```
 ColorantLab(a, b, l) 
```

初始化 [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | int | A 组件。 |
| b | int | B 组件。 |
| l | float | L 组件。 |

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


