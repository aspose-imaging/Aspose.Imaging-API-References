---
title: Dither
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Esegue il dithering sullimmagine corrente.
type: docs
weight: 210
url: /it/net/aspose.imaging.fileformats.dicom/dicomimage/dither/
---
## DicomImage.Dither method

Esegue il dithering sull'immagine corrente.

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | Il metodo di dithering. |
| bitsCount | Int32 | I bit finali contano per il dithering. |
| customPalette | IColorPalette | La tavolozza personalizzata per il dithering. |

### Esempi

L'esempio seguente carica un'immagine DICOM ed esegue il dithering della soglia e del floyd utilizzando una diversa profondità della tavolozza.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Esegui il dithering della soglia utilizzando la tavolozza dei colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e la dimensione maggiore dell'immagine di output.
    // Si noti che al momento sono supportate solo le tavolozze a 1 bit, 4 bit e 8 bit.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Esegui il floyd dithering utilizzando la tavolozza dei colori a 1 bit che contiene solo 2 colori: bianco e nero.
    // Più bit sono specificati, maggiore è la qualità e la dimensione maggiore dell'immagine di output.
    // Si noti che al momento sono supportate solo le tavolozze a 1 bit, 4 bit e 8 bit.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [DicomImage](../../dicomimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
