---
title: "EmfChord"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L’enregistrement EMR_CHORD spécifie un chord qui est une région délimitée par l’intersection d’une ellipse et d’un segment de ligne appelé sécante."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

L’enregistrement EMR\_CHORD spécifie un chord, qui est une région délimitée par l’intersection d’une ellipse et d’un segment de ligne, appelé sécante. Le chord est contourné en utilisant le stylo actuel et rempli en utilisant la brosse actuelle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfChord`. |
| [EmfChord()](#EmfChord--) | Initialise une nouvelle instance de la classe `EmfChord`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBox()](#getBox--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], qui indique le rectangle englobant inclusif-inclusif. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], qui indique le rectangle englobant inclusif-inclusif. |
| [getStart()](#getStart--) | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées logiques du point final du rayon définissant le début du chord. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées logiques du point final du rayon définissant le début du chord. |
| [getEnd()](#getEnd--) | Obtient ou définit un objet WMF PointL de 64 bits qui indique les coordonnées logiques du point final du rayon définissant la fin du chord. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL de 64 bits qui indique les coordonnées logiques du point final du rayon définissant la fin du chord. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfChord`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


Initialise une nouvelle instance de la classe `EmfChord`.

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


Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées logiques du point final du rayon définissant le début du chord.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui indique les coordonnées logiques du point final du rayon définissant le début du chord.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Obtient ou définit un objet WMF PointL de 64 bits qui indique les coordonnées logiques du point final du rayon définissant la fin du chord.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Obtient ou définit un objet WMF PointL de 64 bits qui indique les coordonnées logiques du point final du rayon définissant la fin du chord.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

