---
title: "EmfPlusDrawDriverString"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawDriverString spécifie la sortie de texte avec les positions des caractères."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawDriverString spécifie la sortie de texte avec les positions des caractères.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawDriverString`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtient l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Définit l'identifiant de l'objet. |
| [getBrushId()](#getBrushId--) | Obtient l'identifiant du pinceau Un entier non signé de 32 bits qui spécifie soit la couleur de premier plan du texte, soit un pinceau graphique, selon la valeur du drapeau S dans Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Définit l'identifiant du pinceau Un entier non signé de 32 bits qui spécifie soit la couleur de premier plan du texte, soit un pinceau graphique, selon la valeur du drapeau S dans les Flags. |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Obtient les indicateurs d'options de chaîne du pilote Un entier non signé de 32 bits qui spécifie l'espacement, l'orientation et la qualité du rendu de la chaîne. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Définit les indicateurs d'options de chaîne du pilote Un entier non signé de 32 bits qui spécifie l'espacement, l'orientation et la qualité du rendu de la chaîne. |
| [getGlyphCount()](#getGlyphCount--) | Obtient le nombre de glyphes Un entier non signé de 32 bits qui spécifie le nombre de glyphes dans la chaîne. |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Définit le nombre de glyphes Un entier non signé de 32 bits qui spécifie le nombre de glyphes dans la chaîne. |
| [getGlyphPos()](#getGlyphPos--) | Obtient le tableau des positions des glyphes Un tableau d'objets EmfPlusPointF (section 2.2.2.36) qui spécifient la position de sortie de chaque glyphe de caractère. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Définit le tableau des positions des glyphes Un tableau d'objets EmfPlusPointF (section 2.2.2.36) qui spécifient la position de sortie de chaque glyphe de caractère. |
| [getGlyphs()](#getGlyphs--) | Obtient le tableau des glyphes Un tableau de valeurs de 16 bits qui définissent la chaîne de texte à dessiner. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Définit le tableau des glyphes Un tableau de valeurs de 16 bits qui définissent la chaîne de texte à dessiner. |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Définit une valeur indiquant si cette instance est en couleur. |
| [getMatrixPresent()](#getMatrixPresent--) | Obtient le drapeau de présence de matrice Un entier non signé de 32 bits qui indique si une matrice de transformation est présente dans le champ TransformMatrix 0 - aucune matrice présente. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Définit le drapeau de présence de matrice Un entier non signé de 32 bits qui indique si une matrice de transformation est présente dans le champ TransformMatrix 0 - aucune matrice présente. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient la matrice de transformation Un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie la transformation à appliquer à chaque valeur du tableau de texte. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Définit la matrice de transformation Un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie la transformation à appliquer à chaque valeur du tableau de texte. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawDriverString`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient l'identifiant de l'objet. L'index de la table d'objets EMF+ d'un `` objet (section 2.2.1.3) pour rendre le texte. La valeur DOIT être comprise entre 0 et 63, inclus.

**Returns:**
byte - L'identifiant de l'objet.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Définit l'identifiant de l'objet. L'index de la table d'objets EMF+ d'un `` objet (section 2.2.1.3) pour rendre le texte. La valeur DOIT être comprise entre 0 et 63, inclus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | L'identifiant de l'objet. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtient l'identifiant du pinceau Un entier non signé de 32 bits qui spécifie soit la couleur de premier plan du texte, soit un pinceau graphique, selon la valeur du drapeau S dans Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Définit l'identifiant du pinceau Un entier non signé de 32 bits qui spécifie soit la couleur de premier plan du texte, soit un pinceau graphique, selon la valeur du drapeau S dans les Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Obtient les indicateurs d'options de chaîne du pilote Un entier non signé de 32 bits qui spécifie l'espacement, l'orientation et la qualité du rendu de la chaîne.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Définit les indicateurs d'options de chaîne du pilote Un entier non signé de 32 bits qui spécifie l'espacement, l'orientation et la qualité du rendu de la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Obtient le nombre de glyphes Un entier non signé de 32 bits qui spécifie le nombre de glyphes dans la chaîne.

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Définit le nombre de glyphes Un entier non signé de 32 bits qui spécifie le nombre de glyphes dans la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Obtient le tableau des positions des glyphes Un tableau d'objets EmfPlusPointF (section 2.2.2.36) qui spécifient la position de sortie de chaque glyphe de caractère. Il DOIT y avoir GlyphCount éléments, qui ont une correspondance un à un avec les éléments du tableau Glyphs. Les positions des glyphes sont calculées à partir de la position du premier glyphe si le drapeau DriverStringOptionsRealizedAdvance dans les indicateurs DriverStringOptions est activé. Dans ce cas, GlyphPos spécifie uniquement la position du premier glyphe.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Définit le tableau des positions des glyphes Un tableau d'objets EmfPlusPointF (section 2.2.2.36) qui spécifient la position de sortie de chaque glyphe de caractère. Il DOIT y avoir GlyphCount éléments, qui ont une correspondance un à un avec les éléments du tableau Glyphs. Les positions des glyphes sont calculées à partir de la position du premier glyphe si le drapeau DriverStringOptionsRealizedAdvance dans les indicateurs DriverStringOptions est activé. Dans ce cas, GlyphPos spécifie uniquement la position du premier glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Obtient le tableau des glyphes Un tableau de valeurs de 16 bits qui définissent la chaîne de texte à dessiner. Si le drapeau DriverStringOptionsCmapLookup dans le champ DriverStringOptionsFlags est activé, chaque valeur de ce tableau spécifie un caractère Unicode. Sinon, chaque valeur spécifie un index vers un glyphe de caractère dans l'objet EmfPlusFont spécifié par la valeur ObjectId dans le champ Flags.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Définit le tableau des glyphes Un tableau de valeurs de 16 bits qui définissent la chaîne de texte à dessiner. Si le drapeau DriverStringOptionsCmapLookup dans le champ DriverStringOptionsFlags est activé, chaque valeur de ce tableau spécifie un caractère Unicode. Sinon, chaque valeur spécifie un index vers un glyphe de caractère dans l'objet EmfPlusFont spécifié par la valeur ObjectId dans le champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtient ou définit une valeur indiquant si cette instance est en couleur. Ce bit indique le type de données dans le champ BrushId. S'il est activé, BrushId spécifie la valeur de couleur dans un objet EmfPlusARGB (section 2.2.2.1). S'il est désactivé, BrushId contient l'index de la table d'objets EMF+ d'un objet EmfPlusBrush (section 2.2.1.1).

**Returns:**
boolean - `true` si cette instance est en couleur ; sinon, `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Définit une valeur indiquant si cette instance est en couleur. Ce bit indique le type de données dans le champ BrushId. S'il est activé, BrushId spécifie la valeur de couleur dans un objet EmfPlusARGB (section 2.2.2.1). S'il est désactivé, BrushId contient l'index de la table d'objets EMF+ d'un objet EmfPlusBrush (section 2.2.1.1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si cette instance est en couleur ; sinon, `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


Obtient le drapeau indiquant la présence de la matrice Un entier non signé de 32 bits qui spécifie si une matrice de transformation est présente dans le champ TransformMatrix 0 - aucune matrice présente. 1 - la matrice de transformation est dans le champ TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


Définit le drapeau indiquant la présence de la matrice Un entier non signé de 32 bits qui spécifie si une matrice de transformation est présente dans le champ TransformMatrix 0 - aucune matrice présente. 1 - la matrice de transformation est dans le champ TransformMatrix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtient la matrice de transformation Un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie la transformation à appliquer à chaque valeur du tableau de texte. La présence de ces données est déterminée à partir du champ MatrixPresent.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Définit la matrice de transformation Un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie la transformation à appliquer à chaque valeur du tableau de texte. La présence de ces données est déterminée à partir du champ MatrixPresent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

