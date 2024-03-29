---
title: SetResolution
second_title: Справочник по Aspose.Imaging for .NET API
description: Устанавливает разрешение для этогоRasterImageaspose.imaging/rasterimage .
type: docs
weight: 390
url: /ru/net/aspose.imaging.fileformats.tiff/tiffimage/setresolution/
---
## TiffImage.SetResolution method

Устанавливает разрешение для этого[`RasterImage`](../../../aspose.imaging/rasterimage) .

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | Double | Горизонтальное разрешение, в точках на дюйм,[`RasterImage`](../../../aspose.imaging/rasterimage). |
| dpiY | Double | Вертикальное разрешение, в точках на дюйм,[`RasterImage`](../../../aspose.imaging/rasterimage). |

### Примеры

В следующем примере показано, как установить горизонтальное/вертикальное разрешение изображения TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Получить горизонтальное и вертикальное разрешение TiffImage.
    double horizontalResolution = tiffImage.HorizontalResolution;
    double verticalResolution = tiffImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Используйте метод SetResolution для обновления обоих значений разрешения за один вызов.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        tiffImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", tiffImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", tiffImage.VerticalResolution);
    }
}
```

### Смотрите также

* class [TiffImage](../../tiffimage)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
