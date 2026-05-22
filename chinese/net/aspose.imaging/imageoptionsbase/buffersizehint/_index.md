---
title: "ImageOptionsBase.BufferSizeHint"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageOptionsBase 属性。获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。"
type: docs
weight: 10
url: /zh/net/aspose.imaging/imageoptionsbase/buffersizehint/
---
## ImageOptionsBase.BufferSizeHint property

获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

```csharp
public int BufferSizeHint { get; set; }
```

### Property Value

缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制

## 示例

以下示例展示了在创建新的 JPEG 图像时如何设置内存限制。内存限制是所有内部缓冲区的最大允许大小（以兆字节为单位）。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// 为目标创建的图像设置 50 兆字节的内存限制
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.JpegOptions
{
    CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive,
    BufferSizeHint = 50,
    Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "createdFile.jpg", false),
};
    
using (var image = Aspose.Imaging.Image.Create(createOptions, 1000, 1000))
{
    image.Save(); // save to same location
}
```

以下示例展示了在创建 PNG 图像并在其上绘制复杂图形时如何设置内存限制。内存限制是所有内部缓冲区的最大允许大小（以兆字节为单位）。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3383\\";

const int ImageSize = 2000;
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_simple.png", false);
createOptions.BufferSizeHint = 30; // Memory limit is 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    // 您可以在此使用任何图形操作，所有操作都将在已设定的内存限制内执行
    // 例如：
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);
    graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 3f), 0, 0, image.Width, image.Height);

    image.Save();
}

// 也支持大量图形操作：
const int OperationAreaSize = 10;
createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_complex.png", false);
createOptions.BufferSizeHint = 30; // Memory limit is 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.BeginUpdate();
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);

    int x, y;
    int numberOfOperations = 0;
    for (int column = 0; column * OperationAreaSize < ImageSize; column++)
    {
        for (int row = 0; row * OperationAreaSize < ImageSize; row++)
        {
            x = column * OperationAreaSize;
            y = row * OperationAreaSize;

            bool reversed = (column + row) % 2 != 0;
            if (reversed)
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x + OperationAreaSize - 2,
                    y,
                    x,
                    y + OperationAreaSize);
            }
            else
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x,
                    y,
                    x + OperationAreaSize - 2,
                    y + OperationAreaSize);
            }

            numberOfOperations++;
        }
    }

    // 这里将执行约 40k 次操作，但它们不会占用太多内存
    // 因为它们已被卸载到外部文件，并将一次从中加载一个
    graphics.EndUpdate();

    image.Save();
}
```

### 另请参见

* class [ImageOptionsBase](../)
* namespace [Aspose.Imaging](../../imageoptionsbase/)
* assembly [Aspose.Imaging](../../../)


