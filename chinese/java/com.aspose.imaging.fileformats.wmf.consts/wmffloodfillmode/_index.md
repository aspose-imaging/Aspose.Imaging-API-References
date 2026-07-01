---
title: "WmfFloodFillMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "FloodFill 枚举指定要执行的填充操作类型。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmffloodfillmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFloodFillMode extends System.Enum
```

FloodFill 枚举指定要执行的填充操作类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [FloodFillBorder](#FloodFillBorder) | 填充区域受 Color 成员指定的颜色限制。 |
| [FloodFillSurface](#FloodFillSurface) | 填充区域受由 Color 成员指定的颜色限制。 |
### FloodFillBorder {#FloodFillBorder}
```
public static final int FloodFillBorder
```


填充区域受 Color 成员指定的颜色限制。此样式与 META\\_FLOODFILL 记录执行的填充相同。

### FloodFillSurface {#FloodFillSurface}
```
public static final int FloodFillSurface
```


填充区域受由 Color 成员指定的颜色限制。只要遇到该颜色，填充会向所有方向向外继续。此样式对于填充具有多色边界的区域很有用。

