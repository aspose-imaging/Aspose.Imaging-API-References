---
title: WebPImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delWebPImageaspose.imaging.fileformats.webp/webpimage class de stream.
type: docs
weight: 10
url: /es/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) class de stream.

```csharp
public WebPImage(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La imagen WebP del flujo. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen WebP desde un flujo de archivos y guardarla en PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen WebP desde un flujo de archivos.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // Guardar en PNG
    // Tenga en cuenta que solo el marco activo se almacenará en PNG, ya que PNG no es un formato de varias páginas.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) clase de stream.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La imagen WebP del flujo. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Ver también

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) clase del archivo.

```csharp
public WebPImage(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta al archivo Imagen WebP |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen WebP desde un archivo y guardarla en PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen WebP desde un archivo.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Guardar en PNG
    // Tenga en cuenta que solo el marco activo se almacenará en PNG, ya que PNG no es un formato de varias páginas.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) clase del archivo.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta al archivo Imagen WebP |
| loadOptions | LoadOptions | Las opciones de carga. |

### Ver también

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) clase de rasterImage.

```csharp
public WebPImage(RasterImage rasterImage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen de trama. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen WebP a partir de otra imagen ráster.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Rellena toda la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Crea una imagen WebP basada en la imagen PNG.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Guardar en un archivo WebP con opciones predeterminadas
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) clase de rasterImage.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen de trama. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) clase con imagen vacía.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen |
| height | Int32 | La altura de la imagen. |
| options | WebPOptions | Las opciones. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen WebP con las opciones especificadas desde cero.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// Crea una imagen WebP de 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Rellena toda la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // Guardar en un archivo WebP
    webPImage.Save(dir + "output.webp");
}
```

Este ejemplo muestra cómo crear una imagen WebP animada de varios fotogramas con las opciones especificadas.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// El marco predeterminado más 36 + 36 marcos adicionales.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Crea una imagen WebP de 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // El primer circulo es rojo
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // El segundo circulo es negro
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente el ángulo de la forma del arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Aumenta gradualmente el ángulo del arco negro y borra el arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Guardar en un archivo WebP
    webPImage.Save(dir + "output.webp");
}
```

### Ver también

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Inicializa una nueva instancia del[`WebPImage`](../../webpimage) clase con imagen vacía.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen |
| height | Int32 | La altura de la imagen. |
| options | WebPOptions | Las opciones. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Ver también

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
