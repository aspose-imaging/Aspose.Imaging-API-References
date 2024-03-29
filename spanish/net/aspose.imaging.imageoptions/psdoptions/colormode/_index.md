---
title: ColorMode
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el modo de color psd.
type: docs
weight: 40
url: /es/net/aspose.imaging.imageoptions/psdoptions/colormode/
---
## PsdOptions.ColorMode property

Obtiene o establece el modo de color psd.

```csharp
public ColorModes ColorMode { get; set; }
```

### El valor de la propiedad

El modo de color.

### Ejemplos

Este ejemplo demuestra el uso de Aspsoe.Imaging for .Net API para convertir imágenes a formato PSD. Para lograr este objetivo, este ejemplo carga una imagen existente y luego la guarda de nuevo en formato PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

//Crea una instancia de la clase de imagen y la inicializa con un archivo existente a través de la ruta del archivo
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Crear una instancia de la clase PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //Establecer el método de compresión como RLE
    //Nota: Otro CompressionMethod admitido es CompressionMethod.RAW [Sin compresión]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    // Establezca el modo de color en escala de grises
    //Nota: Otros ColorModes admitidos son ColorModes.Bitmap y ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Guarde la imagen en la ubicación del disco con la configuración de PsdOptions suministrada
    image.Save(dir + "output.psd", psdOptions);
}
```

Este ejemplo muestra cómo guardar una imagen PNG en formato PSD usando varias opciones específicas de PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha))
{
    // Definir un degradado azul transparente lineal.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Rellena la imagen PNG con el degradado azul transparente lineal.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Las siguientes opciones se utilizarán para guardar la imagen PNG en formato PSD.
    Aspose.Imaging.ImageOptions.PsdOptions saveOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // El número de bits por canal
    saveOptions.ChannelBitsCount = 8;

    // El número de canales. Un canal para cada componente de color R,G,B,A
    saveOptions.ChannelsCount = 4;

    // El modo de color
    saveOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Rgb;

    // Sin compresión
    saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.Raw;

    // La versión por defecto es 6
    saveOptions.Version = 6;            

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.psd"))
    {
        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RAW compression: {0}", stream.Length);
    }

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.RLE.psd"))
    {
        // La compresión RLE permite reducir el tamaño de la imagen de salida
        saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.RLE;

        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RLE compression: {0}", stream.Length);
    }

    // La salida puede verse así:
    // El tamaño de la imagen PSD con compresión RAW: 40090
    // El tamaño de la imagen PSD con compresión RLE: 16185
}
```

### Ver también

* enum [ColorModes](../../../aspose.imaging.fileformats.psd/colormodes)
* class [PsdOptions](../../psdoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../psdoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
