---
title: PngImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delPngImageaspose.imaging.fileformats.png/pngimage clase.
type: docs
weight: 10
url: /es/net/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho. |
| height | Int32 | La altura. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen PNG del tamaño especificado, rellenarla con un color sólido y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // Realice algún procesamiento de imagen, por ejemplo, rellene toda la imagen en rojo.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Guardar en un archivo.
    pngImage.Save(dir + "output.png");
}
```

### Ver también

* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar una imagen. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen PNG desde un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen PNG desde un archivo.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Transformar la imagen a representación en escala de grises
    pngImage.Grayscale();

    // Guardar en un archivo.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Ver también

* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(RasterImage rasterImage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen ráster. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen PNG desde una imagen BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen PNG TrueColor desde una imagen BMP.
// Primero, cree una imagen BMP temporal que será la base para crear una imagen PNG.
// También puede cargar una imagen BMP desde un archivo o utilizar una imagen de cualquier otro formato de trama.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Rellene toda la imagen BMP en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(string path, PngColorType colorType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar una imagen. |
| colorType | PngColorType | El tipo de color. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException |  |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen PNG desde un archivo con el tipo de color especificado.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen PNG desde un archivo.
// Tenga en cuenta que la imagen en color se convertirá automáticamente a escala de grises.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Guardar en un archivo.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Ver también

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen ráster. |
| colorType | PngColorType | El tipo de color. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen PNG desde una imagen BMP con el tipo de color especificado.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargue una imagen PNG en escala de grises desde una imagen BMP en color.
// Primero, cree una imagen BMP temporal que será la base para crear una imagen PNG.
// También puede cargar una imagen BMP desde un archivo o utilizar una imagen de cualquier otro formato de trama.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Rellene toda la imagen BMP en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Los colores de los píxeles de la imagen se convertirán a sus equivalentes en escala de grises.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El stream para cargar una imagen. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen PNG desde un archivo o una secuencia de archivos.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen PNG desde un flujo de archivos.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // Transformar la imagen a representación en escala de grises
        pngImage.Grayscale();

        // Guardar en un archivo.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### Ver también

* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho. |
| height | Int32 | La altura. |
| colorType | PngColorType | El tipo de color. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen PNG del tamaño especificado con el tipo de color especificado, rellenarla con un color sólido y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crear una imagen PNG en escala de grises de 100x100 px.
// Todos los colores se convertirán automáticamente al formato de escala de grises.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Realice algún procesamiento de imagen, por ejemplo, rellene toda la imagen en rojo.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Guardar en un archivo.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### Ver también

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

Inicializa una nueva instancia del[`PngImage`](../../pngimage) clase.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pngOptions | PngOptions | Las opciones png. |
| width | Int32 | El ancho. |
| height | Int32 | La altura. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen PNG con las opciones especificadas, rellenarla con colores degradados lineales y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// El número de bits por canal de color
createOptions.BitDepth = 8;

// Cada píxel es un triple (rojo, verde, azul) seguido del componente alfa.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// El nivel máximo de compresión.
createOptions.CompressionLevel = 9;

// El uso de filtros permite comprimir imágenes tonales continuas de manera más efectiva.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Usar carga progresiva
createOptions.Progressive = true;

// Crea una imagen PNG con parámetros personalizados.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Rellena la imagen con un degradado semitransparente.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Guardar en un archivo.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

### Ver también

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Png](../../pngimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
