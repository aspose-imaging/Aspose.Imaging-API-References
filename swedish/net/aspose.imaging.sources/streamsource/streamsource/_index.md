---
title: StreamSource
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avStreamSourceaspose.imaging.sources/streamsource class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Initierar en ny instans av[`StreamSource`](../../streamsource) class.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att öppna. |

### Exempel

Det här exemplet visar hur man laddar pixelinformation i en array av typfärg, manipulerar arrayen och återställer den till bilden. För att utföra dessa operationer skapar det här exemplet en ny bildfil (i GIF-format) med ett MemoryStream-objekt.

```csharp
[C#]

//Skapa en instans av MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Skapa en instans av GifOptions och ställ in dess olika egenskaper inklusive egenskapen Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Skapa en instans av bild
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Hämta pixlarna i bilden genom att ange området som bildgräns
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Slinga över Arrayen och ställer in färgen på alrenativt indexerad pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ställ in den indexerade pixelfärgen till gul
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Ställ in den indexerade pixelfärgen till blå
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Tillämpa pixeländringarna på bilden
        image.SavePixels(image.Bounds, pixels);

        // spara alla ändringar.
        image.Save();
    }

    // Skriv MemoryStream till fil
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Se även

* class [StreamSource](../../streamsource)
* namnutrymme [Aspose.Imaging.Sources](../../streamsource)
* hopsättning [Aspose.Imaging](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initierar en ny instans av[`StreamSource`](../../streamsource) class.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att öppna. |
| disposeStream | Boolean | om inställt på`Sann` strömmen kommer att avyttras. |

### Exempel

Det här exemplet visar användningen av System.IO.Stream för att skapa en ny bildfil (en JPEG-typ)

```csharp
[C#]

//Skapar en instans av JpegOptions och ställer in dess olika egenskaper
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Skapa en instans av System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Definiera källegenskapen för instansen av JpegOptions
//Den andra booleska parametern bestämmer om strömmen kasseras när den kommit utanför räckvidden
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//Skapar en instans av Image and call Create-metoden med JpegOptions som parameter för att initiera Image-objektet   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //gör lite bildbehandling
}
```

### Se även

* class [StreamSource](../../streamsource)
* namnutrymme [Aspose.Imaging.Sources](../../streamsource)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
