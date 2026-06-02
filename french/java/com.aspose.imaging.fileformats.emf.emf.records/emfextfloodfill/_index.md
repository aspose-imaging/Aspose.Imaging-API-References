---
title: "EmfExtFloodFill"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_EXTFLOODFILL remplit une zone de la surface d'affichage avec le pinceau actuel."
type: docs
weight: 54
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

L'enregistrement EMR\_EXTFLOODFILL remplit une zone de la surface d'affichage avec la brosse actuelle
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfExtFloodFill`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStart()](#getStart--) | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15), qui spécifie les coordonnées, en unités logiques, où le remplissage commence. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15), qui spécifie les coordonnées, en unités logiques, où le remplissage commence. |
| [getArgb32Color()](#getArgb32Color--) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8), qui est utilisé avec FloodFillMode pour déterminer la zone à remplir. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8), qui est utilisé avec FloodFillMode pour déterminer la zone à remplir. |
| [getFloodFillMode()](#getFloodFillMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser la valeur Color pour déterminer la zone de l'opération de remplissage. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser la valeur Color pour déterminer la zone de l'opération de remplissage. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfExtFloodFill`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getStart() {#getStart--}
```
public Point getStart()
```


Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15), qui spécifie les coordonnées, en unités logiques, où le remplissage commence.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15), qui spécifie les coordonnées, en unités logiques, où le remplissage commence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8), qui est utilisé avec FloodFillMode pour déterminer la zone à remplir.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8), qui est utilisé avec FloodFillMode pour déterminer la zone à remplir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser la valeur Color pour déterminer la zone de l'opération de remplissage. La valeur DOIT être dans l'énumération FloodFill (section 2.1.13).

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser la valeur Color pour déterminer la zone de l'opération de remplissage. La valeur DOIT être dans l'énumération FloodFill (section 2.1.13).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

