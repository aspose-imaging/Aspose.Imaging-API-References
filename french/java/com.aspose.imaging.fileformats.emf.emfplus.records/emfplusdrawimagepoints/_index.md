---
title: "EmfPlusDrawImagePoints"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawImagePoints spécifie le dessin d'une image mise à l'échelle à l'intérieur d'un parallélogramme."
type: docs
weight: 23
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawImagePoints spécifie le dessin d'une image mise à l'échelle à l'intérieur d'un parallélogramme.

Un EmfPlusImage peut spécifier soit un bitmap, soit un métafichier. Les couleurs d'une image peuvent être manipulées lors du rendu. Elles peuvent être corrigées, assombries, éclaircies et supprimées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawImagePoints`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Obtient ou définit une valeur indiquant si [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Obtient ou définit une valeur indiquant si [applying an effect]. |
| [getRelative()](#getRelative--) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawImagePoints` est relatif. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusDrawImagePoints` est relatif. |
| [getImageAttributesId()](#getImageAttributesId--) | Obtient ou définit un entier non signé de 32 bits qui contient l'index de l'objet optionnel EmfPlusImageAttributes (section 2.2.1.5) dans la table d'objets EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Obtient ou définit un entier non signé de 32 bits qui contient l'index de l'objet optionnel EmfPlusImageAttributes (section 2.2.1.5) dans la table d'objets EMF+. |
| [getSrcUnit()](#getSrcUnit--) | Obtient ou définit un entier signé de 32 bits qui définit les unités du champ SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Obtient ou définit un entier signé de 32 bits qui définit les unités du champ SrcRect. |
| [getSrcRect()](#getSrcRect--) | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit une partie de l'image à rendre. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit une partie de l'image à rendre. |
| [getPointData()](#getPointData--) | Obtient ou définit un tableau de points Count qui spécifient trois points d'un parallélogramme. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtient ou définit un tableau de points Count qui spécifient trois points d'un parallélogramme. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawImagePoints`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtient ou définit une valeur indiquant si le PointData est compressé. Ce bit indique si le champ PointData spécifie des données compressées. S'il est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. S'il est désactivé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits. Remarque : si le drapeau P (ci‑dessus) est défini, ce drapeau est indéfini et DOIT être ignoré.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si le PointData est compressé. Ce bit indique si le champ PointData spécifie des données compressées. S'il est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. S'il est désactivé, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits. Remarque : si le drapeau P (ci‑dessus) est défini, ce drapeau est indéfini et DOIT être ignoré.

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

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Obtient ou définit une valeur indiquant si [applying an effect]. Ce bit indique que le rendu de l'image comprend l'application d'un effet. Si le bit est défini, un objet de la classe Effect DOIT avoir été spécifié dans un enregistrement EmfPlusSerializableObject antérieur (section 2.3.5.2).

Valeur : `true` si [applying an effect] ; sinon, `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Obtient ou définit une valeur indiquant si [applying an effect]. Ce bit indique que le rendu de l'image comprend l'application d'un effet. Si le bit est défini, un objet de la classe Effect DOIT avoir été spécifié dans un enregistrement EmfPlusSerializableObject antérieur (section 2.3.5.2).

Valeur : `true` si [applying an effect] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusDrawImagePoints` est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. Si le bit est défini, chaque élément de PointData indique une position dans l'espace de coordonnées relative à la position spécifiée par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose une position précédente aux coordonnées (0,0). Si le bit est dégagé, PointData indique des positions absolues selon le drapeau C. Remarque : si ce drapeau est défini, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré.

Valeur : `true` si relatif ; sinon, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusDrawImagePoints` est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. Si le bit est défini, chaque élément de PointData indique une position dans l'espace de coordonnées relative à la position spécifiée par l'élément précédent du tableau. Dans le cas du premier élément de PointData, on suppose une position précédente aux coordonnées (0,0). Si le bit est dégagé, PointData indique des positions absolues selon le drapeau C. Remarque : si ce drapeau est défini, le drapeau C (ci‑dessus) est indéfini et DOIT être ignoré.

Valeur : `true` si relatif ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Obtient ou définit un entier non signé de 32 bits qui contient l'index de l'objet optionnel EmfPlusImageAttributes (section 2.2.1.5) dans la table d'objets EMF+.

Valeur : l'identifiant des attributs d'image.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Obtient ou définit un entier non signé de 32 bits qui contient l'index de l'objet optionnel EmfPlusImageAttributes (section 2.2.1.5) dans la table d'objets EMF+.

Valeur : l'identifiant des attributs d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Obtient ou définit un entier signé de 32 bits qui définit les unités du champ SrcRect. Il DOIT être la valeur UnitPixel de l'énumération UnitType (section 2.1.1.33).

Valeur : l'unité source.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Obtient ou définit un entier signé de 32 bits qui définit les unités du champ SrcRect. Il DOIT être la valeur UnitPixel de l'énumération UnitType (section 2.1.1.33).

Valeur : l'unité source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit une partie de l'image à rendre.

Valeur : le rectangle source.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit une partie de l'image à rendre.

Valeur : le rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtient ou définit un tableau de Count points qui spécifient trois points d'un parallélogramme. Les trois points représentent les coins supérieur gauche, supérieur droit et inférieur gauche du parallélogramme. Le quatrième point du parallélogramme est extrapolé à partir des trois premiers. La partie de l'image spécifiée par le champ SrcRect DOIT faire l'objet de transformations d'échelle et de cisaillement si nécessaire pour s'adapter à l'intérieur du parallélogramme.

Valeur : les données de point.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtient ou définit un tableau de Count points qui spécifient trois points d'un parallélogramme. Les trois points représentent les coins supérieur gauche, supérieur droit et inférieur gauche du parallélogramme. Le quatrième point du parallélogramme est extrapolé à partir des trois premiers. La partie de l'image spécifiée par le champ SrcRect DOIT faire l'objet de transformations d'échelle et de cisaillement si nécessaire pour s'adapter à l'intérieur du parallélogramme.

Valeur : les données de point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

