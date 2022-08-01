---
title: GifFrameBlock
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock clase.
type: docs
weight: 10
url: /es/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | UInt16 | El ancho de la imagen. |
| height | UInt16 | La altura de la imagen. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen GIF y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un bloque de marco GIF de 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Rellena todo el bloque en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Este ejemplo muestra cómo crear una imagen GIF con una paleta personalizada y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un bloque de marco GIF de 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Rellena todo el bloque en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Usa la paleta de 4 bits para reducir el tamaño de la imagen. La calidad puede empeorar.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

El siguiente ejemplo muestra cómo componer una imagen GIF animada a partir de bloques GIF individuales.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen GIF de 100 x 100 px.
// El primer bloque es completamente negro por defecto.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // El primer circulo es rojo
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // El segundo circulo es negro
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente el ángulo de la forma del arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Aumenta gradualmente el ángulo del arco negro y borra el arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |
| width | UInt16 | El ancho de la imagen. |
| height | UInt16 | La altura de la imagen. |

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |
| width | UInt16 | El ancho de la imagen. |
| height | UInt16 | La altura de la imagen. |
| colorPalette | IColorPalette | La paleta de colores. |
| isPaletteSorted | Boolean | si se establece en`verdadero` la paleta de colores está ordenada. |
| isGifFrameInterlaced | Boolean | si se establece en`verdadero` el marco GIF está entrelazado. |
| bitsPerPixel | Byte | Los bits por píxel. |

### Ver también

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(RasterImage image)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen con la que inicializar el píxel del cuadro y los datos de la paleta. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen con la que inicializar el píxel del cuadro y los datos de la paleta. |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen con la que inicializar el píxel del cuadro y los datos de la paleta. |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |
| isPaletteSorted | Boolean | si se establece en`verdadero` la paleta de colores está ordenada. |
| isGifFrameInterlaced | Boolean | si se establece en`verdadero` el marco GIF está entrelazado. |
| lzwCodeSize | Byte | Los bits por píxel. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el que cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el que cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el que cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |
| isPaletteSorted | Boolean | si se establece en`verdadero` la paleta de colores está ordenada. |
| isGifFrameInterlaced | Boolean | si se establece en`verdadero` el marco GIF está entrelazado. |
| lzwCodeSize | Byte | Los bits por píxel. |

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Inicializa una nueva instancia del[`GifFrameBlock`](../../gifframeblock) clase.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta para cargar una imagen e inicializar el píxel del cuadro y los datos de la paleta. |
| left | UInt16 | La posición de la imagen izquierda. |
| top | UInt16 | La posición superior de la imagen. |
| isPaletteSorted | Boolean | si se establece en`verdadero` la paleta de colores está ordenada. |
| isGifFrameInterlaced | Boolean | si se establece en`verdadero` el marco GIF está entrelazado. |
| lzwCodeSize | Byte | Los bits por píxel. |

### Ver también

* class [GifFrameBlock](../../gifframeblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
