---
title: SetResolution
second_title: Aspose.Imaging für .NET-API-Referenz
description: Legt die Auflösung dafür festRasterImageaspose.imaging/rasterimage .
type: docs
weight: 390
url: /de/net/aspose.imaging.fileformats.tiff/tiffimage/setresolution/
---
## TiffImage.SetResolution method

Legt die Auflösung dafür fest[`RasterImage`](../../../aspose.imaging/rasterimage) .

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | Double | Die horizontale Auflösung in Punkten pro Zoll der[`RasterImage`](../../../aspose.imaging/rasterimage). |
| dpiY | Double | Die vertikale Auflösung in Punkten pro Zoll der[`RasterImage`](../../../aspose.imaging/rasterimage). |

### Beispiele

Das folgende Beispiel zeigt, wie die horizontale/vertikale Auflösung eines TIFF-Bildes eingestellt wird.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Horizontale und vertikale Auflösung des TiffImage abrufen.
    double horizontalResolution = tiffImage.HorizontalResolution;
    double verticalResolution = tiffImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        tiffImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", tiffImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", tiffImage.VerticalResolution);
    }
}
```

### Siehe auch

* class [TiffImage](../../tiffimage)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->