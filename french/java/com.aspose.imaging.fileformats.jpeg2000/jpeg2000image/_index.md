---
title: "Jpeg2000Image"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez efficacement les fichiers d'image JPEG2000 JP2 avec notre API, qui prend en charge une gamme de profondeurs de bits par pixel et un traitement fluide des métadonnées XMP contenant les informations essentielles de l'image."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Manipulez efficacement les fichiers d'image JPEG2000 (JP2) avec notre API, prenant en charge une gamme de profondeurs de bits par pixel et un traitement fluide des métadonnées XMP contenant les informations essentielles de l'image. Grâce à des capacités de compression sans perte, assurez une qualité d'image optimale tout en préservant l'intégrité du fichier, vous permettant d'adapter les images JP2 à vos spécifications exactes en toute simplicité.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Commencez à travailler avec la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en initialisant une nouvelle instance avec le chemin de l'image que vous souhaitez charger. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Commencez facilement avec la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en créant une nouvelle instance avec à la fois le chemin du fichier et le paramètre de bits par pixel souhaité. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Initialisez facilement une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en fournissant un objet de flux. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Initialisez une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec un flux pour charger l'image, ainsi que les paramètres de bits par pixel. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Créez une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en spécifiant les paramètres de largeur et de hauteur. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Instanciez un nouvel objet [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en fournissant les paramètres de largeur, de hauteur et d'options d'image. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Créez une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec les paramètres de largeur, de hauteur et du nombre de bits. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Instanciez une nouvelle classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec une image raster. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Initialisez une nouvelle instance [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec une image raster et les paramètres de bits par pixel. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Récupérez le format du fichier image. |
| [getRawDataFormat()](#getRawDataFormat--) | Cette propriété récupère le format des données brutes de l'image. |
| [getRawLineSize()](#getRawLineSize--) | Cette propriété récupère la taille d'une seule ligne de données d'image brutes en octets. |
| [getWidth()](#getWidth--) | Cette propriété renvoie la largeur de l'image en pixels. |
| [getHeight()](#getHeight--) | Cette propriété récupère la hauteur de l'image en pixels. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Cette propriété renvoie la profondeur de l'image, mesurée en bits par pixel (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | Cette propriété vous permet de récupérer ou de modifier la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Cette propriété vous permet de récupérer ou de modifier la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | Cette propriété donne accès à la résolution verticale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Cette propriété donne accès à la résolution verticale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). |
| [getComments()](#getComments--) | Cette propriété permet de récupérer ou de mettre à jour les commentaires associés à l'image. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Cette propriété permet de récupérer ou de mettre à jour les commentaires associés à l'image. |
| [getCodec()](#getCodec--) | Cette propriété récupère le codec JPEG2000 associé à l'image. |
| [getOriginalOptions()](#getOriginalOptions--) | Récupérez les options d'image basées sur les paramètres du fichier original. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Chargez une image JPEG2000.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // Enregistrer au format PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Commencez à travailler avec la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en initialisant une nouvelle instance avec le chemin de l'image que vous souhaitez charger. Ce constructeur permet un accès facile aux images JPEG2000, simplifiant le processus de chargement et de gestion des fichiers image. En fournissant le chemin du fichier, vous pouvez rapidement commencer à traiter et à manipuler les images JPEG2000 dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Commencez facilement avec la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en créant une nouvelle instance avec à la fois le chemin du fichier et le paramètre de bits par pixel souhaité. Ce constructeur permet d'ajuster finement le processus de chargement de l'image, assurant la compatibilité avec divers formats d'image et réglages de qualité. Avec cette flexibilité, vous pouvez gérer et manipuler efficacement les images JPEG2000 selon vos exigences spécifiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger l'image et initialiser les données de pixels et de palette |
| bitsPerPixel | int | Les bits par pixel. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Initialisez facilement une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) en fournissant un objet flux. Ce constructeur simplifie le processus de chargement des images JPEG2000 directement depuis des flux, offrant flexibilité et commodité pour la gestion des données d'image provenant de diverses sources.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Initialisez une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec un flux pour charger l'image, ainsi que les paramètres de bits par pixel. Ce constructeur offre de la flexibilité en vous permettant de spécifier à la fois la source des données d'image et les bits par pixel souhaités, offrant un contrôle plus fin du processus de chargement de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image et initialiser les données de pixels et de palette. |
| bitsPerPixel | int | Les bits par pixel. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Créez une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), en spécifiant les paramètres de largeur et de hauteur. Ce constructeur vous permet d'initialiser une image JPEG2000 avec des dimensions spécifiques, ce qui est utile dans les scénarios où vous devez créer programmétiquement une image d'une certaine taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image |
| height | int | La hauteur de l'image |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Instanciez un nouvel objet [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), en fournissant les paramètres de largeur, de hauteur et d'options d'image. Ce constructeur permet la création d'images JPEG2000 avec des dimensions spécifiques et des options supplémentaires, offrant de la flexibilité dans la génération d'images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image |
| height | int | La hauteur de l'image |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Les options. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Créez une nouvelle instance de la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec des paramètres de largeur, de hauteur et de nombre de bits. Ce constructeur permet la création d'images JPEG2000 avec des dimensions spécifiques et des profondeurs de bits, offrant de la flexibilité pour divers besoins d'imagerie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image |
| height | int | La hauteur de l'image |
| bitsCount | int | Le nombre de bits. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Instanciez une nouvelle classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec une image raster. Ce constructeur facilite la création d'une image JPEG2000 à partir d'une image raster existante, offrant une intégration fluide et une conversion entre différents formats d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Initialisez une nouvelle instance de [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) avec une image raster et des paramètres de bits par pixel. Ce constructeur permet un contrôle précis de la qualité et de la taille de l'image JPEG2000 résultante, ce qui le rend idéal pour les scénarios où la personnalisation est cruciale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette. |
| bitsPerPixel | int | Les bits par pixel. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez le format du fichier image. Cette propriété fournit des informations sur le format du fichier de l'image. Utilisez cette propriété pour déterminer le format du fichier image de manière programmatique, facilitant ainsi la gestion et le traitement appropriés en fonction du format du fichier.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Cette propriété récupère le format des données brutes de l'image. Elle fournit des informations sur la façon dont les données de pixels sont stockées en mémoire. Utilisez cette propriété pour comprendre le format de données sous-jacent de l'image, ce qui peut être crucial pour diverses opérations de traitement d'image telles que la conversion de couleur, la compression ou la décompression.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Cette propriété récupère la taille d'une ligne unique de données brutes de l'image en octets. Elle indique la quantité de mémoire occupée par une seule rangée de pixels dans le format de données brutes de l'image. Comprendre la taille de la ligne brute est essentiel pour des tâches telles que l'allocation de mémoire, la manipulation de données et les algorithmes de traitement d'image qui opèrent sur des lignes d'image individuelles.

**Returns:**
int - La taille brute de la ligne en octets.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Cette propriété renvoie la largeur de l'image en pixels. Elle fournit une information fondamentale sur les dimensions de l'image, cruciale pour diverses tâches de traitement d'image, notamment le redimensionnement, le recadrage et le rendu.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Cette propriété récupère la hauteur de l'image en pixels. Elle constitue une information essentielle pour comprendre les dimensions verticales de l'image, facilitant diverses tâches de manipulation d'image telles que le redimensionnement, le recadrage et le rendu. Accéder à cette propriété permet aux utilisateurs de déterminer la taille verticale de l'image, permettant une mise en page et un affichage précis dans les applications.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Cette propriété renvoie la profondeur de l'image, mesurée en bits par pixel (bpp). Elle indique la quantité d'informations couleur stockées dans chaque pixel de l'image. Comprendre la profondeur de l'image est crucial pour déterminer la fidélité des couleurs et la qualité de l'image. Avec ces informations, les utilisateurs peuvent évaluer le niveau de détail et la richesse des couleurs présentes dans l'image.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Cette propriété vous permet de récupérer ou de modifier la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). Ajuster cette résolution peut influencer la taille et la qualité de l'image lors de l'impression ou de l'affichage. En définissant la résolution horizontale, les utilisateurs peuvent optimiser l'image pour des périphériques de sortie ou des applications spécifiques, garantissant les meilleurs résultats visuels possibles.

**Returns:**
double - La résolution horizontale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Obtenez la résolution horizontale et verticale du Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 72,0
// La résolution verticale, en pixels par pouce : 72,0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 72,0
// La résolution verticale, en pixels par pouce : 72,0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Cette propriété vous permet de récupérer ou de modifier la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). Ajuster cette résolution peut influencer la taille et la qualité de l'image lors de l'impression ou de l'affichage. En définissant la résolution horizontale, les utilisateurs peuvent optimiser l'image pour des périphériques de sortie ou des applications spécifiques, garantissant les meilleurs résultats visuels possibles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution horizontale. |

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Cette propriété donne accès à la résolution verticale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). Modifier cette résolution peut affecter la qualité et la taille de l'image lors de l'impression ou de l'affichage. En ajustant la résolution verticale, les utilisateurs peuvent optimiser l'image pour différents périphériques de sortie ou applications, assurant un rendu visuel optimal.

**Returns:**
double - La résolution verticale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Obtenez la résolution horizontale et verticale du Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 72,0
// La résolution verticale, en pixels par pouce : 72,0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 72,0
// La résolution verticale, en pixels par pouce : 72,0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Cette propriété donne accès à la résolution verticale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce (PPI). Modifier cette résolution peut affecter la qualité et la taille de l'image lors de l'impression ou de l'affichage. En ajustant la résolution verticale, les utilisateurs peuvent optimiser l'image pour différents périphériques de sortie ou applications, assurant un rendu visuel optimal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution verticale. |

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Cette propriété permet de récupérer ou de mettre à jour les commentaires associés à l'image. Les commentaires fournissent des informations supplémentaires sur le contenu de l'image, telles que des annotations, des descriptions ou des métadonnées. Modifier ces commentaires peut être utile pour organiser et catégoriser les images, ainsi que pour transmettre des détails importants aux spectateurs ou aux utilisateurs.

**Returns:**
java.lang.String[] - Les commentaires.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Cette propriété permet de récupérer ou de mettre à jour les commentaires associés à l'image. Les commentaires fournissent des informations supplémentaires sur le contenu de l'image, telles que des annotations, des descriptions ou des métadonnées. Modifier ces commentaires peut être utile pour organiser et catégoriser les images, ainsi que pour transmettre des détails importants aux spectateurs ou aux utilisateurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] | Les commentaires. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Cette propriété récupère le codec JPEG2000 associé à l'image. Le codec JPEG2000 est responsable de l'encodage et du décodage des données de l'image au format JPEG2000, offrant une compression efficace tout en maintenant une haute qualité d'image. Accéder à ce codec peut être utile pour effectuer des opérations avancées de traitement d'image ou optimiser les paramètres de compression d'image adaptés à des exigences spécifiques.

**Returns:**
int - Le codec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Récupérez les options d'image basées sur les paramètres du fichier original. Cette méthode est utile pour maintenir la profondeur de couleur et d'autres paramètres de l'image originale, assurant la cohérence et préservant l'intégrité des données de l'image. Accéder à ces options facilite la gestion et le traitement fluides de l'image tout en conservant ses caractéristiques d'origine. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis la sauvegardons en utilisant la méthode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\\#save-String-), l'image PNG de sortie avec 8 bits par pixel sera générée. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\\#save-String--ImageOptionsBase-) en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
