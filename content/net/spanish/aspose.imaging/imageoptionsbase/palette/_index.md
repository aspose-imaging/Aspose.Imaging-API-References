---
title: Palette
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece la paleta de colores.
type: docs
weight: 40
url: /es/aspose.imaging/imageoptionsbase/palette/
---
## ImageOptionsBase.Palette property

Obtiene o establece la paleta de colores.

```csharp
public virtual IColorPalette Palette { get; set; }
```

### El valor de la propiedad

La paleta de colores.

### Ejemplos

El siguiente ejemplo muestra cómo comprimir una imagen PNG, usando color indexado con la paleta de mejor ajuste

```csharp
[C#]

// Carga la imagen png        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Usar tipo de color indexado
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Usar compresión máxima
         CompressionLevel = 9,
      // Obtenga la paleta de colores de 8 bits más cercana que cubra tantos píxeles como sea posible, de modo que una imagen paletizada
         // es casi indistinguible visualmente de uno no paletizado.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // El tamaño del archivo de salida debe reducirse significativamente
```

El siguiente ejemplo carga una imagen BMP y la vuelve a guardar en BMP usando varias opciones de guardado.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Crear BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Use 8 bits por píxel para reducir el tamaño de la imagen de salida.
    saveOptions.BitsPerPixel = 8;

    // Establezca la paleta de colores de 8 bits más cercana que cubra el número máximo de píxeles de la imagen, de modo que una imagen paletizada
    // es casi indistinguible visualmente de uno no paletizado.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Guardar sin compresión.
    // También puede usar la compresión RLE-8 para reducir el tamaño de la imagen de salida.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Establezca la resolución horizontal y vertical en 96 ppp.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

El siguiente ejemplo carga una imagen BMP y la guarda en JPEG usando varias opciones de guardado.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen BMP desde un archivo.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Haz algo de procesamiento de imágenes.

    // Use opciones adicionales para especificar los parámetros de imagen deseados.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // El número de bits por canal es 8.
    // Cuando se usa una paleta, el índice de color se almacena en los datos de la imagen en lugar del color en sí.
    saveOptions.BitsPerChannel = 8;

    // Establecer el tipo progresivo de compresión.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Establecer la calidad de la imagen. Es un valor entre 1 y 100.
    saveOptions.Quality = 100;

    // Establezca la resolución horizontal/vertical en 96 puntos por pulgada.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Si la imagen de origen está coloreada, se convertirá a escala de grises.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Usa una paleta para reducir el tamaño de salida.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

El siguiente ejemplo crea una imagen BMP paletizada en escala de grises y luego la guarda en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Guardar en un archivo
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Use 8 bits por píxel para reducir el tamaño de la imagen de salida.
createOptions.BitsPerPixel = 8;

// Configure la paleta de colores estándar de escala de grises de 8 bits que cubre todos los colores de escala de grises.
// Si la imagen procesada contiene solo colores en escala de grises, entonces su versión paletizada
// es visualmente indistinguible de uno no paletizado.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Guardar sin compresión.
// También puede usar la compresión RLE-8 para reducir el tamaño de la imagen de salida.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Establezca la resolución horizontal y vertical en 96 ppp.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Cree una imagen BMP de 100 x 100 px y guárdela en un archivo.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Rellena la imagen con un degradado en escala de grises
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

El siguiente ejemplo muestra cómo paletizar una imagen BMP para reducir su tamaño de salida.

```csharp
[C#]

// Crea una imagen BMP de 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // El degradado lineal desde la esquina superior izquierda hasta la esquina inferior derecha de la imagen.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Rellena toda la imagen con el pincel de degradado lineal.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Obtenga la paleta de colores de 8 bits más cercana que cubra tantos píxeles como sea posible, de modo que una imagen paletizada
    // es casi indistinguible visualmente de uno no paletizado.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // La paleta de 8 bits contiene como máximo 256 colores.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// La salida se ve así:
// El tamaño de la imagen paletizada es de 11078 bytes.
// El tamaño de la imagen no paletizada es de 40054 bytes.
```

### Ver también

* interface [IColorPalette](../../icolorpalette)
* class [ImageOptionsBase](../../imageoptionsbase)
* espacio de nombres [Aspose.Imaging](../../imageoptionsbase)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
