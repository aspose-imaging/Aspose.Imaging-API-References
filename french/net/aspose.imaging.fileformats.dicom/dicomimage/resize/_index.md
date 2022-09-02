---
title: Resize
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Redimensionne limage.
type: docs
weight: 260
url: /fr/net/aspose.imaging.fileformats.dicom/dicomimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Redimensionne l'image.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| resizeType | ResizeType | Le type de redimensionnement. |

### Exemples

Cet exemple charge une image DICOM et la redimensionne à l'aide de diverses méthodes de redimensionnement.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Augmentez de 2 fois l'échelle à l'aide du rééchantillonnage du voisin le plus proche.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Réduire de 2 fois en utilisant le rééchantillonnage du voisin le plus proche.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
        
    // Enregistrer au format PNG avec les options par défaut.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Augmentez de 2 fois l'échelle en utilisant le rééchantillonnage bilinéaire.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
        
    // Enregistrer au format PNG avec les options par défaut.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [DicomImage](../../dicomimage)
* espace de noms [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* Assemblée [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Redimensionne l'image.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| settings | ImageResizeSettings | Les paramètres de redimensionnement. |

### Exemples

Cet exemple charge une image DICOM et la redimensionne à l'aide de divers paramètres de redimensionnement.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// L'algorithme adaptatif basé sur la fonction rationnelle pondérée et mélangée et l'interpolation lanczos3.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// Le petit filtre rectangulaire
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// Le nombre de couleurs dans la palette.
resizeSettings.EntriesCount = 256;

// La quantification des couleurs n'est pas utilisée
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// La méthode euclidienne
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Réduire de 2 fois en utilisant le rééchantillonnage adaptatif.
    dicomImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // Enregistrer en PNG
    dicomImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [DicomImage](../../dicomimage)
* espace de noms [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
