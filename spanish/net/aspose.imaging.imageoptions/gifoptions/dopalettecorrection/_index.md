---
title: DoPaletteCorrection
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece un valor que indica si se aplica la corrección de paleta.
type: docs
weight: 50
url: /es/net/aspose.imaging.imageoptions/gifoptions/dopalettecorrection/
---
## GifOptions.DoPaletteCorrection property

Obtiene o establece un valor que indica si se aplica la corrección de paleta.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### El valor de la propiedad

`verdadero` si se aplica corrección de paleta; de lo contrario,`falso` .

### Observaciones

La corrección de paleta significa que cada vez que la imagen se exporta a GIF, los colores de la imagen de origen se analizarán para crear la paleta que mejor coincida (en caso de que la Paleta de imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algún tiempo, sin embargo, el la imagen de salida tendrá la mejor paleta de colores coincidentes y el resultado será visualmente mejor.

### Ejemplos

Este ejemplo muestra cómo guardar una imagen BMP en formato GIF usando varias opciones.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(1000, 1000))
{
    // Rellena toda la imagen con el degradado azul-amarillo.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(bmpImage);
    graphics.FillRectangle(gradientBrush, bmpImage.Bounds);

    Aspose.Imaging.ImageOptions.GifOptions saveOptions = new Aspose.Imaging.ImageOptions.GifOptions();

    // El número de bits necesarios para almacenar un color, menos 1.
    saveOptions.ColorResolution = 7;

    // La corrección de paleta significa que siempre que la imagen se exporte a GIF, se analizarán los colores de la imagen de origen
    // para construir la paleta que mejor coincida (en caso de que la Paleta de imagen no exista o no esté especificada en las opciones)
    saveOptions.DoPaletteCorrection = true;

    // Cargar una imagen GIF de forma progresiva.
    // Un GIF entrelazado no muestra sus líneas de exploración linealmente de arriba a abajo, sino que las reordena
    // para que el contenido del GIF se aclare incluso antes de que termine de cargarse.
    saveOptions.Interlaced = true;

    // Guardar como un GIF sin pérdidas.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossless GIF: {0} bytes.", stream.Length);
    }

    // Establecer la diferencia de píxeles máxima permitida. Si es mayor que cero, se utilizará la compresión con pérdida.
    // El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada.
    saveOptions.MaxDiff = 80;

    // Guardar como un GIF con pérdida.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.lossy.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossy GIF: {0} bytes.", stream.Length);
    }
}

//La salida puede verse así:
//El tamaño del GIF sin pérdidas: 212816 bytes.
// El tamaño del GIF con pérdida: 89726 bytes.
```

### Ver también

* class [GifOptions](../../gifoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../gifoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->