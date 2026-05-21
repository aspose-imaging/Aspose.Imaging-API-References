---
title: "EmfPlusFillPath"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Enregistrement Fill path FLAGS entier non signé de 16 bits qui fournit des informations sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement."
type: docs
weight: 34
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Enregistrement Fill path FLAGS : entier non signé de 16 bits qui fournit des informations sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 bit) : ce bit indique le type de données dans le champ BrushId. Si le bit est défini, BrushId spécifie une couleur sous forme d'objet EmfPlusARGB (section 2.2.2.1). Si le bit est désactivé, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1) dans la table d'objets EMF+. X (1 bit) : réservé et DOIT être ignoré. ObjectId (1 octet) : l'index de l'objet EmfPlusPath (section 2.2.1.6) à remplir, dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusFillPath`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getBrushId()](#getBrushId--) | Obtient ou définit le Brush ID Un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit le Brush ID Un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusFillPath`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'index de l'objet EmfPlusPath (section 2.2.1.6) à remplir, dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index de l'objet EmfPlusPath (section 2.2.1.6) à remplir, dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtient ou définit le Brush ID Un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtient ou définit le Brush ID Un entier non signé de 32 bits qui définit le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

