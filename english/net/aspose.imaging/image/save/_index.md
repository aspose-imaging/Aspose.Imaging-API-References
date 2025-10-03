---
title: Image.Save
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Saves the image data to the underlying stream
type: docs
weight: 310
url: /net/aspose.imaging/image/save/
---
## Save() {#save}

Saves the image data to the underlying stream.

```csharp
public void Save()
```

## Examples

The following example shows how to save an entiree BMP image or part of it to a file or stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convert to a black-white image
    bmpImage.BinarizeOtsu();

    // Save to the same location with default options.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // A palette contains only two colors: Black and White in this case.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // For all monochrome images (including black-white ones) it is enough to allocate 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Save to another location with the specified options.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Save only the central part of the image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Save the entire image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Save the central part of the image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//The output may look like this:
//The size of the whole image in bytes: 24062
//The size of the central part of the image in bytes: 6046
```

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Saves the image to the specified file location.

```csharp
public override void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to save the image to. |

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Saves the object's data to the specified file location in the specified file format according to save options.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| options | ImageOptionsBase | The options. |

## Examples

The following example loads a BMP image from a file, then saves the image to a PNG file.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Save the entire image to a PNG file.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

This example shows the simple steps to Save an Image. To demonstrate this operation, we load an existing file from some disk location, performs Rotate operation on the image and Save the image in PSD format using File Path

```csharp
[C#]

string dir = "c:\\temp\\";

//Create an instance of image class and initialize it with an existing file through File path
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Rotate the image at 180 degree about X axis
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //Save the Image as PSD to File Path with default PsdOptions settings
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

The following example shows how to save an entiree BMP image or part of it to a file or stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convert to a black-white image
    bmpImage.BinarizeOtsu();

    // Save to the same location with default options.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // A palette contains only two colors: Black and White in this case.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // For all monochrome images (including black-white ones) it is enough to allocate 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Save to another location with the specified options.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Save only the central part of the image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Save the entire image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Save the central part of the image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//The output may look like this:
//The size of the whole image in bytes: 24062
//The size of the central part of the image in bytes: 6046
```

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Saves the object's data to the specified file location in the specified file format according to save options.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| options | ImageOptionsBase | The options. |
| boundsRectangle | Rectangle | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | options |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | Image saving failed. |

## Examples

The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Save the upper half of the image to a PNG file.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

The following example shows how to save an entiree BMP image or part of it to a file or stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convert to a black-white image
    bmpImage.BinarizeOtsu();

    // Save to the same location with default options.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // A palette contains only two colors: Black and White in this case.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // For all monochrome images (including black-white ones) it is enough to allocate 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Save to another location with the specified options.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Save only the central part of the image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Save the entire image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Save the central part of the image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//The output may look like this:
//The size of the whole image in bytes: 24062
//The size of the central part of the image in bytes: 6046
```

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Saves the image's data to the specified stream in the specified file format according to save options.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to save the image's data to. |
| optionsBase | ImageOptionsBase | The save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Cannot save to the specified format as it is not supported at the moment.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | Image export failed. |

## Examples

The following example loads an image from a file, then saves the image to a PNG file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Save the entire image to a file stream.
        image.Save(outputStream, saveOptions);
    }
}
```

This example shows the process of Saving an Image to MemoryStream. To demonstrate this operation, example loads an existing file from some disk location, performs Rotate operation on the image and Save the image in PSD format

```csharp
[C#]

//Create an instance of MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Create an instance of image class and initialize it with an existing file through File path
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //Rotate the image at 180 degree about X axis
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //Save the Image as PSD to MemoryStream with default PsdOptions settings
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

The following example shows how to save an entiree BMP image or part of it to a file or stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convert to a black-white image
    bmpImage.BinarizeOtsu();

    // Save to the same location with default options.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // A palette contains only two colors: Black and White in this case.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // For all monochrome images (including black-white ones) it is enough to allocate 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Save to another location with the specified options.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Save only the central part of the image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Save the entire image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Save the central part of the image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//The output may look like this:
//The size of the whole image in bytes: 24062
//The size of the central part of the image in bytes: 6046
```

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Saves the image's data to the specified stream in the specified file format according to save options.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to save the image's data to. |
| optionsBase | ImageOptionsBase | The save options. |
| boundsRectangle | Rectangle | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Cannot save to the specified format as it is not supported at the moment.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | Image export failed. |

## Examples

The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Save the upper half of the image to a file stream.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

The following example shows how to save an entiree BMP image or part of it to a file or stream.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convert to a black-white image
    bmpImage.BinarizeOtsu();

    // Save to the same location with default options.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // A palette contains only two colors: Black and White in this case.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // For all monochrome images (including black-white ones) it is enough to allocate 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Save to another location with the specified options.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Save only the central part of the image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Save the entire image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Save the central part of the image to a memory stream
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//The output may look like this:
//The size of the whole image in bytes: 24062
//The size of the central part of the image in bytes: 6046
```

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


