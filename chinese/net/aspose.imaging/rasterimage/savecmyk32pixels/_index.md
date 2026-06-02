---
title: "RasterImage.SaveCmyk32Pixels"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。保存像素"
type: docs
weight: 590
url: /zh/net/aspose.imaging/rasterimage/savecmyk32pixels/
---
## RasterImage.SaveCmyk32Pixels method

保存像素。

```csharp
public void SaveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 用于保存像素的矩形区域。 |
| 像素 | Int32[] | CMYK 像素以 32 位整数值的形式呈现。 |

## 示例

以下示例使用 Aspose.Imaging.RasterImage.SaveCmyk32Pixels 方法在光栅图像的中心区域填充黑色像素。

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 获取黑色在 CMYK 颜色空间中的整数表示。
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // 黑色方块。
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // 在图像中心绘制黑色方块。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

### 另请参见

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


