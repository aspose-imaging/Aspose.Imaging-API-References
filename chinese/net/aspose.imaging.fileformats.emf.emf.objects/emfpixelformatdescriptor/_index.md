---
title: "类 EmfPixelFormatDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfPixelFormatDescriptor 类。PixelFormatDescriptor 对象可在 EMR_HEADER 记录第 2.3.4.2 节中使用，以指定回放设备上下文的输出表面的像素格式。"
type: docs
weight: 3210
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

PixelFormatDescriptor 对象可在 EMR_HEADER 记录（第 2.3.4.2 节）中使用，以指定回放设备上下文的输出表面的像素格式。

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved/) { get; set; } | 获取或设置，指定覆盖平面和底层平面的数量。位 0 到 3 指定最多 15 个覆盖平面，位 4 到 7 指定最多 15 个底层平面。 |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits/) { get; set; } | 获取或设置，指定累积缓冲区中的 alpha 位平面数量。 |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits/) { get; set; } | 获取或设置，指定累积缓冲区中的位平面总数。 |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits/) { get; set; } | 获取或设置，指定累积缓冲区中的蓝色位平面数量。 |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits/) { get; set; } | 获取或设置，指定累积中的绿色位平面数量。 |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits/) { get; set; } | 获取或设置，指定累积缓冲区中的红色位平面数量。 |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits/) { get; set; } | 获取或设置，指定每个 RGBA 颜色缓冲区中的 alpha 位平面数量。 |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift/) { get; set; } | 获取或设置，指定每个 RGBA 颜色缓冲区中 alpha 位平面的移位计数。 |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers/) { get; set; } | 获取或设置，指定辅助缓冲区的数量。辅助缓冲区不受支持。 |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits/) { get; set; } | 获取或设置，指定每个 RGBA 颜色缓冲区中的蓝色位平面数量。 |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift/) { get; set; } | 获取或设置，指定每个 RGBA 颜色缓冲区中蓝色位平面的移位计数。 |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits/) { get; set; } | 获取或设置，指定 RGBA 像素类型的每像素位数（不包括 alpha 位平面）。对于颜色表像素，它是每个颜色表索引的大小。 |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits/) { get; set; } | 获取或设置，指定深度（z 轴）缓冲区的深度。 |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits/) { get; set; } | 获取或设置，指定每个 RGBA 颜色缓冲区中的绿色位平面数量。 |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift/) { get; set; } | 获取或设置 指定每个 RGBA 颜色缓冲区中绿色位平面的移位计数。 |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits/) { get; set; } | 获取或设置 指定每个 RGBA 颜色缓冲区中红色位平面的数量 |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift/) { get; set; } | 获取或设置 指定每个 RGBA 颜色缓冲区中红色位平面的位移计数。 |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits/) { get; set; } | 获取或设置 指定模板缓冲区的深度。 |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask/) { get; set; } | 获取或设置 此字段可能会被忽略 |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags/) { get; set; } | 获取或设置 指定用于输出到绘图表面的像素缓冲区属性的位标志。这些属性并非全部互斥；允许组合标志，除非另有说明。 |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask/) { get; set; } | 获取或设置 此字段可能会被忽略。 |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask/) { get; set; } | 获取或设置 指定底层平面的透明颜色或索引。当像素类型为 RGBA 时，dwVisibleMask 是透明的 RGB 颜色值。当像素类型为颜色索引时，它是透明的索引值。 |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype/) { get; set; } | 获取或设置 此字段可能会被忽略 |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype/) { get; set; } | 获取或设置 像素数据的类型 PFD_TYPE_RGBA 0x00 表示像素格式为 RGBA。PFD_TYPE_COLORINDEX 0x01 表示每个像素是颜色表中的索引。 |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize/) { get; set; } | 获取或设置 指定此数据结构大小（以字节为单位）的 16 位整数。 |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion/) { get; set; } | 获取或设置 必须设置为 0x0001 的 16 位整数。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


