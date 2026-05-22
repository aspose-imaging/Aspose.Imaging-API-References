---
title: "类 EmfPlusCustomLineCapOptionalData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusCustomLineCapOptionalData 类。EmfPlusCustomLineCapOptionalData 对象指定自定义线帽的可选填充和轮廓数据"
type: docs
weight: 5520
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
## EmfPlusCustomLineCapOptionalData class

EmfPlusCustomLineCapOptionalData 对象指定自定义线帽的可选填充和轮廓数据。

```csharp
public sealed class EmfPlusCustomLineCapOptionalData : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData](emfpluscustomlinecapoptionaldata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FillData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/filldata/) { get; set; } | 获取或设置可选的 EmfPlusFillPath 对象（第 2.2.2.17 节），该对象指定用于填充自定义图形线帽的路径。如果在 EmfPlusCustomLineCapData 对象的 CustomLineCapDataFlags 字段中设置了 CustomLineCapDataFillPath 标志，则此字段必须存在。 |
| [OutlineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/outlinedata/) { get; set; } | 获取或设置可选的 EmfPlusLinePath 对象（第 2.2.2.26 节），该对象指定用于描绘自定义图形线帽的路径。如果在 EmfPlusCustomLineCapData 对象的 CustomLineCapDataFlags 字段中设置了 CustomLineCapDataLinePath 标志，则此字段必须存在。 |

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


