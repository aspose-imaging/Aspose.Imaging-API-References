---
title: "EmfSetPixelV"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETPIXELV définit la couleur du pixel aux coordonnées logiques spécifiées."
type: docs
weight: 135
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSetPixelV extends EmfDrawingRecordType
```

L'enregistrement EMR\_SETPIXELV définit la couleur du pixel aux coordonnées logiques spécifiées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetPixelV(EmfRecord source)](#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetPixelV`. |
| [EmfSetPixelV()](#EmfSetPixelV--) | Initialise une nouvelle instance de la classe [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPixel()](#getPixel--) | Obtient ou définit un objet WMF PointL 64 bits ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées logiques du pixel. |
| [setPixel(Point value)](#setPixel-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL 64 bits ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées logiques du pixel. |
| [getArgb32Color()](#getArgb32Color--) | Obtient ou définit un objet WMF ColorRef 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie la couleur du pixel. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Obtient ou définit un objet WMF ColorRef 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie la couleur du pixel. |
### EmfSetPixelV(EmfRecord source) {#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPixelV(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetPixelV`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSetPixelV() {#EmfSetPixelV--}
```
public EmfSetPixelV()
```


Initialise une nouvelle instance de la classe [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv).

### getPixel() {#getPixel--}
```
public Point getPixel()
```


Obtient ou définit un objet WMF PointL 64 bits ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées logiques du pixel.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPixel(Point value) {#setPixel-com.aspose.imaging.Point-}
```
public void setPixel(Point value)
```


Obtient ou définit un objet WMF PointL 64 bits ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées logiques du pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Obtient ou définit un objet WMF ColorRef 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie la couleur du pixel.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Obtient ou définit un objet WMF ColorRef 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie la couleur du pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

