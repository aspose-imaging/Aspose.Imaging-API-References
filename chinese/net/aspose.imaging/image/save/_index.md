---
title: Save
second_title: Aspose.Imaging for .NET API 参考
description: 将图像数据保存到底层流
type: docs
weight: 240
url: /zh/net/aspose.imaging/image/save/
---
## Save() {#save}

将图像数据保存到底层流。

```csharp
public void Save()
```

### 例子

以下示例显示如何将整个 BMP 图像或其中的一部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同的位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 调色板只包含两种颜色：在本例中为黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），每个像素分配 1 位就足够了。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到另一个位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 只保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流
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
//整个图像的大小，以字节为单位：24062
//图片中心部分的大小，以字节为单位：6046
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

将图像保存到指定的文件位置。

```csharp
public override void Save(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 保存图像的文件路径。 |

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| options | ImageOptionsBase | 选项。 |

### 例子

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

此示例显示了保存图像的简单步骤。为了演示此操作，我们从某个磁盘位置加载现有文件，对图像执行旋转操作并使用文件路径以 PSD 格式保存图像

```csharp
[C#]

string dir = "c:\\temp\\";

//创建一个image类的实例，并通过File path用已有的文件对其进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //将图像绕X轴旋转180度
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //使用默认 PsdOptions 设置将图像另存为 PSD 到文件路径
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

以下示例显示如何将整个 BMP 图像或其中的一部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同的位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 调色板只包含两种颜色：在本例中为黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），每个像素分配 1 位就足够了。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到另一个位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 只保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流
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
//整个图像的大小，以字节为单位：24062
//图片中心部分的大小，以字节为单位：6046
```

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| options | ImageOptionsBase | 选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。为使用源边界设置空矩形。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 选项 |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | 图片保存失败。 |

### 例子

以下示例从文件加载 BMP 图像，然后将图像的矩形部分保存到 PNG 文件中。

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

以下示例显示如何将整个 BMP 图像或其中的一部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同的位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 调色板只包含两种颜色：在本例中为黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），每个像素分配 1 位就足够了。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到另一个位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 只保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流
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
//整个图像的大小，以字节为单位：24062
//图片中心部分的大小，以字节为单位：6046
```

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

根据保存选项将图像的数据以指定的文件格式保存到指定的流中。

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 将图像数据保存到的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 选项库 |
| ArgumentException | 无法保存为指定的格式，因为目前不支持。;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | 图片导出失败。 |

### 例子

以下示例从文件加载图像，然后将图像保存到 PNG 文件流。

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

此示例显示将图像保存到 MemoryStream 的过程。为了演示此操作，示例从某个磁盘位置加载现有文件，对图像执行旋转操作并以 PSD 格式保存图像

```csharp
[C#]

//创建一个MemoryStream实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建一个image类的实例，并通过File path用已有的文件对其进行初始化
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //将图像绕X轴旋转180度
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //使用默认 PsdOptions 设置将图像作为 PSD 保存到 MemoryStream
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

以下示例显示如何将整个 BMP 图像或其中的一部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同的位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 调色板只包含两种颜色：在本例中为黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），每个像素分配 1 位就足够了。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到另一个位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 只保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流
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
//整个图像的大小，以字节为单位：24062
//图片中心部分的大小，以字节为单位：6046
```

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

根据保存选项将图像的数据以指定的文件格式保存到指定的流中。

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 将图像数据保存到的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。设置空矩形以使用源边界。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 选项库 |
| ArgumentException | 无法保存为指定的格式，因为目前不支持。;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | 图片导出失败。 |

### 例子

以下示例从文件加载图像，然后将图像的矩形部分保存到 PNG 文件流。

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

以下示例显示如何将整个 BMP 图像或其中的一部分保存到文件或流中。

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // 转换为黑白图像
    bmpImage.BinarizeOtsu();

    // 使用默认选项保存到相同的位置。
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 调色板只包含两种颜色：在本例中为黑色和白色。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // 对于所有单色图像（包括黑白图像），每个像素分配 1 位就足够了。
    saveOptions.BitsPerPixel = 1;

    // 使用指定选项保存到另一个位置。
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // 只保存图像的中心部分。
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // 将整个图像保存到内存流
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
//整个图像的大小，以字节为单位：24062
//图片中心部分的大小，以字节为单位：6046
```

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
