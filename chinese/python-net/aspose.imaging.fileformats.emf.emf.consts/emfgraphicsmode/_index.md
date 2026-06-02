---
title: "EmfGraphicsMode 枚举"
type: docs
weight: 150
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

GraphicsMode 枚举用于指定如何解释形状数据，例如矩形坐标。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| GM_ADVANCED | TrueType 文本输出 必须完全符合播放设备上下文中的当前世界到设备的变换。<br/>            弧线 必须在世界空间中以逆时针方向绘制；然而，弧线控制点 <br/>            和弧线本身 必须完全遵守播放设备上下文中的当前世界到设备的变换。<br/>            可以直接使用 EMR_MODIFYWORLDTRANSFORM 或 <br/>            EMR_SETWORLDTRANSFORM 记录 来修改世界到设备的变换，或者通过更改窗口和视口的范围及原点间接修改，<br/>            使用 EMR_SETWINDOWEXTEX（第 2.3.11.30 节）和 EMR_SETVIEWPORTEXTEX（第 2.3.11.28 节）记录，<br/>            以及 EMR_SETWINDOWORGEX（第 2.3.11.31 节）和 EMR_SETVIEWPORTORGEX（第 2.3.11.30 节）记录，分别对应。<br/>            在 GM_ADVANCED 图形模式下，绘制矩形时 必须 包含底部和最右侧的边缘。 |
| GM_COMPATIBLE | TrueType 文本 必须从左到右、正向书写，即使其余图形 <br/>            因播放设备上下文中的当前世界到设备变换而围绕 x 轴或 y 轴旋转。只能对文本的高度进行缩放。弧线 必须使用播放设备上下文中的当前弧线方向绘制，但它们 必须 不遵循当前的世界到设备变换，因为该变换可能需要沿 x 轴或 y 轴旋转。<br/>            世界到设备的变换 应仅通过更改窗口和视口的范围及原点来修改，使用 EMR_SETWINDOWEXTEX（第 2.3.11.30 节）和 EMR_SETVIEWPORTEXTEX（第 2.3.11.28 节）记录，<br/>            以及 EMR_SETWINDOWORGEX（第 2.3.11.31 节）和 EMR_SETVIEWPORTORGEX（第 2.3.11.30 节）记录，分别对应。bChanging 直接使用 EMR_MODIFYWORLDTRANSFORM（第 2.3.12.1 节）或 EMR_SETWORLDTRANSFORM（第 2.3.12.2 节）记录 来更改变换 可能不受支持。<br/>            在 GM_COMPATIBLE 图形模式下，绘制矩形时 必须 排除底部和最右侧的边缘。 |
