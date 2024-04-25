---
title: DicomOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de création de format de fichier DICOM.
type: docs
weight: 9940
url: /fr/aspose.imaging.imageoptions/dicomoptions/
---
## DicomOptions class

Les options de création de format de fichier DICOM.

```csharp
public class DicomOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DicomOptions](dicomoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ColorType](../../aspose.imaging.imageoptions/dicomoptions/colortype) { get; set; } | Obtient ou définit le type de la couleur. |
| [Compression](../../aspose.imaging.imageoptions/dicomoptions/compression) { get; set; } | Obtient ou définit la compression. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.imaging.imageoptions/dicomoptions/xmpdata) { get; set; } | Obtient ou définit les données Xmp. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

Modifier le type de couleur dans la compression DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Utilisez la compression RLE dans l'image DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

Utilisez la compression JPEG 2000 dans l'image DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

Utilisez la compression JPEG dans l'image DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

L'exemple suivant montre l'exportation au format de fichier DICOM (page unique et multipage).

```csharp
[C#]

string fileName = "sample.jpg";
string inputFileNameSingle = fileName;
string inputFileNameMultipage = "multipage.tif";
string outputFileNameSingleDcm = "output.dcm";
string outputFileNameMultipageDcm = "outputMultipage.dcm";

// L'exemple de code suivant convertit l'image JPEG au format de fichier DICOM
using (var image = Aspose.Imaging.Image.Load(inputFileNameSingle))
{
    image.Save(outputFileNameSingleDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}

// Le format DICOM prend en charge les images multipages. Vous pouvez convertir des images GIF ou TIFF en DICOM de la même manière que les images JPEG
using (var imageMultiple = Aspose.Imaging.Image.Load(inputFileNameMultipage))
{
    imageMultiple.Save(outputFileNameMultipageDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}
```

Créez une image Dicom de plusieurs pages.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // Dessine quelque chose en utilisant des graphiques vectoriels
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Enregistre les pixels de l'image dessinée. Ils sont maintenant sur la première page de l'image Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // Ajoute quelques pages après, les rendant plus sombres
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // Ajoute quelques pages devant la page principale, les rendant plus lumineuses
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // Enregistre l'image multi-pages créée dans le fichier de sortie
    image.Save("MultiPage.dcm");
}
```

### Voir également

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espace de noms [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
