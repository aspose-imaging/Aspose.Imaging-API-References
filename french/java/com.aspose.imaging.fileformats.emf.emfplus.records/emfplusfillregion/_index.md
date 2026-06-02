---
title: "EmfPlusFillRegion"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusFillRegion spécifie le remplissage de l'intérieur d'une région graphique"
type: docs
weight: 38
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRegion extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusFillRegion spécifie le remplissage de l'intérieur d'une région graphique
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFillRegion(EmfPlusRecord source)](#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusFillRegion`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [getBrushId()](#getBrushId--) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit l'identifiant du pinceau, un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
### EmfPlusFillRegion(EmfPlusRecord source) {#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRegion(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusFillRegion`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'index de l'objet EmfPlusRegion (section 2.2.1.8) à remplir, dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index de l'objet EmfPlusRegion (section 2.2.1.8) à remplir, dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

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

