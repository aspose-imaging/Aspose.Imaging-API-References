---
title: "EmfLineTo"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_LINETO spécifie une ligne depuis la position actuelle jusqu'au point spécifié sans l'inclure. Il réinitialise la position actuelle au point spécifié."
type: docs
weight: 68
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emflineto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfLineTo extends EmfRecord
```

L'enregistrement EMR\_LINETO spécifie une ligne depuis la position actuelle jusqu'au point spécifié, sans l'inclure. Il réinitialise la position actuelle au point spécifié.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfLineTo(EmfRecord record)](#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfLineTo`. |
| [EmfLineTo()](#EmfLineTo--) | Initialise une nouvelle instance de la classe `EmfLineTo`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPoint()](#getPoint--) | Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées du point final de la ligne. |
| [setPoint(Point value)](#setPoint-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées du point final de la ligne. |
### EmfLineTo(EmfRecord record) {#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfLineTo(EmfRecord record)
```


Initialise une nouvelle instance de la classe `EmfLineTo`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | L'enregistrement. |

### EmfLineTo() {#EmfLineTo--}
```
public EmfLineTo()
```


Initialise une nouvelle instance de la classe `EmfLineTo`.

### getPoint() {#getPoint--}
```
public Point getPoint()
```


Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées du point final de la ligne.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPoint(Point value) {#setPoint-com.aspose.imaging.Point-}
```
public void setPoint(Point value)
```


Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique les coordonnées du point final de la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

