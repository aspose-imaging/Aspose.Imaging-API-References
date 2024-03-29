---
title: CreateFrameFrom
second_title: Aspose.Imaging för .NET API-referens
description: Skapar ramen från specificeradtiffFrame använder det angivnaoptions . Pixeldata bevaras men konverteras till önskat format.
type: docs
weight: 30
url: /sv/net/aspose.imaging.fileformats.tiff/tiffframe/createframefrom/
---
## TiffFrame.CreateFrameFrom method

Skapar ramen från specificerad*tiffFrame* använder det angivna*options* . Pixeldata bevaras men konverteras till önskat format.

```csharp
public static TiffFrame CreateFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tiffFrame | TiffFrame | Tiff-ramen att skapa från. |
| options | TiffOptions | De nya alternativen att använda. |

### Returvärde

Den nyskapade ramen.

### Exempel

Följande exempel visar hur du skapar en gråskalekopia av en befintlig ram och lägger till den i en TIFF-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Skapa en permanent, inte temporär filkälla.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Den linjära gradienten från bildens övre vänstra hörn till det nedre högra hörnet.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fyll den aktiva ramen med en linjär gradientborste.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Alternativ för gråskala
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Skapa en gråskalekopia av den aktiva ramen.
    // Pixeldata bevaras men konverteras till önskat format.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Lägg till den nyskapade ramen till TIFF-bilden.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Se även

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
