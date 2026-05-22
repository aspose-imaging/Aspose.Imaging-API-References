---
title: "EpsImage.SetPalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EpsImage 方法。自定义图像调色板以实现独特的配色方案并提升视觉吸引力。针对特定效果调整颜色，并轻松在不同平台和设备上优化图像质量"
type: docs
weight: 190
url: /zh/net/aspose.imaging.fileformats.eps/epsimage/setpalette/
---
## EpsImage.SetPalette method

自定义图像调色板以实现独特的配色方案并提升视觉吸引力。轻松为特定效果调整颜色，并在不同平台和设备上优化图像质量。

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
| NotSupportedException | VectorImage 不支持此功能 |

### 另请参见

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)


