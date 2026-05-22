---
title: "类 EmfPlusTextureBrushOptionalData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTextureBrushOptionalData 类。EmfPlusTextureBrushOptionalData 对象指定纹理画笔的可选数据"
type: docs
weight: 5940
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
## EmfPlusTextureBrushOptionalData class

EmfPlusTextureBrushOptionalData 对象指定纹理画刷的可选数据。

```csharp
public sealed class EmfPlusTextureBrushOptionalData : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusTextureBrushOptionalData](emfplustexturebrushoptionaldata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ImageObject](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/imageobject/) { get; set; } | 获取或设置可选的 EmfPlusImage 对象（第 2.2.1.4 节），指定画笔纹理。如果定义此纹理画笔的 EmfPlusObject 记录（第 2.3.5.1 节）的大小足以容纳除 EmfPlusTextureBrushData 对象的必需字段外的 EmfPlusImage 对象（以及可选的 EmfPlusTransformMatrix 对象），则此字段必须存在。 |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/transformmatrix/) { get; set; } | 获取或设置可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定纹理画笔的世界空间到设备空间的变换。如果在 EmfPlusTextureBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。 |

## 备注

注意：此对象的每个字段都是可选的，可能不会出现在 EmfPlusTextureBrushData 对象（第 2.2.2.45 节）的 OptionalData 字段中，这取决于其 BrushDataFlags 字段中设置的 BrushData 标志（第 2.1.2.1 节）。虽然不实际列举所有可能的字段出现或缺失的组合，但本节指定了它们在对象中的相对顺序。实现者需负责确定给定元文件记录中实际存在的字段，并对各字段的数据进行单独且适当的解组。

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


