---
title: "类 EmfGradientRectangle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfGradientRectangle 类。GradientRectangle 对象使用 TriVertex 对象（第 2.2.26 节）在 EMR_GRADIENTFILL 记录（第 2.3.5.12 节）中定义一个矩形。"
type: docs
weight: 3060
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---
## EmfGradientRectangle class

GradientRectangle 对象使用 TriVertex 对象（第 2.2.26 节）在 EMR_GRADIENTFILL 记录（第 2.3.5.12 节）中定义矩形。

```csharp
public sealed class EmfGradientRectangle : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfGradientRectangle](emfgradientrectangle/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [LowerRight](../../aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/lowerright/) { get; set; } | 获取或设置指向 TriVertex 对象数组的索引，以指定矩形的右下顶点。该索引必须小于数组的大小，大小由 EMR_GRADIENTFILL 记录的 nVer 字段定义。 |
| [UpperLeft](../../aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/upperleft/) { get; set; } | 获取或设置指向 TriVertex 对象数组的索引，以指定矩形的左上顶点。该索引必须小于数组的大小，大小由 EMR_GRADIENTFILL 记录的 nVer 字段定义。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


