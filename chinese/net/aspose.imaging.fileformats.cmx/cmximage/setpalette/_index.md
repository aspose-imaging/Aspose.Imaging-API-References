---
title: "CmxImage.SetPalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmxImage 方法。使用此直观方法自定义图像的颜色调色板。适用于希望动态应用特定配色方案或调整、确保对图像视觉外观进行精确控制的开发者。"
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.cmx/cmximage/setpalette/
---
## CmxImage.SetPalette method

使用此直观方法自定义图像的颜色调色板。适用于希望动态应用特定配色方案或调整的开发者，确保对图像视觉外观的精确控制。

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | IColorPalette | 要设置的调色板。 |
| updateColors | Boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能导致图像加载时崩溃。 |

### 另请参见

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [CmxImage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximage/)
* assembly [Aspose.Imaging](../../../)


