---
title: "TgaImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez les fichiers d'image raster TGA avec notre API adaptée au format TARGA Truevision Advanced Raster Adapter, permettant un chargement et une personnalisation fluides."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

Manipulez les fichiers d'image raster TGA avec notre API, adaptée au format TARGA (Truevision Advanced Raster Adapter), permettant un chargement et une personnalisation fluides. Mettez facilement à jour les propriétés publiques telles que l'auteur, l'horodatage, l'ID de l'image et la version du logiciel, tout en utilisant divers réglages de bits par pixel, le canal alpha et la transparence des couleurs. De plus, vous pouvez exporter les images TGA vers d'autres formats raster populaires, assurant la compatibilité pour vos projets.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Initialise un nouvel objet [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) en utilisant le chemin de fichier fourni pour charger le contenu de l'image. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Créez une nouvelle instance de la classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) en fournissant un objet image raster. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Initialisez une nouvelle instance de la classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) en utilisant un flux pour charger l'image. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupérez la valeur des bits par pixel, fournissant des informations essentielles sur la profondeur de couleur de l'image. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Obtenez la valeur des octets par pixel, qui indique la quantité de mémoire occupée par chaque pixel de l'image. |
| [hasAlpha()](#hasAlpha--) | Récupérez une valeur booléenne indiquant si le [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) comprend un canal alpha, facilitant les effets de transparence. |
| [isGrayScale()](#isGrayScale--) | Obtenez une valeur booléenne indiquant si le [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) représente une image en niveaux de gris. |
| [getWidth()](#getWidth--) | Récupérez la largeur de l'image représentée par cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getHeight()](#getHeight--) | Obtenez la hauteur de l'image encapsulée par cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getFileFormat()](#getFileFormat--) | Obtenez des informations cruciales sur le format de fichier de l'image représentée par cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [hasColorMap()](#hasColorMap--) | Récupérez si cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) contient une table de couleurs. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Obtient la partie numérateur de la valeur gamma, qui est essentielle pour une représentation précise des couleurs dans les images. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Récupère la partie dénominateur de la valeur gamma, un facteur essentiel pour déterminer la représentation des couleurs dans les images. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Récupère le composant numérateur du rapport d'aspect des pixels, qui influence l'aspect visuel des pixels dans l'image. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Récupère la partie dénominateur du rapport d'aspect des pixels, un facteur crucial pour déterminer l'aspect visuel des pixels dans l'image. |
| [getXOrigin()](#getXOrigin--) | Obtient la coordonnée horizontale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA). |
| [setXOrigin(int value)](#setXOrigin-int-) | Définit la coordonnée horizontale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA). |
| [getYOrigin()](#getYOrigin--) | Obtient la coordonnée verticale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA). |
| [setYOrigin(int value)](#setYOrigin-int-) | Définit la coordonnée verticale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA). |
| [getImageId()](#getImageId--) | Obtient l'identifiant unique associé à l'image. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Définit l'identifiant unique associé à l'image. |
| [getAuthorComments()](#getAuthorComments--) | Récupère ou définit les commentaires fournis par l'auteur de l'image. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Récupère ou définit les commentaires fournis par l'auteur de l'image. |
| [getAuthorName()](#getAuthorName--) | Récupère ou définit le nom de l'auteur associé à l'image. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Récupère ou définit le nom de l'auteur associé à l'image. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Obtient l'horodatage date/heure. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Définit l'horodatage date/heure. |
| [getJobNameOrId()](#getJobNameOrId--) | Récupère ou définit le nom ou l'ID du travail associé à l'image. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Récupère ou définit le nom ou l'ID du travail associé à l'image. |
| [getJobTime()](#getJobTime--) | Récupère ou définit l'horodatage indiquant l'heure du travail associé à l'image. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Récupère ou définit l'horodatage indiquant l'heure du travail associé à l'image. |
| [getTransparentColor()](#getTransparentColor--) | Récupère ou définit la couleur clé associée à l'image. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Récupère ou définit la couleur clé associée à l'image. |
| [hasTransparentColor()](#hasTransparentColor--) | Récupère ou définit une valeur booléenne indiquant si l'image contient une couleur transparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Récupère ou définit une valeur booléenne indiquant si l'image contient une couleur transparente. |
| [getBackgroundColor()](#getBackgroundColor--) | Récupère ou définit la couleur d'arrière-plan de l'image. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Récupère ou définit la couleur d'arrière-plan de l'image. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Récupère ou définit une valeur indiquant si l'image contient une couleur d'arrière-plan. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Récupère ou définit une valeur indiquant si l'image contient une couleur d'arrière-plan. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Récupère ou définit la version du logiciel associée à l'image. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Récupère ou définit la version du logiciel associée à l'image. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Récupère ou définit le composant lettre de la version du logiciel associée à l'image. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Récupère ou définit le composant lettre de la version du logiciel associée à l'image. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Récupère ou définit le composant numérique de la version du logiciel associée à l'image. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Récupère ou définit le composant numérique de la version du logiciel associée à l'image. |
| [getSoftwareId()](#getSoftwareId--) | Gère l'identification du logiciel (ID) associée à l'image, permettant jusqu'à 40 caractères ASCII. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Gère l'identification du logiciel (ID) associée à l'image, permettant jusqu'à 40 caractères ASCII. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Effectue une comparaison d'égalité entre deux images TGA, en considérant à la fois la première et la seconde image impliquées dans le processus de comparaison. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Effectue une comparaison d'inégalité entre deux images TGA, en évaluant à la fois la première et la seconde image impliquées dans la comparaison. |
| [deepClone()](#deepClone--) | Produit un duplicata de l'instance actuelle, générant un nouvel objet qui clone tous les attributs et propriétés de l'original. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Réplique les propriétés d'un autre objet [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), créant une nouvelle instance avec des attributs identiques. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | Dans une comparaison d'égalité, la méthode évalue si l'instance actuelle de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) est égale à la seconde image fournie en paramètre. |
| [equals(Object other)](#equals-java.lang.Object-) | La méthode effectue une comparaison d'égalité entre l'instance actuelle de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) et un autre objet fourni en paramètre. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | La méthode "rotateFlip" permet les opérations de rotation et de retournement sur l'image. |
| [hashCode()](#hashCode--) | Récupère le code de hachage de l'instance actuelle. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre l'image à une région spécifiée. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recadre l'image en spécifiant des décalages pour les bordures gauche, droite, supérieure et inférieure. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne l'image tout en appliquant des paramètres spécifiques pour maintenir les dimensions souhaitées et le rapport d'aspect. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ajuste la taille de l'image en utilisant un type de redimensionnement spécifié, qui détermine comment l'opération de redimensionnement est effectuée. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Fait pivoter l'image autour de son centre d'un angle spécifié tout en maintenant la proportionnalité du redimensionnement et en préservant la couleur d'arrière-plan. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Initialise un nouvel objet [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) en utilisant le chemin de fichier fourni pour charger le contenu de l'image. Ce constructeur initialise efficacement l'instance d'image, permettant un accès fluide aux fichiers d'images TGA, simplifiant l'intégration dans le flux de travail de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin pour charger une image. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Créez une nouvelle instance de la classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) en fournissant un objet image raster. Ce constructeur facilite l'intégration directe d'images raster existantes au format d'image TGA, rationalisant le processus de conversion pour une compatibilité accrue au sein de vos systèmes logiciels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Initialisez une nouvelle instance de la classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) en utilisant un flux pour charger l'image. Ce constructeur permet une intégration fluide des données d'image provenant de flux, facilitant la gestion et le traitement efficaces des images TGA au sein de vos applications logicielles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux pour charger une image. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupérez la valeur des bits par pixel, fournissant des informations essentielles sur la profondeur de couleur de l'image. Cette propriété constitue une métrique cruciale pour comprendre le niveau de détail et la richesse des couleurs présentes dans l'image, aidant les développeurs à optimiser les algorithmes de traitement et l'allocation des ressources pour une manipulation et un rendu d'image efficaces.

**Returns:**
int - bits par pixel.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Obtenez la valeur des octets par pixel, qui indique la quantité de mémoire occupée par chaque pixel dans l'image. Cette propriété constitue une métrique cruciale pour la gestion et l'optimisation de la mémoire, aidant les développeurs à allouer efficacement les ressources et à traiter les données d'image.

**Returns:**
int - octets par pixel.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Récupérez une valeur booléenne indiquant si le [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) comprend un canal alpha, facilitant les effets de transparence. Cette propriété fournit des informations essentielles pour la gestion de la composition et du rendu d'images, aidant les développeurs à implémenter divers effets visuels et opérations de composition.

**Returns:**
booléen - une valeur indiquant si ce [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) possède un canal alpha.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Obtenez une valeur booléenne indiquant si le [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) représente une image en niveaux de gris. Cette propriété est cruciale pour distinguer les images couleur des images en niveaux de gris, aidant les développeurs à appliquer les techniques de traitement et de rendu appropriées en fonction des caractéristiques chromatiques de l'image.

**Returns:**
booléen - une valeur indiquant si ce [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) est en niveaux de gris.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Récupérez la largeur de l'image représentée par cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Cette propriété fournit aux développeurs des informations essentielles sur les dimensions de l'image, facilitant diverses tâches de manipulation et de traitement d'images au sein de leurs applications logicielles.

**Returns:**
int - largeur de cette image en pixels.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtenez la hauteur de l'image encapsulée par cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Cette propriété fournit aux développeurs des détails critiques concernant les dimensions verticales de l'image, permettant une intégration et une manipulation fluides des images au sein de leurs solutions logicielles.

**Returns:**
int - hauteur de cette image en pixels.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtenez des informations cruciales sur le format de fichier de l'image représentée par cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Comprendre le format de fichier est essentiel pour les vérifications de compatibilité et garantir une intégration transparente au sein des systèmes logiciels, permettant un traitement et une manipulation efficaces des images.

**Returns:**
long - informations cruciales sur le format de fichier de l'image représentée par cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage).
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Récupérez si cette instance de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) contient une table de couleurs. Comprendre la présence d'une table de couleurs est crucial pour une interprétation précise et la manipulation des données de couleur de l'image.

**Returns:**
boolean - une valeur indiquant si cette image possède une table de couleurs.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Obtient la partie numérateur de la valeur gamma, qui est essentielle pour une représentation précise des couleurs dans les images. Dans les images sans correction gamma, cette valeur doit être de 1,0. Comprendre et utiliser cette valeur est crucial pour maintenir la fidélité des couleurs et assurer un rendu d'image précis.

**Returns:**
int - la partie numérateur de la valeur gamma, qui est essentielle pour une représentation précise des couleurs dans les images.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Récupère la partie dénominateur de la valeur gamma, un facteur essentiel pour déterminer la représentation des couleurs dans les images. Pour les images dépourvues de correction gamma, cette valeur doit être de 1,0, assurant un rendu de couleur précis. Apprécier et exploiter ce paramètre est fondamental pour préserver la fidélité des couleurs et obtenir une visualisation d'image précise.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Récupère le composant numérateur du rapport d'aspect des pixels, qui influence l'aspect visuel des pixels dans l'image. Comprendre et manipuler cette valeur est essentiel pour obtenir une représentation précise des pixels et des rapports d'aspect lors du rendu et du traitement d'images.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Récupère la partie dénominateur du rapport d'aspect des pixels, un facteur crucial pour déterminer l'aspect visuel des pixels dans l'image. Cette valeur est essentielle pour préserver une représentation précise des pixels et des rapports d'aspect tout au long des différentes opérations de rendu et de traitement d'images, garantissant une sortie visuelle de haute qualité.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Obtient la coordonnée horizontale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA).

**Returns:**
int - coordonnée horizontale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant son origine en bas à gauche de l'écran.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Définit la coordonnée horizontale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | coordonnée horizontale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant son origine en bas à gauche de l'écran. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Obtient la coordonnée verticale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA).

**Returns:**
int - coordonnée verticale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant son origine en bas à gauche de l'écran.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Définit la coordonnée verticale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par ex., la série TARGA).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | coordonnée verticale absolue du coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant son origine en bas à gauche de l'écran. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Obtient l'identifiant unique associé à l'image. Cet ID sert de point de référence pour identifier et distinguer l'image des autres au sein d'un système ou d'une application. En définissant ou en récupérant l'ID d'image, vous pouvez gérer et suivre les images efficacement, facilitant une gestion et une récupération organisées des images.

Ce champ optionnel contient des informations d'identification sur l'image. La longueur maximale de ce champ est de 255 octets.

**Returns:**
java.lang.String - l'identifiant unique associé à l'image.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Définit l'identifiant unique associé à l'image. Cet ID sert de point de référence pour identifier et distinguer l'image des autres au sein d'un système ou d'une application. En définissant ou en récupérant l'ID d'image, vous pouvez gérer et suivre les images efficacement, facilitant une gestion et une récupération organisées des images.

Ce champ optionnel contient des informations d'identification sur l'image. La longueur maximale de ce champ est de 255 octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | l'identifiant unique associé à l'image. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Récupère ou définit les commentaires fournis par l'auteur de l'image. Ces commentaires contiennent souvent des informations précieuses, telles que des descriptions, des annotations ou un contexte supplémentaire sur l'image. En accédant ou en modifiant la propriété Commentaires de l'auteur, les développeurs peuvent enrichir les métadonnées associées à l'image, offrant aux utilisateurs des informations et un contexte précieux concernant son contenu ou sa création. Il s'agit d'un champ ASCII de 324 octets organisé en quatre lignes de 80 caractères, chacune suivie d'un terminateur nul.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Récupère ou définit les commentaires fournis par l'auteur de l'image. Ces commentaires contiennent souvent des informations précieuses, telles que des descriptions, des annotations ou un contexte supplémentaire sur l'image. En accédant ou en modifiant la propriété Commentaires de l'auteur, les développeurs peuvent enrichir les métadonnées associées à l'image, offrant aux utilisateurs des informations et un contexte précieux concernant son contenu ou sa création. Il s'agit d'un champ ASCII de 324 octets organisé en quatre lignes de 80 caractères, chacune suivie d'un terminateur nul.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Récupère ou définit le nom de l'auteur associé à l'image. Cette propriété permet aux développeurs d'accéder ou de modifier les métadonnées du nom de l'auteur, fournissant des informations précieuses sur le créateur de l'image. En utilisant la propriété Nom de l'auteur, les utilisateurs peuvent facilement identifier la personne responsable de la création ou de la contribution à l'image, améliorant ainsi ses métadonnées globales et fournissant un contexte précieux aux spectateurs. Ce champ comprend au total 40 caractères ASCII pour le nom. Si le champ est utilisé, il doit contenir le nom de la personne qui a créé l'image (auteur).

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Récupère ou définit le nom de l'auteur associé à l'image. Cette propriété permet aux développeurs d'accéder ou de modifier les métadonnées du nom de l'auteur, fournissant des informations précieuses sur le créateur de l'image. En utilisant la propriété Nom de l'auteur, les utilisateurs peuvent facilement identifier la personne responsable de la création ou de la contribution à l'image, améliorant ainsi ses métadonnées globales et fournissant un contexte précieux aux spectateurs. Ce champ comprend au total 40 caractères ASCII pour le nom. Si le champ est utilisé, il doit contenir le nom de la personne qui a créé l'image (auteur).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nom de l'auteur. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Obtient le horodatage Date/Heure. Ce champ définit la valeur pour la date et l'heure auxquelles l'image a été enregistrée. Bien que les systèmes d'exploitation horodatent généralement les fichiers, cette fonctionnalité est fournie car le système d'exploitation peut modifier l'horodatage si le fichier est copié. En utilisant cette zone, vous êtes assuré d'une région non modifiée pour l'enregistrement de la date et de l'heure.

**Returns:**
java.util.Date - Horodatage Date/Heure.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Définit l'horodatage. Ce champ définit la valeur de la date et de l'heure auxquelles l'image a été enregistrée. Bien que les systèmes d'exploitation horodent généralement les fichiers, cette fonctionnalité est fournie car le système d'exploitation peut modifier l'horodatage si le fichier est copié. En utilisant cette zone, vous êtes assuré d'une région non modifiée pour l'enregistrement de la date et de l'heure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date | Horodatage. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


Récupère ou définit le nom ou l'ID du travail associé à l'image. Cette propriété vous permet d'accéder ou de modifier les métadonnées liées au travail ou au projet spécifique associé à l'image. En utilisant la propriété Nom/ID du travail, les utilisateurs peuvent facilement identifier le projet ou la tâche auquel l'image se rapporte, facilitant l'organisation et la gestion des ressources d'image au sein de flux de travail ou de projets plus vastes.

**Returns:**
java.lang.String - Nom/ID du travail.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Récupère ou définit le nom ou l'ID du travail associé à l'image. Cette propriété vous permet d'accéder ou de modifier les métadonnées liées au travail ou au projet spécifique associé à l'image. En utilisant la propriété Nom/ID du travail, les utilisateurs peuvent facilement identifier le projet ou la tâche auquel l'image se rapporte, facilitant l'organisation et la gestion des ressources d'image au sein de flux de travail ou de projets plus vastes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nom/ID du travail. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Récupère ou définit l'horodatage indiquant l'heure du travail associée à l'image. Cette propriété permet aux développeurs d'accéder ou de modifier les métadonnées temporelles liées au travail ou au projet spécifique associé à l'image.

**Returns:**
java.util.Date - Heure du travail.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Récupère ou définit l'horodatage indiquant l'heure du travail associée à l'image. Cette propriété permet aux développeurs d'accéder ou de modifier les métadonnées temporelles liées au travail ou au projet spécifique associé à l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date | Heure du travail. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Récupère ou définit la couleur clé associée à l'image. Cette propriété vous permet d'accéder ou de modifier la couleur désignée comme couleur clé pour des tâches ou effets spécifiques de traitement d'image. L'utilisation de la propriété Couleur clé permet aux utilisateurs d'appliquer des opérations basées sur la couleur telles que le chroma key ou le remplacement de couleur, améliorant les capacités de manipulation d'image et les possibilités créatives.

La Couleur clé peut être considérée comme la \\u2018background color\\u2019 ou la \\u2018transparent color\\u2019. C'est la couleur de la zone \\u2018non image\\u2019 de l'écran, et la même couleur à laquelle l'écran serait réinitialisé s'il était effacé dans l'application.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Récupère ou définit la couleur clé associée à l'image. Cette propriété vous permet d'accéder ou de modifier la couleur désignée comme couleur clé pour des tâches ou effets spécifiques de traitement d'image. L'utilisation de la propriété Couleur clé permet aux utilisateurs d'appliquer des opérations basées sur la couleur telles que le chroma key ou le remplacement de couleur, améliorant les capacités de manipulation d'image et les possibilités créatives.

La Couleur clé peut être considérée comme la \\u2018background color\\u2019 ou la \\u2018transparent color\\u2019. C'est la couleur de la zone \\u2018non image\\u2019 de l'écran, et la même couleur à laquelle l'écran serait réinitialisé s'il était effacé dans l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Couleur clé. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Récupère ou définit une valeur booléenne indiquant si l'image contient une couleur transparente. Cette propriété est essentielle pour identifier si l'image prend en charge la transparence, vous aidant à mettre en œuvre une gestion appropriée des opérations liées à la transparence telles que le mélange, le compositing ou le masquage.

**Returns:**
boolean - une valeur indiquant si l'image possède une couleur transparente.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Récupère ou définit une valeur booléenne indiquant si l'image contient une couleur transparente. Cette propriété est essentielle pour identifier si l'image prend en charge la transparence, vous aidant à mettre en œuvre une gestion appropriée des opérations liées à la transparence telles que le mélange, le compositing ou le masquage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si l'image possède une couleur transparente. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Récupère ou définit la couleur d'arrière-plan de l'image. Cette propriété vous permet de spécifier la couleur utilisée pour l'arrière-plan de l'image, assurant la cohérence et améliorant la présentation visuelle. Elle est particulièrement utile dans les scénarios où l'image est affichée sur un arrière-plan de couleur différente ou lors du rendu de l'image sur un autre canevas.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Récupère ou définit la couleur d'arrière-plan de l'image. Cette propriété vous permet de spécifier la couleur utilisée pour l'arrière-plan de l'image, assurant la cohérence et améliorant la présentation visuelle. Elle est particulièrement utile dans les scénarios où l'image est affichée sur un arrière-plan de couleur différente ou lors du rendu de l'image sur un autre canevas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | la couleur d'arrière-plan. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Récupère ou définit une valeur indiquant si l'image contient une couleur d'arrière-plan. Cette propriété est utile pour déterminer si l'image comprend une couleur d'arrière-plan distincte du contenu premier plan. Elle vous permet de personnaliser le traitement ou le rendu de l'image en fonction de la présence ou de l'absence d'une couleur d'arrière-plan.

**Returns:**
boolean - une valeur indiquant si l'image possède une couleur d'arrière-plan.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Récupère ou définit une valeur indiquant si l'image contient une couleur d'arrière-plan. Cette propriété est utile pour déterminer si l'image comprend une couleur d'arrière-plan distincte du contenu premier plan. Elle vous permet de personnaliser le traitement ou le rendu de l'image en fonction de la présence ou de l'absence d'une couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si l'image possède une couleur d'arrière-plan. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Récupère ou définit la version du logiciel associée à l'image. La longueur acceptée pour la chaîne de version est généralement de 3 à 4 caractères. Cette propriété est utile pour suivre le logiciel utilisé pour créer ou manipuler l'image et peut fournir un contexte précieux pour le traitement d'image et les vérifications de compatibilité.

**Returns:**
java.lang.String - Version du logiciel.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Récupère ou définit la version du logiciel associée à l'image. La longueur acceptée pour la chaîne de version est généralement de 3 à 4 caractères. Cette propriété est utile pour suivre le logiciel utilisé pour créer ou manipuler l'image et peut fournir un contexte précieux pour le traitement d'image et les vérifications de compatibilité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Version du logiciel. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Récupère ou définit le composant lettre de la version du logiciel associée à l'image. Cette propriété représente un détail supplémentaire dans la chaîne de version du logiciel et peut être utile pour une différenciation plus fine des versions.

**Returns:**
char - Partie lettre de la version du logiciel.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Récupère ou définit le composant lettre de la version du logiciel associée à l'image. Cette propriété représente un détail supplémentaire dans la chaîne de version du logiciel et peut être utile pour une différenciation plus fine des versions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | char | Partie lettre de la version du logiciel. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Récupère ou définit le composant numérique de la version du logiciel associée à l'image. Cette propriété représente la partie numérique de la chaîne de version du logiciel, fournissant des informations importantes sur la version du logiciel utilisée pour créer ou modifier l'image.

**Returns:**
int - Partie numérique de la version du logiciel.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Récupère ou définit le composant numérique de la version du logiciel associée à l'image. Cette propriété représente la partie numérique de la chaîne de version du logiciel, fournissant des informations importantes sur la version du logiciel utilisée pour créer ou modifier l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Partie numérique de la version du logiciel. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Gère l'identification du logiciel (ID) associée à l'image, permettant jusqu'à 40 caractères ASCII. Cette propriété sert à identifier de manière unique le logiciel utilisé pour créer ou traiter l'image, fournissant des métadonnées précieuses à des fins d'organisation et d'information.

**Returns:**
java.lang.String - ID du logiciel.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Gère l'identification du logiciel (ID) associée à l'image, permettant jusqu'à 40 caractères ASCII. Cette propriété sert à identifier de manière unique le logiciel utilisé pour créer ou traiter l'image, fournissant des métadonnées précieuses à des fins d'organisation et d'information.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | ID du logiciel. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Effectue une comparaison d'égalité entre deux images TGA, en considérant à la fois la première et la deuxième image impliquées dans le processus de comparaison. Cette méthode facilite l'évaluation simple de l'égalité des images, garantissant une analyse précise et une prise de décision fiable dans les flux de travail de traitement d'images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Première [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) participant à la comparaison. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Deuxième [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) participant à la comparaison. |

**Returns:**
boolean - Résultats de la comparaison.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Effectue une comparaison d'inégalité entre deux images TGA, en évaluant à la fois la première et la deuxième image impliquées dans la comparaison. Cette méthode aide à identifier les divergences ou différences entre les images, permettant une analyse précise et une prise de décision dans les tâches de traitement d'images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Première [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) participant à la comparaison. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Deuxième [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) participant à la comparaison. |

**Returns:**
boolean - Résultats de la comparaison.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Produit un duplicata de l'instance actuelle, générant un nouvel objet qui clone toutes les attributs et propriétés de l'original. Cette méthode facilite la création de copies identiques, garantissant l'intégrité des données et préservant l'état de l'instance actuelle sans affecter l'objet original.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Réplique les propriétés d'un autre objet [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), créant une nouvelle instance avec des attributs identiques. Cette opération assure la préservation de l'intégrité des données et facilite la duplication des propriétés de l'image sans modifier l'objet source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Autre [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


Dans une comparaison d'égalité, la méthode évalue si l'instance actuelle de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) est égale à la deuxième image fournie en paramètre. Cette opération facilite la détermination de l'identité de deux images TGA, aidant aux tâches de traitement et de comparaison d'images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Deuxième [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) participant à la comparaison. |

**Returns:**
boolean - Résultats de la comparaison.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


La méthode effectue une comparaison d'égalité entre l'instance actuelle de [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) et un autre objet fourni en paramètre. Plus précisément, elle évalue si les propriétés de l'image actuelle correspondent à celles du second objet, aidant à déterminer leur équivalence à des fins de comparaison dans les flux de travail de traitement d'images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | Deuxième [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) participant à la comparaison. |

**Returns:**
boolean - Résultats de la comparaison.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


La méthode "rotateFlip" permet des opérations de rotation et de retournement sur l'image. Elle offre une fonctionnalité polyvalente pour manipuler l'orientation de l'image, permettant aux utilisateurs d'effectuer des rotations et des retournements selon leurs besoins, facilitant les tâches de traitement d'images efficaces au sein des applications logicielles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation/retournement. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Récupère le code de hachage de l'instance actuelle. Cependant, il est important de noter que ce code de hachage peut ne pas être adapté à une utilisation comme clé, notamment parce que les instances de la classe TgaImage ne sont pas immuables.

**Returns:**
int - Code de hachage de cette instance.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadre l'image à une région spécifiée. Cette méthode vous permet de définir une zone rectangulaire à conserver dans l'image, en rejetant le reste. Cette opération est utile pour se concentrer sur un contenu spécifique de l'image ou supprimer les parties indésirables.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recadrez l'image en spécifiant les décalages pour les limites gauche, droite, supérieure et inférieure. Cette méthode vous permet de couper l'image en déplaçant ses limites indépendamment le long des axes horizontal et vertical. En ajustant ces décalages, vous pouvez contrôler précisément quelles parties de l'image conserver, recadrant ainsi l'image aux dimensions souhaitées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | int | Le décalage gauche. |
| rightShift | int | Le décalage droit. |
| topShift | int | Le décalage supérieur. |
| bottomShift | int | Le décalage inférieur. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionnez l'image en appliquant des paramètres spécifiques pour maintenir les dimensions et le rapport d'aspect souhaités. En personnalisant les paramètres de l'image, vous pouvez redimensionner efficacement l'image tout en garantissant une qualité visuelle optimale et une compatibilité avec différents appareils d'affichage ou applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ajuste la taille de l'image en utilisant un type de redimensionnement spécifié, qui détermine la façon dont l'opération de redimensionnement est effectuée. Cette méthode offre une flexibilité dans le redimensionnement des images selon différents algorithmes ou techniques. En choisissant le type de redimensionnement approprié, vous pouvez obtenir le compromis souhaité entre la qualité de l'image et l'efficacité computationnelle en fonction des exigences ou préférences spécifiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Fait pivoter l'image autour de son centre d'un angle spécifié tout en maintenant la proportionnalité du redimensionnement et en préservant la couleur d'arrière-plan. Cette méthode permet une manipulation précise de l'image, garantissant que la rotation conserve l'équilibre visuel et la cohérence avec la couleur d'arrière-plan spécifiée. Elle est idéale pour les tâches nécessitant une rotation précise autour du centre, comme la correction d'orientation ou les ajustements artistiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resizeProportionally | boolean | si défini sur `true` vous verrez la taille de votre image modifiée selon les projections du rectangle tourné (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul `` le contenu de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

