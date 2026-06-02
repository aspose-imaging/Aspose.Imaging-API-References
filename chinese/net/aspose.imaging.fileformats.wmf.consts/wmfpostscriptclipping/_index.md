---
title: "枚举 WmfPostScriptClipping"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfPostScriptClipping 枚举。PostScriptClipping 枚举定义可应用于 PostScript 输出的裁剪路径的函数。"
type: docs
weight: 8490
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfpostscriptclipping/
---
## WmfPostScriptClipping enumeration

此 PostScriptClipping 枚举定义了可应用于 PostScript 输出所使用的剪裁路径的功能。

```csharp
public enum WmfPostScriptClipping
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| CLIP_SAVE | `0` | 保存当前的 PostScript 裁剪路径。 |
| CLIP_RESTORE | `1` | 将 PostScript 裁剪路径恢复到上一次由 CLIP_SAVE 函数保存、并通过 CLIP_TO_PATH 记录应用的裁剪路径（第 2.3.6.6 节）。 |
| CLIP_INCLUSIVE | `2` | 将当前 PostScript 裁剪路径与当前裁剪路径相交，并将结果保存为新的 PostScript 裁剪路径。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


