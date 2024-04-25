---
title: JpegImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delJpegImageaspose.imaging.fileformats.jpeg/jpegimage clase.
type: docs
weight: 10
url: /es/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

Inicializa una nueva instancia del[`JpegImage`](../../jpegimage) clase.

```csharp
public JpegImage(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar la imagen e inicializar los datos de píxeles y paleta con. |

### Ejemplos

El ejemplo muestra cómo cargar una imagen Jpeg de un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen JPEG desde un archivo.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Haz algo de procesamiento de imágenes.
    // Guardar en otro archivo JPEG.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Ver también

* class [JpegImage](../../jpegimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* asamblea [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

Inicializa una nueva instancia del[`JpegImage`](../../jpegimage) clase.

```csharp
public JpegImage(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo para cargar la imagen e inicializar los datos de píxeles y paleta con. |

### Ejemplos

El ejemplo muestra cómo cargar una imagen Jpeg de un flujo de archivos.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen JPEG desde un flujo de archivos.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // Haz algo de procesamiento de imágenes.
        // Guardar en otro archivo JPEG.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### Ver también

* class [JpegImage](../../jpegimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* asamblea [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

Inicializa una nueva instancia del[`JpegImage`](../../jpegimage) clase.

```csharp
public JpegImage(RasterImage rasterImage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen con la que inicializar los datos de píxeles y paleta. |

### Ejemplos

El ejemplo muestra cómo cargar una JpegImage desde otra RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen JPEG desde otra imagen rasterizada.
// Primero, crea una imagen PNG temporal que será la base para construir una imagen JPEG.
// También puede cargar una imagen PNG desde un archivo o usar una imagen de cualquier otro formato de trama.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Rellena toda la imagen PNG en rojo.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // Crea una imagen JPEG basada en la imagen PNG.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // Guardar en un archivo JPEG
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* asamblea [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

Inicializa una nueva instancia del[`JpegImage`](../../jpegimage) clase.

```csharp
public JpegImage(int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |

### Ejemplos

El siguiente ejemplo muestra cómo crear una imagen JPEG del tamaño especificado.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // Haz algo de procesamiento de imágenes.
    // Guardar en un archivo.
    jpegImage.Save(dir + "output.jpg");
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

### Ver también

* class [JpegImage](../../jpegimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* asamblea [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

Inicializa una nueva instancia del[`JpegImage`](../../jpegimage) clase.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| jpegOptions | JpegOptions | Las opciones jpeg. |
| width | Int32 | Ancho de la imagen. |
| height | Int32 | Altura de la imagen. |

### Ejemplos

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

El siguiente ejemplo muestra cómo crear una imagen JPEG del tamaño especificado con los parámetros especificados.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
// Use opciones adicionales para especificar los parámetros de imagen deseados.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// El número de bits por canal es 8, 8, 8 para los componentes Y, Cr, Cb en consecuencia.
createOptions.BitsPerChannel = 8;

// Establecer el tipo progresivo de compresión.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Establecer la calidad de la imagen. Es un valor entre 1 y 100.
createOptions.Quality = 100;

// Establezca la resolución horizontal/vertical en 96 puntos por pulgada.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Esta es una opción estándar para imágenes JPEG.
// Dos componentes de croma (Cb y Cr) se pueden reducir en ancho de banda, submuestrear y comprimir.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Rellena la imagen con un degradado en escala de grises
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Guardar en un archivo.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Ver también

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
