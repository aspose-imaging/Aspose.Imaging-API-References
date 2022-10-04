---
title: SaveCmyk32Pixels
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Salva i pixel.
type: docs
weight: 520
url: /it/net/aspose.imaging/rasterimage/savecmyk32pixels/
---
## RasterImage.SaveCmyk32Pixels method

Salva i pixel.

```csharp
public void SaveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Il rettangolo in cui salvare i pixel. |
| pixels | Int32[] | I pixel CMYK presentati come valori interi a 32 bit. |

### Esempi

L'esempio seguente riempie l'area centrale di un'immagine raster con pixel neri usando il metodo Aspose.Imaging.RasterImage.SaveCmyk32Pixels.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Ottieni una rappresentazione intera del nero nello spazio colore CMYK.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // Il quadrato nero.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Disegna il quadrato nero al centro dell'immagine.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

### Guarda anche

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->