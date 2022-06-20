---
title: HorizontalResolution
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает разрешение по горизонтали.
type: docs
weight: 90
url: /ru/net/aspose.imaging.fileformats.png/pngimage/horizontalresolution/
---
## PngImage.HorizontalResolution property

Получает или задает разрешение по горизонтали.

```csharp
public override double HorizontalResolution { get; set; }
```

### Примеры

В следующем примере показано, как установить горизонтальное/вертикальное разрешение изображения PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

     // Получить горизонтальное и вертикальное разрешение PngImage.
    double horizontalResolution = pngImage.HorizontalResolution;
    double verticalResolution = pngImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
         // Используйте метод SetResolution для обновления обоих значений разрешения в одном вызове.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        pngImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", pngImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", pngImage.VerticalResolution);
    }
}
```

### Смотрите также

* class [PngImage](../../pngimage)
* пространство имен [Aspose.Imaging.FileFormats.Png](../../pngimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->