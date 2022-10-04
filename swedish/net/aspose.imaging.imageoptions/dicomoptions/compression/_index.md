---
title: Compression
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in komprimeringen.
type: docs
weight: 30
url: /sv/net/aspose.imaging.imageoptions/dicomoptions/compression/
---
## DicomOptions.Compression property

Hämtar eller ställer in komprimeringen.

```csharp
public Compression Compression { get; set; }
```

### Fastighetsvärde

Kompressionen.

### Exempel

Ändra färgtyp i DICOM-komprimering.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Använd RLE-komprimering i DICOM-bild.

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

Använd JPEG 2000-komprimering i DICOM-bild.

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

Använd JPEG-komprimering i DICOM-bild.

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

### Se även

* class [Compression](../../../aspose.imaging.fileformats.dicom/compression)
* class [DicomOptions](../../dicomoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../dicomoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->