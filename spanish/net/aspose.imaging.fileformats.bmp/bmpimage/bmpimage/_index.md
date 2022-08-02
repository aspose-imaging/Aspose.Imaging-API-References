---
title: BmpImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delBmpImageaspose.imaging.fileformats.bmp/bmpimage clase.
type: docs
weight: 10
url: /es/net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar la imagen e inicializar los datos de píxeles y paletas. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | la imagen rasterizada es nula;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo cargar una BmpImage desde un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen BMP desde un archivo.
// Los píxeles de origen se convertirán al formato de 32 bpp si es necesario.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Haz algo de procesamiento de imágenes.
    // Guardar en otro archivo BMP.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### Ver también

* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar la imagen e inicializar los datos de píxeles y paletas. |
| bitsPerPixel | UInt16 | Los bits por píxel. |
| compression | BitmapCompression | La compresión a utilizar. |
| horizontalResolution | Double | La resolución horizontal. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |
| verticalResolution | Double | La resolución vertical. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | La imagen rasterizada no puede ser nula;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo cargar una BmpImage desde un archivo con la profundidad de bits y la resolución especificadas.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen BMP desde un archivo.
// Los píxeles de origen se convertirán al formato de 24 bpp si es necesario.
// La resolución se establecerá en 96 ppp.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Haz algo de procesamiento de imágenes.
    // Guardar en otro archivo BMP.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### Ver también

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia para cargar la imagen e inicializar los datos de píxeles y paletas. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | La imagen rasterizada no puede ser nula;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo cargar una BmpImage desde un flujo de archivos.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen BMP desde un flujo de archivos.
// Los píxeles de origen se convertirán al formato de 32 bpp si es necesario.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Haz algo de procesamiento de imágenes.
        // Guardar en otro archivo BMP.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### Ver también

* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia para cargar la imagen e inicializar los datos de píxeles y paletas. |
| bitsPerPixel | UInt16 | Los bits por píxel. |
| compression | BitmapCompression | La compresión a utilizar. |
| horizontalResolution | Double | La resolución horizontal. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |
| verticalResolution | Double | La resolución vertical. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | La imagen rasterizada no puede ser nula;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo cargar una BmpImage desde un flujo de archivos con la profundidad de bits y la resolución especificadas.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen BMP desde un flujo de archivos.
// Los píxeles de origen se convertirán al formato de 24 bpp si es necesario.
// La resolución se establecerá en 96 ppp.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Haz algo de procesamiento de imágenes.
        // Guardar en otro archivo BMP.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### Ver también

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen con la que inicializar los datos de píxeles y paletas. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | La imagen rasterizada no puede ser nula;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo cargar un BmpImage desde otra instancia de RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una nueva imagen PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Rellena toda la imagen PNG en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Crea una imagen BMP basada en la imagen PNG.
    // Los píxeles de origen se convertirán al formato de 32 bpp si es necesario.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // Guardar en un archivo BMP
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen con la que inicializar los datos de píxeles y paletas. |
| bitsPerPixel | UInt16 | Los bits por píxel. |
| compression | BitmapCompression | La compresión a utilizar. |
| horizontalResolution | Double | La resolución horizontal. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |
| verticalResolution | Double | La resolución vertical. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | La imagen rasterizada no puede ser nula;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo cargar una BmpImage desde otra instancia de RasterImage con la profundidad de bits y la compresión especificadas.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una nueva imagen PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Rellena toda la imagen PNG en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Crea una imagen BMP basada en la imagen PNG.
    // Los píxeles de origen se convertirán al formato de 24 bpp si es necesario.
    // La resolución se establecerá en 96 ppp.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Guardar en un archivo BMP
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |

### Excepciones

| excepción | condición |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo crear una BmpImage del tamaño especificado.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen BMP de 32 bpp de 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Rellena toda la imagen en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Guardar en un archivo BMP
    bmpImage.Save(dir + "output.bmp");
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

* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |
| bitsPerPixel | UInt16 | Los bits por píxel. |
| palette | IColorPalette | La paleta de colores. |

### Excepciones

| excepción | condición |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo crear una BmpImage del tamaño especificado con la paleta especificada.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Cree una paleta monocromática que contenga solo colores rojo y verde.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Cree una imagen BMP monocromática de 1 bpp de 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Rellena la mitad superior de la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Rellena la mitad inferior de la imagen en verde.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Guardar en BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### Ver también

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

Inicializa una nueva instancia del[`BmpImage`](../../bmpimage) clase.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |
| bitsPerPixel | UInt16 | Los bits por píxel. |
| palette | IColorPalette | La paleta de colores. |
| compression | BitmapCompression | La compresión a utilizar. |
| horizontalResolution | Double | La resolución horizontal. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |
| verticalResolution | Double | La resolución vertical. Tenga en cuenta que, debido al redondeo, la resolución resultante puede diferir ligeramente de la pasada. |

### Excepciones

| excepción | condición |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La altura debe ser positiva. |
| ArgumentException | Paleta debe especificarse para imágenes con 8 bits por píxel o menos.;paleta |

### Ejemplos

El ejemplo muestra cómo crear un BmpImage usando varias opciones.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Cree una paleta monocromática que contenga solo colores rojo y verde.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Cree una imagen BMP monocromática de 1 bpp de 100 x 100 px.
// La resolución horizontal y vertical se establecerá en 96 ppp.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Rellena la mitad superior de la imagen en rojo.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Rellena la mitad inferior de la imagen en verde.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Guardar en un archivo BMP
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### Ver también

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
