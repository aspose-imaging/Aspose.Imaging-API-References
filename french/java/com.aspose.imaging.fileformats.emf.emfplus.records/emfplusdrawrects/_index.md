---
title: "EmfPlusDrawRects"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawRects spécifie le dessin d'une série de rectangles"
type: docs
weight: 27
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawRects extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawRects spécifie le dessin d'une série de rectangles
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawRects(EmfPlusRecord source)](#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawRects`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getRectData()](#getRectData--) | Obtient ou définit les données du rectangle Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Obtient ou définit les données du rectangle Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle. |
### EmfPlusDrawRects(EmfPlusRecord source) {#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawRects(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawRects`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtient ou définit une valeur indiquant si le PointData est compressé. Si elle est définie, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si elle n'est pas définie, RectData contient un objet EmfPlusRectF (section 2.2.2.39).

Valeur : `true` si compressé ; sinon, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si le PointData est compressé. Si elle est définie, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si elle n'est pas définie, RectData contient un objet EmfPlusRectF (section 2.2.2.39).

Valeur : `true` si compressé ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'indice d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner les rectangles. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'indice d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner les rectangles. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Obtient ou définit les données du rectangle Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Obtient ou définit les données du rectangle Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

