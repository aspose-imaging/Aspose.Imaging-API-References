---
title: "DicomOptions.ColorType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية DicomOptions. يحصل أو يضبط نوع اللون."
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/dicomoptions/colortype/
---
## DicomOptions.ColorType property

يحصل أو يضبط نوع اللون.

```csharp
public ColorType ColorType { get; set; }
```

### Property Value

نوع اللون.

## أمثلة

تغيير نوع اللون في ضغط DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

استخدام ضغط RLE في صورة DICOM.

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

استخدام ضغط JPEG 2000 في صورة DICOM.

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

استخدام ضغط JPEG في صورة DICOM.

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

### انظر أيضًا

* enum [ColorType](../../../aspose.imaging.fileformats.dicom/colortype/)
* class [DicomOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../dicomoptions/)
* assembly [Aspose.Imaging](../../../)


