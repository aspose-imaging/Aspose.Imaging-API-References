---
title: "类 EmfDesignVector"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfDesignVector 类。DesignVector 第 2.2.3 节对象定义设计向量，指定多主字体的字体轴值"
type: docs
weight: 3030
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
## EmfDesignVector class

DesignVector（第 2.2.3 节）对象定义了设计向量，用于指定多主字体的字体轴值。

```csharp
public sealed class EmfDesignVector : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfDesignVector](emfdesignvector/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [NumAxes](../../aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/numaxes/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 Values 数组的元素数量。它必须在 0 到 16（含）之间。 |
| [Signature](../../aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/signature/) { get; set; } | 获取或设置一个 32 位无符号整数，必须设置为值 0x08007664。 |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/values/) { get; set; } | 获取或设置一个可选的 32 位有符号整数数组，指定多主 OpenType 字体的字体轴值。数组中值的最大数量为 16。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


