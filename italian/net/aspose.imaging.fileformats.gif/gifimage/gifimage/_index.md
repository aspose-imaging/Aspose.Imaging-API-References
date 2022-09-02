---
title: GifImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diGifImageaspose.imaging.fileformats.gif/gifimage classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Inizializza una nuova istanza di[`GifImage`](../../gifimage) classe.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Il primo fotogramma con cui inizializzare l'immagine gif. |
| globalPalette | IColorPalette | La tavolozza globale da utilizzare. Nota se entrambi*firstFrame* e*globalPalette* sono nulli, viene utilizzata la tavolozza globale predefinita. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Il frame non può essere null;firstFrame |
| ArgumentException | Il primo fotogramma appartiene già a qualche altra immagine. Controllare la proprietà Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La tavolozza specificata dovrebbe contenere il conteggio delle voci pari alla potenza di 2. La dimensione minima della tavolozza è 2, la massima è 256. |

### Esempi

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

### Guarda anche

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assemblea [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

Inizializza una nuova istanza di[`GifImage`](../../gifimage) classe.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Il primo fotogramma con cui inizializzare l'immagine gif. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Il frame non può essere null;firstFrame |
| ArgumentException | Il primo fotogramma appartiene già a qualche altra immagine. Controllare la proprietà Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La tavolozza specificata dovrebbe contenere il conteggio delle voci pari alla potenza di 2. La dimensione minima della tavolozza è 2, la massima è 256. |

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

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assemblea [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

Inizializza una nuova istanza di[`GifImage`](../../gifimage) classe.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Il primo fotogramma con cui inizializzare l'immagine gif. |
| globalPalette | IColorPalette | La tavolozza globale da utilizzare. Nota se entrambi*firstFrame* e*globalPalette* sono nulli, viene utilizzata la tavolozza globale predefinita. |
| isPaletteSorted | Boolean | se impostato su`VERO` la tavolozza è ordinata. Si noti che il parametro viene utilizzato quando*globalPalette* non è nullo. |
| paletteColorResolution | Byte | La risoluzione del colore della tavolozza. Si noti che il parametro viene utilizzato quando*globalPalette* non è nullo. |
| paletteBackgroundColorIndex | Byte | L'indice del colore di sfondo della tavolozza. |
| aspectRatio | Byte | Le proporzioni. |
| hasTrailer | Boolean | se impostato su`VERO` l'immagine gif ha trailer altrimenti nessun trailer scritto alla fine dello stream. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Il frame non può essere null;firstFrame |
| ArgumentException | Il primo fotogramma appartiene già a qualche altra immagine. Controllare la proprietà Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La tavolozza specificata dovrebbe contenere il conteggio delle voci pari alla potenza di 2. La dimensione minima della tavolozza è 2, la massima è 256. |

### Guarda anche

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
