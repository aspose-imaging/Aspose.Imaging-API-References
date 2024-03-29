---
title: YOrigin
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece la coordenada vertical absoluta para la esquina inferior izquierda de la imagen tal como se coloca en un dispositivo de visualización que tiene un origen en la parte inferior izquierda de la pantalla p. ej. la serie TARGA.
type: docs
weight: 290
url: /es/net/aspose.imaging.fileformats.tga/tgaimage/yorigin/
---
## TgaImage.YOrigin property

Obtiene o establece la coordenada vertical absoluta para la esquina inferior izquierda de la imagen tal como se coloca en un dispositivo de visualización que tiene un origen en la parte inferior izquierda de la pantalla (p. ej., la serie TARGA).

```csharp
public ushort YOrigin { get; set; }
```

### Ejemplos

Actualización de propiedades públicas de la imagen TGA cargada.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Obtener valores de las propiedades públicas de la imagen TGA cargada.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### Ver también

* class [TgaImage](../../tgaimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
