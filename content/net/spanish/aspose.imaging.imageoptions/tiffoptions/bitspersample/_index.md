---
title: BitsPerSample
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece los bits por muestra.
type: docs
weight: 50
url: /es/aspose.imaging.imageoptions/tiffoptions/bitspersample/
---
## TiffOptions.BitsPerSample property

Obtiene o establece los bits por muestra.

```csharp
public ushort[] BitsPerSample { get; set; }
```

### El valor de la propiedad

Los bits por valor de muestra.

### Observaciones

Al establecer este valor, tenga en cuenta que también establecerá el valor de SamplesPerPixel en la longitud de la matriz. Estas 2 propiedades están muy estrechamente acopladas, por lo que solo se pueden establecer juntas.

### Ejemplos

Este ejemplo muestra cómo crear una imagen TIFF desde cero y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Establecer 8 bits para cada componente de color.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Establecer el orden de bytes Big Endian (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Establecer la compresión LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Establecer el modelo de color RGB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Todos los componentes de color se almacenarán en un solo plano.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crea un Marco TIFF de 100x100 px.
// Tenga en cuenta que no tiene que desechar un marco explícitamente si está incluido en TiffImage.
// Cuando se desecha el contenedor, todos los marcos se desecharán automáticamente.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Rellena todo el cuadro con el degradado azul-amarillo.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Crea una imagen TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

El siguiente ejemplo muestra cómo componer un TIFF de varias páginas a partir de imágenes ráster individuales.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Esto es Fuente y Pincel para dibujar texto en marcos individuales.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // Crear 5 marcos
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Crea una imagen PNG y dibuja el número de página en ella.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Crea un marco basado en la imagen PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Agrega el marco a la imagen TIFF.
        tiffImage.AddFrame(frame);
    }

    // La imagen se creó con un solo marco predeterminado. Quitémoslo.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // No olvide desechar el marco si no lo agregará a alguna otra TiffImage
    activeFrame.Dispose();

    tiffImage.Save();
}
```

El siguiente ejemplo muestra cómo crear una copia en escala de grises de un marco existente y agregarlo a una imagen TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Crear una fuente de archivo permanente, no temporal.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // El degradado lineal desde la esquina superior izquierda hasta la esquina inferior derecha de la imagen.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Rellena el cuadro activo con un pincel de degradado lineal.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Opciones de escala de grises
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Crea una copia en escala de grises del marco activo.
    // Los datos de píxeles se conservan pero se convierten al formato deseado.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Agregue el marco recién creado a la imagen TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

Este ejemplo muestra cómo guardar una imagen ráster en formato TIFF usando varias opciones.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Establecer 8 bits para cada componente de color.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Establecer el orden de bytes Big Endian (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Establecer la compresión LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Permitir reducir el tamaño de las imágenes de tono continuo.
// Actualmente, este campo se usa solo con la codificación LZW porque LZW es probablemente el único esquema de codificación TIFF
// que se beneficia significativamente de un paso de predictor.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// Establecer el modelo de color RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Para YCbCr, puede usar una de las siguientes opciones:
// YCbCrSubSampling campo Factores de muestreo JPEG
// ----------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(valor predeterminado) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Todos los componentes de color se almacenarán en un solo plano.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crea un Marco TIFF de 100x100 px.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Rellena toda la imagen con el degradado azul-amarillo.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

Este ejemplo muestra cómo crear una imagen TIFF con 2 marcos y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Opciones para el primer cuadro
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Establecer 8 bits para cada componente de color.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Establecer el orden de bytes Big Endian (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Establecer la compresión LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Establecer el modelo de color RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Todos los componentes de color se almacenarán en un solo plano.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crea el primer marco TIFF de 100x100 px.
// Tenga en cuenta que no tiene que deshacerse de los marcos explícitamente si están incluidos en TiffImage.
// Cuando se desecha el contenedor, todos los marcos se desecharán automáticamente.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Rellena el primer cuadro con el degradado azul-amarillo.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Opciones para el primer cuadro
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Establecer 1 bit por píxel para una imagen en blanco y negro.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Establecer el orden de bytes de Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Configure la compresión de fax CCITT Grupo 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Establecer el modelo de color B/N donde 0 es negro, 1 es blanco.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Crea el segundo marco TIFF de 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Rellena el segundo cuadro con el degradado azul-amarillo.
// Se convertirá automáticamente al formato B/N debido a la configuración correspondiente del marco.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Crea una imagen TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Ver también

* class [TiffOptions](../../tiffoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../tiffoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
