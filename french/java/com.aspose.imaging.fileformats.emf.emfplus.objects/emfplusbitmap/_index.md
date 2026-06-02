---
title: "EmfPlusBitmap"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusBitmap spécifie un bitmap qui contient une image graphique."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

L'objet EmfPlusBitmap spécifie un bitmap qui contient une image graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Obtient ou définit les données du bitmap BitmapData (variable) : données de longueur variable qui définissent l'objet de données du bitmap spécifié dans le champ Type. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Obtient ou définit les données du bitmap BitmapData (variable) : données de longueur variable qui définissent l'objet de données du bitmap spécifié dans le champ Type. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur du bitmap Height (4 octets) : un entier signé de 32 bits qui spécifie la hauteur en pixels de la zone occupée par le bitmap. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit la hauteur du bitmap Height (4 octets) : un entier signé de 32 bits qui spécifie la hauteur en pixels de la zone occupée par le bitmap. |
| [getPixelFormat()](#getPixelFormat--) | Obtient ou définit le format de pixel PixelFormat (4 octets) : un entier non signé de 32 bits qui spécifie le format des pixels qui composent l'image bitmap. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Obtient ou définit le format de pixel PixelFormat (4 octets) : un entier non signé de 32 bits qui spécifie le format des pixels qui composent l'image bitmap. |
| [getStride()](#getStride--) | Obtient ou définit le pas de l'image Stride (4 octets) : un entier signé de 32 bits qui spécifie le décalage en octets entre le début d'une ligne de balayage et la suivante. |
| [setStride(int value)](#setStride-int-) | Obtient ou définit le pas de l'image Stride (4 octets) : un entier signé de 32 bits qui spécifie le décalage en octets entre le début d'une ligne de balayage et la suivante. |
| [getType()](#getType--) | Obtient ou définit le type de l'image Type (4 octets) : un entier non signé de 32 bits qui spécifie le type de données dans le champ BitmapData. |
| [setType(int value)](#setType-int-) | Obtient ou définit le type de l'image Type (4 octets) : un entier non signé de 32 bits qui spécifie le type de données dans le champ BitmapData. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de l'image Width (4 octets) : un entier signé de 32 bits qui spécifie la largeur en pixels de la zone occupée par le bitmap. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit la largeur de l'image Width (4 octets) : un entier signé de 32 bits qui spécifie la largeur en pixels de la zone occupée par le bitmap. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Obtient ou définit les données du bitmap BitmapData (variable) : données de longueur variable qui définissent l'objet de données du bitmap spécifié dans le champ Type. Le contenu et le format des données peuvent différer pour chaque type de bitmap.

Valeur : les données du bitmap.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Obtient ou définit les données du bitmap BitmapData (variable) : données de longueur variable qui définissent l'objet de données du bitmap spécifié dans le champ Type. Le contenu et le format des données peuvent différer pour chaque type de bitmap.

Valeur : les données du bitmap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit la hauteur du bitmap Height (4 octets) : un entier signé de 32 bits qui spécifie la hauteur en pixels de la zone occupée par le bitmap. Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur: la hauteur.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit la hauteur du bitmap Height (4 octets) : un entier signé de 32 bits qui spécifie la hauteur en pixels de la zone occupée par le bitmap. Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur: la hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtient ou définit le format de pixel PixelFormat (4 octets) : un entier non signé de 32 bits qui spécifie le format des pixels qui composent l'image bitmap. Les formats de pixel pris en charge sont spécifiés dans l'énumération `EmfPlusPixelFormat` (section 2.1.1.25). Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur : le format de pixel.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Obtient ou définit le format de pixel PixelFormat (4 octets) : un entier non signé de 32 bits qui spécifie le format des pixels qui composent l'image bitmap. Les formats de pixel pris en charge sont spécifiés dans l'énumération `EmfPlusPixelFormat` (section 2.1.1.25). Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur : le format de pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Obtient ou définit le pas de l'image Stride (4 octets) : un entier signé de 32 bits qui spécifie le décalage en octets entre le début d'une ligne de balayage et la suivante. Cette valeur correspond au nombre d'octets par pixel, indiqué dans le champ PixelFormat, multiplié par la largeur en pixels, indiquée dans le champ Width. La valeur de ce champ DOIT être un multiple de quatre. Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur : le pas.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Obtient ou définit le pas de l'image Stride (4 octets) : un entier signé de 32 bits qui spécifie le décalage en octets entre le début d'une ligne de balayage et la suivante. Cette valeur correspond au nombre d'octets par pixel, indiqué dans le champ PixelFormat, multiplié par la largeur en pixels, indiquée dans le champ Width. La valeur de ce champ DOIT être un multiple de quatre. Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur : le pas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getType() {#getType--}
```
public int getType()
```


Obtient ou définit le type de l'image Type (4 octets) : un entier non signé de 32 bits qui spécifie le type de données dans le champ BitmapData. Cette valeur DOIT être définie dans l'énumération `EmcPlusBitmapDataType` (section 2.1.1.2).

Valeur: le type.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtient ou définit le type de l'image Type (4 octets) : un entier non signé de 32 bits qui spécifie le type de données dans le champ BitmapData. Cette valeur DOIT être définie dans l'énumération `EmcPlusBitmapDataType` (section 2.1.1.2).

Valeur: le type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit la largeur de l'image Width (4 octets) : un entier signé de 32 bits qui spécifie la largeur en pixels de la zone occupée par le bitmap. Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur: la largeur.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit la largeur de l'image Width (4 octets) : un entier signé de 32 bits qui spécifie la largeur en pixels de la zone occupée par le bitmap. Si l'image est compressée, selon le champ Type, cette valeur est indéfinie et DOIT être ignorée.

Valeur: la largeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

