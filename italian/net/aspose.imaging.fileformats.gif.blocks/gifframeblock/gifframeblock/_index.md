---
title: GifFrameBlock
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | UInt16 | La larghezza dell'immagine. |
| height | UInt16 | L'altezza dell'immagine. |

### Esempi

Questo esempio mostra come creare un'immagine GIF e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un blocco GIF Frame di 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Riempi di rosso l'intero blocco.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Questo esempio mostra come creare un'immagine GIF con una tavolozza personalizzata e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un blocco GIF Frame di 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Riempi di rosso l'intero blocco.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Usa la tavolozza a 4 bit per ridurre le dimensioni dell'immagine. La qualità può peggiorare.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

L'esempio seguente mostra come comporre un'immagine GIF animata da singoli blocchi GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine GIF 100 x 100 px.
// Il primo blocco è completamente nero per impostazione predefinita.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Il primo cerchio è rosso
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Il secondo cerchio è nero
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente l'angolo della forma dell'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
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

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |
| width | UInt16 | La larghezza dell'immagine. |
| height | UInt16 | L'altezza dell'immagine. |

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |
| width | UInt16 | La larghezza dell'immagine. |
| height | UInt16 | L'altezza dell'immagine. |
| colorPalette | IColorPalette | La tavolozza dei colori. |
| isPaletteSorted | Boolean | se impostato su`VERO` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | Boolean | se impostato su`VERO` la cornice GIF è intrecciata. |
| bitsPerPixel | Byte | I bit per pixel. |

### Guarda anche

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(RasterImage image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine con cui inizializzare i pixel del frame e i dati della tavolozza. |

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine con cui inizializzare i pixel del frame e i dati della tavolozza. |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine con cui inizializzare i pixel del frame e i dati della tavolozza. |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |
| isPaletteSorted | Boolean | se impostato su`VERO` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | Boolean | se impostato su`VERO` la cornice GIF è intrecciata. |
| lzwCodeSize | Byte | I bit per pixel. |

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |
| isPaletteSorted | Boolean | se impostato su`VERO` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | Boolean | se impostato su`VERO` la cornice GIF è intrecciata. |
| lzwCodeSize | Byte | I bit per pixel. |

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Inizializza una nuova istanza di[`GifFrameBlock`](../../gifframeblock) classe.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |
| left | UInt16 | La posizione dell'immagine a sinistra. |
| top | UInt16 | La posizione dell'immagine in alto. |
| isPaletteSorted | Boolean | se impostato su`VERO` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | Boolean | se impostato su`VERO` la cornice GIF è intrecciata. |
| lzwCodeSize | Byte | I bit per pixel. |

### Guarda anche

* class [GifFrameBlock](../../gifframeblock)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
