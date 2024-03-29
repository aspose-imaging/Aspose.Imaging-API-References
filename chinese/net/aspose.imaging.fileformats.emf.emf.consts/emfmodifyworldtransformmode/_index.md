---
title: EmfModifyWorldTransformMode
second_title: Aspose.Imaging for .NET API 参考
description: ModifyWorldTransformMode 枚举定义使用指定变换数据的模式 修改当前在播放设备上下文中定义的世界空间到页面空间变换
type: docs
weight: 2770
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
## EmfModifyWorldTransformMode enumeration

ModifyWorldTransformMode 枚举定义使用指定变换数据的模式 修改当前在播放设备上下文中定义的世界空间到页面空间变换。

```csharp
public enum EmfModifyWorldTransformMode
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| MWT_IDENTITY | `1` | 使用单位矩阵重置当前变换。在这种模式下，指定的变换数据被忽略 |
| MWT_LEFTMULTIPLY | `2` | 乘以当前变换。在这种模式下，指定的变换数据是左被乘数， 当前在播放设备上下文中定义的变换是右被乘数 |
| MWT_RIGHTMULTIPLY | `3` | 乘以当前变换。在这种模式下，指定的变换数据是右被乘数 ，当前在播放设备上下文中定义的变换是左被乘数 |
| MWT_SET | `4` | 执行 EMR_SETWORLDTRANSFORM 记录的功能（第 2.3.12.2 节）。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
