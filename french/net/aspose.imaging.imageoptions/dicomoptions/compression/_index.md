---
title: Compression
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit la compression.
type: docs
weight: 30
url: /fr/net/aspose.imaging.imageoptions/dicomoptions/compression/
---
## DicomOptions.Compression property

Obtient ou définit la compression.

```csharp
public Compression Compression { get; set; }
```

### Valeur de la propriété

La compression.

### Exemples

Modifier le type de couleur dans la compression DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Utilisez la compression RLE dans l'image DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

Utilisez la compression JPEG 2000 dans l'image DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

Utilisez la compression JPEG dans l'image DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

### Voir également

* class [Compression](../../../aspose.imaging.fileformats.dicom/compression)
* class [DicomOptions](../../dicomoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../dicomoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
