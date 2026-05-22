---
title: "枚举 WmfTextAlignmentModeFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfTextAlignmentModeFlags 枚举。TextAlignmentMode 标志指定参考点与文本对齐的边界矩形之间的关系。这些标志可以组合以指定多个选项，但限制只能选择一个会改变回放设备上下文中绘图位置的标志。当字体具有水平默认基线时，执行水平文本对齐。"
type: docs
weight: 8530
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
## WmfTextAlignmentModeFlags enumeration

TextAlignmentMode 标志指定参考点与边界矩形之间的关系，用于文本对齐。这些标志可以组合以指定多个选项，但限制只能选择一个会更改回放设备上下文中绘制位置的标志。当字体具有水平默认基线时，执行水平文本对齐。

```csharp
[Flags]
public enum WmfTextAlignmentModeFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Noupdatecp | `0` | 回放设备上下文中的绘图位置在每次文本输出调用后不得更新。必须将参考点传递给文本输出函数。 |
| Left | `0` | 参考点必须位于边界矩形的左侧边缘。 |
| Top | `0` | 参考点必须位于边界矩形的顶部边缘。 |
| Updatecp | `1` | 回放设备上下文中的绘图位置在每次文本输出调用后必须更新。它必须用作参考点。 |
| Right | `2` | 参考点必须位于边界矩形的右侧边缘。 |
| Center | `6` | 参考点必须在水平上与边界矩形的中心对齐。 |
| Bottom | `8` | 参考点必须位于边界矩形的底部边缘。 |
| Baseline | `18` | 参考点必须位于文本的基线位置。 |
| Rtlreading | `100` | 文本必须以从右到左的阅读顺序布局，而不是默认的从左到右顺序。仅当回放设备上下文中定义的字体是希伯来语或阿拉伯语时，才应这样做。 |
| Horizontal | `6` | 表示水平文本对齐集合（左 &#x7C; 右 &#x7C; 居中） |
| Vertical | `18` | 表示垂直文本对齐集合（上 &#x7C; 下 &#x7C; 基线） |

## 备注

TextAlignmentMode 标志指定文本对齐的三个不同组成部分：- 参考点的水平位置由 TA_RIGHT 和 TA_CENTER 决定；如果这些位被清除，则对齐必须为 TA_LEFT。- 参考点的垂直位置由 TA_BOTTOM 和 TA_BASELINE 决定；如果这些位被清除，则对齐必须为 TA_TOP。- 是否在文本输出后更新回放设备上下文中的输出位置由 TA_UPDATECP 决定；如果该位被清除，则位置不得更新。这就是在枚举中定义三个不同零值的原因；它们代表文本对齐三个组成部分的默认状态。

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


