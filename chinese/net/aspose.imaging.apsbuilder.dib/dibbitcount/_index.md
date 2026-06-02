---
title: "枚举 DibBitCount"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ApsBuilder.Dib.DibBitCount 枚举。BitCount 枚举指定定义每个像素的位数以及设备无关位图（DIB）中的最大颜色数"
type: docs
weight: 30
url: /zh/net/aspose.imaging.apsbuilder.dib/dibbitcount/
---
## DibBitCount enumeration

BitCount 枚举指定定义每个像素的位数以及设备无关位图 (DIB) 中的最大颜色数。

```csharp
public enum DibBitCount : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Bitcount0 | `0` | 每像素的位数未定义。图像应为 JPEG 或 PNG 格式。这两种格式都不包含颜色表，因此该值表示不存在颜色表。有关 JPEG 和 PNG 压缩格式的更多信息，请参阅 [JFIF] 和 [RFC2083]。 |
| Bitcount1 | `1` | 该图像指定为两种颜色。位图中的每个像素由单个位表示。如果位为 0，则像素显示颜色表中第一个条目的颜色；如果位为 1，则像素显示第二个条目的颜色。 |
| Bitcount2 | `4` | 该图像指定最多 16 种颜色。位图中的每个像素由 4 位索引到颜色表表示，每个字节包含 2 个像素。 |
| Bitcount3 | `8` | 该图像指定最多 256 种颜色。位图中的每个像素由 8 位索引到颜色表表示，每个字节包含 1 个像素。 |
| Bitcount4 | `16` | 该图像指定最多 2^16 种颜色。位图中的每个像素由 16 位值表示。 |
| Bitcount5 | `24` | 该位图最多支持 2^24 种颜色，且 DIB 的 Colors 字段为 NULL。位图数组中的每个 3 字节三元组分别表示像素的蓝、绿、红相对强度。Colors 颜色表用于优化基于调色板设备的颜色使用，且必须包含 BitmapInfoHeader 对象的 ColorUsed 字段指定的条目数。 |
| Bitcount6 | `32` | 位图的颜色数最大为 2^24 |

### 另请参见

* namespace [Aspose.Imaging.ApsBuilder.Dib](../../aspose.imaging.apsbuilder.dib/)
* assembly [Aspose.Imaging](../../)


