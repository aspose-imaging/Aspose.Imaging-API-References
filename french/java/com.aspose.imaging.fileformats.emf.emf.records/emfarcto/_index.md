---
title: "EmfArcTo"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L’enregistrement EMR_ARCTO spécifie un arc elliptique."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

L’enregistrement EMR\_ARCTO spécifie un arc elliptique. Il réinitialise la position actuelle au point final de l’arc.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfArcTo`. |
| [EmfArcTo()](#EmfArcTo--) | Initialise une nouvelle instance de la classe `EmfArcTo`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBox()](#getBox--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant. |
| [getStart()](#getStart--) | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées du premier point final radial, en unités logiques. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées du premier point final radial, en unités logiques. |
| [getEnd()](#getEnd--) | Obtient ou définit un objet WMF PointL de 64 bits qui spécifie les coordonnées du deuxième point final radial, en unités logiques. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL de 64 bits qui spécifie les coordonnées du deuxième point final radial, en unités logiques. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfArcTo`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


Initialise une nouvelle instance de la classe `EmfArcTo`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées du premier point final radial, en unités logiques.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées du premier point final radial, en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Obtient ou définit un objet WMF PointL de 64 bits qui spécifie les coordonnées du deuxième point final radial, en unités logiques.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Obtient ou définit un objet WMF PointL de 64 bits qui spécifie les coordonnées du deuxième point final radial, en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

