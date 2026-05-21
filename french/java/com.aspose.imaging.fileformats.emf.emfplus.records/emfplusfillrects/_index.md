---
title: "EmfPlusFillRects"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusFillRects spécifie le remplissage des intérieurs d'une série de rectangles"
type: docs
weight: 37
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusFillRects spécifie le remplissage des intérieurs d'une série de rectangles
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusFillRects`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [getCompressed()](#getCompressed--) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillRects` est compressé. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtient ou définit une valeur indiquant si ce `EmfPlusFillRects` est compressé. |
| [getBrushId()](#getBrushId--) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [getRectData()](#getRectData--) | Obtient ou définit les données du rectangle. Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Obtient ou définit les données du rectangle. Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusFillRects`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtient ou définit une valeur indiquant si cette instance est colorée. Si elle est définie, BrushId spécifie une couleur sous forme d'objet EmfPlusARGB (section 2.2.2.1). Si elle est désactivée, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1) dans la table d'objets EMF+.

Valeur : `true` si cette instance est en couleur ; sinon, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est colorée. Si elle est définie, BrushId spécifie une couleur sous forme d'objet EmfPlusARGB (section 2.2.2.1). Si elle est désactivée, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1) dans la table d'objets EMF+.

Valeur : `true` si cette instance est en couleur ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillRects` est compressé. Si le bit est activé, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si le bit est désactivé, RectData contient un objet EmfPlusRectF (section 2.2.2.39) object

Valeur : `true` si compressé ; sinon, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtient ou définit une valeur indiquant si ce `EmfPlusFillRects` est compressé. Si le bit est activé, RectData contient un objet EmfPlusRect (section 2.2.2.38). Si le bit est désactivé, RectData contient un objet EmfPlusRectF (section 2.2.2.39) object

Valeur : `true` si compressé ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

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

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Obtient ou définit les données du rectangle. Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Obtient ou définit les données du rectangle. Un tableau d'objets EmfPlusRect ou EmfPlusRectF d'une longueur Count qui définit les données du rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

