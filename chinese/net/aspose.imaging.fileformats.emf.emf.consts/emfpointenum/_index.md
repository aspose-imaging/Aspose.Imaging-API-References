---
title: "Enum EmfPointEnum"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfPointEnum 枚举。Point 枚举用于指定在绘图调用中如何使用点。"
type: docs
weight: 2880
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
## EmfPointEnum enumeration

该 Point 枚举用于指定在绘图调用中如何使用点。

```csharp
[Flags]
public enum EmfPointEnum : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PT_CLOSEFIGURE | `1` | 可以使用位运算符 OR 将 PT_LINETO 或 PT_BEZIERTO 类型与此值组合，以指示相应的点是图形中的最后一点且图形已闭合。 |
| PT_LINETO | `2` | 指定应从当前位置信息绘制一条线到此点，随后此点成为新的当前位置信息。 |
| PT_BEZIERTO | `4` | 指定此点是贝塞尔曲线的控制点或结束点。 |
| PT_MOVETO | `6` | 指定此点开始一个不相连的图形。此点成为新的当前位置信息。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


