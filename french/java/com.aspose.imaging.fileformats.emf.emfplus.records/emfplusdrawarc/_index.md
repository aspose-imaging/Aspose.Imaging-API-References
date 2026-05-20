---
title: "EmfPlusDrawArc"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawArc spécifie le dessin de l'arc d'une ellipse."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawArc spécifie le dessin de l'arc d'une ellipse.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawArc`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDataSize()](#getDataSize--) | Obtient la taille des données. |
| [setDataSize(int value)](#setDataSize-int-) | Définit la taille des données. |
| [getRectFloat()](#getRectFloat--) | Obtient une valeur indiquant si les données contiennent des enregistrements EmfPlusRectF ou EmfPlusRect. Ce bit indique si les données du champ RectData sont compressées. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Définit une valeur indiquant si les données contiennent des enregistrements EmfPlusRectF ou EmfPlusRect. Ce bit indique si les données du champ RectData sont compressées. |
| [getObjectId()](#getObjectId--) | Obtient l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Définit l'identifiant de l'objet. |
| [getSize()](#getSize--) | Obtient la taille. |
| [setSize(int value)](#setSize-int-) | Définit la taille. |
| [getStartAngle()](#getStartAngle--) | Obtient l'angle de départ, une valeur flottante non négative de 32 bits qui spécifie l'angle entre l'axe des x et le point de départ de l'arc. |
| [setStartAngle(float value)](#setStartAngle-float-) | Définit l'angle de départ, une valeur flottante non négative de 32 bits qui spécifie l'angle entre l'axe des x et le point de départ de l'arc. |
| [getSweepAngle()](#getSweepAngle--) | Obtient l'angle d'extension, une valeur flottante de 32 bits qui spécifie l'étendue de l'arc à tracer, exprimée en degrés mesurés depuis le point de départ défini par la valeur StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Définit l'angle d'extension, une valeur flottante de 32 bits qui spécifie l'étendue de l'arc à tracer, exprimée en degrés mesurés depuis le point de départ défini par la valeur StartAngle. |
| [getRectangleData()](#getRectangleData--) | Obtient les données du rectangle, soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse colinéaire à l'arc. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Définit les données du rectangle, soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse colinéaire à l'arc. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawArc`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtient la taille des données. Un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits des données spécifiques à l'enregistrement qui suivent. Pour ce type d'enregistrement, la valeur DOIT être l'une des suivantes : 0x00000010 si le bit C est activé dans le champ Flags. 0x00000018 si le bit C est désactivé dans le champ Flags.

**Returns:**
int - La taille des données.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Définit la taille des données. Un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits des données spécifiques à l'enregistrement qui suivent. Pour ce type d'enregistrement, la valeur DOIT être l'une des suivantes : 0x00000010 si le bit C est activé dans le champ Flags. 0x00000018 si le bit C est désactivé dans le champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La taille des données. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Obtient une valeur indiquant si les données contiennent des enregistrements EmfPlusRectF ou EmfPlusRect. Ce bit indique si les données du champ RectData sont compressées. Si le bit est activé, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si le bit est désactivé, RectData contient un objet EmfPlusRectF (section 2.2.2.39).

**Returns:**
booléen - `true` si flottant ; sinon, `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Définit une valeur indiquant si les données contiennent des enregistrements EmfPlusRectF ou EmfPlusRect. Ce bit indique si les données du champ RectData sont compressées. Si le bit est activé, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si le bit est désactivé, RectData contient un objet EmfPlusRectF (section 2.2.2.39).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si flottant ; sinon, `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner l'arc. La valeur DOIT être comprise entre 0 et 63, inclusivement.

**Returns:**
byte - L'identifiant de l'objet.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner l'arc. La valeur DOIT être comprise entre 0 et 63, inclusivement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | L'identifiant de l'objet. |

### getSize() {#getSize--}
```
public int getSize()
```


Obtient la taille. Un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits de l'intégralité de l'enregistrement, y compris l'en-tête de 12 octets et les données spécifiques à l'enregistrement. Pour ce type d'enregistrement, la valeur DOIT être l'une des suivantes : 0x0000001C si le bit C est activé dans le champ Flags. 0x00000024 si le bit C est désactivé dans le champ Flags.

**Returns:**
int - La taille.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Définit la taille. Un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits de l'intégralité de l'enregistrement, y compris l'en-tête de 12 octets et les données spécifiques à l'enregistrement. Pour ce type d'enregistrement, la valeur DOIT être l'une des suivantes : 0x0000001C si le bit C est activé dans le champ Flags. 0x00000024 si le bit C est désactivé dans le champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La taille. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtient l'angle de départ. Une valeur flottante non négative de 32 bits qui spécifie l'angle entre l'axe x et le point de départ de l'arc. Toute valeur est acceptable, mais elle DOIT être interprétée modulo 360, le résultat utilisé devant être compris entre 0,0 inclus et 360,0 exclus.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Définit l'angle de départ. Une valeur flottante non négative de 32 bits qui spécifie l'angle entre l'axe x et le point de départ de l'arc. Toute valeur est acceptable, mais elle DOIT être interprétée modulo 360, le résultat utilisé devant être compris entre 0,0 inclus et 360,0 exclus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtient l'angle d'extension. Une valeur flottante de 32 bits qui spécifie l'étendue de l'arc à dessiner, en tant qu'angle en degrés mesuré depuis le point de départ défini par la valeur StartAngle. Toute valeur est acceptable, mais elle DOIT être limitée à -360,0 à 360,0 inclus. Une valeur positive indique que l'extension est définie dans le sens horaire, et une valeur négative indique qu'elle est définie dans le sens antihoraire.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Définit l'angle d'extension. Une valeur flottante de 32 bits qui spécifie l'étendue de l'arc à dessiner, en tant qu'angle en degrés mesuré depuis le point de départ défini par la valeur StartAngle. Toute valeur est acceptable, mais elle DOIT être limitée à -360,0 à 360,0 inclus. Une valeur positive indique que l'extension est définie dans le sens horaire, et une valeur négative indique qu'elle est définie dans le sens antihoraire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Obtient les données du rectangle. Soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'ellipse colinéaire à l'arc. Ce rectangle définit la position, la taille et la forme de l'arc. Le type d'objet dans ce champ est spécifié par la valeur du champ Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Définit les données du rectangle. Soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'ellipse colinéaire à l'arc. Ce rectangle définit la position, la taille et la forme de l'arc. Le type d'objet dans ce champ est spécifié par la valeur du champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

