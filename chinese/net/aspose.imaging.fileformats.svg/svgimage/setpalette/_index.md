---
title: "SvgImage.SetPalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "SvgImage 方法。将指定的调色板应用于图像，实现对色彩方案的美观或功能性定制。此方法在管理色彩调色板以满足各种设计或应用需求方面提供了灵活性。"
type: docs
weight: 90
url: /zh/net/aspose.imaging.fileformats.svg/svgimage/setpalette/
---
## SvgImage.SetPalette method

将指定的调色板应用于图像，实现对色彩方案的美观或功能性定制。此方法在管理色彩调色板以满足各种设计或应用需求方面提供了灵活性。

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
* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)


