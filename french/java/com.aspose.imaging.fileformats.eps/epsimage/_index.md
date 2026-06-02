---
title: "EpsImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API de prise en charge du format de fichier image Encapsulated PostScript EPS offre des capacités robustes pour manipuler des compositions comprenant du texte, des graphiques et des images."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

L'API de prise en charge du format de fichier image Encapsulated PostScript (EPS) offre des capacités robustes pour manipuler des compositions comprenant du texte, des graphiques et des images. Avec des fonctionnalités telles que la gestion des images d'aperçu bitmap, le retournement d'orientation, la récupération de la boîte englobante pour les limites d'illustration, le redimensionnement, la rotation des images et l'ajout d'images d'aperçu. Cette API garantit un traitement fluide et une intégration des fichiers EPS dans diverses applications avec précision et polyvalence.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Accédez facilement au nombre d'images d'aperçu disponibles. |
| [getPreviewImages()](#getPreviewImages--) | Récupérez les images d'aperçu associées à votre fichier. |
| [getFileFormat()](#getFileFormat--) | Accédez au format de fichier de votre image avec cette propriété. |
| [getEpsType()](#getEpsType--) | Accédez et interprétez la valeur du sous-type de votre image EPS, simplifiant votre flux de travail et améliorant la compatibilité entre les plates-formes. |
| [hasRasterPreview()](#hasRasterPreview--) | Découvrez la présence d'un aperçu raster sans effort grâce à cette propriété. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Accédez à la profondeur de couleur précise de l'image sans effort grâce à cette propriété. |
| [getWidthF()](#getWidthF--) | Récupérez la largeur de l'image avec cette propriété pratique. |
| [getHeightF()](#getHeightF--) | Accédez à la hauteur de l'image en utilisant cette propriété. |
| [isCached()](#isCached--) | Cette propriété offre un moyen pratique de vérifier si les données de l'objet sont actuellement en cache, éliminant ainsi le besoin de lectures de données supplémentaires. |
| [getPsStream()](#getPsStream--) | Obtient le flux contenant le PostScript à exécuter. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Cette propriété récupère la version du PostScript associée à l'instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getTitle()](#getTitle--) | Cette propriété récupère le titre extrait des commentaires EPS Document Structuring Conventions (DSC) intégrés dans le fichier EPS. |
| [getCreator()](#getCreator--) | Cette propriété offre l'accès aux informations du créateur provenant des commentaires EPS Document Structuring Conventions (DSC) présents dans le fichier EPS. |
| [getCreationDate()](#getCreationDate--) | En récupérant la date de création à partir des commentaires EPS Document Structuring Conventions (DSC), cette propriété fournit des métadonnées essentielles indiquant la création du fichier EPS. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | En récupérant la date de création à partir des commentaires EPS Document Structuring Conventions (DSC), cette propriété fournit des métadonnées essentielles indiquant la création du fichier EPS. |
| [getBoundingBox()](#getBoundingBox--) | En accédant à la boîte englobante originale en points indépendants du dispositif, cette propriété fournit des informations géométriques cruciales sur les dimensions du [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Cette propriété renvoie la boîte englobante originale de l'instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en pixels, fournissant des données géométriques essentielles pour un rendu et une manipulation précis. |
| [cacheData()](#cacheData--) | Cette propriété renvoie la boîte englobante originale de l'instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en pixels, fournissant des données géométriques essentielles pour un rendu et une manipulation précis. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Accède aux images d'aperçu liées à l'instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), permettant une récupération fluide pour l'inspection ou l'utilisation dans les applications. |
| [getPreviewImage()](#getPreviewImage--) | Récupère l'image d'aperçu existante dans le `format` spécifié ou renvoie `` si aucune n'est trouvée. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Récupère l'image d'aperçu existante dans le `format` spécifié ou renvoie `` si aucune n'est trouvée. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personnalisez les palettes d'images pour obtenir des schémas de couleurs uniques et améliorer l'attrait visuel. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// Charger l'image EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Redimensionner l'image en utilisant la méthode d'interpolation cubique Mitchell
    image.resize(400, 400, ResizeType.Mitchell);

    // Exporter l'image au format PNG
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// Charger l'image EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Définir le mode d'interpolation
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Définir le type du filtre
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Définit la méthode de comparaison des couleurs
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Définir la méthode de quantification des couleurs
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Redimensionner l'image en utilisant des paramètres de redimensionnement avancés
    image.resize(400, 400, resizeSettings);

    // Exporter l'image au format PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Accédez facilement au nombre d'images d'aperçu disponibles. Cette propriété vous permet de récupérer sans effort le nombre d'images d'aperçu associées à votre fichier, facilitant la gestion efficace et la navigation parmi vos aperçus d'images. Idéal pour optimiser votre flux de travail et organiser vos ressources d'images de manière efficace.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Récupérez les images d'aperçu associées à votre fichier. Cette propriété offre un accès fluide à la collection d'images d'aperçu, vous permettant de parcourir et de gérer efficacement celles-ci selon vos besoins. Idéal pour prévisualiser rapidement et sélectionner l'image appropriée pour votre projet.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accédez au format de fichier de votre image avec cette propriété. Récupérez les informations essentielles sur le format de votre fichier image, facilitant la compatibilité et le traitement efficace. Idéal pour identifier le format de vos fichiers image afin d'assurer une intégration fluide dans vos projets.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Accédez et interprétez la valeur du sous‑type de votre image EPS, simplifiant votre flux de travail et améliorant la compatibilité entre plateformes. Idéal pour optimiser la récupération du sous‑type EPS dans vos projets avec précision et efficacité.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Découvrez la présence d’un aperçu raster sans effort grâce à cette propriété. Accédez à la valeur booléenne indiquant si l’instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) comprend un aperçu raster, renforçant vos tâches de traitement d’image avec clarté et efficacité. Idéal pour rationaliser les décisions de flux de travail en fonction de la présence ou de l’absence d’aperçus raster dans les images EPS.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Accédez facilement à la profondeur de couleur précise de l’image grâce à cette propriété. Récupérez le nombre de bits par pixel, offrant des informations essentielles sur la profondeur de couleur de l’image et aidant à optimiser les tâches de traitement. Idéal pour les applications nécessitant un contrôle fin de la manipulation et de l’analyse d’image.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Récupérez la largeur de l’image avec cette propriété pratique. Obtenez la largeur de l’image sans effort, facilitant les calculs de mise en page précis, les opérations de mise à l’échelle et les tâches liées aux dimensions dans votre application. Idéal pour garantir un rendu et un affichage précis des images sur diverses plateformes et appareils.

**Returns:**
float - La largeur de l'image en pixels.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Accédez à la hauteur de l’image à l’aide de cette propriété. Obtenez la hauteur de l’image facilement, permettant des ajustements de mise en page fluides, des calculs de ratio d’aspect et un rendu précis sur différentes résolutions d’écran et environnements d’affichage.

**Returns:**
float - La hauteur de l'image en pixels.
### isCached() {#isCached--}
```
public boolean isCached()
```


Cette propriété offre un moyen pratique de vérifier si les données de l’objet sont actuellement en cache, éliminant le besoin de lectures de données supplémentaires. Elle fournit une méthode rapide et efficace pour déterminer si l’information requise est immédiatement disponible, optimisant les performances et réduisant la charge des ressources dans les opérations intensives en données.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Obtient le flux contenant le PostScript à exécuter.

**Returns:**
java.io.InputStream - le flux contenant le PostScript à exécuter.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Cette propriété récupère la version du PostScript associée à l’instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Elle donne un aperçu de la version spécifique du langage PostScript utilisée dans le fichier EPS, aidant à l’évaluation de la compatibilité et facilitant une intégration transparente avec les environnements compatibles PostScript.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


Cette propriété récupère le titre extrait des commentaires EPS Document Structuring Conventions (DSC) intégrés dans le fichier EPS. Elle fournit des métadonnées précieuses sur le contenu du fichier EPS, aidant à l’organisation et à l’identification du document dans les applications logicielles compatibles.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Cette propriété donne accès aux informations du créateur provenant des commentaires EPS Document Structuring Conventions (DSC) présents dans le fichier EPS. Comprendre les détails du créateur fournit des informations sur le logiciel ou l’outil utilisé pour générer le fichier EPS, facilitant l’évaluation de la compatibilité sur diverses plateformes et applications.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


En récupérant la date de création à partir des commentaires EPS Document Structuring Conventions (DSC), cette propriété fournit des métadonnées essentielles indiquant la création du fichier EPS. En accédant à ces informations, les utilisateurs obtiennent des indications sur l’origine et la chronologie du fichier, améliorant la gestion et l’organisation des fichiers.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


En récupérant la date de création à partir des commentaires EPS Document Structuring Conventions (DSC), cette propriété fournit des métadonnées essentielles indiquant la création du fichier EPS. En accédant à ces informations, les utilisateurs obtiennent des indications sur l’origine et la chronologie du fichier, améliorant la gestion et l’organisation des fichiers.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


En accédant à la boîte englobante originale en points indépendants du dispositif, cette propriété fournit des informations géométriques cruciales sur les dimensions de l’[EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). En récupérant ces données, les utilisateurs peuvent évaluer avec précision la taille et le ratio d’aspect de l’image, facilitant une mise en page et un positionnement précis dans diverses applications.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Cette propriété renvoie la boîte englobante originale de l’instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en pixels, fournissant des données géométriques essentielles pour un rendu et une manipulation précis. Avec ces informations, les utilisateurs peuvent assurer un placement et une dimension exacts des images EPS dans leurs projets, améliorant la présentation visuelle globale et la qualité.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cette propriété renvoie la boîte englobante originale de l’instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) en pixels, fournissant des données géométriques essentielles pour un rendu et une manipulation précis. Avec ces informations, les utilisateurs peuvent assurer un placement et une dimension exacts des images EPS dans leurs projets, améliorant la présentation visuelle globale et la qualité.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Accède aux images d’aperçu liées à l’instance [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), permettant une récupération fluide pour inspection ou utilisation dans les applications. Cette méthode offre un accès pratique aux images d’aperçu, améliorant l’interaction de l’utilisateur avec les données d’image.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - Les images d’aperçu.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Récupère l’image d’aperçu existante dans le `format` spécifié ou renvoie `` si aucune n’est trouvée. Cette méthode offre une flexibilité dans l’accès aux images d’aperçu adaptées à des formats spécifiques, optimisant la compatibilité et la gestion des ressources au sein des applications.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Récupère l’image d’aperçu existante dans le `format` spécifié ou renvoie `` si aucune n’est trouvée. Cette méthode offre une flexibilité dans l’accès aux images d’aperçu adaptées à des formats spécifiques, optimisant la compatibilité et la gestion des ressources au sein des applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | long | Le format de l’image d’aperçu EPS. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Personnalisez les palettes d’image pour obtenir des schémas de couleurs uniques et améliorer l’attrait visuel. Adaptez les couleurs pour des effets spécifiques et optimisez la qualité de l’image sur différentes plateformes et appareils avec facilité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette à définir. |
| updateColors | boolean | si défini sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

