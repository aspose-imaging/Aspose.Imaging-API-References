---
title: ColorType
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el tipo de color.
type: docs
weight: 20
url: /es/net/aspose.imaging.imageoptions/dicomoptions/colortype/
---
## DicomOptions.ColorType property

Obtiene o establece el tipo de color.

```csharp
public ColorType ColorType { get; set; }
```

### El valor de la propiedad

El tipo de color.

### Ejemplos

Cambiar el tipo de color en la compresión DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Utilice la compresión RLE en la imagen DICOM.

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

Utilice la compresión JPEG 2000 en la imagen DICOM.

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

Utilice la compresión JPEG en la imagen DICOM.

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

### Ver también

* enum [ColorType](../../../aspose.imaging.fileformats.dicom/colortype)
* class [DicomOptions](../../dicomoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../dicomoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
