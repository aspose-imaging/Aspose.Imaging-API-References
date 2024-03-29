---
title: Resize
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ridimensiona limmagine.
type: docs
weight: 60
url: /it/net/aspose.imaging.fileformats.opendocument/odgimage/resize/
---
## Resize(int, int, ImageResizeSettings) {#resize_1}

Ridimensiona l'immagine.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| settings | ImageResizeSettings | Le impostazioni di ridimensionamento. |

### Guarda anche

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [OdgImage](../../odgimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* assemblea [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Ridimensiona l'immagine.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| resizeType | ResizeType | Il tipo di ridimensionamento. |

### Esempi

Questo esempio carica un'immagine ODG multipagina e la ridimensiona utilizzando vari metodi di ridimensionamento.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Ridimensiona di 2 volte usando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento bilineare.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Ridimensiona di 2 volte usando il ricampionamento bilineare.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [OdgImage](../../odgimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
