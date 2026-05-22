---
title: "EmfModifyWorldTransformMode 枚举"
type: docs
weight: 240
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---

ModifyWorldTransformMode 枚举定义了使用指定的变换数据<br/>            来修改当前在回放设备上下文中定义的世界空间到页面空间变换的模式。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfModifyWorldTransformMode

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| MWT_IDENTITY | 使用单位矩阵重置当前变换。在此模式下，指定的变换数据将被忽略。 |
| MWT_LEFTMULTIPLY | 对当前变换进行相乘。在此模式下，指定的变换数据为左乘子，<br/>            当前在回放设备上下文中定义的变换为右乘子。 |
| MWT_RIGHTMULTIPLY | 将当前变换相乘。在此模式下，指定的变换数据是右乘数，<br/>            并且在播放设备上下文中当前定义的变换是左乘数 |
| MWT_SET | 执行 EMR_SETWORLDTRANSFORM 记录的功能（第 2.3.12.2 节）。 |
