---
title: GetPixel
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene un pixel dellimmagine.
type: docs
weight: 330
url: /it/net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

Ottiene un pixel dell'immagine.

```csharp
public Color GetPixel(int x, int y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Int32 | La posizione del pixel x. |
| y | Int32 | La posizione del pixel y. |

### Valore di ritorno

Il colore del pixel per la posizione specificata.

### Esempi

L'esempio seguente carica un'immagine raster e ottiene il colore di un pixel arbitrario.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Ottieni il colore del pixel in alto a sinistra dell'immagine.
    Color color = rasterImage.GetPixel(0, 0);

    // Ottieni i valori dei singoli componenti del colore
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### Guarda anche

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
