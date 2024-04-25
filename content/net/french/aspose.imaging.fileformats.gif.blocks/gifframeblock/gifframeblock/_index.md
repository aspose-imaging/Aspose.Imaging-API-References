---
title: GifFrameBlock
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock classe.
type: docs
weight: 10
url: /fr/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | UInt16 | La largeur de l'image. |
| height | UInt16 | La hauteur de l'image. |

### Exemples

Cet exemple montre comment créer une image GIF et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée un bloc Frame GIF de 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Remplit tout le bloc en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Cet exemple montre comment créer une image GIF avec une palette personnalisée et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée un bloc Frame GIF de 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Remplit tout le bloc en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Utilisez la palette 4 bits pour réduire la taille de l'image. La qualité peut empirer.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

L'exemple suivant montre comment composer une image GIF animée à partir de blocs GIF individuels.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image GIF 100 x 100 px.
// Le premier bloc est entièrement noir par défaut.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Le premier cercle est rouge
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Le deuxième cercle est noir
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Augmente progressivement l'angle de la forme d'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Augmente progressivement l'angle de l'arc noir et efface l'arc rouge.
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

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |
| width | UInt16 | La largeur de l'image. |
| height | UInt16 | La hauteur de l'image. |

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |
| width | UInt16 | La largeur de l'image. |
| height | UInt16 | La hauteur de l'image. |
| colorPalette | IColorPalette | La palette de couleurs. |
| isPaletteSorted | Boolean | si réglé sur`vrai` la palette de couleurs est triée. |
| isGifFrameInterlaced | Boolean | si réglé sur`vrai` le cadre GIF est entrelacé. |
| bitsPerPixel | Byte | Les bits par pixel. |

### Voir également

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(RasterImage image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette du cadre. |

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette du cadre. |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette du cadre. |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |
| isPaletteSorted | Boolean | si réglé sur`vrai` la palette de couleurs est triée. |
| isGifFrameInterlaced | Boolean | si réglé sur`vrai` le cadre GIF est entrelacé. |
| lzwCodeSize | Byte | Les bits par pixel. |

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger une image et initialiser les données de pixel et de palette du cadre avec. |

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger une image et initialiser les données de pixel et de palette du cadre avec. |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger une image et initialiser les données de pixel et de palette du cadre avec. |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |
| isPaletteSorted | Boolean | si réglé sur`vrai` la palette de couleurs est triée. |
| isGifFrameInterlaced | Boolean | si réglé sur`vrai` le cadre GIF est entrelacé. |
| lzwCodeSize | Byte | Les bits par pixel. |

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès à partir duquel charger une image et initialiser les données de pixels et de palette du cadre. |

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès à partir duquel charger une image et initialiser les données de pixels et de palette du cadre. |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Initialise une nouvelle instance du[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès à partir duquel charger une image et initialiser les données de pixels et de palette du cadre. |
| left | UInt16 | La position de l'image à gauche. |
| top | UInt16 | La position supérieure de l'image. |
| isPaletteSorted | Boolean | si réglé sur`vrai` la palette de couleurs est triée. |
| isGifFrameInterlaced | Boolean | si réglé sur`vrai` le cadre GIF est entrelacé. |
| lzwCodeSize | Byte | Les bits par pixel. |

### Voir également

* class [GifFrameBlock](../../gifframeblock)
* espace de noms [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
