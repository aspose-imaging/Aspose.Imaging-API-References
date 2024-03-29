---
title: ActiveFrame
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den aktiven Frame ab oder setzt ihn.
type: docs
weight: 20
url: /de/net/aspose.imaging.fileformats.tiff/tiffimage/activeframe/
---
## TiffImage.ActiveFrame property

Ruft den aktiven Frame ab oder setzt ihn.

```csharp
public TiffFrame ActiveFrame { get; set; }
```

### Eigentumswert

Aktiver Rahmen.

### Beispiele

Das folgende Beispiel zeigt, wie aus einzelnen Rasterbildern ein mehrseitiges TIFF zusammengesetzt wird.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Dies ist Schriftart und Pinsel zum Zeichnen von Text auf einzelnen Rahmen.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // 5 Frames erstellen
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Erstellen Sie ein PNG-Bild und zeichnen Sie die Seitenzahl darauf.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Erstellen Sie einen Rahmen basierend auf dem PNG-Bild.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Rahmen zum TIFF-Bild hinzufügen.
        tiffImage.AddFrame(frame);
    }

    // Das Bild wurde mit einem einzelnen Standardrahmen erstellt. Entfernen wir es.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // Vergessen Sie nicht, den Rahmen zu entsorgen, wenn Sie ihn keinem anderen TiffImage hinzufügen
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### Siehe auch

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
