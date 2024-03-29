---
title: Resize
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ridimensiona limmagine.
type: docs
weight: 150
url: /it/net/aspose.imaging.fileformats.wmf/wmfimage/resize/
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

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException |  |

### Esempi

Questo esempio carica un'immagine WMF e la ridimensiona utilizzando vari metodi di ridimensionamento.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Ridimensiona di 2 volte usando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento bilineare.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.BilinearResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Ridimensiona di 2 volte usando il ricampionamento bilineare.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
}
```

### Guarda anche

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [WmfImage](../../wmfimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Wmf](../../wmfimage)
* assemblea [Aspose.Imaging](../../../)

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

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException |  |

### Guarda anche

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [WmfImage](../../wmfimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Wmf](../../wmfimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
