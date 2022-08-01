---
title: TiffOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delTiffOptionsaspose.imaging.imageoptions/tiffoptions clase.
type: docs
weight: 10
url: /es/net/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

Inicializa una nueva instancia del[`TiffOptions`](../../tiffoptions) clase.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | El formato de archivo tiff esperado. |
| byteOrder | TiffByteOrder | El orden de bytes del formato de archivo tiff a utilizar. |

### Ver también

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../tiffoptions)
* asamblea [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

Inicializa una nueva instancia del[`TiffOptions`](../../tiffoptions)clase. Por defecto se usa la convención little endian.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | El formato de archivo tiff esperado. |

### Ejemplos

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

### Ver también

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../tiffoptions)
* asamblea [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

Inicializa una nueva instancia del[`TiffOptions`](../../tiffoptions) clase.

```csharp
public TiffOptions(TiffOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | TiffOptions | Las opciones desde las que copiar. |

### Ver también

* class [TiffOptions](../../tiffoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../tiffoptions)
* asamblea [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

Inicializa una nueva instancia del[`TiffOptions`](../../tiffoptions) clase.

```csharp
public TiffOptions(TiffDataType[] tags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| tags | TiffDataType[] | Las etiquetas con las que inicializar las opciones. |

### Ver también

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../tiffoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
