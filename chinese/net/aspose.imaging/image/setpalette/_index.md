---
title: "Image.SetPalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。设置图像调色板"
type: docs
weight: 320
url: /zh/net/aspose.imaging/image/setpalette/
---
## Image.SetPalette method

设置图像调色板。

```csharp
public abstract void SetPalette(IColorPalette palette, bool updateColors)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | IColorPalette | 要设置的调色板。 |
| updateColors | Boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能导致图像加载时崩溃。 |

### 另请参见

* interface [IColorPalette](../../icolorpalette/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


