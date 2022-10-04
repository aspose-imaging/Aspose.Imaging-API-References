---
title: ColorType
second_title: Aspose.Imaging for .NET API Referansı
description: Rengin türünü alır veya ayarlar.
type: docs
weight: 20
url: /tr/net/aspose.imaging.imageoptions/dicomoptions/colortype/
---
## DicomOptions.ColorType property

Rengin türünü alır veya ayarlar.

```csharp
public ColorType ColorType { get; set; }
```

### Mülk değeri

Rengin türü.

### Örnekler

DICOM sıkıştırmasında Renk Türünü değiştirin.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

DICOM görüntüsünde RLE sıkıştırmasını kullanın.

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

DICOM görüntüsünde JPEG 2000 sıkıştırmasını kullanın.

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

DICOM görüntüsünde JPEG sıkıştırmasını kullanın.

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

### Ayrıca bakınız

* enum [ColorType](../../../aspose.imaging.fileformats.dicom/colortype)
* class [DicomOptions](../../dicomoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../dicomoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->