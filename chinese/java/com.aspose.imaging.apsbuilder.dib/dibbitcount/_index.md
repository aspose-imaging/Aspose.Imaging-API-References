---
title: "DibBitCount"
second_title: "Aspose.Imaging for Java API 参考"
description: "BitCount 枚举指定定义每个像素的位数以及设备无关位图 DIB 中的最大颜色数。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

BitCount 枚举指定定义每个像素的位数以及设备无关位图（DIB）中的最大颜色数。
## 字段

| 字段 | 描述 |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | 每像素的位数未定义。 |
| [BIT_COUNT_1](#BIT-COUNT-1) | 图像指定为两种颜色。位图中的每个像素由单个位表示。 |
| [BIT_COUNT_2](#BIT-COUNT-2) | 图像指定的最大颜色数为 16 种。 |
| [BIT_COUNT_3](#BIT-COUNT-3) | 图像指定的最大颜色数为 256 种。 |
| [BIT_COUNT_4](#BIT-COUNT-4) | 图像指定的最大颜色数为 2^16 种。 |
| [BIT_COUNT_5](#BIT-COUNT-5) | 位图的最大颜色数为 2^24，且 DIB 的 Colors 字段为 NULL。 |
| [BIT_COUNT_6](#BIT-COUNT-6) | 位图的最大颜色数为 2^24。 |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


每像素的位数未定义。图像应为 JPEG 或 PNG 格式。这两种格式均不包含颜色表，因此该值表示不存在颜色表。有关 JPEG 和 PNG 压缩格式的更多信息，请参阅 [JFIF] 和 [RFC2083]。

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


图像指定为两种颜色。位图中的每个像素由单个位表示。如果该位为 0，则像素显示颜色表中第一个条目的颜色；如果该位为 1，则像素显示颜色表中第二个条目的颜色。

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


图像指定的最大颜色数为 16 种。位图中的每个像素由指向颜色表的 4 位索引表示，每个字节包含 2 个像素。

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


图像指定的最大颜色数为 256 种。位图中的每个像素由指向颜色表的 8 位索引表示，每个字节包含 1 个像素。

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


图像指定的最大颜色数为 2^16 种。位图中的每个像素由 16 位值表示。

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


位图的最大颜色数为 2^24，且 DIB 的 Colors 字段为 NULL。位图数组中的每个 3 字节三元组分别表示像素的蓝、绿、红相对强度。Colors 颜色表用于优化基于调色板的设备上使用的颜色，并且必须包含由 BitmapInfoHeader 对象的 ColorUsed 字段指定的条目数量。

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


位图的最大颜色数为 2^24。

