---
title: Dither
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Esegue il dithering sullimmagine corrente.
type: docs
weight: 260
url: /it/net/aspose.imaging/rasterimage/dither/
---
## Dither(DitheringMethod, int, IColorPalette) {#dither_1}

Esegue il dithering sull'immagine corrente.

```csharp
public abstract void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | Il metodo di dithering. |
| bitsCount | Int32 | I bit finali contano per il dithering. |
| customPalette | IColorPalette | La tavolozza personalizzata per il dithering. |

### Guarda anche

* enum [DitheringMethod](../../ditheringmethod)
* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

---

## Dither(DitheringMethod, int) {#dither}

Esegue il dithering sull'immagine corrente.

```csharp
public void Dither(DitheringMethod ditheringMethod, int bitsCount)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | Il metodo di dithering. |
| bitsCount | Int32 | I bit finali contano per il dithering. |

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

* enum [DitheringMethod](../../ditheringmethod)
* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
