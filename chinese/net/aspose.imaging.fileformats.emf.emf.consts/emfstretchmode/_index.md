---
title: "Enum EmfStretchMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfStretchMode enum. StretchMode 枚举用于指定在拉伸或压缩位图时，如何添加或移除颜色数据。"
type: docs
weight: 2960
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
## EmfStretchMode enumeration

StretchMode 枚举用于指定在拉伸或压缩位图时，如何添加或移除颜色数据。

```csharp
public enum EmfStretchMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| STRETCH_ANDSCANS | `1` | 使用被消除像素和现有像素的颜色值执行布尔 AND 运算。如果位图是单色位图，此模式会以牺牲白色像素为代价保留黑色像素。 |
| STRETCH_ORSCANS | `2` | 使用被消除像素和现有像素的颜色值执行布尔 OR 运算。如果位图是单色位图，此模式会以牺牲黑色像素为代价保留白色像素。 |
| STRETCH_DELETESCANS | `3` | 删除像素。此模式删除所有被消除的像素行，而不尝试保留其信息。 |
| STRETCH_HALFTONE | `4` | 将像素从源矩形映射到目标矩形中的像素块。目标像素块的平均颜色近似于源像素的颜色。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


