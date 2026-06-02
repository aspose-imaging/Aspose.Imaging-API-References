---
title: "TiffImage.PremultiplyComponents"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 属性。指示组件是否需要预乘，以确保对视觉元素的高效处理。通过切换此属性来提升渲染过程，简化图形工作流，实现性能优化。"
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/
---
## TiffImage.PremultiplyComponents property

指示组件是否需要预乘，以确保对视觉元素的高效处理。通过切换此属性来提升渲染过程，简化图形工作流，实现性能优化。

```csharp
public override bool PremultiplyComponents { get; set; }
```

### Property Value

`true` 表示组件必须预乘；否则为 `false`。

## 示例

以下示例创建一个新的 TIFF 图像，保存指定的半透明像素，然后加载这些像素并获取预乘形式的最终颜色。

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

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Create(createOptions, imageWidth, imageHeight))
{
    // 保存整幅图像的像素。
    image.SavePixels(image.Bounds, colors);

    // 像素以非预乘形式存储在原始图像中。
    // 需要显式指定相应选项以获取预乘颜色分量。
    // 预乘颜色分量通过以下公式计算：
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.PremultiplyComponents = true;
    Aspose.Imaging.Color[] premultipliedColors = image.LoadPixels(image.Bounds);

    for (int i = 0; i < colors.Length; i++)
    {
        System.Console.WriteLine("Original color: {0}", colors[i].ToString());
        System.Console.WriteLine("Premultiplied color: {0}", premultipliedColors[i].ToString());
    }
}

//输出将如下所示：
//原始颜色：Color [A=127, R=255, G=0, B=0]
//预乘颜色：Color [A=127, R=127, G=0, B=0]
//原始颜色：Color [A=127, R=0, G=255, B=0]
//预乘颜色：Color [A=127, R=0, G=127, B=0]
//原始颜色：Color [A=127, R=0, G=0, B=255]
//预乘颜色：Color [A=127, R=0, G=0, B=127]
//原始颜色：Color [A=127, R=255, G=255, B=0]
//预乘颜色：Color [A=127, R=127, G=127, B=0]
//原始颜色：Color [A=127, R=255, G=0, B=255]
//预乘颜色：Color [A=127, R=127, G=0, B=127]
//原始颜色：Color [A=127, R=0, G=255, B=255]
//预乘颜色：Color [A=127, R=0, G=127, B=127]
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


