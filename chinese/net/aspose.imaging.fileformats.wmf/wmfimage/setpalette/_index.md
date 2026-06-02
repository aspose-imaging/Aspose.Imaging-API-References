---
title: "WmfImage.SetPalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WmfImage 方法。将指定的调色板应用于图像，以实现颜色表示的自定义。利用此方法提升视觉渲染效果，并在您的应用程序中实现特定的颜色效果。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.wmf/wmfimage/setpalette/
---
## WmfImage.SetPalette method

对图像应用指定的调色板，以实现颜色表示的自定义。使用此方法提升视觉渲染效果，并在您的应用程序中实现特定的颜色效果。

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | IColorPalette | 要设置的调色板。 |
| updateColors | Boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能导致图像加载时崩溃。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| NotImplementedException |  |

### 另请参见

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


