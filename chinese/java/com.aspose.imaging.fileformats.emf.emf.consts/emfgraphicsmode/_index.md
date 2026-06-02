---
title: "EmfGraphicsMode"
second_title: "Aspose.Imaging for Java API 参考文档"
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
| [GM_COMPATIBLE](#GM-COMPATIBLE) | TrueType 文本 必须 从左到右、正向书写，即使其余图形因播放设备上下文中的当前世界到设备变换而围绕 x 轴或 y 轴旋转。 |
| [GM_ADVANCED](#GM-ADVANCED) | TrueType 文本输出 必须 完全符合播放设备上下文中的当前世界到设备变换。 |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


TrueType 文本 必须 从左到右、正向书写，即使其余图形因播放设备上下文中的当前世界到设备变换而围绕 x 轴或 y 轴旋转。文本的高度 应该 进行缩放。弧线 必须 使用播放设备上下文中的当前弧线方向绘制，但它们 必须 不遵循当前的世界到设备变换，因为该变换可能需要沿 x 轴或 y 轴旋转。世界到设备变换 应该 仅通过更改窗口和视口的范围及原点来修改，使用 EMR\_SETWINDOWEXTEX（section 2.3.11.30）和 EMR\_SETVIEWPORTEXTEX（section 2.3.11.28）记录，以及 EMR\_SETWINDOWORGEX（section 2.3.11.31）和 EMR\_SETVIEWPORTORGEX（section 2.3.11.30）记录，分别。bChanging 转换 直接 使用 EMR\_MODIFYWORLDTRANSFORM（section 2.3.12.1）或 EMR\_SETWORLDTRANSFORM（section 2.3.12.2）记录 可能 不受支持。在 GM\_COMPATIBLE 图形模式下，绘制矩形时 必须 排除底部和最右侧的边缘。

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


TrueType 文本输出 必须 完全符合播放设备上下文中的当前世界到设备变换。弧线 必须 在世界空间中逆时针方向绘制；然而，弧线的控制点和弧线本身 必须 完全遵循播放设备上下文中的当前世界到设备变换。世界到设备变换 可以 直接使用 EMR\_MODIFYWORLDTRANSFORM 或 EMR\_SETWORLDTRANSFORM 记录进行修改，或通过更改窗口和视口的范围及原点间接修改，使用 EMR\_SETWINDOWEXTEX（section 2.3.11.30）和 EMR\_SETVIEWPORTEXTEX（section 2.3.11.28）记录，以及 EMR\_SETWINDOWORGEX（section 2.3.11.31）和 EMR\_SETVIEWPORTORGEX（section 2.3.11.30）记录，分别。在 GM\_ADVANCED 图形模式下，绘制矩形时 底部和最右侧的边缘 必须 包含。

