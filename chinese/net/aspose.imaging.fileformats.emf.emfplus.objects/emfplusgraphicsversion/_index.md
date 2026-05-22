---
title: "类 EmfPlusGraphicsVersion"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusGraphicsVersion 类。EmfPlusGraphicsVersion 对象指定用于创建 EMF 元文件的操作系统图形版本"
type: docs
weight: 5590
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
## EmfPlusGraphicsVersion class

EmfPlusGraphicsVersion 对象指定用于创建 EMF+ 元文件的操作系统图形版本。

```csharp
public sealed class EmfPlusGraphicsVersion : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusGraphicsVersion](emfplusgraphicsversion/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [GraphicsVersion](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/graphicsversion/) { get; set; } | 获取 GraphicsVersion（12 位）：操作系统图形的版本。此值必须在 `EmfPlusGraphicsVersion` 枚举中定义。 |
| [MetafileSignature](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/metafilesignature/) { get; set; } | 获取 MetafileSignature（20 位）：用于标识元文件类型的值。EMF+ 元文件的值为 0xDBC01。 |

## 备注

图形版本可由供应商扩展；但是，为确保互操作性，任何此类扩展必须在 EMF+ 元文件的客户端和服务器端都实现。

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


