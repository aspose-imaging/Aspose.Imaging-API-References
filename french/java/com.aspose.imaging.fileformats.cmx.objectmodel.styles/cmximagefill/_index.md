---
title: "CmxImageFill"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Informations de remplissage d'image"
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---
**Inheritance:**
java.lang.Object
```
public class CmxImageFill
```

Informations de remplissage d'image
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CmxImageFill()](#CmxImageFill--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImages()](#getImages--) | Obtient les images. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Définit les images. |
| [getProcedure()](#getProcedure--) | Obtient la procédure. |
| [setProcedure(CmxProcedure value)](#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-) | Définit la procédure. |
| [getTileOffsetX()](#getTileOffsetX--) | Obtient le décalage de tuile X. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Définit le décalage de tuile X. |
| [getTileOffsetY()](#getTileOffsetY--) | Obtient le décalage de tuile Y. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Définit le décalage de tuile Y. |
| [getRcpOffset()](#getRcpOffset--) | Obtient le décalage relatif entre les lignes ou colonnes de tuiles (dépend de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [setRcpOffset(float value)](#setRcpOffset-float-) | Définit le décalage relatif entre les lignes ou colonnes de tuiles (dépend de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [getOffsetType()](#getOffsetType--) | Obtient le type de décalage entre les tuiles adjacentes. |
| [setOffsetType(int value)](#setOffsetType-int-) | Définit le type de décalage entre les tuiles adjacentes. |
| [getPatternWidth()](#getPatternWidth--) | Obtient la largeur du motif. |
| [setPatternWidth(float value)](#setPatternWidth-float-) | Définit la largeur du motif. |
| [getPatternHeight()](#getPatternHeight--) | Obtient la hauteur du motif. |
| [setPatternHeight(float value)](#setPatternHeight-float-) | Définit la hauteur du motif. |
| [isRelative()](#isRelative--) | Obtient une valeur indiquant si les valeurs de taille des motifs sont relatives. |
| [setRelative(boolean value)](#setRelative-boolean-) | Définit une valeur indiquant si les valeurs de taille des motifs sont relatives. |
| [getRotate180()](#getRotate180--) | Obtient une valeur indiquant si cet [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) est à l'envers. |
| [setRotate180(boolean value)](#setRotate180-boolean-) | Définit une valeur indiquant si cet [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) est à l'envers. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### CmxImageFill() {#CmxImageFill--}
```
public CmxImageFill()
```


### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Obtient les images.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - les images.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Définit les images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | les images. |

### getProcedure() {#getProcedure--}
```
public final CmxProcedure getProcedure()
```


Obtient la procédure.

**Returns:**
[CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) - the procedure.
### setProcedure(CmxProcedure value) {#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-}
```
public final void setProcedure(CmxProcedure value)
```


Définit la procédure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) | la procédure. |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Obtient le décalage de tuile X.

**Returns:**
float - le décalage de tuile X.
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Définit le décalage de tuile X.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | le décalage de tuile X. |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Obtient le décalage de tuile Y.

**Returns:**
float - le décalage de tuile Y.
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Définit le décalage de tuile Y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | le décalage de tuile Y. |

### getRcpOffset() {#getRcpOffset--}
```
public final float getRcpOffset()
```


Obtient le décalage relatif entre les rangées ou colonnes de tuiles (dépend de `OffsetType`(\\#getOffsetType.getOffsetType/\\#setOffsetType(int).setOffsetType(int))). La dimension est exprimée en fractions de la hauteur ou de la largeur.

**Returns:**
float - le décalage relatif entre les rangées ou colonnes de tuiles (dépend de `OffsetType`(\\#getOffsetType.getOffsetType/\\#setOffsetType(int).setOffsetType(int))).
### setRcpOffset(float value) {#setRcpOffset-float-}
```
public final void setRcpOffset(float value)
```


Définit le décalage relatif entre les rangées ou colonnes de tuiles (dépend de `OffsetType`(\\#getOffsetType.getOffsetType/\\#setOffsetType(int).setOffsetType(int))). La dimension est exprimée en fractions de la hauteur ou de la largeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | le décalage relatif entre les rangées ou colonnes de tuiles (dépend de `OffsetType`(\\#getOffsetType.getOffsetType/\\#setOffsetType(int).setOffsetType(int))). |

### getOffsetType() {#getOffsetType--}
```
public final int getOffsetType()
```


Obtient le type de décalage entre les tuiles adjacentes.

**Returns:**
int - le type de décalage entre les tuiles adjacentes.
### setOffsetType(int value) {#setOffsetType-int-}
```
public final void setOffsetType(int value)
```


Définit le type de décalage entre les tuiles adjacentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le type de décalage entre les tuiles adjacentes. |

### getPatternWidth() {#getPatternWidth--}
```
public final float getPatternWidth()
```


Obtient la largeur du motif. Utilise l'unité de mesure de distance de document commune si `IsRelative`(\\#isRelative.isRelative/\\#setRelative(boolean).setRelative(boolean)) est `false`, sinon la dimension est la fraction de la largeur en pixels de l'image.

**Returns:**
float - la largeur du motif.
### setPatternWidth(float value) {#setPatternWidth-float-}
```
public final void setPatternWidth(float value)
```


Définit la largeur du motif. Utilise l'unité de mesure de distance de document commune si `IsRelative`(\\#isRelative.isRelative/\\#setRelative(boolean).setRelative(boolean)) est `false`, sinon la dimension est la fraction de la largeur en pixels de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | la largeur du motif. |

### getPatternHeight() {#getPatternHeight--}
```
public final float getPatternHeight()
```


Obtient la hauteur du motif. Utilise l'unité de mesure de distance de document commune si `IsRelative`(\\#isRelative.isRelative/\\#setRelative(boolean).setRelative(boolean)) est `false`, sinon la dimension est la fraction de la hauteur en pixels de l'image.

**Returns:**
float - la hauteur du motif.
### setPatternHeight(float value) {#setPatternHeight-float-}
```
public final void setPatternHeight(float value)
```


Définit la hauteur du motif. Utilise l'unité de mesure de distance de document commune si `IsRelative`(\\#isRelative.isRelative/\\#setRelative(boolean).setRelative(boolean)) est `false`, sinon la dimension est la fraction de la hauteur en pixels de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | la hauteur du motif. |

### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Obtient une valeur indiquant si les valeurs de taille des motifs sont relatives.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public final void setRelative(boolean value)
```


Définit une valeur indiquant si les valeurs de taille des motifs sont relatives.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getRotate180() {#getRotate180--}
```
public final boolean getRotate180()
```


Obtient une valeur indiquant si cet [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) est à l'envers.

Valeur : `true` si l'image est à l'envers ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si ce [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) est à l'envers.
### setRotate180(boolean value) {#setRotate180-boolean-}
```
public final void setRotate180(boolean value)
```


Définit une valeur indiquant si cet [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) est à l'envers.

Valeur : `true` si l'image est à l'envers ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | une valeur indiquant si ce [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) est à l'envers. |

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente cette instance.

**Returns:**
java.lang.String - Une chaîne qui représente cette instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
