---
title: UsePalette
second_title: Aspose.Imaging for .NET API 参考
description: 获取指示是否使用图像调色板的值
type: docs
weight: 150
url: /zh/net/aspose.imaging/image/usepalette/
---
## Image.UsePalette property

获取指示是否使用图像调色板的值。

```csharp
public virtual bool UsePalette { get; }
```

### 适当的价值

` true` 如果图像中使用了调色板；否则，` false` 。

### 例子

确定图像是否使用调色板。

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->