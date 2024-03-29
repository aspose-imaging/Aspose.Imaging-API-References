---
title: DitheringMethod
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Metodo di dithering.
type: docs
weight: 840
url: /it/net/aspose.imaging/ditheringmethod/
---
## DitheringMethod enumeration

Metodo di dithering.

```csharp
public enum DitheringMethod
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ThresholdDithering | `0` | Soglia dithering. Algoritmo di dithering più semplice e veloce. |
| FloydSteinbergDithering | `1` | Il dithering di Floyd-Steinberg. Un algoritmo di dithering più complesso, utilizza i valori di intensità dei vicini più vicini. |

### Esempi

L'esempio seguente carica un'immagine raster ed esegue il dithering della soglia e del floyd utilizzando una diversa profondità della tavolozza.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Esegui il dithering della soglia utilizzando la tavolozza dei colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e la dimensione maggiore dell'immagine di output.
    // Si noti che al momento sono supportate solo le tavolozze a 1 bit, 4 bit e 8 bit.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Esegui il floyd dithering utilizzando la tavolozza dei colori a 1 bit che contiene solo 2 colori: bianco e nero.
    // Più bit sono specificati, maggiore è la qualità e la dimensione maggiore dell'immagine di output.
    // Si noti che al momento sono supportate solo le tavolozze a 1 bit, 4 bit e 8 bit.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
