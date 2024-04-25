---
title: Compression
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene la compresión de la imagen.
type: docs
weight: 40
url: /es/aspose.imaging.fileformats.bmp/bmpimage/compression/
---
## BmpImage.Compression property

Obtiene la compresión de la imagen.

```csharp
public BitmapCompression Compression { get; }
```

### El valor de la propiedad

La compresión de la imagen.

### Ejemplos

El siguiente ejemplo obtiene la información general sobre la imagen, incluido el formato de píxeles, el tamaño de la imagen, la resolución, la compresión, etc.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;                

    System.Console.WriteLine("The pixel format: {0}", bmpImage.RawDataFormat);                
    System.Console.WriteLine("The raw line size in bytes: {0}", bmpImage.RawLineSize);
    System.Console.WriteLine("The bitmap compression: {0}", bmpImage.Compression);
    System.Console.WriteLine("The bitmap width: {0}", bmpImage.Width);
    System.Console.WriteLine("The bitmap height: {0}", bmpImage.Height);
    System.Console.WriteLine("The number of bits per pixel: {0}", bmpImage.BitsPerPixel);

    double hres = bmpImage.HorizontalResolution;
    double vres = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", hres);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", vres);

    if (hres != 96.0 || vres != 96.0)
    {
        // Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //La salida puede verse así:
    //El formato de píxel: Rgb24Bpp, canales usados: 8,8,8
    //El tamaño de línea sin procesar en bytes: 1500
    //La compresión de mapa de bits: Rgb
    //El ancho del mapa de bits: 500
    //La altura del mapa de bits: 375
    //El número de bits por píxel: 24
    //La resolución horizontal, en píxeles por pulgada: 0
    //La resolución vertical, en píxeles por pulgada: 0
    //Establecer valores de resolución a 96 dpi
    //La resolución horizontal, en píxeles por pulgada: 96.012
    //La resolución vertical, en píxeles por pulgada: 96.012
}
```

El siguiente ejemplo muestra cómo la compresión del mapa de bits afecta el tamaño de la imagen de salida.

```csharp
[C#]

Aspose.Imaging.FileFormats.Bmp.BitmapCompression[] compressions = new Aspose.Imaging.FileFormats.Bmp.BitmapCompression[]
{
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb,
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rle8,
};

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Cree una paleta monocromática que contenga solo colores rojo y verde.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // Crea una imagen BMP de 8 bpp de 100 x 100 px.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Rellena toda la imagen en rojo.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Guarde la imagen en una secuencia para obtener el tamaño de la imagen de salida.
        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            bmpImage.Save(stream);

            System.Console.WriteLine("---------------------------------------------");
            System.Console.WriteLine("The compression={0}", bmpImage.Compression);
            System.Console.WriteLine("The number of bits per pixel={0}", bmpImage.BitsPerPixel);
            System.Console.WriteLine("The image dimensions={0} x {1}", bmpImage.Width, bmpImage.Height);
            System.Console.WriteLine("The raw line size={0}", bmpImage.RawLineSize);
            System.Console.WriteLine("The output size in bytes={0}", stream.Length);
        }
    }
}

// La salida se ve así:
// -----------------------------------------------------------------------------
// La compresión = Rgb
// El número de bits por píxel = 8
// Las dimensiones de la imagen = 100 x 100
// El tamaño de línea sin procesar = 100
// El tamaño de salida en bytes = 11078
// -----------------------------------------------------------------------------
// La compresión = Rle8
// El número de bits por píxel = 8
// Las dimensiones de la imagen = 100 x 100
// El tamaño de línea sin procesar = 100
// El tamaño de salida en bytes = 856
```

### Ver también

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
