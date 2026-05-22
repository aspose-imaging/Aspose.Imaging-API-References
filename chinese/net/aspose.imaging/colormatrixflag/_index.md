---
title: "枚举 ColorMatrixFlag"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ColorMatrixFlag 枚举。指定受 ImageAttributes 的颜色和灰度调整设置影响的图像和颜色类型。"
type: docs
weight: 370
url: /zh/net/aspose.imaging/colormatrixflag/
---
## ColorMatrixFlag enumeration

指定受 [`ImageAttributes`](../imageattributes/) 的颜色和灰度调整设置影响的图像和颜色类型。

```csharp
public enum ColorMatrixFlag
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 所有颜色值，包括灰色阴影，均由相同的颜色调整矩阵进行调整。 |
| SkipGrays | `1` | 所有颜色都会被调整，但灰色阴影不会被调整。灰色阴影是指红、绿、蓝分量值相同的任何颜色。 |
| AltGrays | `2` | 仅调整灰色阴影。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


