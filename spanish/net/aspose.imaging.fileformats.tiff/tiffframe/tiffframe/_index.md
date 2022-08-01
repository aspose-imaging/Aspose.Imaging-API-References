---
title: TiffFrame
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delTiffFrameaspose.imaging.fileformats.tiff/tiffframe clase.
type: docs
weight: 10
url: /es/net/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

Inicializa una nueva instancia del[`TiffFrame`](../../tiffframe) clase.

```csharp
public TiffFrame(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el que cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |

### Ver también

* class [TiffFrame](../../tiffframe)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* asamblea [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

Inicializa una nueva instancia del[`TiffFrame`](../../tiffframe) clase.

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el que cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |
| options | TiffOptions | Las opciones a usar para el marco recién creado. |

### Ver también

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* asamblea [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

Inicializa una nueva instancia del[`TiffFrame`](../../tiffframe) clase.

```csharp
public TiffFrame(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |

### Ver también

* class [TiffFrame](../../tiffframe)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* asamblea [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

Inicializa una nueva instancia del[`TiffFrame`](../../tiffframe) clase.

```csharp
public TiffFrame(string path, TiffOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |
| options | TiffOptions | Las opciones a usar para el marco recién creado. |

### Ver también

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* asamblea [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

Inicializa una nueva instancia del[`TiffFrame`](../../tiffframe) clase.

```csharp
public TiffFrame(RasterImage image)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen con la que inicializar el píxel del cuadro y los datos de la paleta. |

### Ejemplos

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

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffFrame](../../tiffframe)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* asamblea [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

Inicializa una nueva instancia del[`TiffFrame`](../../tiffframe) clase.

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen con la que inicializar el píxel del cuadro y los datos de la paleta. |
| options | TiffOptions | Las opciones a usar para el marco recién creado. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* asamblea [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

Inicializa una nueva instancia del[`TiffFrame`](../../tiffframe) clase.

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | TiffOptions | Las opciones de marco. |
| width | Int32 | La anchura. |
| height | Int32 | La altura. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El parámetro de opciones es nulo. |

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

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
