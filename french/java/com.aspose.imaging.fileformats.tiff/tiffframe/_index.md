---
title: "TiffFrame"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le cadre TIFF."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.tiff/tiffframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class TiffFrame extends RasterCachedImage
```

Le cadre TIFF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffFrame(InputStream stream)](#TiffFrame-java.io.InputStream-) | Initialise une nouvelle instance de la classe `TiffFrame`. |
| [TiffFrame(InputStream stream, TiffOptions options)](#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-) | Initialise une nouvelle instance de la classe `TiffFrame`. |
| [TiffFrame(String path)](#TiffFrame-java.lang.String-) | Initialise une nouvelle instance de la classe `TiffFrame`. |
| [TiffFrame(String path, TiffOptions options)](#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-) | Initialise une nouvelle instance de la classe `TiffFrame`. |
| [TiffFrame(RasterImage image)](#TiffFrame-com.aspose.imaging.RasterImage-) | Initialise une nouvelle instance de la classe `TiffFrame`. |
| [TiffFrame(RasterImage image, TiffOptions options)](#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-) | Initialise une nouvelle instance de la classe `TiffFrame`. |
| [TiffFrame(TiffOptions options, int width, int height)](#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-) | Initialise une nouvelle instance de la classe `TiffFrame`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient une valeur pour la couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Définit une valeur pour la couleur d'arrière-plan. |
| [hasAlpha()](#hasAlpha--) | Obtient une valeur indiquant si cette instance possède de l'alpha. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getFrameOptions()](#getFrameOptions--) | Obtient les options de création du cadre. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtient la résolution horizontale, en pixels par pouce, de ce `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Définit la résolution horizontale, en pixels par pouce, de ce `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtient la résolution verticale, en pixels par pouce, de ce `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Définit la résolution verticale, en pixels par pouce, de ce `RasterImage`. |
| [getPathResources()](#getPathResources--) | Obtient les ressources de chemin. |
| [setPathResources(List<PathResource> value)](#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--) | Définit les ressources de chemin. |
| [removeMetadata()](#removeMetadata--) | Supprime les métadonnées de cette instance d'image en définissant IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) et `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) à `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |
| [alignResolutions()](#alignResolutions--) | Méthode d'assistance pour rendre les résolutions horizontale et verticale égales. |
| [copyFrame(TiffFrame tiffFrame)](#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Copie le cadre entier (dupliques). |
| [createFrameFrom(TiffFrame tiffFrame, TiffOptions options)](#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-) | Crée le cadre à partir du `tiffFrame` spécifié en utilisant les `options` spécifiées. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Fait pivoter, retourner, ou pivoter et retourner l'image. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Faire pivoter l'image autour du centre. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadrage de l'image. |

## Example: This example shows how to create a TIFF image from scratch and save it to a file.

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

### TiffFrame(InputStream stream) {#TiffFrame-java.io.InputStream-}
```
public TiffFrame(InputStream stream)
```


Initialise une nouvelle instance de la classe `TiffFrame`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |

### TiffFrame(InputStream stream, TiffOptions options) {#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(InputStream stream, TiffOptions options)
```


Initialise une nouvelle instance de la classe `TiffFrame`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Les options à utiliser pour le cadre nouvellement créé. |

### TiffFrame(String path) {#TiffFrame-java.lang.String-}
```
public TiffFrame(String path)
```


Initialise une nouvelle instance de la classe `TiffFrame`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |

### TiffFrame(String path, TiffOptions options) {#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(String path, TiffOptions options)
```


Initialise une nouvelle instance de la classe `TiffFrame`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Les options à utiliser pour le cadre nouvellement créé. |

### TiffFrame(RasterImage image) {#TiffFrame-com.aspose.imaging.RasterImage-}
```
public TiffFrame(RasterImage image)
```


Initialise une nouvelle instance de la classe `TiffFrame`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette du cadre. |

### TiffFrame(RasterImage image, TiffOptions options) {#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(RasterImage image, TiffOptions options)
```


Initialise une nouvelle instance de la classe `TiffFrame`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette du cadre. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Les options à utiliser pour le cadre nouvellement créé. |

### TiffFrame(TiffOptions options, int width, int height) {#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-}
```
public TiffFrame(TiffOptions options, int width, int height)
```


Initialise une nouvelle instance de la classe `TiffFrame`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Les options du cadre. |
| width | int | La largeur. |
| height | int | La hauteur. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient une valeur pour la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Définit une valeur pour la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient une valeur indiquant si cette instance possède de l'alpha.

**Returns:**
boolean - `true` si cette instance possède un canal alpha ; sinon, `false`.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Si la trame TIFF active possède un canal alpha, alors l'ensemble de l'image TIFF est considéré comme ayant un canal alpha.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getFrameOptions() {#getFrameOptions--}
```
public TiffOptions getFrameOptions()
```


Obtient les options de création du cadre.

**Returns:**
[TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

**Returns:**
int - La hauteur de l'image.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

**Returns:**
int - La largeur de l'image.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtient la résolution horizontale, en pixels par pouce, de ce `RasterImage`.

**Returns:**
double - La résolution horizontale.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Chargez une image TIFF à partir d'un fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Obtenez la résolution horizontale et verticale du TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Définit la résolution horizontale, en pixels par pouce, de ce `RasterImage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La résolution horizontale. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtient la résolution verticale, en pixels par pouce, de ce `RasterImage`.

**Returns:**
double - La résolution verticale.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Chargez une image TIFF à partir d'un fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Obtenez la résolution horizontale et verticale du TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Définit la résolution verticale, en pixels par pouce, de ce `RasterImage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La résolution verticale. |

### getPathResources() {#getPathResources--}
```
public List<PathResource> getPathResources()
```


Obtient les ressources de chemin.

Valeur : les ressources de chemin.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> - les ressources de chemin.

**Example: The following example shows how to retrieve paths from TIFF image and display their names in the console.**

``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    for (PathResource path : image.getActiveFrame().getPathResources())
    {
        System.out.println(path.getName());
    }
}
```


**Example: The following example shows how to modify already existing Clipping Paths.**
L'exemple suivant montre comment modifier les chemins de découpe déjà existants. Par exemple, vous pouvez ne conserver qu'un seul chemin de découpe dans l'image.
``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    List<PathResource> paths = image.getActiveFrame().getPathResources();
    image.getActiveFrame().setPathResources(Collections.singletonList(paths.get(0)));
    image.save();
}
```


**Example: Transfer Clipping Paths during export from TIFF to PSD image.**

``` java
try (Image image = Image.load("Sample.tif"))
{
    image.save("SampleWithPaths.psd", new PsdOptions());
}
```


**Example: Create Clipping Path manually.**

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Sample.tif"))
    {
        PathResource res = new PathResource();
        res.setBlockId((short) 2000);                                                  // Block Id according to Photoshop specification
        res.setName("My Clipping Path");                                               // Path name
        res.setRecords(createRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)); // Create path records using coordinates
                    
        image.getActiveFrame().setPathResources(Collections.singletonList(res));

        image.save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> createRecords(float ... coordinates)
{
    List<VectorPathRecord>  records = createBezierRecords(coordinates);                                  // Create Bezier records using coordinates

    LengthRecord lr = new LengthRecord(); // LengthRecord required by Photoshop specification
    lr.setOpen(false);                    // Lets create closed path
    lr.setRecordCount(records.size());    // Record count in the path
                
    records.add(0, lr);

    return records;
}

private static List<VectorPathRecord> createBezierRecords(float[] coordinates)
{
    List<VectorPathRecord> l = new LinkedList<VectorPathRecord>();
                
    for (int index = 0; index < coordinates.length - 1; index += 2)
    {
        PointF pt = new PointF(coordinates[index], coordinates[index + 1]);
        BezierKnotRecord br = new BezierKnotRecord();
        br.setPathPoints(new PointF[] {pt, pt, pt});
        l.add(br);
    }
                    
    return l;
}

```

### setPathResources(List<PathResource> value) {#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--}
```
public void setPathResources(List<PathResource> value)
```


Définit les ressources de chemin.

Valeur : les ressources de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> | les ressources de chemin. |

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Supprime les métadonnées de cette instance d'image en définissant IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) et `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) à `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) , une image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### alignResolutions() {#alignResolutions--}
```
public void alignResolutions()
```


Méthode d'assistance pour rendre les résolutions horizontale et verticale égales.

### copyFrame(TiffFrame tiffFrame) {#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public static TiffFrame copyFrame(TiffFrame tiffFrame)
```


Copie le cadre entier (dupliques).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Le cadre TIFF à copier. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly copied tiff frame.
### createFrameFrom(TiffFrame tiffFrame, TiffOptions options) {#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-}
```
public static TiffFrame createFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```


Crée le cadre à partir du `tiffFrame` spécifié en utilisant les `options` spécifiées. Les données de pixels sont conservées mais converties au format souhaité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Le cadre TIFF à créer à partir de. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Les nouvelles options à utiliser. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly created frame.

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

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Fait pivoter, retourner, ou pivoter et retourner l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation et retournement. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resizeProportionally | boolean | si défini sur `true`, la taille de votre image sera modifiée selon les projections du rectangle pivoté (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est pivoté. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrage de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |

