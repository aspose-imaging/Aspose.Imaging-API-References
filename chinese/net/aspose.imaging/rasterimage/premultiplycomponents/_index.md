---
title: "RasterImage.PremultiplyComponents"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 属性。获取或设置一个值，指示是否必须对图像组件进行预乘"
type: docs
weight: 60
url: /zh/net/aspose.imaging/rasterimage/premultiplycomponents/
---
## RasterImage.PremultiplyComponents property

获取或设置一个值，指示图像组件是否必须预乘。

```csharp
public virtual bool PremultiplyComponents { get; set; }
```

### Property Value

如果必须对图像组件进行预乘，则为 `true`；否则为 `false`。

## 示例

以下示例创建一个新的光栅图像，保存指定的半透明像素，然后加载这些像素并以预乘形式获取最终颜色。

```csharp
[C#]

int imageWidth = 3;
int imageHeight = 2;

Aspose.Imaging.Color[] colors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 255, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 255),
};

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, imageWidth, imageHeight))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 保存整幅图像的像素。
    rasterImage.SavePixels(rasterImage.Bounds, colors);

    // 像素以非预乘形式存储在原始图像中。
    // 需要显式指定相应选项以获取预乘颜色分量。
    // 预乘颜色分量通过以下公式计算：
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    rasterImage.PremultiplyComponents = true;
    Aspose.Imaging.Color[] premultipliedColors = rasterImage.LoadPixels(rasterImage.Bounds);

    for (int i = 0; i < colors.Length; i++)
    {
        System.Console.WriteLine("Original color: {0}", colors[i].ToString());
        System.Console.WriteLine("Premultiplied color: {0}", premultipliedColors[i].ToString());
    }
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


