---
title: "EmfPixelFormatDescriptor 类"
type: docs
weight: 220
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | 初始化 EmfPixelFormatDescriptor 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | 获取或设置，指定覆盖平面和底层平面的数量。位 0 到 3 指定<br/>            最多 15 个覆盖平面，位 4 到 7 指定最多 15 个底层平面。 |
| c_accum_alpha_bits | System.Byte | r/w | 获取或设置，指定累积缓冲区中的 alpha 位平面数量 |
| c_accum_bits | System.Byte | r/w | 获取或设置，指定累积缓冲区中的位平面总数。 |
| c_accum_blue_bits | System.Byte | r/w | 获取或设置，指定累积缓冲区中蓝色位平面的数量。 |
| c_accum_green_bits | System.Byte | r/w | 获取或设置，指定累积缓冲区中绿色位平面的数量。 |
| c_accum_red_bits | System.Byte | r/w | 获取或设置，指定累积缓冲区中红色位平面的数量。 |
| c_alpha_bits | System.Byte | r/w | 获取或设置，指定每个 RGBA 颜色缓冲区中的 alpha 位平面数量。 |
| c_alpha_shift | System.Byte | r/w | 获取或设置，指定每个 RGBA 颜色缓冲区中 alpha 位平面的移位计数。 |
| c_aux_buffers | System.Byte | r/w | 获取或设置，指定辅助缓冲区的数量。辅助缓冲区不受支持。 |
| c_blue_bits | System.Byte | r/w | 获取或设置，指定每个 RGBA 颜色缓冲区中的蓝色位平面数量。 |
| c_blue_shift | System.Byte | r/w | 获取或设置，指定每个 RGBA 颜色缓冲区中蓝色位平面的移位计数。 |
| c_color_bits | System.Byte | r/w | 获取或设置 RGBA 像素类型每像素的位数，不包括 alpha 位平面。对于颜色表像素，它是每个颜色表索引的大小。 |
| c_depth_bits | System.Byte | r/w | 获取或设置，指定深度（z 轴）缓冲区的深度。 |
| c_green_bits | System.Byte | r/w | 获取或设置，指定每个 RGBA 颜色缓冲区中的绿色位平面数量。 |
| c_green_shift | System.Byte | r/w | 获取或设置 指定每个 RGBA 颜色缓冲区中绿色位平面的移位计数。 |
| c_red_bits | System.Byte | r/w | 获取或设置 指定每个 RGBA 颜色缓冲区中红色位平面的数量 |
| c_red_shift | System.Byte | r/w | 获取或设置 指定每个 RGBA 颜色缓冲区中红色位平面的位移计数。 |
| c_stencil_bits | System.Byte | r/w | 获取或设置 指定模板缓冲区的深度。 |
| dw_damage_mask | int | r/w | 获取或设置 此字段可能会被忽略 |
| dw_flags | int | r/w | 获取或设置 指定用于输出到绘图表面的像素缓冲区属性的位标志。<br/>            这些属性并非全部相互排斥；允许组合标志，除非另有说明。 |
| dw_layer_mask | int | r/w | 获取或设置 此字段可能会被忽略。 |
| dw_visible_mask | int | r/w | 获取或设置 指定底层平面的透明颜色或索引。当像素<br/>            类型为 RGBA 时，dwVisibleMask 是透明的 RGB 颜色值。当像素<br/>            类型为颜色索引时，它是透明的索引值。 |
| layer_type | System.Byte | r/w | 获取或设置 此字段可能会被忽略 |
| n_size | int | r/w | 获取或设置 指定此数据结构大小（以字节为单位）的 16 位整数。 |
| n_version | int | r/w | 获取或设置 必须设置为 0x0001 的 16 位整数。 |
| pixel_type | System.Byte | r/w | 获取或设置 像素数据的类型<br/>            PFD_TYPE_RGBA       0x00 像素格式为 RGBA。<br/>            PFD_TYPE_COLORINDEX 0x01 每个像素是颜色表中的索引。 |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

初始化 EmfPixelFormatDescriptor 类的新实例

