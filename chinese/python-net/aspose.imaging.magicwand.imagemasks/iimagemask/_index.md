---
title: "IImageMask 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取此掩码的边界（以像素为单位）。 |
| height | int | r | 获取此掩码的高度（以像素为单位）。 |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取掩码选定部分的边界（以像素为单位）。 |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | 获取用于创建此掩码的源图像（如果存在）。 |
| width | int | r | 获取此掩码的宽度（以像素为单位）。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建一个新对象，该对象是当前实例的副本。 |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | 获取指定像素的透明度（以字节精度）。 |
| [is_opaque(x, y)](#is_opaque_x_y_3) | 检查指定像素是否不透明。 |
| [is_transparent(x, y)](#is_transparent_x_y_4) | 检查指定像素是否透明。 |


### Method: clone() {#clone__1}


```
 clone() 
```

创建一个新对象，该对象是当前实例的副本。

**Returns**

| Type | Description |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


```
 get_byte_opacity(x, y) 
```

获取指定像素的透明度（以字节精度）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 字节值，表示指定像素的透明度。 |


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


```
 is_opaque(x, y) 
```

检查指定像素是否不透明。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定像素不透明则为 true；否则为 false。 |


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


```
 is_transparent(x, y) 
```

检查指定像素是否透明。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定像素透明则为 true；否则为 false。 |


