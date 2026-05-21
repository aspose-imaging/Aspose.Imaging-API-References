---
title: "TiffOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options du format de fichier TIFF."
type: docs
weight: 48
url: /fr/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

Les options du format de fichier TIFF. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de l'image par les paramètres de largeur et de hauteur, il n'est donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut, mais cela ne signifie pas que cette option est définie explicitement comme valeur de balise. Pour vérifier la présence de la balise, utilisez la propriété Tags ou la méthode correspondante IsTagPresent.

` WARNING! ne jamais modifier les options TIFF lors de l'enregistrement car cela peut provoquer des effets secondaires et des bugs difficiles à détecter. La ligne suivante a été spécialement laissée commentée car elle entraînait une détermination incorrecte du début des données. Les options passées ne contenaient pas spp (bien que les options ne soient pas correctes dans ce cas, ce scénario provoque néanmoins des erreurs) et la ligne suivante a ajouté les balises +spp et +bpp et lorsque les options ont été écrites après que les données ont été complètement écrites, elles ont écrasé le début des données pour le codec non compressé !!! Voir TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initialise une nouvelle instance de la classe `TiffOptions`. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initialise une nouvelle instance de la classe `TiffOptions`. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initialise une nouvelle instance de la classe `TiffOptions`. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la classe `TiffOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtient le nombre de balises valides. |
| [getTagCount()](#getTagCount--) | Obtient le nombre de balises. |
| [getFileStandard()](#getFileStandard--) | Obtient ou définit la norme du fichier TIFF. |
| [setFileStandard(int value)](#setFileStandard-int-) | Obtient ou définit la norme du fichier TIFF. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Obtient ou définit la limite d'allocation mémoire par défaut. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Obtient ou définit la limite d'allocation mémoire par défaut. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| [isValid()](#isValid--) | Obtient une valeur indiquant si les `TiffOptions` ont été correctement configurées. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Obtient ou définit les facteurs de sous-échantillonnage pour la photométrie YCbCr. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Obtient ou définit les facteurs de sous-échantillonnage pour la photométrie YCbCr. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Obtient ou définit les YCbCrCoefficients. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit les YCbCrCoefficients. |
| [isTiled()](#isTiled--) | Obtient une valeur indiquant si l'image est découpée en tuiles. |
| [getArtist()](#getArtist--) | Obtient ou définit l'artiste. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Obtient ou définit l'artiste. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Détermine si la balise est présente dans les options ou non. |
| [getByteOrder()](#getByteOrder--) | Obtient ou définit une valeur indiquant l'ordre des octets TIFF. |
| [setByteOrder(int value)](#setByteOrder-int-) | Obtient ou définit une valeur indiquant l'ordre des octets TIFF. |
| [getIccProfile()](#getIccProfile--) | Obtient le flux du profil icc. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Définit le flux du profil icc. |
| [isDisableIccExport()](#isDisableIccExport--) | Obtient une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué aux pixels source au préalable). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | Définit une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué aux pixels source au préalable). |
| [getBitsPerSample()](#getBitsPerSample--) | Obtient les bits par échantillon. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Définit les bits par échantillon. |
| [getExtraSamples()](#getExtraSamples--) | Obtient les valeurs des échantillons supplémentaires. |
| [getCompression()](#getCompression--) | Obtient la compression. |
| [setCompression(int value)](#setCompression-int-) | Définit la compression. |
| [getCompressedQuality()](#getCompressedQuality--) | Obtient la qualité de l'image compressée. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Définit la qualité de l'image compressée. |
| [getCopyright()](#getCopyright--) | Obtient le droit d'auteur. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Définit le droit d'auteur. |
| [getColorMap()](#getColorMap--) | Obtient ou définit la carte des couleurs. |
| [setColorMap(int[] value)](#setColorMap-int---) | Obtient ou définit la carte des couleurs. |
| [getPalette()](#getPalette--) | Obtient ou définit la palette de couleurs. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Obtient ou définit la palette de couleurs. |
| [getDateTime()](#getDateTime--) | Obtient ou définit la date et l'heure. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Obtient ou définit la date et l'heure. |
| [getDocumentName()](#getDocumentName--) | Obtient ou définit le nom du document. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Obtient ou définit le nom du document. |
| [getAlphaStorage()](#getAlphaStorage--) | Obtient ou définit l'option de stockage alpha. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Obtient ou définit l'option de stockage alpha. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Obtient une valeur indiquant si les échantillons supplémentaires sont présents. |
| [getFillOrder()](#getFillOrder--) | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| [setFillOrder(int value)](#setFillOrder-int-) | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| [getHalfToneHints()](#getHalfToneHints--) | Obtient ou définit les indications de demi-teinte. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Obtient ou définit les indications de demi-teinte. |
| [getImageDescription()](#getImageDescription--) | Obtient ou définit la description de l'image. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Obtient ou définit la description de l'image. |
| [getInkNames()](#getInkNames--) | Obtient ou définit les noms d'encre. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Obtient ou définit les noms d'encre. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Obtient ou définit le fabricant du scanner. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Obtient ou définit le fabricant du scanner. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Obtient ou définit la valeur maximale de l'échantillon. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Obtient ou définit la valeur maximale de l'échantillon. |
| [getMinSampleValue()](#getMinSampleValue--) | Obtient ou définit la valeur minimale de l'échantillon. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Obtient ou définit la valeur minimale de l'échantillon. |
| [getScannerModel()](#getScannerModel--) | Obtient ou définit le modèle du scanner. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Obtient ou définit le modèle du scanner. |
| [getOrientation()](#getOrientation--) | Obtient ou définit l'orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Obtient ou définit l'orientation. |
| [getPageName()](#getPageName--) | Obtient ou définit le nom de la page. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Obtient ou définit le nom de la page. |
| [getPageNumber()](#getPageNumber--) | Obtient ou définit l'étiquette du numéro de page. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Obtient ou définit l'étiquette du numéro de page. |
| [getPhotometric()](#getPhotometric--) | Obtient ou définit le photométrique. |
| [setPhotometric(int value)](#setPhotometric-int-) | Obtient ou définit le photométrique. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtient ou définit la configuration planaire. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Obtient ou définit la configuration planaire. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtient ou définit l'unité de résolution. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtient ou définit l'unité de résolution. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Obtient ou définit le nombre de lignes par bande. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Obtient ou définit le nombre de lignes par bande. |
| [getTileWidth()](#getTileWidth--) | Obtient ou définit la largeur de la tuile. |
| [setTileWidth(long value)](#setTileWidth-long-) | Obtient ou définit la largeur de la tuile. |
| [getTileLength()](#getTileLength--) | Obtient ou définit la longueur de la tuile. |
| [setTileLength(long value)](#setTileLength-long-) | Obtient ou définit la longueur de la tuile. |
| [getSampleFormat()](#getSampleFormat--) | Obtient ou définit le format d'échantillon. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Obtient ou définit le format d'échantillon. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtient les échantillons par pixel. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Obtient ou définit la valeur maximale de l'échantillon. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Obtient ou définit la valeur maximale de l'échantillon. |
| [getSminSampleValue()](#getSminSampleValue--) | Obtient ou définit la valeur minimale de l'échantillon. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Obtient ou définit la valeur minimale de l'échantillon. |
| [getSoftwareType()](#getSoftwareType--) | Obtient ou définit le type de logiciel. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Obtient ou définit le type de logiciel. |
| [getStripByteCounts()](#getStripByteCounts--) | Obtient ou définit le nombre d'octets par bande. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Obtient ou définit le nombre d'octets par bande. |
| [getStripOffsets()](#getStripOffsets--) | Obtient ou définit les décalages de bande. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Obtient ou définit les décalages de bande. |
| [getTileByteCounts()](#getTileByteCounts--) | Obtient ou définit les comptes d'octets des tuiles. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Obtient ou définit les comptes d'octets des tuiles. |
| [getTileOffsets()](#getTileOffsets--) | Obtient ou définit les décalages de tuile. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Obtient ou définit les décalages de tuile. |
| [getSubFileType()](#getSubFileType--) | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| [setSubFileType(long value)](#setSubFileType-long-) | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| [getTargetPrinter()](#getTargetPrinter--) | Obtient ou définit l'imprimante cible. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Obtient ou définit l'imprimante cible. |
| [getThreshholding()](#getThreshholding--) | Obtient ou définit le seuillage. |
| [setThreshholding(int value)](#setThreshholding-int-) | Obtient ou définit le seuillage. |
| [getTotalPages()](#getTotalPages--) | Obtient le nombre total de pages. |
| [getXposition()](#getXposition--) | Obtient ou définit la position x. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la position x. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtient ou définit les paramètres de résolution. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Obtient ou définit les paramètres de résolution. |
| [getXresolution()](#getXresolution--) | Obtient ou définit la résolution x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution x. |
| [getYposition()](#getYposition--) | Obtient ou définit la position y. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la position y. |
| [getYresolution()](#getYresolution--) | Obtient ou définit la résolution y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution y. |
| [getFaxT4Options()](#getFaxT4Options--) | Obtient ou définit les options fax t4. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Obtient ou définit les options fax t4. |
| [getPredictor()](#getPredictor--) | Obtient ou définit le prédicteur pour la compression LZW. |
| [setPredictor(int value)](#setPredictor-int-) | Obtient ou définit le prédicteur pour la compression LZW. |
| [getImageLength()](#getImageLength--) | Obtient ou définit la longueur de l'image. |
| [setImageLength(long value)](#setImageLength-long-) | Obtient ou définit la longueur de l'image. |
| [getImageWidth()](#getImageWidth--) | Obtient ou définit la largeur de l'image. |
| [setImageWidth(long value)](#setImageWidth-long-) | Obtient ou définit la largeur de l'image. |
| [getExifIfd()](#getExifIfd--) | Obtient ou définit le pointeur vers l'EXIF IFD. |
| [getTags()](#getTags--) | Obtient ou définit les balises. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises. |
| [getValidTagCount()](#getValidTagCount--) | Obtient le nombre de balises valides. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient les bits par pixel. |
| [getXPTitle()](#getXPTitle--) | Obtient les informations sur l'image, utilisées par l'Explorateur Windows. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| [getXPComment()](#getXPComment--) | Obtient le commentaire sur l'image, utilisé par l'Explorateur Windows. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Définit le commentaire sur l'image, utilisé par l'Explorateur Windows. |
| [getXPAuthor()](#getXPAuthor--) | Obtient l'auteur de l'image, utilisé par l'Explorateur Windows. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Définit l'auteur de l'image, utilisé par l'Explorateur Windows. |
| [getXPKeywords()](#getXPKeywords--) | Obtient le sujet de l'image, utilisé par l'Explorateur Windows. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Définit l'image du sujet, utilisée par l'Explorateur Windows. |
| [getXPSubject()](#getXPSubject--) | Obtient les informations sur l'image, utilisées par l'Explorateur Windows. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| [getExifData()](#getExifData--) | Obtient les données Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Définit les données Exif. |
| [removeTag(int tag)](#removeTag-int-) | Supprime l'étiquette. |
| [removeTags(int[] tags)](#removeTags-int...-) | Supprime les étiquettes. |
| [validate()](#validate--) | Valide si les options ont une combinaison valide d'étiquettes |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ajoute les étiquettes. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Ajoute une nouvelle étiquette. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Obtient l'instance de l'étiquette par type. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Cet exemple montre l'utilisation de différentes classes du namespace SaveOptions à des fins d'exportation. Une image de type Gif est chargée dans une instance de Image, puis exportée vers plusieurs formats.
``` java
String dir = "c:\\temp\\";

//Chargez une image existante (de type Gif) dans une instance de la classe Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportez au format de fichier BMP en utilisant les options par défaut.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportez au format de fichier JPEG en utilisant les options par défaut.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportez au format de fichier PNG en utilisant les options par défaut.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportez au format de fichier TIFF en utilisant les options par défaut.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporte uniquement les deux premières pages. Ces pages seront présentées comme des cadres dans le TIFF de sortie.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Initialise une nouvelle instance de la classe `TiffOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| expectedFormat | int | Le format de fichier TIFF attendu. |
| byteOrder | int | L'ordre des octets du format de fichier TIFF. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initialise une nouvelle instance de la classe `TiffOptions`. Par défaut, la convention little endian est utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| expectedFormat | int | Le format de fichier TIFF attendu. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initialise une nouvelle instance de la classe `TiffOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Les options à copier. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initialise une nouvelle instance de la classe `TiffOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les étiquettes avec lesquelles initialiser les options. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Obtient le nombre de balises valides.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les étiquettes à valider. |

**Returns:**
int - Le nombre d'étiquettes valides.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Obtient le nombre de balises.

**Returns:**
int - le nombre d'étiquettes.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Obtient ou définit la norme du fichier TIFF.

**Returns:**
int - La norme du fichier TIFF.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Obtient ou définit la norme du fichier TIFF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La norme du fichier TIFF. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Obtient ou définit la limite d'allocation mémoire par défaut.

**Returns:**
int - La limite d'allocation mémoire par défaut.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Obtient ou définit la limite d'allocation mémoire par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La limite d'allocation mémoire par défaut. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés.

**Returns:**
boolean - `true` si les composants doivent être prémultipliés ; sinon, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si les composants doivent être prémultipliés ; sinon, `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Obtient une valeur indiquant si le `TiffOptions` a été correctement configuré. Utilisez la méthode Validate pour trouver la raison de l'échec.

**Returns:**
boolean - `true` si TiffOptions est correctement configuré ; sinon, `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Obtient ou définit les facteurs de sous-échantillonnage pour la photométrie YCbCr.

**Returns:**
int[] - Les facteurs de sous-échantillonnage pour le photométrique YCbCr.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Obtient ou définit les facteurs de sous-échantillonnage pour la photométrie YCbCr.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | Les facteurs de sous-échantillonnage pour le photométrique YCbCr. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Définit 8 bits pour chaque composant de couleur.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Définit l'ordre des octets Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Définit la compression LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Permet de réduire la taille des images à tons continus.
// Actuellement ce champ n'est utilisé qu'avec l'encodage LZW car LZW est probablement le seul schéma d'encodage TIFF.
// qui bénéficie considérablement d'une étape de prédicteur.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Définit le modèle de couleur RVB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Pour YCbCr, vous pouvez utiliser l'une des options suivantes :
// Champ YCbCrSubSampling   Facteurs d'échantillonnage JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valeur par défaut)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tous les composants de couleur seront stockés dans un seul plan.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Créez un cadre TIFF de 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Remplissez l'intégralité de l'image avec le dégradé bleu-jaune.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Obtient ou définit les YCbCrCoefficients.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Les YCbCrCoefficients.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Obtient ou définit les YCbCrCoefficients.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Les YCbCrCoefficients. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Obtient une valeur indiquant si l'image est découpée en tuiles.

**Returns:**
booléen - `true` si l'image est découpée en tuiles ; sinon, `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtient ou définit l'artiste.

**Returns:**
java.lang.String - L'artiste.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Obtient ou définit l'artiste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | L'artiste. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Détermine si la balise est présente dans les options ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tag | int | L'identifiant du tag à vérifier. |

**Returns:**
booléen - `true` si le tag est présent ; sinon, `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Obtient ou définit une valeur indiquant l'ordre des octets TIFF.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Obtient ou définit une valeur indiquant l'ordre des octets TIFF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Définit 8 bits pour chaque composant de couleur.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Définit l'ordre des octets Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Définit la compression LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Permet de réduire la taille des images à tons continus.
// Actuellement ce champ n'est utilisé qu'avec l'encodage LZW car LZW est probablement le seul schéma d'encodage TIFF.
// qui bénéficie considérablement d'une étape de prédicteur.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Définit le modèle de couleur RVB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Pour YCbCr, vous pouvez utiliser l'une des options suivantes :
// Champ YCbCrSubSampling   Facteurs d'échantillonnage JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valeur par défaut)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tous les composants de couleur seront stockés dans un seul plan.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Créez un cadre TIFF de 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Remplissez l'intégralité de l'image avec le dégradé bleu-jaune.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Obtient le flux du profil icc.

**Returns:**
byte[] - Le profil icc.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Définit le flux du profil icc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] | Le profil icc. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


Obtient une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué aux pixels source au préalable).

**Returns:**
booléen - une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué aux pixels source au préalable).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


Définit une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué aux pixels source au préalable).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué aux pixels source au préalable). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Obtient les bits par échantillon.

**Returns:**
int[] - La valeur des bits par échantillon.

Lors de la définition de cette valeur, gardez à l'esprit qu'elle définira également la valeur SamplesPerPixel à la longueur du tableau. Ces 2 propriétés sont très étroitement liées, il se peut donc qu'elles ne puissent être définies qu'ensemble.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Définit les bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | La valeur des bits par échantillon. |

Lors de la définition de cette valeur, gardez à l'esprit qu'elle définira également la valeur SamplesPerPixel à la longueur du tableau. Ces 2 propriétés sont très étroitement liées, il se peut donc qu'elles ne puissent être définies qu'ensemble. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Créez une source de fichier permanente, pas temporaire.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Remplissez le cadre actif avec un pinceau à dégradé linéaire.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Options de niveaux de gris
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Créez une copie en niveaux de gris du cadre actif.
    // Les données de pixels sont conservées mais converties au format souhaité.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Ajoutez le cadre nouvellement créé à l'image TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


Obtient les valeurs des échantillons supplémentaires.

Valeur : la valeur des échantillons supplémentaires.

**Returns:**
int[] - les valeurs des échantillons supplémentaires.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtient la compression.

**Returns:**
int - La compression.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Définit la compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La compression. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// Options pour le premier cadre
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Définit 8 bits pour chaque composant de couleur.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Définit l'ordre des octets Big Endian (Motorola)
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Définit la compression LZW.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Définit le modèle de couleur RVB.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Tous les composants de couleur seront stockés dans un seul plan.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Créez le premier cadre TIFF de 100x100 px.
// Notez que vous n'avez pas besoin de libérer les cadres explicitement s'ils sont inclus dans TiffImage.
// Lorsque le conteneur est libéré, tous les cadres seront libérés automatiquement.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// Remplissez le premier cadre avec le dégradé bleu-jaune.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// Options pour le premier cadre
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Définissez 1 bit par pixel pour une image N/B.
createOptions2.setBitsPerSample(new int[]{1});

// Définissez l'ordre des octets Little Endian (Intel)
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// Définissez la compression CCITT Group 3 Fax.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// Définissez le modèle de couleur N/B où 0 est noir, 1 est blanc.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// Créez le deuxième cadre TIFF de 200x200px.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// Remplissez le deuxième cadre avec le dégradé bleu-jaune.
// Il sera automatiquement converti au format N/B en raison des paramètres correspondants du cadre.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Créez une image TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Obtient la qualité d'image compressée. Utilisé avec la compression Jpeg.

**Returns:**
int - qualité d'image compressée.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Définit la qualité d'image compressée. Utilisé avec la compression Jpeg.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | qualité d'image compressée. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // Définit le modèle de couleur RVB.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Définissez la compression Jpeg.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Définit 8 bits pour chaque composant de couleur.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtient le droit d'auteur.

**Returns:**
java.lang.String - Le droit d'auteur.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Définit le droit d'auteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le droit d'auteur. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Obtient ou définit la carte des couleurs.

**Returns:**
int[] - La table de couleur.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Obtient ou définit la carte des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La table de couleur. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient ou définit la palette de couleurs.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtient ou définit la palette de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Obtient ou définit la date et l'heure.

**Returns:**
java.lang.String - La date et l'heure.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Obtient ou définit la date et l'heure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La date et l'heure. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Obtient ou définit le nom du document.

**Returns:**
java.lang.String - Le nom du document.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Obtient ou définit le nom du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le nom du document. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Obtient ou définit l'option de stockage alpha. Les options autres que `TiffAlphaStorage.Unspecified` sont utilisées lorsqu'il y a plus de 3 `SamplesPerPixel` définis.

**Returns:**
int - L'option de stockage alpha.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Obtient ou définit l'option de stockage alpha. Les options autres que `TiffAlphaStorage.Unspecified` sont utilisées lorsqu'il y a plus de 3 `SamplesPerPixel` définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'option de stockage alpha. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Obtient une valeur indiquant si les échantillons supplémentaires sont présents.

**Returns:**
boolean - `true` si les échantillons supplémentaires sont présents ; sinon, `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Obtient ou définit l'ordre de remplissage des bits d'octet.

**Returns:**
int - L'ordre de remplissage des bits d'octet.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Obtient ou définit l'ordre de remplissage des bits d'octet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'ordre de remplissage des bits d'octet. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Obtient ou définit les indications de demi-teinte.

**Returns:**
int[] - Les indices de demi-teinte.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Obtient ou définit les indications de demi-teinte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | Les indices de demi-teinte. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Obtient ou définit la description de l'image.

**Returns:**
java.lang.String - La description de l'image.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Obtient ou définit la description de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La description de l'image. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Obtient ou définit les noms d'encre.

**Returns:**
java.lang.String - Les noms d'encre.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Obtient ou définit les noms d'encre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Les noms d'encre. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Obtient ou définit le fabricant du scanner.

**Returns:**
java.lang.String - Le fabricant du scanner.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Obtient ou définit le fabricant du scanner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le fabricant du scanner. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Obtient ou définit la valeur maximale de l'échantillon.

**Returns:**
int[] - La valeur maximale d'échantillon.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Obtient ou définit la valeur maximale de l'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La valeur maximale d'échantillon. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Obtient ou définit la valeur minimale de l'échantillon.

**Returns:**
int[] - La valeur minimale d'échantillon.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Obtient ou définit la valeur minimale de l'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La valeur minimale d'échantillon. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Obtient ou définit le modèle du scanner.

**Returns:**
java.lang.String - Le modèle du scanner.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Obtient ou définit le modèle du scanner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le modèle du scanner. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtient ou définit l'orientation.

**Returns:**
int - L'orientation [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Obtient ou définit l'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | L'orientation [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Obtient ou définit le nom de la page.

**Returns:**
java.lang.String - Le nom de la page.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Obtient ou définit le nom de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le nom de la page. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Obtient ou définit l'étiquette du numéro de page.

**Returns:**
int[] - L'étiquette du numéro de page.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Obtient ou définit l'étiquette du numéro de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | L'étiquette du numéro de page. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Obtient ou définit le photométrique.

**Returns:**
int - Le photométrique.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Obtient ou définit le photométrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le photométrique. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Créez une source de fichier permanente, pas temporaire.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Remplissez le cadre actif avec un pinceau à dégradé linéaire.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Options de niveaux de gris
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Créez une copie en niveaux de gris du cadre actif.
    // Les données de pixels sont conservées mais converties au format souhaité.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Ajoutez le cadre nouvellement créé à l'image TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtient ou définit la configuration planaire.

**Returns:**
int - La configuration planaire.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Obtient ou définit la configuration planaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La configuration planaire. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Définit 8 bits pour chaque composant de couleur.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Définit l'ordre des octets Big Endian (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Définit la compression LZW.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Définit le modèle de couleur RVB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Tous les composants de couleur seront stockés dans un seul plan.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Créez un cadre TIFF de 100x100 px.
// Notez que vous n'avez pas besoin de libérer explicitement un cadre s'il est inclus dans TiffImage.
// Lorsque le conteneur est libéré, tous les cadres seront libérés automatiquement.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Remplissez le cadre entier avec le dégradé bleu-jaune.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Créez une image TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Obtient ou définit l'unité de résolution.

**Returns:**
int - L'unité de résolution.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Obtient ou définit l'unité de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'unité de résolution. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Obtient ou définit le nombre de lignes par bande.

**Returns:**
long - Le nombre de lignes par bande.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Obtient ou définit le nombre de lignes par bande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Le nombre de lignes par bande. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Obtient ou définit la largeur de la tuile.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Obtient ou définit la largeur de la tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Obtient ou définit la longueur de la tuile.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Obtient ou définit la longueur de la tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Obtient ou définit le format d'échantillon.

**Returns:**
int[] - Le format d'échantillon.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Obtient ou définit le format d'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | Le format d'échantillon. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtient les échantillons par pixel. Pour modifier la valeur de cette propriété, utilisez le setter de propriété `BitsPerSample`.

**Returns:**
int - Le nombre d'échantillons par pixel.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Obtient ou définit la valeur maximale d'échantillon. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Returns:**
long[] - La valeur maximale d'échantillon.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Obtient ou définit la valeur maximale d'échantillon. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | La valeur maximale d'échantillon. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Obtient ou définit la valeur minimale d'échantillon. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Returns:**
long[] - La valeur minimale d'échantillon.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Obtient ou définit la valeur minimale d'échantillon. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | La valeur minimale d'échantillon. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Obtient ou définit le type de logiciel.

**Returns:**
java.lang.String - Le type de logiciel.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Obtient ou définit le type de logiciel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le type de logiciel. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Obtient ou définit le nombre d'octets par bande.

**Returns:**
long[] - Le nombre d'octets par bande.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Obtient ou définit le nombre d'octets par bande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | Le nombre d'octets par bande. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Obtient ou définit les décalages de bande.

**Returns:**
long[] - Les décalages de bande.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Obtient ou définit les décalages de bande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] | Les décalages de bande. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Obtient ou définit les comptes d'octets des tuiles.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Obtient ou définit les comptes d'octets des tuiles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Obtient ou définit les décalages de tuile.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Obtient ou définit les décalages de tuile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier.

**Returns:**
long - L'indication générale du type de données contenues dans ce sous-fichier.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | L'indication générale du type de données contenues dans ce sous-fichier. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Obtient ou définit l'imprimante cible.

**Returns:**
java.lang.String - L'imprimante cible.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Obtient ou définit l'imprimante cible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | L'imprimante cible. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Obtient ou définit le seuillage.

**Returns:**
int - Le seuillage.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Obtient ou définit le seuillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le seuillage. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Obtient le nombre total de pages.

**Returns:**
int - Le nombre total de pages.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Obtient ou définit la position x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Obtient ou définit la position x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La position x. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtient ou définit les paramètres de résolution.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtient ou définit les paramètres de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Obtient ou définit la résolution x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Obtient ou définit la résolution x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La résolution x. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Obtient ou définit la position y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Obtient ou définit la position y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La position y. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Obtient ou définit la résolution y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Obtient ou définit la résolution y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La résolution y. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Obtient ou définit les options fax t4.

**Returns:**
long - Les options fax t4.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Obtient ou définit les options fax t4.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Les options fax t4. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Obtient ou définit le prédicteur pour la compression LZW.

**Returns:**
int - Le type de prédicteur.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Obtient ou définit le prédicteur pour la compression LZW.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le type de prédicteur. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Définit 8 bits pour chaque composant de couleur.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Définit l'ordre des octets Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Définit la compression LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Permet de réduire la taille des images à tons continus.
// Actuellement ce champ n'est utilisé qu'avec l'encodage LZW car LZW est probablement le seul schéma d'encodage TIFF.
// qui bénéficie considérablement d'une étape de prédicteur.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Définit le modèle de couleur RVB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Pour YCbCr, vous pouvez utiliser l'une des options suivantes :
// Champ YCbCrSubSampling   Facteurs d'échantillonnage JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valeur par défaut)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tous les composants de couleur seront stockés dans un seul plan.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Créez un cadre TIFF de 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Remplissez l'intégralité de l'image avec le dégradé bleu-jaune.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Obtient ou définit la longueur de l'image.

**Returns:**
long - La longueur de l'image.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Obtient ou définit la longueur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La longueur de l'image. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Obtient ou définit la largeur de l'image.

**Returns:**
long - La largeur de l'image.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Obtient ou définit la largeur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La largeur de l'image. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Obtient ou définit le pointeur vers l'EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Obtient ou définit les balises.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - Les balises.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Obtient ou définit les balises.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Obtient le nombre de balises valides. Ce n'est pas le nombre total de balises mais le nombre de balises qui peuvent être conservées.

**Returns:**
int - Le nombre de balises valides.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient les bits par pixel.

**Returns:**
int - Le nombre de bits par pixel.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Obtient les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Information sur l'image, utilisée par Windows Explorer. Le `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) est ignoré par Windows Explorer si la balise `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) existe.

**Returns:**
java.lang.String - information sur l'image, qui est utilisée par Windows Explorer.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Définit les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Information sur l'image, utilisée par Windows Explorer. Le `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) est ignoré par Windows Explorer si la balise `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) existe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | information sur l'image, qui est utilisée par Windows Explorer. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Obtient le commentaire sur l'image, utilisé par l'Explorateur Windows.

Valeur : Commentaire sur l'image, utilisé par Windows Explorer.

**Returns:**
java.lang.String - commentaire sur l'image, qui est utilisé par Windows Explorer.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Définit le commentaire sur l'image, utilisé par l'Explorateur Windows.

Valeur : Commentaire sur l'image, utilisé par Windows Explorer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | commentaire sur l'image, utilisé par l'Explorateur Windows. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Obtient l'auteur de l'image, utilisé par l'Explorateur Windows.

Valeur : Auteur de l'image, utilisé par l'Explorateur Windows. Le `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) est ignoré par l'Explorateur Windows si le tag `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) existe.

**Returns:**
java.lang.String - auteur de l'image, utilisé par l'Explorateur Windows.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Définit l'auteur de l'image, utilisé par l'Explorateur Windows.

Valeur : Auteur de l'image, utilisé par l'Explorateur Windows. Le `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) est ignoré par l'Explorateur Windows si le tag `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) existe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | auteur de l'image, utilisé par l'Explorateur Windows. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Obtient le sujet de l'image, utilisé par l'Explorateur Windows.

Valeur : Image sujet, utilisé par l'Explorateur Windows.

**Returns:**
java.lang.String - image sujet, utilisé par l'Explorateur Windows.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Définit l'image du sujet, utilisée par l'Explorateur Windows.

Valeur : Image sujet, utilisé par l'Explorateur Windows.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | image sujet, utilisé par l'Explorateur Windows. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Obtient les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Informations sur l'image, utilisé par l'Explorateur Windows.

**Returns:**
java.lang.String - information sur l'image, qui est utilisée par Windows Explorer.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Définit les informations sur l'image, utilisées par l'Explorateur Windows.

Valeur : Informations sur l'image, utilisé par l'Explorateur Windows.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | information sur l'image, qui est utilisée par Windows Explorer. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtient les données Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Définit les données Exif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Données Exif. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Supprime l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tag | int | Le tag à supprimer. |

**Returns:**
boolean - vrai si supprimé avec succès
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Supprime les étiquettes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tags | int[] | Les tags à supprimer. |

**Returns:**
boolean - `` si la taille de la collection de tags a changé.
### validate() {#validate--}
```
public void validate()
```


Valide si les options ont une combinaison valide d'étiquettes

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Ajoute les étiquettes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les tags à ajouter. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Ajoute une nouvelle étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Le tag à ajouter. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Obtient l'instance de l'étiquette par type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagKey | int | La clé du tag. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
