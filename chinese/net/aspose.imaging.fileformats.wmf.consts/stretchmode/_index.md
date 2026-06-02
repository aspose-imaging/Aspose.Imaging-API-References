---
title: "枚举 StretchMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.StretchMode 枚举。StretchMode 枚举指定位图拉伸模式，该模式定义系统如何将位图的行或列与现有像素合并。"
type: docs
weight: 8270
url: /zh/net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---
## StretchMode enumeration

The `StretchMode` 枚举指定位图拉伸模式，该模式定义系统如何将位图的行或列与现有像素合并。

```csharp
public enum StretchMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| BlackOnWhite | `1` | 通过使用被消除像素和现有像素的颜色值执行布尔 AND 操作。如果位图是单色位图，则此模式以牺牲白色像素为代价保留黑色像素。 |
| WhiteOnBlack | `2` | 通过使用被消除像素和现有像素的颜色值执行布尔 OR 操作。如果位图是单色位图，则此模式以牺牲黑色像素为代价保留白色像素。 |
| ColorOnColor | `3` | 删除像素。此模式删除所有被消除的像素行，而不尝试保留其信息。 |
| HalfTone | `4` | 将像素从源矩形映射到目标矩形中的像素块。目标像素块的平均颜色近似于源像素的颜色。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


