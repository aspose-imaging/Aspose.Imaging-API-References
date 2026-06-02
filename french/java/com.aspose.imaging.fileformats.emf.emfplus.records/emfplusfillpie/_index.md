---
title: "EmfPlusFillPie"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusFillPie spécifie le remplissage d'une section de l'intérieur d'une ellipse"
type: docs
weight: 35
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusFillPie spécifie le remplissage d'une section de l'intérieur d'une ellipse
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusFillPie`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si le PointData est compressé. |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [getStartAngle()](#getStartAngle--) | Obtient ou définit l'angle de départ Un nombre à virgule flottante de 32 bits, non négatif, qui spécifie l'angle entre l'axe des x et le point de départ du secteur de tarte. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtient ou définit l'angle de départ Un nombre à virgule flottante de 32 bits, non négatif, qui spécifie l'angle entre l'axe des x et le point de départ du secteur de tarte. |
| [getSweepAngle()](#getSweepAngle--) | Obtient ou définit l'angle d'arc Un nombre à virgule flottante de 32 bits qui spécifie l'étendue de l'arc définissant le secteur de tarte à dessiner, exprimé en degrés mesurés à partir du point de départ défini par la valeur StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtient ou définit l'angle d'arc Un nombre à virgule flottante de 32 bits qui spécifie l'étendue de l'arc définissant le secteur de tarte à dessiner, exprimé en degrés mesurés à partir du point de départ défini par la valeur StartAngle. |
| [getRectData()](#getRectData--) | Obtient ou définit les données du rectangle Soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse contenant le secteur de tarte. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtient ou définit les données du rectangle Soit un objet EmfPlusRect soit EmfPlusRectF qui définit la boîte englobante de l'ellipse contenant le secteur de tarte. |
| [getBrushId()](#getBrushId--) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusFillPie`.

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

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtient ou définit une valeur indiquant si cette instance est en couleur. Si définie, BrushId spécifie une couleur sous forme d’un objet EmfPlusARGB (section 2.2.2.1). Si non définie, BrushId contient l’index d’un objet EmfPlusBrush (section 2.2.1.1) dans la table d’objets EMF+.

Valeur : `true` si cette instance est en couleur ; sinon, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est en couleur. Si définie, BrushId spécifie une couleur sous forme d’un objet EmfPlusARGB (section 2.2.2.1). Si non définie, BrushId contient l’index d’un objet EmfPlusBrush (section 2.2.1.1) dans la table d’objets EMF+.

Valeur : `true` si cette instance est en couleur ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

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

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

