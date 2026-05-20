---
title: "EmfPlusFillEllipse"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusFillEllipse spécifie le remplissage de l'intérieur d'une ellipse"
type: docs
weight: 33
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusFillEllipse spécifie le remplissage de l'intérieur d'une ellipse
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusFillEllipse`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [isCompressed()](#isCompressed--) | Obtient ou définit une valeur indiquant si cette instance est compressée. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si cette instance est compressée. |
| [getBrushId()](#getBrushId--) | Obtient ou définit l’identifiant du pinceau, un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit l’identifiant du pinceau, un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [getRectData()](#getRectData--) | Obtient ou définit les données du rectangle : soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'ellipse. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtient ou définit les données du rectangle : soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'ellipse. |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusFillEllipse`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

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

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Obtient ou définit une valeur indiquant si cette instance est compressée. Si le bit est défini, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si le bit est dégagé, RectData contient un objet EmfPlusRectF (section 2.2.2.39).

Valeur : `true` si cette instance est compressée ; sinon, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est compressée. Si le bit est défini, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si le bit est dégagé, RectData contient un objet EmfPlusRectF (section 2.2.2.39).

Valeur : `true` si cette instance est compressée ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtient ou définit l'identifiant du pinceau : un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. Cette définition est utilisée pour remplir l'intérieur de l'ellipse.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtient ou définit l'identifiant du pinceau : un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. Cette définition est utilisée pour remplir l'intérieur de l'ellipse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Obtient ou définit les données du rectangle : soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'ellipse.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Obtient ou définit les données du rectangle : soit un objet EmfPlusRect, soit un objet EmfPlusRectF qui définit la boîte englobante de l'ellipse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

