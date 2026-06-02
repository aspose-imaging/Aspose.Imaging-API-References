---
title: "DicomOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API pour la création du format d'image raster DICOM (Digital Imaging and Communications in Medicine) est un outil spécialisé conçu pour les applications de dispositifs médicaux."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.imageoptions/dicomoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DicomOptions extends ImageOptionsBase
```

L'API de création de format d'image raster Digital Imaging and Communications in Medicine (DICOM) est un outil spécialisé conçu pour les applications de dispositifs médicaux. Elle permet la génération fluide d'images DICOM, essentielles pour le stockage des données médicales et contenant des informations d'identification vitales. Avec des fonctionnalités pour définir la compression, spécifier les types de couleur et intégrer les métadonnées XMP, les développeurs peuvent garantir la conformité et la flexibilité dans la gestion des images DICOM à des fins d'imagerie médicale.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DicomOptions()](#DicomOptions--) | Initialise une nouvelle instance de la classe [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions). |
| [DicomOptions(DicomOptions options)](#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompression()](#getCompression--) | Obtient la compression. |
| [setCompression(Compression value)](#setCompression-com.aspose.imaging.fileformats.dicom.Compression-) | Définit la compression. |
| [getColorType()](#getColorType--) | Obtient le type de la couleur. |
| [setColorType(int value)](#setColorType-int-) | Définit le type de la couleur. |

## Example: The following example shows export to DICOM file format (single and multipage).

``` java
String fileName = "sample.jpg";
String inputFileNameSingle = fileName;
String inputFileNameMultipage = "multipage.tif";
String outputFileNameSingleDcm = "output.dcm";
String outputFileNameMultipageDcm = "outputMultipage.dcm";

// L'exemple de code suivant convertit une image JPEG au format de fichier DICOM.
try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileNameSingle))
{
    image.save(outputFileNameSingleDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}

// Le format DICOM prend en charge les images multipages. Vous pouvez convertir des images GIF ou TIFF en DICOM de la même manière que les images JPEG.
try(com.aspose.imaging.Image imageMultiple = com.aspose.imaging.Image.load(inputFileNameMultipage))
{
    imageMultiple.save(outputFileNameMultipageDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Dessinez quelque chose en utilisant des graphiques vectoriels.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Enregistrez les pixels de l'image dessinée. Ils se trouvent maintenant sur la première page de l'image Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Ajoutez quelques pages après, les rendant plus sombres.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Ajoutez quelques pages avant la page principale, les rendant plus claires.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Enregistrez l'image multipage créée dans le fichier de sortie.
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomOptions() {#DicomOptions--}
```
public DicomOptions()
```


Initialise une nouvelle instance de la classe [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions).

### DicomOptions(DicomOptions options) {#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-}
```
public DicomOptions(DicomOptions options)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) |  |

### getCompression() {#getCompression--}
```
public final Compression getCompression()
```


Obtient la compression.

Valeur : la compression.

**Returns:**
[Compression](../../com.aspose.imaging.fileformats.dicom/compression) - the compression.
### setCompression(Compression value) {#setCompression-com.aspose.imaging.fileformats.dicom.Compression-}
```
public final void setCompression(Compression value)
```


Définit la compression.

Valeur : la compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Compression](../../com.aspose.imaging.fileformats.dicom/compression) | la compression. |

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Obtient le type de la couleur.

Valeur : le type de la couleur.

**Returns:**
int - le type de la couleur.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Définit le type de la couleur.

Valeur : le type de la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le type de la couleur. |


**Example: Use JPEG compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


**Example: Use JPEG 2000 compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


**Example: Use RLE compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


**Example: Change Color Type in DICOM compression.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

