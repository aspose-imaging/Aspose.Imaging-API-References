---
title: BufferSizeHint
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置缓冲区大小提示该提示定义了所有内部缓冲区的最大允许大小
type: docs
weight: 10
url: /zh/net/aspose.imaging/imageoptionsbase/buffersizehint/
---
## ImageOptionsBase.BufferSizeHint property

获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

```csharp
public int BufferSizeHint { get; set; }
```

### 适当的价值

缓冲区大小提示，以兆字节为单位。 非正值表示内部缓冲区没有内存限制

### 例子

以下示例显示如何设置内存创建新 JPEG 图像时的限制。内存限制是所有内部缓冲区的最大允许大小（以兆字节为单位）。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3383\\";

const int ImageSize = 2000;
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_simple.png", false);
createOptions.BufferSizeHint = 30;        // 内存限制为 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
        // 这里可以使用任何图形操作，都将在已建立的内存限制内执行
        // 例如：
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);
    graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 3f), 0, 0, image.Width, image.Height);

    image.Save();
}

    // 也支持大量的图形操作：
const int OperationAreaSize = 10;
createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_complex.png", false);
createOptions.BufferSizeHint = 30;        // 内存限制为 30 Mb

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

        // 这里会应用大约 40k 的操作，但不会占用太多内存 
    // 因为它们已经被卸载到外部文件中，并且会从那里一次加载一个
    graphics.EndUpdate();

    image.Save();
}
```

以下示例显示了在创建 PNG 图像并在其上绘制复杂图形时如何设置内存限制。内存限制是所有内部缓冲区的最大允许大小（以兆字节为单位）。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3383\\";

const int ImageSize = 2000;
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_simple.png", false);
createOptions.BufferSizeHint = 30;        // 内存限制为 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
        // 这里可以使用任何图形操作，都将在已建立的内存限制内执行
        // 例如：
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);
    graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 3f), 0, 0, image.Width, image.Height);

    image.Save();
}

    // 也支持大量的图形操作：
const int OperationAreaSize = 10;
createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_complex.png", false);
createOptions.BufferSizeHint = 30;        // 内存限制为 30 Mb

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

        // 这里会应用大约 40k 的操作，但不会占用太多内存 
    // 因为它们已经被卸载到外部文件中，并且会从那里一次加载一个
    graphics.EndUpdate();

    image.Save();
}
```

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* 命名空间 [Aspose.Imaging](../../imageoptionsbase)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->