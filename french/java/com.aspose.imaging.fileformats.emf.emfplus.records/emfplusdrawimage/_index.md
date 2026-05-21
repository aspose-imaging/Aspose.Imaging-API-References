---
title: "EmfPlusDrawImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawImage spécifie le dessin d'une image mise à l'échelle."
type: docs
weight: 22
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawImage spécifie le dessin d'une image mise à l'échelle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawImage`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getImageAttributesId()](#getImageAttributesId--) | Obtient ou définit l'identifiant des attributs d'image Un entier non signé de 32 bits qui spécifie l'index d'un objet EmfPlusImageAttributes optionnel (section 2.2.1.5) dans la table d'objets EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Obtient ou définit l'identifiant des attributs d'image Un entier non signé de 32 bits qui spécifie l'index d'un objet EmfPlusImageAttributes optionnel (section 2.2.1.5) dans la table d'objets EMF+. |
| [getRectData()](#getRectData--) | Obtient ou définit les données de rectangle Soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'image. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtient ou définit les données de rectangle Soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'image. |
| [getSrcRect()](#getSrcRect--) | Obtient ou définit le rectangle source Un objet EmfPlusRectF qui spécifie une portion de l'image à rendre. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Obtient ou définit le rectangle source Un objet EmfPlusRectF qui spécifie une portion de l'image à rendre. |
| [getSrcUnit()](#getSrcUnit--) | Obtient ou définit l'unité source Un entier signé de 32 bits qui spécifie les unités du champ SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Obtient ou définit l'unité source Un entier signé de 32 bits qui spécifie les unités du champ SrcRect. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawImage`.

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


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusImage (section 2.2.1.4) dans la table d'objets EMF+, qui spécifie l'image à rendre. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusImage (section 2.2.1.4) dans la table d'objets EMF+, qui spécifie l'image à rendre. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Obtient ou définit l'identifiant des attributs d'image Un entier non signé de 32 bits qui spécifie l'index d'un objet EmfPlusImageAttributes optionnel (section 2.2.1.5) dans la table d'objets EMF+.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Obtient ou définit l'identifiant des attributs d'image Un entier non signé de 32 bits qui spécifie l'index d'un objet EmfPlusImageAttributes optionnel (section 2.2.1.5) dans la table d'objets EMF+.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Obtient ou définit les données de rectangle Soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'image. La portion de l'image spécifiée par le champ SrcRect est mise à l'échelle pour s'adapter à ce rectangle.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Obtient ou définit les données de rectangle Soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'image. La portion de l'image spécifiée par le champ SrcRect est mise à l'échelle pour s'adapter à ce rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Obtient ou définit le rectangle source Un objet EmfPlusRectF qui spécifie une portion de l'image à rendre. La portion de l'image spécifiée par ce rectangle est mise à l'échelle pour s'adapter au rectangle de destination spécifié par le champ RectData.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Obtient ou définit le rectangle source Un objet EmfPlusRectF qui spécifie une portion de l'image à rendre. La portion de l'image spécifiée par ce rectangle est mise à l'échelle pour s'adapter au rectangle de destination spécifié par le champ RectData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Obtient ou définit l'unité source Un entier signé de 32 bits qui spécifie les unités du champ SrcRect. Il DOIT être le membre UnitTypePixel de l'énumération UnitType (section 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Obtient ou définit l'unité source Un entier signé de 32 bits qui spécifie les unités du champ SrcRect. Il DOIT être le membre UnitTypePixel de l'énumération UnitType (section 2.1.1.33).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

