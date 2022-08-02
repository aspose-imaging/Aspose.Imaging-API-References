---
title: AdjustGamma
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Corrección gamma de una imagen.
type: docs
weight: 170
url: /es/net/aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/
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

El siguiente ejemplo realiza la corrección gamma de una imagen DJVU.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
    djvuImage.AdjustGamma(2.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [DjvuImage](../../djvuimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
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

El siguiente ejemplo realiza la corrección gamma de una imagen DJVU aplicando diferentes coeficientes para los componentes de color.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Establecer coeficientes gamma individuales para los canales rojo, verde y azul.
    djvuImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [DjvuImage](../../djvuimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->