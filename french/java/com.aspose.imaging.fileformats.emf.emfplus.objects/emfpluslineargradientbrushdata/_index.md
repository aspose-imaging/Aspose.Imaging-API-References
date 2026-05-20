---
title: "EmfPlusLinearGradientBrushData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusLinearGradientBrushData spécifie un dégradé linéaire pour une brosse graphique."
type: docs
weight: 53
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

L'objet EmfPlusLinearGradientBrushData spécifie un dégradé linéaire pour une brosse graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Obtient ou définit les drapeaux de données du pinceau. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Obtient ou définit les drapeaux de données du pinceau. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Obtient ou définit la couleur de fin. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Obtient ou définit la couleur de fin. |
| [getOptionalData()](#getOptionalData--) | Obtient ou définit les données optionnelles. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | Obtient ou définit les données optionnelles. |
| [getRectF()](#getRectF--) | Obtient ou définit le rect f. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | Obtient ou définit le rect f. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Obtient ou définit la couleur de départ. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Obtient ou définit la couleur de départ. |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit le mode d'habillage. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit le mode d'habillage. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Obtient ou définit les drapeaux de données du pinceau.

Valeur : BrushDataFlags (4 octets) : Un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée de `EmfPlusBrushDataFlags` (section 2.1.2.1).

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Obtient ou définit les drapeaux de données du pinceau.

Valeur : BrushDataFlags (4 octets) : Un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée de `EmfPlusBrushDataFlags` (section 2.1.2.1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Obtient ou définit la couleur de fin.

Valeur : Un objet EmfPlusARGB qui spécifie la couleur au point de bordure final du pinceau de dégradé linéaire.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Obtient ou définit la couleur de fin.

Valeur : Un objet EmfPlusARGB qui spécifie la couleur au point de bordure final du pinceau de dégradé linéaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


Obtient ou définit les données optionnelles.

Valeur : Un objet optionnel `EmfPlusLinearGradientBrushOptionalData` (section 2.2.2.25) qui spécifie des données supplémentaires pour le pinceau de dégradé linéaire. Le contenu spécifique de ce champ est déterminé par la valeur du champ BrushDataFlags.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


Obtient ou définit les données optionnelles.

Valeur : Un objet optionnel `EmfPlusLinearGradientBrushOptionalData` (section 2.2.2.25) qui spécifie des données supplémentaires pour le pinceau de dégradé linéaire. Le contenu spécifique de ce champ est déterminé par la valeur du champ BrushDataFlags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


Obtient ou définit le rect f.

Valeur : Un objet EmfPlusRectF (section 2.2.2.39) qui spécifie les points de départ et d'arrivée de la ligne de dégradé. Le coin supérieur gauche du rectangle est le point de départ. Le coin inférieur droit est le point d'arrivée.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


Obtient ou définit le rect f.

Valeur : Un objet EmfPlusRectF (section 2.2.2.39) qui spécifie les points de départ et d'arrivée de la ligne de dégradé. Le coin supérieur gauche du rectangle est le point de départ. Le coin inférieur droit est le point d'arrivée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Obtient ou définit la couleur de départ.

Valeur : Un objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur au point de bordure de départ du pinceau de dégradé linéaire.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Obtient ou définit la couleur de départ.

Valeur : Un objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur au point de bordure de départ du pinceau de dégradé linéaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit le mode d'habillage.

Valeur : Un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie s'il faut peindre la zone en dehors de la bordure du pinceau. Lors du dessin en dehors de la bordure, le mode d'habillage spécifie comment le dégradé de couleur est répété.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit le mode d'habillage.

Valeur : Un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie s'il faut peindre la zone en dehors de la bordure du pinceau. Lors du dessin en dehors de la bordure, le mode d'habillage spécifie comment le dégradé de couleur est répété.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

