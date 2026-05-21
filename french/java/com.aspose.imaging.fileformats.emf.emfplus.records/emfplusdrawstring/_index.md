---
title: "EmfPlusDrawString"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawString spécifie la sortie de texte avec le formatage de chaîne"
type: docs
weight: 28
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawString spécifie la sortie de texte avec le formatage de chaîne
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawString`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isColor()](#isColor--) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [setColor(boolean value)](#setColor-boolean-) | Obtient ou définit une valeur indiquant si cette instance est en couleur. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getBrushId()](#getBrushId--) | Obtient ou définit l’identifiant du pinceau, un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtient ou définit l’identifiant du pinceau, un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. |
| [getFormatId()](#getFormatId--) | Obtient ou définit l’identifiant du format, un entier non signé de 32 bits qui spécifie l’index d’un objet optionnel EmfPlusStringFormat (section 2.2.1.9) dans la table d’objets EMF+. |
| [setFormatId(int value)](#setFormatId-int-) | Obtient ou définit l’identifiant du format, un entier non signé de 32 bits qui spécifie l’index d’un objet optionnel EmfPlusStringFormat (section 2.2.1.9) dans la table d’objets EMF+. |
| [getLength()](#getLength--) | Obtient ou définit la longueur, un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne. |
| [setLength(int value)](#setLength-int-) | Obtient ou définit la longueur, un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne. |
| [getLayoutRect()](#getLayoutRect--) | Obtient ou définit le rectangle de mise en page, un objet EmfPlusRectF (section 2.2.2.39) qui définit la zone de délimitation de la destination qui recevra la chaîne. |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Obtient ou définit le rectangle de mise en page, un objet EmfPlusRectF (section 2.2.2.39) qui définit la zone de délimitation de la destination qui recevra la chaîne. |
| [getStringData()](#getStringData--) | Obtient ou définit les données de la chaîne, un tableau de caractères Unicode de 16 bits qui spécifie la chaîne à dessiner. |
| [setStringData(String value)](#setStringData-java.lang.String-) | Obtient ou définit les données de la chaîne, un tableau de caractères Unicode de 16 bits qui spécifie la chaîne à dessiner. |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawString`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l’identifiant de l’objet. L’index d’un objet EmfPlusFont (section 2.2.1.3) dans la table d’objets EMF+ pour rendre le texte. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l’identifiant de l’objet. L’index d’un objet EmfPlusFont (section 2.2.1.3) dans la table d’objets EMF+ pour rendre le texte. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtient ou définit l’identifiant du pinceau, un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. Cette définition est utilisée pour peindre la couleur du texte au premier plan ; c’est‑à‑dire, uniquement les glyphes eux‑mêmes.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtient ou définit l’identifiant du pinceau, un entier non signé de 32 bits qui spécifie le pinceau, dont le contenu est déterminé par le bit S dans le champ Flags. Cette définition est utilisée pour peindre la couleur du texte au premier plan ; c’est‑à‑dire, uniquement les glyphes eux‑mêmes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Obtient ou définit l’identifiant du format, un entier non signé de 32 bits qui spécifie l’index d’un objet optionnel EmfPlusStringFormat (section 2.2.1.9) dans la table d’objets EMF+. Cet objet spécifie les informations de mise en page du texte et les manipulations d’affichage à appliquer à une chaîne.

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Obtient ou définit l’identifiant du format, un entier non signé de 32 bits qui spécifie l’index d’un objet optionnel EmfPlusStringFormat (section 2.2.1.9) dans la table d’objets EMF+. Cet objet spécifie les informations de mise en page du texte et les manipulations d’affichage à appliquer à une chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Obtient ou définit la longueur, un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Obtient ou définit la longueur, un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Obtient ou définit le rectangle de mise en page, un objet EmfPlusRectF (section 2.2.2.39) qui définit la zone de délimitation de la destination qui recevra la chaîne.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Obtient ou définit le rectangle de mise en page, un objet EmfPlusRectF (section 2.2.2.39) qui définit la zone de délimitation de la destination qui recevra la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Obtient ou définit les données de la chaîne, un tableau de caractères Unicode de 16 bits qui spécifie la chaîne à dessiner.

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Obtient ou définit les données de la chaîne, un tableau de caractères Unicode de 16 bits qui spécifie la chaîne à dessiner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

