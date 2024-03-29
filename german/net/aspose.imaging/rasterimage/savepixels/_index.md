---
title: SavePixels
second_title: Aspose.Imaging für .NET-API-Referenz
description: Speichert die Pixel.
type: docs
weight: 530
url: /de/net/aspose.imaging/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Speichert die Pixel.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck, in dem Pixel gespeichert werden sollen. |
| pixels | Color[] | Das Pixel-Array. |

### Beispiele

Im folgenden Beispiel wird der zentrale Bereich eines Rasterbilds mithilfe der Aspose.Imaging.RasterImage.SavePixels-Methode mit schwarzen Pixeln gefüllt.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Das schwarze Quadrat
    Color[] pixels = new Color[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black;
    }

    // Zeichnen Sie das schwarze Quadrat in der Mitte des Bildes.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SavePixels(area, pixels);

    rasterImage.Save(dir + "sample.SavePixels.png");
}
```

Dieses Beispiel zeigt, wie Pixelinformationen in ein Array vom Typ Color geladen, das Array manipuliert und wieder auf das Bild gesetzt wird. Um diese Vorgänge auszuführen, erstellt dieses Beispiel eine neue Bilddatei (im GIF-Format) mit dem MemoryStream-Objekt.

```csharp
[C#]

//Eine Instanz von MemoryStream erstellen
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstellen Sie eine Instanz von GifOptions und legen Sie ihre verschiedenen Eigenschaften einschließlich der Source-Eigenschaft fest
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Die Pixel des Bildes abrufen, indem der Bereich als Bildgrenze angegeben wird
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // Schleife über das Array und setzt die Farbe des alternativen indizierten Pixels
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Indizierte Pixelfarbe auf gelb setzen
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Indizierte Pixelfarbe auf Blau setzen
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        // Pixeländerungen auf das Bild anwenden
        image.SavePixels(image.Bounds, pixels);

        // Alle Änderungen speichern.
        image.Save();
    }

    // MemoryStream in Datei schreiben
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Siehe auch

* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* namensraum [Aspose.Imaging](../../rasterimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
