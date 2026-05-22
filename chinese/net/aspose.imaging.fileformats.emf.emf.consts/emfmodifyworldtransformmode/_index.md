---
title: "枚举 EmfModifyWorldTransformMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfModifyWorldTransformMode 枚举。ModifyWorldTransformMode 枚举定义了使用指定的变换数据来修改当前在回放设备上下文中定义的世界空间到页面空间变换的模式"
type: docs
weight: 2860
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
## EmfModifyWorldTransformMode enumeration

该 ModifyWorldTransformMode 枚举定义了使用指定的变换数据来修改当前在回放设备上下文中定义的世界空间到页面空间变换的模式。

```csharp
public enum EmfModifyWorldTransformMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| MWT_IDENTITY | `1` | 使用单位矩阵重置当前变换。在此模式下，指定的变换数据将被忽略 |
| MWT_LEFTMULTIPLY | `2` | 对当前变换进行相乘。在此模式下，指定的变换数据为左乘数，而当前在回放设备上下文中定义的变换为右乘数 |
| MWT_RIGHTMULTIPLY | `3` | 对当前变换进行相乘。在此模式下，指定的变换数据为右乘数，而当前在回放设备上下文中定义的变换为左乘数 |
| MWT_SET | `4` | 执行 EMR_SETWORLDTRANSFORM 记录的功能（第 2.3.12.2 节）。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


