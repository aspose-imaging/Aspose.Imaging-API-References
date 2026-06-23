---
title: "EmfGraphicsMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "GraphicsMode 枚举用于指定如何解释形状数据，例如矩形坐标。"
type: docs
weight: 24
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

GraphicsMode 枚举用于指定如何解释形状数据，例如矩形坐标。
## 字段

| 字段 | 描述 |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | TrueType 文本必须从左到右、正面向上书写，即使由于播放设备上下文中的当前世界到设备变换，其他图形围绕 x 轴或 y 轴旋转。 |
| [GM_ADVANCED](#GM-ADVANCED) | TrueType 文本输出必须完全符合播放设备上下文中的当前世界到设备变换。 |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


TrueType 文本必须从左到右、正面向上书写，即使由于播放设备上下文中的当前世界到设备变换，其他图形围绕 x 轴或 y 轴旋转。仅应缩放文本的高度。弧线必须使用播放设备上下文中的当前弧线方向绘制，但它们不得遵循当前的世界到设备变换，因为该变换可能需要沿 x 轴或 y 轴旋转。世界到设备变换应仅通过更改窗口和视口的范围及原点来修改，使用 EMR\_SETWINDOWEXTEX（第 2.3.11.30 节）和 EMR\_SETVIEWPORTEXTEX（第 2.3.11.28 节）记录，以及 EMR\_SETWINDOWORGEX（第 2.3.11.31 节）和 EMR\_SETVIEWPORTORGEX（第 2.3.11.30 节）记录，分别。bChanging 直接使用 EMR\_MODIFYWORLDTRANSFORM（第 2.3.12.1 节）或 EMR\_SETWORLDTRANSFORM（第 2.3.12.2 节）记录可能不受支持。在 GM\_COMPATIBLE 图形模式下，绘制矩形时必须排除底部和最右侧的边缘。

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


TrueType 文本输出必须完全符合播放设备上下文中的当前世界到设备变换。弧线必须在世界空间中以逆时针方向绘制；然而，弧线的控制点和弧线本身必须完全遵循播放设备上下文中的当前世界到设备变换。世界到设备变换可以通过使用 EMR\_MODIFYWORLDTRANSFORM 或 EMR\_SETWORLDTRANSFORM 记录直接修改，或通过更改窗口和视口的范围及原点间接修改，使用 EMR\_SETWINDOWEXTEX（第 2.3.11.30 节）和 EMR\_SETVIEWPORTEXTEX（第 2.3.11.28 节）记录，以及 EMR\_SETWINDOWORGEX（第 2.3.11.31 节）和 EMR\_SETVIEWPORTORGEX（第 2.3.11.30 节）记录，分别。在 GM\_ADVANCED 图形模式下，绘制矩形时必须包含底部和最右侧的边缘。

