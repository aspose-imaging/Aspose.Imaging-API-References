---
title: "EmfPie"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_PIE spécifie un secteur en forme de tarte limité par l'intersection d'une ellipse et de deux radiales."
type: docs
weight: 82
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

L'enregistrement EMR\_PIE spécifie un secteur en forme de tarte limité par l'intersection d'une ellipse et de deux radiales. La tarte est contournée en utilisant le stylo actuel et remplie en utilisant le pinceau actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPie`. |
| [EmfPie()](#EmfPie--) | Initialise une nouvelle instance de la classe `EmfPie`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBox()](#getBox--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], qui indique le rectangle englobant inclusif-inclusif. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], qui indique le rectangle englobant inclusif-inclusif. |
| [getStart()](#getStart--) | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées, en unités logiques, du point final de la première radiale. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées, en unités logiques, du point final de la première radiale. |
| [getEnd()](#getEnd--) | Obtient ou définit un objet PointL de 64 bits qui indique les coordonnées, en unités logiques, du point final de la deuxième radiale. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Obtient ou définit un objet PointL de 64 bits qui indique les coordonnées, en unités logiques, du point final de la deuxième radiale. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPie`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


Initialise une nouvelle instance de la classe `EmfPie`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], qui indique le rectangle englobant inclusif-inclusif.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], qui indique le rectangle englobant inclusif-inclusif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées, en unités logiques, du point final de la première radiale.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées, en unités logiques, du point final de la première radiale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Obtient ou définit un objet PointL de 64 bits qui indique les coordonnées, en unités logiques, du point final de la deuxième radiale.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Obtient ou définit un objet PointL de 64 bits qui indique les coordonnées, en unités logiques, du point final de la deuxième radiale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

