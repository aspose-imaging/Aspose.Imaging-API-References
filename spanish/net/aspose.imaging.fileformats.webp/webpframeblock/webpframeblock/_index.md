---
title: WebPFrameBlock
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delWebPFrameBlockaspose.imaging.fileformats.webp/webpframeblock
type: docs
weight: 10
url: /es/net/aspose.imaging.fileformats.webp/webpframeblock/webpframeblock/
---
## WebPFrameBlock(RasterImage) {#constructor}

Inicializa una nueva instancia del[`WebPFrameBlock`](../../webpframeblock)

clase.

```csharp
public WebPFrameBlock(RasterImage rasterImage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen de trama. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPFrameBlock](../../webpframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## WebPFrameBlock(int, int) {#constructor_1}

Inicializa una nueva instancia del[`WebPFrameBlock`](../../webpframeblock) clase.

```csharp
public WebPFrameBlock(int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | La anchura. |
| height | Int32 | La altura. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen WebP animada de varios fotogramas con las opciones especificadas.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// El marco predeterminado más 36 + 36 marcos adicionales.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Crea una imagen WebP de 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // El primer circulo es rojo
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // El segundo circulo es negro
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente el ángulo de la forma del arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Aumenta gradualmente el ángulo del arco negro y borra el arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Guardar en un archivo WebP
    webPImage.Save(dir + "output.webp");
}
```

### Ver también

* class [WebPFrameBlock](../../webpframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
