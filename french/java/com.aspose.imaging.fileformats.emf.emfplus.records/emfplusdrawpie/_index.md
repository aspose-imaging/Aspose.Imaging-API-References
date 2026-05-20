---
title: "EmfPlusDrawPie"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawPie spécifie le dessin d'une section de l'intérieur d'une ellipse."
type: docs
weight: 26
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawPie spécifie le dessin d'une section de l'intérieur d'une ellipse.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawPie`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getStartAngle()](#getStartAngle--) | Obtient ou définit l'angle de départ Un nombre à virgule flottante de 32 bits, non négatif, qui spécifie l'angle entre l'axe des x et le point de départ du secteur de tarte. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtient ou définit l'angle de départ Un nombre à virgule flottante de 32 bits, non négatif, qui spécifie l'angle entre l'axe des x et le point de départ du secteur de tarte. |
| [getSweepAngle()](#getSweepAngle--) | Obtient ou définit l'angle d'arc Un nombre à virgule flottante de 32 bits qui spécifie l'étendue de l'arc définissant le secteur de tarte à dessiner, exprimé en degrés mesurés à partir du point de départ défini par la valeur StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtient ou définit l'angle d'arc Un nombre à virgule flottante de 32 bits qui spécifie l'étendue de l'arc définissant le secteur de tarte à dessiner, exprimé en degrés mesurés à partir du point de départ défini par la valeur StartAngle. |
| [getRectData()](#getRectData--) | Obtient ou définit les données du rectangle Soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse contenant le secteur de tarte. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtient ou définit les données du rectangle Soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse contenant le secteur de tarte. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawPie`.

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


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner le secteur. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner le secteur. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtient ou définit l'angle de départ Un nombre à virgule flottante de 32 bits, non négatif, qui spécifie l'angle entre l'axe des x et le point de départ du secteur de tarte. Toute valeur est acceptable, mais elle DOIT être interprétée modulo 360, le résultat utilisé devant être compris entre 0,0 inclus et 360,0 exclus.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Obtient ou définit l'angle de départ Un nombre à virgule flottante de 32 bits, non négatif, qui spécifie l'angle entre l'axe des x et le point de départ du secteur de tarte. Toute valeur est acceptable, mais elle DOIT être interprétée modulo 360, le résultat utilisé devant être compris entre 0,0 inclus et 360,0 exclus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtient ou définit l'angle d'arc Un nombre à virgule flottante de 32 bits qui spécifie l'étendue de l'arc définissant le secteur de tarte à dessiner, exprimé en degrés mesurés à partir du point de départ défini par la valeur StartAngle. Toute valeur est acceptable, mais elle DOIT être limitée à -360,0 à 360,0 inclus. Une valeur positive indique que le balayage est défini dans le sens horaire, et une valeur négative indique qu'il est défini dans le sens antihoraire.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Obtient ou définit l'angle d'arc Un nombre à virgule flottante de 32 bits qui spécifie l'étendue de l'arc définissant le secteur de tarte à dessiner, exprimé en degrés mesurés à partir du point de départ défini par la valeur StartAngle. Toute valeur est acceptable, mais elle DOIT être limitée à -360,0 à 360,0 inclus. Une valeur positive indique que le balayage est défini dans le sens horaire, et une valeur négative indique qu'il est défini dans le sens antihoraire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Obtient ou définit les données du rectangle Soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse contenant le secteur de tarte. Ce rectangle définit la position, la taille et la forme de la tarte. Le type d'objet dans ce champ est indiqué par la valeur du champ Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Obtient ou définit les données du rectangle Soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse contenant le secteur de tarte. Ce rectangle définit la position, la taille et la forme de la tarte. Le type d'objet dans ce champ est indiqué par la valeur du champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

