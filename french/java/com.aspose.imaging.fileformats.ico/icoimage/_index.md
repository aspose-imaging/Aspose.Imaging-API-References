---
title: "IcoImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez facilement les fichiers d'images ICO avec notre API prenant en charge divers formats de fichiers et types de trames, y compris PNG et BMP."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Manipulez facilement les fichiers d'images ICO avec notre API, prenant en charge divers formats de fichiers et types de trames, y compris PNG et BMP. Personnalisez les paramètres de bits par pixel et mettez à jour les dimensions de l'image de manière fluide, garantissant une représentation optimale et une compatibilité de vos icônes sur différentes plateformes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | Commencez la création d'images ICO facilement en utilisant la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Conçue pour la simplicité et l'efficacité, la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) vous permet de créer des images ICO en toute simplicité. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Récupérez le format de fichier facilement avec cette propriété, permettant une intégration fluide dans votre flux de travail. |
| [getPageCount()](#getPageCount--) | Obtenez immédiatement un aperçu de la structure du document grâce à cette propriété simple. |
| [getPages()](#getPages--) | Récupérez facilement des informations complètes sur les pages du document grâce à cette propriété. |
| [hasAlpha()](#hasAlpha--) | Déterminez si un canal alpha est présent dans cette instance à l'aide de cette propriété. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Étendez votre image ICO en ajoutant une entrée de page d'image, en tirant parti de [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | Enrichissez votre image ICO sans effort en insérant une entrée de page d'image en utilisant les paramètres par défaut de [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Diversifiez votre image ICO sans effort en intégrant une entrée d'image adaptée à vos besoins avec les [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) spécifiés. |
| [removePage(int index)](#removePage-int-) | Affinez votre image ICO en supprimant une entrée d'image spécifique située à l'emplacement désigné `` dans le fichier. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


Commencez la création d'images ICO sans effort en utilisant la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). Ce constructeur vous permet d'initialiser de nouvelles instances d'images ICO en spécifiant les paramètres de largeur, de hauteur et d'options de création. Avec ce constructeur simple, vous pouvez adapter les images ICO à vos spécifications exactes, garantissant une compatibilité fluide et un attrait visuel sur différentes plateformes et appareils.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Les options de création ICO. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


Conçue pour la simplicité et l'efficacité, la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) vous permet de créer des images ICO facilement. Ce constructeur initialise une nouvelle instance de la classe, offrant une base solide pour vos besoins de manipulation d'images. Que vous développiez des applications ou amélioriez des interfaces utilisateur, la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) simplifie la gestion des images ICO, vous permettant de vous concentrer sur la fourniture d'expériences exceptionnelles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'image. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Les options ICO. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez le format du fichier sans effort grâce à cette propriété, permettant une intégration fluide dans votre flux de travail. En utilisant cette propriété, vous accédez à des informations essentielles sur le format de votre fichier, garantissant compatibilité et traitement efficace.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Obtenez immédiatement un aperçu de la structure du document grâce à cette propriété simple. En invoquant cette propriété, vous récupérez sans effort le nombre total de pages contenues dans le fichier.

**Returns:**
int - le nombre de pages.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Récupérez facilement des informations complètes sur les pages du document grâce à cette propriété. En accédant à cette propriété, vous obtenez une collection ou un tableau contenant toutes les pages présentes dans le document.

**Returns:**
com.aspose.imaging.Image[] - les pages.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Déterminez si un canal alpha est présent dans cette instance à l'aide de cette propriété. Elle offre un moyen rapide de vérifier si l'image ou le document contient un canal alpha, ce qui est crucial pour diverses tâches de traitement et de rendu d'images. Idéale pour assurer la compatibilité et gérer les effets de transparence dans les images ou les documents.

**Returns:**
booléen - une valeur indiquant si cette instance possède un canal alpha.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


Étendez votre image ICO en ajoutant une entrée de page d'image, en tirant parti de [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Cette méthode intègre parfaitement les images raster dans votre fichier ICO, les convertissant en un format PNG 32 bits de haute qualité. Idéale pour améliorer vos fichiers ICO avec des images raster tout en garantissant une compatibilité optimale et une qualité de rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


Enrichissez votre image ICO sans effort en insérant une entrée de page d'image en utilisant les paramètres par défaut de [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Cette méthode convertit commodément l'image insérée en un format PNG 32 bits, assurant compatibilité et rendu de haute qualité dans l'image ICO. Idéale pour intégrer parfaitement des images PNG dans vos fichiers ICO avec facilité et efficacité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | L'image. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Diversifiez votre image ICO sans effort en intégrant une entrée d'image adaptée à vos besoins avec les [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) spécifiés. Cette méthode intègre parfaitement l'image selon vos options personnalisées, garantissant flexibilité et précision dans votre fichier ICO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | L'image. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Les options ICO. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Affinez votre image ICO en supprimant une entrée d'image spécifique située à l'emplacement désigné `` dans le fichier. Cette méthode offre un contrôle précis sur la composition de votre image, vous permettant de peaufiner votre fichier ICO avec facilité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. |

