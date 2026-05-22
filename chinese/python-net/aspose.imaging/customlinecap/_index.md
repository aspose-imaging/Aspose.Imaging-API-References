---
title: "CustomLineCap 类"
type: docs
weight: 1350
url: /zh/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | 使用指定的轮廓和填充初始化一个新的 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 类实例。 |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | 使用指定的轮廓和填充，从指定的现有 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举初始化一个新的 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 类实例。 |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | 使用指定的轮廓、填充和内嵌，从指定的现有 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举初始化一个新的 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | 获取或设置此 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 所基于的 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举。 |
| base_inset | float | r/w | 获取或设置帽子与线之间的距离。 |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | 获取或设置定义自定义帽子填充的对象。 |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | 获取或设置决定组成此 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 对象的线段如何连接的 [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) 枚举。 |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | 获取或设置定义自定义帽子轮廓的对象。 |
| width_scale | float | r/w | 获取或设置相对于对象宽度缩放此 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 类对象的比例。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | 获取用于开始和结束构成此自定义帽子的线段的帽子。 |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | 设置用于开始和结束构成此自定义帽子的线段的帽子。 |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

使用指定的轮廓和填充初始化一个新的 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 一个定义自定义帽子填充的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 对象。 |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 一个定义自定义帽子轮廓的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 对象。 |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

使用指定的轮廓和填充，从指定的现有 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举初始化一个新的 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 一个定义自定义帽子填充的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 对象。 |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 一个定义自定义帽子轮廓的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 对象。 |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | 用于创建自定义帽子的线帽。 |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

使用指定的轮廓、填充和内嵌，从指定的现有 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举初始化一个新的 [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 一个定义自定义帽子填充的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 对象。 |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 一个定义自定义帽子轮廓的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 对象。 |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | 用于创建自定义帽子的线帽。 |
| base_inset | float | 帽子与线之间的距离。 |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

获取用于开始和结束构成此自定义帽子的线段的帽子。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | 此帽子内线段起始处使用的 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举。 |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | 此帽子内线段结束处使用的 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举。 |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

设置用于开始和结束构成此自定义帽子的线段的帽子。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | 此帽子内线段起始处使用的 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举。 |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | 此帽子内线段结束处使用的 [LineCap](/imaging/python-net/aspose.imaging/linecap/) 枚举。 |

