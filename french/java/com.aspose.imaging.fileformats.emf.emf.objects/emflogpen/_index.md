---
title: "EmfLogPen"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet LogPen définit la largeur du style et la couleur d'un crayon logique."
type: docs
weight: 27
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

L'objet LogPen définit le style, la largeur et la couleur d'un stylo logique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le PenStyle. |
| [setPenStyle(int value)](#setPenStyle-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le PenStyle. |
| [getWidth()](#getWidth--) | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie la largeur du crayon par la valeur de son champ x. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie la largeur du crayon par la valeur de son champ x. |
| [getAffectWidth()](#getAffectWidth--) | Obtient ou définit la largeur de l'affect. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Obtient ou définit la largeur de l'affect. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la valeur de la couleur du crayon. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la valeur de la couleur du crayon. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le PenStyle. La valeur DOIT être définie à partir de la table d'énumération PenStyle, spécifiée dans la section 2.1.25.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le PenStyle. La valeur DOIT être définie à partir de la table d'énumération PenStyle, spécifiée dans la section 2.1.25.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie la largeur du crayon par la valeur de son champ x. La valeur de son champ y DOIT être ignorée.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie la largeur du crayon par la valeur de son champ x. La valeur de son champ y DOIT être ignorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Obtient ou définit la largeur de l'affect.

Valeur : la largeur de l'affect.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Obtient ou définit la largeur de l'affect.

Valeur : la largeur de l'affect.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la valeur de la couleur du crayon.

Valeur : la couleur ARGB de 32 bits

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la valeur de la couleur du crayon.

Valeur : la couleur ARGB de 32 bits

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

