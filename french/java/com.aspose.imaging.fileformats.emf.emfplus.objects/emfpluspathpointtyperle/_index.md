---
title: "EmfPlusPathPointTypeRle"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusPathPointTypeRle spécifie des valeurs de type associées aux points d'un chemin graphique en utilisant la compression RLE."
type: docs
weight: 62
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

L'objet EmfPlusPathPointTypeRle spécifie les valeurs de type associées aux points d'un tracé graphique en utilisant la compression RLE. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 bit): Si défini, les points du tracé sont sur une courbe de Bézier. Si non défini, les points du tracé sont sur une ligne graphique. RunCount (6 bits): Le nombre d'exécutions, qui correspond au nombre de points du tracé à associer au type dans le champ PointType. PointType (1 octet): Un objet EmfPlusPathPointType (section 2.2.2.31) qui spécifie le type à associer aux points du tracé.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getData()](#getData--) | Obtient ou définit les données. |
| [setData(int value)](#setData-int-) | Obtient ou définit les données. |
| [getBezier()](#getBezier--) | Obtient ou définit une valeur indiquant si ce `EmfPlusPathPointTypeRle` est de type Bézier. |
| [setBezier(boolean value)](#setBezier-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusPathPointTypeRle` est de type Bézier. |
| [getRunCount()](#getRunCount--) | Obtient ou définit le nombre d'exécutions. |
| [setRunCount(byte value)](#setRunCount-byte-) | Obtient ou définit le nombre d'exécutions. |
| [getPointType()](#getPointType--) | Obtient ou définit le type du point. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Obtient ou définit le type du point. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Obtient ou définit les données.

Valeur : les données.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Obtient ou définit les données.

Valeur : les données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusPathPointTypeRle` est de type Bézier. Si défini, les points du tracé sont sur une courbe de Bézier. Si non défini, les points du tracé sont sur une ligne graphique.

Valeur: `true` si Bézier; sinon, `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusPathPointTypeRle` est de type Bézier. Si défini, les points du tracé sont sur une courbe de Bézier. Si non défini, les points du tracé sont sur une ligne graphique.

Valeur: `true` si Bézier; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Obtient ou définit le nombre d'exécutions. RunCount (6 bits): Le nombre d'exécutions, qui correspond au nombre de points du tracé à associer au type dans le champ PointType

Valeur: le nombre d'exécutions.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Obtient ou définit le nombre d'exécutions. RunCount (6 bits): Le nombre d'exécutions, qui correspond au nombre de points du tracé à associer au type dans le champ PointType

Valeur: le nombre d'exécutions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Obtient ou définit le type du point. PointType (1 octet): Un objet EmfPlusPathPointType (section 2.2.31) qui spécifie le type à associer aux points du tracé.

Valeur: le type du point.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Obtient ou définit le type du point. PointType (1 octet): Un objet EmfPlusPathPointType (section 2.2.31) qui spécifie le type à associer aux points du tracé.

Valeur: le type du point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

