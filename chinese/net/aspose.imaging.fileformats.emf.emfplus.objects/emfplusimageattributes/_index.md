---
title: "类 EmfPlusImageAttributes"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusImageAttributes 类。EmfPlusImageAttributes 对象指定在渲染期间如何操作位图图像的颜色。"
type: docs
weight: 5630
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
## EmfPlusImageAttributes class

EmfPlusImageAttributes 对象指定在渲染过程中如何操作位图图像的颜色。

```csharp
public sealed class EmfPlusImageAttributes : EmfPlusGraphicsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusImageAttributes](emfplusimageattributes/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ClampArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/clampargb32color/) { get; set; } | 获取或设置 EmfPlusARGB（章节 2.2.2.1）对象，该对象指定当 WrapMode 值为 WrapModeClamp 时使用的边缘颜色。当 EmfPlusDrawImage（章节 2.3.4.8）记录处理的源矩形大于图像本身时，此颜色可见。 |
| [ObjectClamp](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/objectclamp/) { get; set; } | 获取或设置 32 位有符号整数，指定对象的夹紧行为。该值在对象应用于正在绘制的图像之前不会使用。此值必须是下表中定义的值之一。 |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | 获取或设置版本。 |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/wrapmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定使用 WrapMode 枚举（章节 2.1.1.34）中的值来处理边缘条件的方式。 |

### 另请参见

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


