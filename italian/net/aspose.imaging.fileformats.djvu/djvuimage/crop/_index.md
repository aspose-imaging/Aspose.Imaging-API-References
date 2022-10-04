---
title: Crop
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ritaglio dellimmagine.
type: docs
weight: 220
url: /it/net/aspose.imaging.fileformats.djvu/djvuimage/crop/
---
## Crop(Rectangle) {#crop}

Ritaglio dell'immagine.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Il rettangolo. |

### Esempi

L'esempio seguente ritaglia un'immagine DJVU. L'area di ritaglio viene specificata tramite Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Ritaglia l'immagine. L'area di ritaglio è l'area centrale rettangolare dell'immagine.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(djvuImage.Width / 4, djvuImage.Height / 4, djvuImage.Width / 2, djvuImage.Height / 2);
    djvuImage.Crop(area);

    // Salva l'immagine ritagliata in PNG
    djvuImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [DjvuImage](../../djvuimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* assemblea [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Ritaglia immagine con spostamenti.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | Int32 | Il turno di sinistra. |
| rightShift | Int32 | Il turno giusto. |
| topShift | Int32 | Il turno più alto. |
| bottomShift | Int32 | Lo spostamento in basso. |

### Guarda anche

* class [DjvuImage](../../djvuimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->