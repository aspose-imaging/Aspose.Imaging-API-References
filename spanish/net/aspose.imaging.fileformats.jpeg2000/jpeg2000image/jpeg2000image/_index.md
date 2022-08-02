---
title: Jpeg2000Image
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image clase.
type: docs
weight: 10
url: /es/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar la imagen e inicializar los datos de píxeles y paletas. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen JPEG2000 desde un archivo y guardarla en PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen JPEG2000.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // Guardar en PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar la imagen e inicializar los datos de píxeles y paletas con |
| bitsPerPixel | Int32 | Los bits por píxel. |

### Ver también

* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia para cargar la imagen e inicializar los datos de píxeles y paletas. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen JPEG2000 desde un flujo de archivos y guardarla en PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen JPEG2000 desde la transmisión.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // Guardar en PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia para cargar la imagen e inicializar los datos de píxeles y paletas. |
| bitsPerPixel | Int32 | Los bits por píxel. |

### Ver también

* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen |
| height | Int32 | la altura de la imagen |

### Ejemplos

Este ejemplo muestra cómo crear una imagen JPEG2000 y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen JPEG2000 de 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Rellena toda la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Guardar en un archivo
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### Ver también

* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen |
| height | Int32 | la altura de la imagen |
| options | Jpeg2000Options | Las opciones. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen PNG y guardarla en JPEG2000 con las opciones deseadas.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Rellena toda la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // Usar la Transformada Wavelet Discreta irreversible 9-7
    saveOptions.Irreversible = true;

    // JP2 es el formato "contenedor" para flujos de código JPEG 2000.
    // J2K son datos comprimidos sin procesar, sin contenedor.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // Guardar en un archivo
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

Este ejemplo muestra cómo crear una imagen JPEG2000 con las opciones deseadas y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// Usar la Transformada Wavelet Discreta irreversible 9-7
createOptions.Irreversible = true;

// JP2 es el formato "contenedor" para flujos de código JPEG 2000.
// J2K son datos comprimidos sin procesar, sin contenedor.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// Crea una imagen JPEG2000 de 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Rellena toda la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Guardar en un archivo
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### Ver también

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen |
| height | Int32 | la altura de la imagen |
| bitsCount | Int32 | Los bits cuentan. |

### Ver también

* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen JPEG2000 a partir de otra imagen ráster.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Rellena toda la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Crea una imagen JPEG2000 basada en la imagen PNG.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // Guardar en un archivo
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Inicializa una nueva instancia del[`Jpeg2000Image`](../../jpeg2000image) clase.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen con la que inicializar los datos de píxeles y paletas. |
| bitsPerPixel | Int32 | Los bits por píxel. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* espacio de nombres [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
