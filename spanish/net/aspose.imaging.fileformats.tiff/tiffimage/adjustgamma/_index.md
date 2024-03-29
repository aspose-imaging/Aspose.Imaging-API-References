---
title: AdjustGamma
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Corrección gamma de una imagen.
type: docs
weight: 190
url: /es/net/aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

Corrección gamma de una imagen.

```csharp
public override void AdjustGamma(float gamma)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| gamma | Single | Gamma para coeficiente de canales rojo, verde y azul |

### Ejemplos

El siguiente ejemplo realiza la corrección gamma de una imagen TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
    tiffImage.AdjustGamma(2.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [TiffImage](../../tiffimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* asamblea [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

Corrección gamma de una imagen.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| gammaRed | Single | Gamma para coeficiente de canal rojo |
| gammaGreen | Single | Gamma para coeficiente de canal verde |
| gammaBlue | Single | Gamma para coeficiente de canal azul |

### Ejemplos

El siguiente ejemplo realiza la corrección gamma de una imagen TIFF aplicando diferentes coeficientes para los componentes de color.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Establecer coeficientes gamma individuales para los canales rojo, verde y azul.
    tiffImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [TiffImage](../../tiffimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
