---
title: GifImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delGifImageaspose.imaging.fileformats.gif/gifimage clase.
type: docs
weight: 10
url: /es/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Inicializa una nueva instancia del[`GifImage`](../../gifimage) clase.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstFrame | GifFrameBlock | El primer cuadro para inicializar la imagen gif. |
| globalPalette | IColorPalette | La paleta global a utilizar. Tenga en cuenta si ambos*firstFrame* y*globalPalette* son nulos, entonces se usa la paleta global predeterminada. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El marco no puede ser nulo;firstFrame |
| ArgumentException | El primer cuadro ya pertenece a alguna otra imagen. Compruebe la propiedad Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La paleta especificada debe contener un número de entradas igual a la potencia de 2. El tamaño mínimo de la paleta es 2, el máximo es 256. |

### Ejemplos

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

### Ver también

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* asamblea [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

Inicializa una nueva instancia del[`GifImage`](../../gifimage) clase.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstFrame | GifFrameBlock | El primer cuadro para inicializar la imagen gif. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El marco no puede ser nulo;firstFrame |
| ArgumentException | El primer cuadro ya pertenece a alguna otra imagen. Compruebe la propiedad Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La paleta especificada debe contener un número de entradas igual a la potencia de 2. El tamaño mínimo de la paleta es 2, el máximo es 256. |

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

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* asamblea [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

Inicializa una nueva instancia del[`GifImage`](../../gifimage) clase.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstFrame | GifFrameBlock | El primer cuadro para inicializar la imagen gif. |
| globalPalette | IColorPalette | La paleta global a utilizar. Tenga en cuenta si ambos*firstFrame* y*globalPalette* son nulos, entonces se usa la paleta global predeterminada. |
| isPaletteSorted | Boolean | si se establece en`verdadero` la paleta está ordenada. Tenga en cuenta que el parámetro se utiliza cuando*globalPalette* No es nulo. |
| paletteColorResolution | Byte | La resolución de color de la paleta. Tenga en cuenta que el parámetro se utiliza cuando*globalPalette* No es nulo. |
| paletteBackgroundColorIndex | Byte | El índice de color de fondo de la paleta. |
| aspectRatio | Byte | La relación de aspecto. |
| hasTrailer | Boolean | si se establece en`verdadero` la imagen gif tiene un tráiler; de lo contrario, no hay un tráiler escrito al final de la transmisión. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El marco no puede ser nulo;firstFrame |
| ArgumentException | El primer cuadro ya pertenece a alguna otra imagen. Compruebe la propiedad Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La paleta especificada debe contener un número de entradas igual a la potencia de 2. El tamaño mínimo de la paleta es 2, el máximo es 256. |

### Ver también

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
