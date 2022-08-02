---
title: HasAlpha
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene un valor que indica si esta instancia tiene alfa.
type: docs
weight: 80
url: /es/net/aspose.imaging.fileformats.webp/webpframeblock/hasalpha/
---
## WebPFrameBlock.HasAlpha property

Obtiene un valor que indica si esta instancia tiene alfa.

```csharp
public override bool HasAlpha { get; }
```

### El valor de la propiedad

`verdadero` si esta instancia tiene alfa; de lo contrario,`falso` .

### Ejemplos

El siguiente ejemplo carga una imagen WEBP e imprime información sobre el formato de datos sin procesar y el canal alfa.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Si el cuadro TIFF activo tiene canal alfa, se considera que toda la imagen TIFF tiene canal alfa.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, webpImage.RawDataFormat, webpImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Webp.IFrame frame in webpImage.Blocks)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock frameBlock = frame as Aspose.Imaging.FileFormats.Webp.WebPFrameBlock;
        if (frameBlock != null)
        {
            System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", i++, frameBlock.RawDataFormat, frameBlock.HasAlpha);
        }
    }
}

// La salida puede verse así:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False
```

### Ver también

* class [WebPFrameBlock](../../webpframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->