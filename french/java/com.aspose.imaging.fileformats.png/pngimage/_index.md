---
title: "PngImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez les images raster PNG (Portable Network Graphics) avec notre API polyvalente offrant la prise en charge des niveaux de compression et de diverses profondeurs de couleur, y compris le niveau de gris, la couleur indexée, le TrueColor et les canaux alpha."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

Manipulez les images raster Portable Network Graphics (PNG) avec notre API polyvalente, offrant la prise en charge des niveaux de compression et de diverses profondeurs de couleur, y compris le niveau de gris, la couleur indexée, le TrueColor et les canaux alpha. Traitez sans effort les métadonnées XMP, permettant une gestion complète des métadonnées d'image, tout en chargeant facilement les images PNG, en effectuant diverses manipulations, en appliquant des filtres et en convertissant les images vers d’autres formats de fichiers pour une polyvalence et une personnalisation optimales.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Initialisez un nouvel objet de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en fournissant les paramètres de largeur et de hauteur. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Construit une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en utilisant le paramètre de chemin pour spécifier l'emplacement du fichier image à charger. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Crée une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en fournissant une image raster comme paramètre. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Initialise une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en spécifiant le chemin du fichier image et le type de couleur. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Crée une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en spécifiant une image raster et un type de couleur. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Crée une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en l'initialisant avec un flux. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Instanciez une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), en spécifiant les paramètres souhaités de largeur, de hauteur et de type de couleur. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Initialisez une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), en incorporant les options PNG ainsi que les paramètres de largeur et de hauteur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupérez la valeur des bits par pixel de l'image. |
| [getHeight()](#getHeight--) | Obtenez la hauteur de l'image en pixels. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Récupérez ou modifiez la résolution horizontale de l'image. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Récupérez ou modifiez la résolution horizontale de l'image. |
| [getFileFormat()](#getFileFormat--) | Récupère le format du fichier associé à l'instance d'image. |
| [getRawDataFormat()](#getRawDataFormat--) | Accède au format des données brutes de l'image. |
| [getVerticalResolution()](#getVerticalResolution--) | Fournit l'accès à la résolution verticale de l'image. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Fournit l'accès à la résolution verticale de l'image. |
| [getWidth()](#getWidth--) | Permet de récupérer la largeur de l'image en pixels, fournissant des informations essentielles sur ses dimensions. |
| [hasTransparentColor()](#hasTransparentColor--) | Fournit une valeur booléenne indiquant si l'image contient une couleur transparente. |
| [hasAlpha()](#hasAlpha--) | Renvoie une valeur booléenne indiquant si l'image possède un canal alpha, ce qui détermine sa transparence. |
| [getTransparentColor()](#getTransparentColor--) | Récupère la couleur transparente de l'image, si elle existe. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Fournit une valeur booléenne indiquant si l'image contient une couleur transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Modifie la couleur transparente de l'image, si elle existe. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Récupère une valeur booléenne indiquant si l'image possède une couleur d'arrière-plan. |
| [getBackgroundColor()](#getBackgroundColor--) | Récupère la couleur d'arrière-plan de l'image, si elle est spécifiée. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Récupère une valeur booléenne indiquant si l'image possède une couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Récupère la couleur d'arrière-plan de l'image, si elle est spécifiée. |
| [getInterlaced()](#getInterlaced--) | Récupère une valeur booléenne indiquant si le [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est entrelacé, ce qui détermine si les données de l'image sont stockées de manière progressive pour un chargement ou une transmission plus rapides. |
| [isInterlaced()](#isInterlaced--) | Obtient une valeur indiquant si cette instance d'image est entrelacée. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtient les options par défaut. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Charger une image PNG depuis un fichier.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Transformer l'image en représentation en niveaux de gris
    pngImage.grayscale();

    // Enregistrer dans un fichier.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Initialisez un nouvel objet de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en fournissant les paramètres de largeur et de hauteur. Ce constructeur simplifie la création d'images PNG en permettant aux développeurs de spécifier directement les dimensions, facilitant ainsi la gestion efficace des données d'images PNG au sein de leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Construit une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en utilisant le paramètre de chemin pour spécifier l'emplacement du fichier image à charger. Ce constructeur permet aux développeurs de créer facilement des images PNG en les chargeant depuis un fichier, simplifiant le processus de travail avec les images PNG dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin pour charger une image. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Crée une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en fournissant une image raster en paramètre. Ce constructeur permet aux développeurs d'initialiser directement un objet image PNG à partir d'une image raster existante, rationalisant le processus de travail avec les images PNG dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Initialise une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en spécifiant le chemin du fichier image et le type de couleur. Ce constructeur permet une création pratique d'images PNG à partir de fichiers avec différents types de couleur, offrant une flexibilité dans la gestion de divers formats d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin pour charger une image. |
| colorType | int | Le type de couleur. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Crée une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en spécifiant une image raster et un type de couleur. Ce constructeur permet aux développeurs de convertir directement les images raster au format PNG tout en spécifiant le type de couleur souhaité, offrant une flexibilité dans la représentation des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| colorType | int | Le type de couleur. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Crée une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) en l'initialisant avec un flux. Ce constructeur permet aux développeurs de charger des images PNG directement à partir d'un flux, offrant une flexibilité dans la récupération d'images depuis différentes sources.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux pour charger une image. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Instanciez une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), en spécifiant les paramètres de largeur, de hauteur et de type de couleur souhaités. Ce constructeur permet une création rapide d'images PNG avec des dimensions et des configurations de couleur sur mesure, facilitant la génération d'images optimisée pour diverses applications et flux de travail.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |
| colorType | int | Le type de couleur. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


Initialisez une nouvelle instance de la classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), en incorporant des options PNG ainsi que les paramètres de largeur et de hauteur. Ce constructeur permet aux développeurs de créer des images PNG avec des paramètres et des dimensions personnalisables, offrant une flexibilité dans la génération d'images pour divers cas d'utilisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Les options png. |
| width | int | La largeur. |
| height | int | La hauteur. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupérez la valeur des bits par pixel de l'image. Cette propriété fournit des informations essentielles sur la profondeur de couleur de l'image, permettant aux développeurs de comprendre le niveau de détail et la précision des couleurs présentes dans les données de l'image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtenez la hauteur de l'image en pixels. Cette propriété renvoie la dimension verticale de l'image, permettant aux développeurs de déterminer sa taille en pixels le long de l'axe vertical.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Récupérez ou modifiez la résolution horizontale de l'image. Cette propriété représente le nombre de pixels par pouce le long de l'axe horizontal de l'image. Ajuster cette résolution peut affecter la taille physique de l'image lorsqu'elle est imprimée ou affichée.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Obtenez la résolution horizontale et verticale du PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//La résolution horizontale, en pixels par pouce : 96.0
//La résolution verticale, en pixels par pouce : 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Récupérez ou modifiez la résolution horizontale de l'image. Cette propriété représente le nombre de pixels par pouce le long de l'axe horizontal de l'image. Ajuster cette résolution peut affecter la taille physique de l'image lorsqu'elle est imprimée ou affichée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupère le format du fichier associé à l'instance d'image. Cette propriété fournit des informations essentielles sur le type de fichier, permettant une gestion et un traitement efficaces en fonction des exigences spécifiques du format.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Accède au format des données brutes de l'image. Cette propriété donne un aperçu de la façon dont les données de l'image sont structurées en interne, ce qui peut être utile pour des tâches avancées de traitement d'image ou de conversion de format.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// Les images PNG à charger.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// La sortie peut ressembler à ceci :
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Fournit l'accès à la résolution verticale de l'image. Les développeurs peuvent utiliser cette propriété pour récupérer ou modifier le réglage de résolution, qui indique le nombre de pixels par pouce (PPI) le long de l'axe vertical de l'image.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Obtenez la résolution horizontale et verticale du PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//La résolution horizontale, en pixels par pouce : 96.0
//La résolution verticale, en pixels par pouce : 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Fournit l'accès à la résolution verticale de l'image. Les développeurs peuvent utiliser cette propriété pour récupérer ou modifier le réglage de résolution, qui indique le nombre de pixels par pouce (PPI) le long de l'axe vertical de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Permet de récupérer la largeur de l'image en pixels, fournissant des informations essentielles sur ses dimensions. Cette propriété est fréquemment utilisée par les développeurs pour déterminer la largeur de l'image, leur permettant d'effectuer diverses opérations en fonction de sa taille

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Fournit une valeur booléenne indiquant si l'image contient une couleur transparente. Cette propriété est cruciale pour les applications qui doivent gérer la transparence, permettant aux développeurs de déterminer si un traitement supplémentaire est nécessaire pour gérer les zones transparentes de l'image.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Renvoie une valeur booléenne indiquant si l'image possède un canal alpha, ce qui détermine sa transparence. Cette propriété est utile pour les applications qui doivent gérer la transparence, permettant aux développeurs de déterminer si un traitement supplémentaire est nécessaire pour gérer les zones transparentes de l'image.

**Returns:**
boolean - `true` si cette instance possède un canal alpha ; sinon, `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Classe d'assistance
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// Voici l'exemple principal
Utils utils = new Utils();

// Obtenir tous les types de couleur PNG pris en charge.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// Le résultat ressemble à ceci :
// Une image PNG en niveaux de gris ne prend pas en charge le canal alpha
// Une image PNG en couleur vraie ne prend pas en charge le canal alpha
// Une image PNG à couleur indexée ne prend pas en charge le canal alpha
// Une image PNG en niveaux de gris avec alpha prend en charge le canal alpha
// Une image PNG en couleur vraie avec alpha prend en charge le canal alpha
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Récupère la couleur transparente de l'image, si elle existe. Cette propriété est précieuse pour les applications nécessitant une gestion précise des zones transparentes dans les images, permettant aux développeurs d'accéder et de manipuler la couleur transparente spécifique utilisée.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Fournit une valeur booléenne indiquant si l'image contient une couleur transparente. Cette propriété est cruciale pour les applications qui doivent gérer la transparence, permettant aux développeurs de déterminer si un traitement supplémentaire est nécessaire pour gérer les zones transparentes de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Créer une image PNG en couleur vraie de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tous les pixels rouges seront considérés comme entièrement transparents.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tous les pixels transparents auront une couleur d'arrière-plan.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Remplir l'image entière avec la couleur blanche.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Remplir le quart supérieur gauche de l'image avec la couleur transparente.
    // Cela colore le quart supérieur gauche avec la couleur d'arrière-plan.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Modifie la couleur transparente de l'image, si elle existe. Cette propriété est précieuse pour les applications nécessitant une gestion précise des zones transparentes dans les images, permettant aux développeurs d'accéder et de manipuler la couleur transparente spécifique utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Créer une image PNG en couleur vraie de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tous les pixels rouges seront considérés comme entièrement transparents.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tous les pixels transparents auront une couleur d'arrière-plan.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Remplir l'image entière avec la couleur blanche.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Remplir le quart supérieur gauche de l'image avec la couleur transparente.
    // Cela colore le quart supérieur gauche avec la couleur d'arrière-plan.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Récupère une valeur booléenne indiquant si l'image possède une couleur d'arrière-plan. Cette propriété est utile pour les applications qui doivent déterminer si une image inclut une couleur d'arrière-plan, ce qui peut être important pour diverses tâches de traitement telles que le compositing, le rendu ou l'exportation.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Récupère la couleur d'arrière-plan de l'image, si elle est spécifiée. Cette propriété est utile pour les applications qui doivent identifier et éventuellement manipuler la couleur d'arrière-plan d'une image.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Récupère une valeur booléenne indiquant si l'image possède une couleur d'arrière-plan. Cette propriété est utile pour les applications qui doivent déterminer si une image inclut une couleur d'arrière-plan, ce qui peut être important pour diverses tâches de traitement telles que le compositing, le rendu ou l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Créer une image PNG en couleur vraie de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tous les pixels rouges seront considérés comme entièrement transparents.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tous les pixels transparents auront une couleur d'arrière-plan.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Remplir l'image entière avec la couleur blanche.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Remplir le quart supérieur gauche de l'image avec la couleur transparente.
    // Cela colore le quart supérieur gauche avec la couleur d'arrière-plan.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Récupère la couleur d'arrière-plan de l'image, si elle est spécifiée. Cette propriété est utile pour les applications qui doivent identifier et éventuellement manipuler la couleur d'arrière-plan d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Créer une image PNG en couleur vraie de 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tous les pixels rouges seront considérés comme entièrement transparents.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tous les pixels transparents auront une couleur d'arrière-plan.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Remplir l'image entière avec la couleur blanche.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Remplir le quart supérieur gauche de l'image avec la couleur transparente.
    // Cela colore le quart supérieur gauche avec la couleur d'arrière-plan.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Récupère une valeur booléenne indiquant si le [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est entrelacé, ce qui détermine si les données de l'image sont stockées de manière progressive pour un chargement ou une transmission plus rapides.

**Returns:**
boolean - `true` si entrelacé ; sinon, `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Obtient une valeur indiquant si cette instance d'image est entrelacée.

Valeur : `true` si cette instance d'image est entrelacée ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si cette instance d'image est entrelacée.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtient les options par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | Les arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis la sauvegardons en utilisant la méthode `DataStreamSupporter.Save(string)`, une image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode `Image.Save(string, ImageOptionsBase)` en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
