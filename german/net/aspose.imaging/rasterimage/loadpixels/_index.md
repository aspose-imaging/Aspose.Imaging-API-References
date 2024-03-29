---
title: LoadPixels
second_title: Aspose.Imaging für .NET-API-Referenz
description: Lädt Pixel.
type: docs
weight: 410
url: /de/net/aspose.imaging/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

Lädt Pixel.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck, aus dem Pixel geladen werden sollen. |

### Rückgabewert

Das geladene Pixelarray.

### Beispiele

Das folgende Beispiel zeigt, wie Pixel eines Rasterbilds geladen und verarbeitet werden. Betrachten wir zum Beispiel ein Problem des Zählens von vollständig transparenten Pixeln eines Bildes.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Pixel für das ganze Bild laden. Jeder rechteckige Teil des Bildes kann als Parameter der Aspose.Imaging.RasterImage.LoadPixels-Methode angegeben werden.
    Color[] pixels = rasterImage.LoadPixels(rasterImage.Bounds);

    int count = 0;
    foreach (Color pixel in pixels)
    {
        if (pixel.A == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
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

* struct [Color](../../color)
* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* namensraum [Aspose.Imaging](../../rasterimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
