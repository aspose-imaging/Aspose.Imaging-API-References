---
title: "Image.UsePalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 属性。获取一个值，指示是否使用图像调色板"
type: docs
weight: 170
url: /zh/net/aspose.imaging/image/usepalette/
---
## Image.UsePalette property

获取一个值，指示是否使用图像调色板。

```csharp
public virtual bool UsePalette { get; }
```

### Property Value

`true` 如果在图像中使用调色板；否则，`false`。

## 示例

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

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


