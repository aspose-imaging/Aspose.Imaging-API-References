---
title: "EmfAngleArc"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_ANGLEARC spécifie un segment de ligne d'un arc."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

L'enregistrement EMR\_ANGLEARC spécifie un segment de ligne d'un arc. Le segment de ligne est tracé depuis la position actuelle jusqu'au début de l'arc. L'arc est dessiné le long du périmètre d'un cercle de rayon et de centre donnés. La longueur de l'arc est définie par les angles de départ et de balayage fournis.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfAngleArc`. |
| [EmfAngleArc()](#EmfAngleArc--) | Initialise une nouvelle instance de la classe `EmfAngleArc`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCenter()](#getCenter--) | Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées logiques du centre du cercle. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées logiques du centre du cercle. |
| [getRadius()](#getRadius--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le rayon du cercle, en unités logiques. |
| [setRadius(int value)](#setRadius-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le rayon du cercle, en unités logiques. |
| [getStartAngle()](#getStartAngle--) | Obtient ou définit un flottant de 32 bits qui spécifie l'angle de départ de l'arc, en degrés. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtient ou définit un flottant de 32 bits qui spécifie l'angle de départ de l'arc, en degrés. |
| [getSweepAngle()](#getSweepAngle--) | Obtient ou définit un flottant de 32 bits qui spécifie l'angle d'extension de l'arc, en degrés. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtient ou définit un flottant de 32 bits qui spécifie l'angle d'extension de l'arc, en degrés. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfAngleArc`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Initialise une nouvelle instance de la classe `EmfAngleArc`.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées logiques du centre du cercle.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées logiques du centre du cercle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le rayon du cercle, en unités logiques.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le rayon du cercle, en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtient ou définit un flottant de 32 bits qui spécifie l'angle de départ de l'arc, en degrés.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Obtient ou définit un flottant de 32 bits qui spécifie l'angle de départ de l'arc, en degrés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtient ou définit un flottant de 32 bits qui spécifie l'angle d'extension de l'arc, en degrés.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Obtient ou définit un flottant de 32 bits qui spécifie l'angle d'extension de l'arc, en degrés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

