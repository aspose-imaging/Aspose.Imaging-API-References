---
title: TiffImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delTiffImageaspose.imaging.fileformats.tiff/tiffimage clase.
type: docs
weight: 10
url: /es/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

Inicializa una nueva instancia del[`TiffImage`](../../tiffimage) clase.

```csharp
public TiffImage(TiffFrame frame)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| frame | TiffFrame | El marco tiff para inicializar la imagen. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El marco tiff no puede estar vacío.;marco |

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

### Ver también

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* asamblea [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

Inicializa una nueva instancia del[`TiffImage`](../../tiffimage) clase.

```csharp
public TiffImage(TiffFrame[] frames)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| frames | TiffFrame[] | los marcos |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | marcos |

### Ejemplos

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

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
