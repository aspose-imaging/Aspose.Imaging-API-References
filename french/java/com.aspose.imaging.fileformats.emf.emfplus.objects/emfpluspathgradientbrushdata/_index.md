---
title: "EmfPlusPathGradientBrushData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusPathGradientBrushData spécifie un dégradé de chemin pour une brosse graphique."
type: docs
weight: 59
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

L'objet EmfPlusPathGradientBrushData spécifie un dégradé de chemin pour une brosse graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie s'il faut peindre la zone en dehors de la bordure du pinceau. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie s'il faut peindre la zone en dehors de la bordure du pinceau. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. |
| [getCenterPointF()](#getCenterPointF--) | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Obtient ou définit un tableau d'objets EmfPlusARGB de type SurroundingColorCount qui spécifient les couleurs pour des points discrets sur la bordure du pinceau. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Obtient ou définit un tableau d'objets EmfPlusARGB de type SurroundingColorCount qui spécifient les couleurs pour des points discrets sur la bordure du pinceau. |
| [getBoundaryData()](#getBoundaryData--) | Obtient ou définit la bordure du pinceau de dégradé de chemin, qui est spécifiée soit par un chemin, soit par une spline cardinal fermée. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Obtient ou définit la bordure du pinceau de dégradé de chemin, qui est spécifiée soit par un chemin, soit par une spline cardinal fermée. |
| [getOptionalData()](#getOptionalData--) | Obtient ou définit un objet optionnel EmfPlusPathGradientBrushOptionalData (section 2.2.2.30) qui spécifie des données supplémentaires pour le pinceau de dégradé de chemin. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Obtient ou définit un objet optionnel EmfPlusPathGradientBrushOptionalData (section 2.2.2.30) qui spécifie des données supplémentaires pour le pinceau de dégradé de chemin. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée des indicateurs BrushData (section 2.1.2.1). Les indicateurs suivants sont pertinents pour un pinceau de dégradé de chemin :

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée des indicateurs BrushData (section 2.1.2.1). Les indicateurs suivants sont pertinents pour un pinceau de dégradé de chemin :

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui indique s'il faut peindre la zone en dehors de la bordure du pinceau. Lors du dessin en dehors de la bordure, le mode d'enroulement spécifie comment le dégradé de couleur est répété

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui indique s'il faut peindre la zone en dehors de la bordure du pinceau. Lors du dessin en dehors de la bordure, le mode d'enroulement spécifie comment le dégradé de couleur est répété

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. La couleur du pinceau passe progressivement de la couleur de la bordure à la couleur centrale lorsqu'elle se déplace de la bordure vers le point central.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. La couleur du pinceau passe progressivement de la couleur de la bordure à la couleur centrale lorsqu'elle se déplace de la bordure vers le point central.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. La couleur du pinceau passe progressivement de la couleur de la bordure à la couleur centrale lorsqu'elle se déplace de la bordure vers le point central.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau de dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. La couleur du pinceau passe progressivement de la couleur de la bordure à la couleur centrale lorsqu'elle se déplace de la bordure vers le point central.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Obtient ou définit un tableau d'objets EmfPlusARGB de type SurroundingColorCount qui spécifient les couleurs pour des points discrets sur la bordure du pinceau.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Obtient ou définit un tableau d'objets EmfPlusARGB de type SurroundingColorCount qui spécifient les couleurs pour des points discrets sur la bordure du pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Obtient ou définit la bordure du pinceau de dégradé de chemin, qui est spécifiée soit par un chemin, soit par une spline cardinal fermée. Si le drapeau BrushDataPath est défini dans le champ BrushDataFlags, ce champ DOIT contenir un objet EmfPlusBoundaryPathData (section 2.2.2.6) ; sinon, ce champ DOIT contenir un objet EmfPlusBoundaryPointData (section 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Obtient ou définit la bordure du pinceau de dégradé de chemin, qui est spécifiée soit par un chemin, soit par une spline cardinal fermée. Si le drapeau BrushDataPath est défini dans le champ BrushDataFlags, ce champ DOIT contenir un objet EmfPlusBoundaryPathData (section 2.2.2.6) ; sinon, ce champ DOIT contenir un objet EmfPlusBoundaryPointData (section 2.2.2.7).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Obtient ou définit un objet optionnel EmfPlusPathGradientBrushOptionalData (section 2.2.2.30) qui spécifie des données supplémentaires pour le pinceau de dégradé de chemin. Le contenu spécifique de ce champ est déterminé par la valeur du champ BrushDataFlags.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Obtient ou définit un objet optionnel EmfPlusPathGradientBrushOptionalData (section 2.2.2.30) qui spécifie des données supplémentaires pour le pinceau de dégradé de chemin. Le contenu spécifique de ce champ est déterminé par la valeur du champ BrushDataFlags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

