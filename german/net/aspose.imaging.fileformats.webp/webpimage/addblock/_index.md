---
title: AddBlock
second_title: Aspose.Imaging für .NET-API-Referenz
description: Fügt einen neuen Webp-Block hinzu.
type: docs
weight: 80
url: /de/net/aspose.imaging.fileformats.webp/webpimage/addblock/
---
## WebPImage.AddBlock method

Fügt einen neuen Webp-Block hinzu.

```csharp
public void AddBlock(IFrame block)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| block | IFrame | Der hinzuzufügende Webp-Block. |

### Beispiele

Dieses Beispiel zeigt, wie Sie mit den angegebenen Optionen ein animiertes WebP-Bild mit mehreren Frames erstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Der Standardframe plus 36 + 36 zusätzliche Frames.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Erstellen Sie ein WebP-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Der erste Kreis ist rot
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Der zweite Kreis ist schwarz
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Erhöhen Sie allmählich den Winkel der roten Bogenform.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Erhöhen Sie allmählich den Winkel des schwarzen Bogens und löschen Sie den roten Bogen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // In einer WebP-Datei speichern
    webPImage.Save(dir + "output.webp");
}
```

### Siehe auch

* interface [IFrame](../../iframe)
* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
