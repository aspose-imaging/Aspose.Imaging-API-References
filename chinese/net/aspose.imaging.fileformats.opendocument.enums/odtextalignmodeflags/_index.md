---
title: "Enum OdTextAlignModeFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.OpenDocument.Enums.OdTextAlignModeFlags 枚举。OpenDocument 文本对齐模式标志"
type: docs
weight: 6990
url: /zh/net/aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
## OdTextAlignModeFlags enumeration

开放文档文本对齐模式标志

```csharp
[Flags]
public enum OdTextAlignModeFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Noupdatecp | `0` | 回放设备上下文中的绘图位置在每次文本输出调用后不得更新。必须将参考点传递给文本输出函数。 |
| Left | `0` | 参考点必须位于边界矩形的左侧边缘。 |
| Top | `0` | 参考点必须位于边界矩形的顶部边缘。 |
| Updatecp | `0` | 回放设备上下文中的绘图位置在每次文本输出调用后必须更新。它必须用作参考点。 |
| Right | `1` | 参考点必须位于边界矩形的右侧边缘。 |
| Center | `2` | 参考点必须在水平上与边界矩形的中心对齐。 |
| Justify | `4` | 文本必须以每段的每行具有相同长度的方式对齐。 |
| Bottom | `8` | 参考点必须位于边界矩形的底部边缘。 |
| Baseline | `10` | 参考点必须位于文本的基线位置。 |
| Rtlreading | `100` | 文本必须以从右到左的阅读顺序布局，而不是默认的从左到右顺序。仅当回放设备上下文中定义的字体是希伯来语或阿拉伯语时，才应这样做。 |
| Horizontal | `3` | 表示水平文本对齐集合（左 &#x7C; 右 &#x7C; 居中） |
| Vertical | `18` | 表示垂直文本对齐集合（上 &#x7C; 下 &#x7C; 基线） |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.OpenDocument.Enums](../../aspose.imaging.fileformats.opendocument.enums/)
* assembly [Aspose.Imaging](../../)


