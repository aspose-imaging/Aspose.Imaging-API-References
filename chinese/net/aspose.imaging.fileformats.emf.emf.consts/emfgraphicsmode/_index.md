---
title: "枚举 EmfGraphicsMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfGraphicsMode 枚举。GraphicsMode 枚举用于指定如何解释形状数据，例如矩形坐标"
type: docs
weight: 2770
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
## EmfGraphicsMode enumeration

该 GraphicsMode 枚举用于指定如何解释形状数据，例如矩形坐标。

```csharp
public enum EmfGraphicsMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| GM_COMPATIBLE | `1` | TrueType 文本必须从左到右、正向书写，即使由于回放设备上下文中的当前世界坐标到设备坐标变换导致其余图形围绕 x 轴或 y 轴旋转。仅应缩放文本的高度。弧线必须使用回放设备上下文中的当前弧线方向绘制，但它们不得遵循当前的世界坐标到设备坐标变换，该变换可能需要沿 x 轴或 y 轴旋转。世界坐标到设备坐标的变换应仅通过更改窗口和视口的范围及原点来修改，使用 EMR_SETWINDOWEXTEX（第 2.3.11.30 节）和 EMR_SETVIEWPORTEXTEX（第 2.3.11.28 节）记录，以及 EMR_SETWINDOWORGEX（第 2.3.11.31 节）和 EMR_SETVIEWPORTORGEX（第 2.3.11.30 节）记录。直接使用 EMR_MODIFYWORLDTRANSFORM（第 2.3.12.1 节）或 EMR_SETWORLDTRANSFORM（第 2.3.12.2 节）记录更改变换可能不受支持。在 GM_COMPATIBLE 图形模式下，绘制矩形时必须排除底部和最右侧的边缘。 |
| GM_ADVANCED | `2` | TrueType 文本输出必须完全符合回放设备上下文中的当前世界坐标到设备坐标变换。弧线必须在世界空间中逆时针方向绘制；然而，弧线的控制点和弧线本身必须完全遵循回放设备上下文中的当前世界坐标到设备坐标变换。世界坐标到设备坐标的变换可以通过使用 EMR_MODIFYWORLDTRANSFORM 或 EMR_SETWORLDTRANSFORM 记录直接修改，也可以通过更改窗口和视口的范围及原点间接修改，使用 EMR_SETWINDOWEXTEX（第 2.3.11.30 节）和 EMR_SETVIEWPORTEXTEX（第 2.3.11.28 节）记录，以及 EMR_SETWINDOWORGEX（第 2.3.11.31 节）和 EMR_SETVIEWPORTORGEX（第 2.3.11.30 节）记录。在 GM_ADVANCED 图形模式下，绘制矩形时必须包含底部和最右侧的边缘。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


