---
title: GetCloseImagePalette
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene la paleta de colores de la imagen raster paletiza la imagen en caso de que la imagen no la tenga. En caso de que exista una paleta se usará en su lugar para realizar los cálculos.
type: docs
weight: 60
url: /es/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no la tenga. En caso de que exista una paleta, se usará en su lugar para realizar los cálculos.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen de trama. |
| entriesCount | Int32 | Las entradas deseadas cuentan. |

### Valor_devuelto

La paleta de colores que comienza con los colores más frecuentes del*image* y contiene*entriesCount* entradas.

### Ejemplos

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
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espacio de nombres [Aspose.Imaging](../../colorpalettehelper)
* asamblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no la tenga. Palette está a punto de optimizarse para una mejor calidad de imagen indexada o tomarse "TAL CUAL" cuando se usa PaletteMiningMethod.UseCurrentPalette.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen de trama. |
| entriesCount | Int32 | Las entradas deseadas cuentan. |
| paletteMiningMethod | PaletteMiningMethod | El método de minería de paletas. |

### Valor_devuelto

La paleta de colores que comienza con los colores más frecuentes del*image* y contiene*entriesCount* entradas.

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

### Ver también

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espacio de nombres [Aspose.Imaging](../../colorpalettehelper)
* asamblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no la tenga. En caso de que exista una paleta, se usará en su lugar para realizar los cálculos.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen de trama. |
| destBounds | Rectangle | Los límites de la imagen de destino. |
| entriesCount | Int32 | Las entradas deseadas cuentan. |

### Valor_devuelto

La paleta de colores que comienza con los colores más frecuentes del*image* y contiene*entriesCount* entradas.

### Ver también

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espacio de nombres [Aspose.Imaging](../../colorpalettehelper)
* asamblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no la tenga. En caso de que exista una paleta, se usará en su lugar para realizar los cálculos.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen de trama. |
| destBounds | Rectangle | Los límites de la imagen de destino. |
| entriesCount | Int32 | Las entradas deseadas cuentan. |
| useImagePalette | Boolean | Si está configurado, usará su propia paleta de imágenes si está disponible |

### Valor_devuelto

La paleta de colores que comienza con los colores más frecuentes del*image* y contiene*entriesCount* entradas.

### Ver también

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espacio de nombres [Aspose.Imaging](../../colorpalettehelper)
* asamblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no la tenga. En caso de que exista una paleta, se usará en su lugar para realizar los cálculos.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen de trama. |
| destBounds | Rectangle | Los límites de la imagen de destino. |
| entriesCount | Int32 | Las entradas deseadas cuentan. |
| useImagePalette | Boolean | Si está configurado, usará su propia paleta de imágenes si está disponible |
| alphaBlendInColor | Color | El color que debe usarse como color de fondo para el reemplazo alfa semitransparente. |

### Valor_devuelto

La paleta de colores que comienza con los colores más frecuentes del*image* y contiene*entriesCount* entradas.

### Ver también

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espacio de nombres [Aspose.Imaging](../../colorpalettehelper)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
