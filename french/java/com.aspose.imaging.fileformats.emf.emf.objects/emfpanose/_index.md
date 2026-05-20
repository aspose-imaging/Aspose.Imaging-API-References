---
title: "EmfPanose"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet Panose décrit les valeurs de classification PANOSE d'une police TrueType."
type: docs
weight: 30
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPanose extends EmfObject
```

L'objet Panose décrit les valeurs de classification PANOSE d'une police TrueType. Ces caractéristiques sont utilisées pour associer la police à d'autres polices d'apparence similaire mais de noms différents.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPanose()](#EmfPanose--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFamilyType()](#getFamilyType--) | Obtient ou définit un entier non signé de 8 bits qui spécifie le type de famille. |
| [setFamilyType(byte value)](#setFamilyType-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie le type de famille. |
| [getSerifStyle()](#getSerifStyle--) | Obtient ou définit un entier non signé de 8 bits qui spécifie le style sérif. |
| [setSerifStyle(byte value)](#setSerifStyle-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie le style sérif. |
| [getWeight()](#getWeight--) | Obtient ou définit un entier non signé de 8 bits qui spécifie le poids de la police. |
| [setWeight(byte value)](#setWeight-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie le poids de la police. |
| [getProportion()](#getProportion--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la proportion de la police. |
| [setProportion(byte value)](#setProportion-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la proportion de la police. |
| [getContrast()](#getContrast--) | Obtient ou définit un entier non signé de 8 bits qui spécifie le contraste de la police. |
| [setContrast(byte value)](#setContrast-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie le contraste de la police. |
| [getStrokeVariation()](#getStrokeVariation--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la variation du trait pour la police. |
| [setStrokeVariation(byte value)](#setStrokeVariation-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la variation du trait pour la police. |
| [getArmStyle()](#getArmStyle--) | Obtient ou définit un entier non signé de 8 bits qui spécifie le style du bras de la police. |
| [setArmStyle(byte value)](#setArmStyle-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie le style du bras de la police. |
| [getLetterform()](#getLetterform--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la forme des lettres de la police. |
| [setLetterform(byte value)](#setLetterform-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la forme des lettres de la police. |
| [getMidline()](#getMidline--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la ligne médiane de la police. |
| [setMidline(byte value)](#setMidline-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la ligne médiane de la police. |
| [getXHeight()](#getXHeight--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la hauteur x de la police. |
| [setXHeight(byte value)](#setXHeight-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la hauteur x de la police. |
### EmfPanose() {#EmfPanose--}
```
public EmfPanose()
```


### getFamilyType() {#getFamilyType--}
```
public byte getFamilyType()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le type de famille. La valeur DOIT être dans la table d'énumération FamilyType (section 2.1.12).

**Returns:**
byte
### setFamilyType(byte value) {#setFamilyType-byte-}
```
public void setFamilyType(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le type de famille. La valeur DOIT être dans la table d'énumération FamilyType (section 2.1.12).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getSerifStyle() {#getSerifStyle--}
```
public byte getSerifStyle()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le style sérif. La valeur DOIT être dans la table d'énumération SerifType (section 2.1.30).

**Returns:**
byte
### setSerifStyle(byte value) {#setSerifStyle-byte-}
```
public void setSerifStyle(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le style sérif. La valeur DOIT être dans la table d'énumération SerifType (section 2.1.30).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getWeight() {#getWeight--}
```
public byte getWeight()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le poids de la police. La valeur DOIT être dans la table d'énumération Weight (section 2.1.34).

**Returns:**
byte
### setWeight(byte value) {#setWeight-byte-}
```
public void setWeight(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le poids de la police. La valeur DOIT être dans la table d'énumération Weight (section 2.1.34).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getProportion() {#getProportion--}
```
public byte getProportion()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la proportion de la police. La valeur DOIT être dans la table d'énumération Proportion (section 2.1.28).

**Returns:**
byte
### setProportion(byte value) {#setProportion-byte-}
```
public void setProportion(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la proportion de la police. La valeur DOIT être dans la table d'énumération Proportion (section 2.1.28).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getContrast() {#getContrast--}
```
public byte getContrast()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le contraste de la police. La valeur DOIT être dans la table d'énumération Contrast (section 2.1.8).

**Returns:**
byte
### setContrast(byte value) {#setContrast-byte-}
```
public void setContrast(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le contraste de la police. La valeur DOIT être dans la table d'énumération Contrast (section 2.1.8).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getStrokeVariation() {#getStrokeVariation--}
```
public byte getStrokeVariation()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la variation du trait pour la police. La valeur DOIT être dans la table d'énumération StrokeVariation (section 2.1.33).

**Returns:**
byte
### setStrokeVariation(byte value) {#setStrokeVariation-byte-}
```
public void setStrokeVariation(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la variation du trait pour la police. La valeur DOIT être dans la table d'énumération StrokeVariation (section 2.1.33).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getArmStyle() {#getArmStyle--}
```
public byte getArmStyle()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le style du bras de la police. La valeur DOIT être dans la table d'énumération ArmStyle (section 2.1.3).

**Returns:**
byte
### setArmStyle(byte value) {#setArmStyle-byte-}
```
public void setArmStyle(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le style du bras de la police. La valeur DOIT être dans la table d'énumération ArmStyle (section 2.1.3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getLetterform() {#getLetterform--}
```
public byte getLetterform()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la forme des lettres de la police. La valeur DOIT être dans la table d'énumération Letterform (section 2.1.20)

**Returns:**
byte
### setLetterform(byte value) {#setLetterform-byte-}
```
public void setLetterform(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la forme des lettres de la police. La valeur DOIT être dans la table d'énumération Letterform (section 2.1.20)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getMidline() {#getMidline--}
```
public byte getMidline()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la ligne médiane de la police. La valeur DOIT être dans la table d'énumération MidLine (section 2.1.23).

**Returns:**
byte
### setMidline(byte value) {#setMidline-byte-}
```
public void setMidline(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la ligne médiane de la police. La valeur DOIT être dans la table d'énumération MidLine (section 2.1.23).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getXHeight() {#getXHeight--}
```
public byte getXHeight()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la hauteur x de la police. La valeur DOIT être dans la table d'énumération XHeight (section 2.1.35).

**Returns:**
byte
### setXHeight(byte value) {#setXHeight-byte-}
```
public void setXHeight(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la hauteur x de la police. La valeur DOIT être dans la table d'énumération XHeight (section 2.1.35).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

