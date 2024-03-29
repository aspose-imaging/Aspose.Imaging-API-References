---
title: HasBackgroundColor
second_title: Aspose.Imaging för .NET API-referens
description: Får ett värde som anger om har bakgrundsfärg.
type: docs
weight: 60
url: /sv/net/aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/
---
## PngImage.HasBackgroundColor property

Får ett värde som anger om har bakgrundsfärg.

```csharp
public override bool HasBackgroundColor { get; set; }
```

### Exempel

Följande exempel visar hur du ställer in helt transparenta färger för en del av en TrueColor PNG-bild som inte stöder alfakanal.

```csharp
[C#]

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\transparent.png", false);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.Truecolor;

// Skapa en TrueColor PNG-bild på 100x100 px.
using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);

    // Alla röda pixlar kommer att betraktas som helt genomskinliga.
    pngImage.TransparentColor = Aspose.Imaging.Color.Red;
    pngImage.HasTransparentColor = true;

    // Alla genomskinliga pixlar kommer att ha en bakgrundsfärg.
    pngImage.BackgroundColor = Aspose.Imaging.Color.Green;
    pngImage.HasBackgroundColor = true;

    // Fyll hela bilden med vit färg.
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White), pngImage.Bounds);

    // Fyll den övre vänstra fjärdedelen av bilden med den genomskinliga färgen.
    // Detta gör den övre vänstra fjärdedelen färgad i bakgrundsfärgen.
    Rectangle rect = new Rectangle(0, 0, pngImage.Width / 2, pngImage.Height / 2);
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red), rect);

    pngImage.Save();
}
```

### Se även

* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
