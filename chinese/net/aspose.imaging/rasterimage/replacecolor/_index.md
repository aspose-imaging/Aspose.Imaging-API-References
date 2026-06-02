---
title: "RasterImage.ReplaceColor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage method. 将一种颜色替换为另一种颜色，允许一定差异，并保留原始 alpha 值以保持平滑边缘"
type: docs
weight: 530
url: /zh/net/aspose.imaging/rasterimage/replacecolor/
---
## ReplaceColor(Color, byte, Color) {#replacecolor}

将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。

```csharp
public void ReplaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldColor | 颜色 | 要被替换的旧颜色。 |
| oldColorDiff | Byte | 允许的旧颜色差异，以便扩大替换后的颜色色调。 |
| newColor | 颜色 | 用于替换旧颜色的新颜色。 |

### 另请参见

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## ReplaceColor(int, byte, int) {#replacecolor_1}

将一种颜色替换为另一种颜色，允许差异并保留原始 alpha 值以保持平滑边缘。

```csharp
public virtual void ReplaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldColorArgb | Int32 | 待替换的旧颜色 ARGB 值。 |
| oldColorDiff | Byte | 允许的旧颜色差异，以便扩大替换后的颜色色调。 |
| newColorArgb | Int32 | 用于替换旧颜色的新颜色 ARGB 值。 |

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


