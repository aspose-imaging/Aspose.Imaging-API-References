---
title: "DibBitCount 枚举"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/
---

BitCount 枚举指定定义每个像素的位数以及<br/>                设备无关位图 (DIB) 中的最大颜色数。

**Module:** [aspose.imaging.apsbuilder.dib](/imaging/python-net/aspose.imaging.apsbuilder.dib/)

**Full Name:** aspose.imaging.apsbuilder.dib.DibBitCount

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| BITCOUNT0 | 每像素的位数未定义。<br/>                图像应为 JPEG 或 PNG 格式。<br/>                这两种格式都不包含颜色表，因此此值<br/>                表示不存在颜色表。请参阅 [JFIF] 和 [RFC2083]<br/>                以获取有关 JPEG 和 PNG 压缩格式的更多信息。 |
| BITCOUNT1 | 该图像指定为两种颜色。位图中的每个像素<br/>                由单个位表示。如果该位为 0，则像素显示为颜色表中第一个条目的颜色；<br/>                如果该位为 1，则像素使用颜色表中第二个条目的颜色。 |
| BITCOUNT2 | 该图像最多可包含 16 种颜色。<br/>                位图中的每个像素由指向颜色表的 4 位索引表示，每个字节包含 2 个像素。 |
| BITCOUNT3 | 该图像最多可包含 256 种颜色。<br/>                位图中的每个像素由指向颜色表的 8 位索引表示，每个字节包含 1 个像素。 |
| BITCOUNT4 | 该图像最多可包含 2^16 种颜色。<br/>                位图中的每个像素由 16 位值表示。 |
| BITCOUNT5 | 该位图最多可包含 2^24 种颜色，且 DIB 的 Colors 字段为 NULL。<br/>                位图数组中的每个 3 字节三元组分别表示像素的蓝、绿、红相对强度。Colors 颜色表用于优化基于调色板设备的颜色，并且必须包含由 BitmapInfoHeader 对象的 ColorUsed 字段指定的条目数量。 |
| BITCOUNT6 | 该位图最多可包含 2^24 种颜色 |
