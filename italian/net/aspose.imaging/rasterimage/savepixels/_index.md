---
title: SavePixels
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Salva i pixel.
type: docs
weight: 530
url: /it/net/aspose.imaging/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Salva i pixel.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Il rettangolo in cui salvare i pixel. |
| pixels | Color[] | La matrice dei pixel. |

### Esempi

L'esempio seguente riempie l'area centrale di un'immagine raster con pixel neri usando il metodo Aspose.Imaging.RasterImage.SavePixels.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Il quadrato nero
    Color[] pixels = new Color[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black;
    }

    // Disegna il quadrato nero al centro dell'immagine.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SavePixels(area, pixels);

    rasterImage.Save(dir + "sample.SavePixels.png");
}
```

Questo esempio mostra come caricare le informazioni sui pixel in una matrice di tipo colore, manipolare la matrice e reimpostarla sull'immagine. Per eseguire queste operazioni, questo esempio crea un nuovo file immagine (in formato GIF) utilizzando l'oggetto MemoryStream.

```csharp
[C#]

//Crea un'istanza di MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea un'istanza di GifOptions e imposta le sue varie proprietà inclusa la proprietà Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crea un'istanza di Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Ottieni i pixel dell'immagine specificando l'area come limite dell'immagine
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Cicla sull'array e imposta il colore del pixel indicizzato alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Imposta il colore del pixel indicizzato su giallo
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Imposta il colore del pixel indicizzato su blu
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Applica le modifiche ai pixel all'immagine
        image.SavePixels(image.Bounds, pixels);

        // salva tutte le modifiche.
        image.Save();
    }

    // Scrivi MemoryStream su file
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Guarda anche

* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->