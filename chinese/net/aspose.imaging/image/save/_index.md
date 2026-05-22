---
title: "Image.Save"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。将图像数据保存到底层流中"
type: docs
weight: 310
url: /zh/net/aspose.imaging/image/save/
---
## Save() {#save}

将图像数据保存到底层流。

```csharp
public void Save()
```

## 示例

以下示例展示了如何将整个 BMP 图像或其部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 此情况下调色板仅包含两种颜色：黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），分配每像素 1 位即可。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到其他位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 仅保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // 将图像的中心部分保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//输出可能如下所示：
//整个图像的大小（字节）：24062
//图像中心部分的大小（字节）：6046
```

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

将图像保存到指定的文件位置。

```csharp
public override void Save(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 保存图像的文件路径。 |

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| 选项 | ImageOptionsBase | 选项。 |

## 示例

以下示例从文件加载 BMP 图像，然后将图像保存为 PNG 文件。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // 将整个图像保存为 PNG 文件。
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

本示例展示了保存图像的简易步骤。为演示此操作，我们从某磁盘位置加载现有文件，对图像执行旋转操作，并使用 File Path 将图像保存为 PSD 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

//通过 File path 创建 image 类的实例并使用现有文件进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //将图像绕 X 轴旋转 180 度
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //使用默认的 PsdOptions 设置将 Image 保存为 PSD 到 File Path
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

以下示例展示了如何将整个 BMP 图像或其部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 此情况下调色板仅包含两种颜色：黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），分配每像素 1 位即可。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到其他位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 仅保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // 将图像的中心部分保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//输出可能如下所示：
//整个图像的大小（字节）：24062
//图像中心部分的大小（字节）：6046
```

### 另请参见

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| 选项 | ImageOptionsBase | 选项。 |
| boundsRectangle | Rectangle | 目标图像的边界矩形。将空矩形设置为使用源边界。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 选项 |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | 图像保存失败。 |

## 示例

以下示例从文件加载 BMP 图像，然后将图像的矩形部分保存为 PNG 文件。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // 将图像的上半部分保存为 PNG 文件。
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

以下示例展示了如何将整个 BMP 图像或其部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 此情况下调色板仅包含两种颜色：黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），分配每像素 1 位即可。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到其他位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 仅保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // 将图像的中心部分保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//输出可能如下所示：
//整个图像的大小（字节）：24062
//图像中心部分的大小（字节）：6046
```

### 另请参见

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

根据保存选项，将图像数据以指定的文件格式保存到指定的流中。

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于保存图像数据的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 当前不支持指定的格式，无法保存。;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | 图像导出失败。 |

## 示例

以下示例从文件加载图像，然后将图像保存到 PNG 文件流中。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // 将整个图像保存到文件流中。
        image.Save(outputStream, saveOptions);
    }
}
```

此示例展示了将图像保存到 MemoryStream 的过程。为了演示此操作，示例从磁盘的某个位置加载现有文件，对图像执行旋转操作并以 PSD 格式保存图像。

```csharp
[C#]

//创建 MemoryStream 的实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //通过 File path 创建 image 类的实例并使用现有文件进行初始化
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //将图像绕 X 轴旋转 180 度
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //使用默认的 PsdOptions 设置将图像以 PSD 格式保存到 MemoryStream。
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

以下示例展示了如何将整个 BMP 图像或其部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 此情况下调色板仅包含两种颜色：黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），分配每像素 1 位即可。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到其他位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 仅保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // 将图像的中心部分保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//输出可能如下所示：
//整个图像的大小（字节）：24062
//图像中心部分的大小（字节）：6046
```

### 另请参见

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

根据保存选项，将图像数据以指定的文件格式保存到指定的流中。

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于保存图像数据的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |
| boundsRectangle | Rectangle | 目标图像的边界矩形。设置空矩形以使用源边界。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 当前不支持指定的格式，无法保存。;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | 图像导出失败。 |

## 示例

以下示例从文件加载图像，然后将图像的矩形部分保存到 PNG 文件流中。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // 将图像的上半部分保存到文件流中。
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

以下示例展示了如何将整个 BMP 图像或其部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 此情况下调色板仅包含两种颜色：黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），分配每像素 1 位即可。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到其他位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 仅保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // 将图像的中心部分保存到内存流中
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//输出可能如下所示：
//整个图像的大小（字节）：24062
//图像中心部分的大小（字节）：6046
```

### 另请参见

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


