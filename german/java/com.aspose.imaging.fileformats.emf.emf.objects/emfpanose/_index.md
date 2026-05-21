---
title: "EmfPanose"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Panose‑Objekt beschreibt die PANOSE‑Schriftklassifizierungswerte für eine TrueType‑Schrift."
type: docs
weight: 30
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPanose extends EmfObject
```

Das Panose‑Objekt beschreibt die PANOSE‑Schriftklassifizierungswerte für eine TrueType‑Schrift. Diese Merkmale werden verwendet, um die Schrift mit anderen Schriften ähnlichen Aussehens, aber unterschiedlicher Namen zu verknüpfen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPanose()](#EmfPanose--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFamilyType()](#getFamilyType--) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die den Familientyp angibt. |
| [setFamilyType(byte value)](#setFamilyType-byte-) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die den Familientyp angibt. |
| [getSerifStyle()](#getSerifStyle--) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die den Serif‑Stil angibt. |
| [setSerifStyle(byte value)](#setSerifStyle-byte-) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die den Serif‑Stil angibt. |
| [getWeight()](#getWeight--) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die das Gewicht der Schriftart angibt. |
| [setWeight(byte value)](#setWeight-byte-) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die das Gewicht der Schriftart angibt. |
| [getProportion()](#getProportion--) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die das Verhältnis der Schriftart angibt. |
| [setProportion(byte value)](#setProportion-byte-) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die das Verhältnis der Schriftart angibt. |
| [getContrast()](#getContrast--) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die den Kontrast der Schriftart angibt. |
| [setContrast(byte value)](#setContrast-byte-) | Liest oder setzt eine 8‑Bit‑Ganzzahl ohne Vorzeichen, die den Kontrast der Schriftart angibt. |
| [getStrokeVariation()](#getStrokeVariation--) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Strichvariation für die Schriftart angibt. |
| [setStrokeVariation(byte value)](#setStrokeVariation-byte-) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Strichvariation für die Schriftart angibt. |
| [getArmStyle()](#getArmStyle--) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Armstil der Schriftart angibt. |
| [setArmStyle(byte value)](#setArmStyle-byte-) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Armstil der Schriftart angibt. |
| [getLetterform()](#getLetterform--) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Buchstabenform der Schriftart angibt. |
| [setLetterform(byte value)](#setLetterform-byte-) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Buchstabenform der Schriftart angibt. |
| [getMidline()](#getMidline--) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Mittelachse der Schriftart angibt. |
| [setMidline(byte value)](#setMidline-byte-) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Mittelachse der Schriftart angibt. |
| [getXHeight()](#getXHeight--) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die x‑Höhe der Schriftart angibt. |
| [setXHeight(byte value)](#setXHeight-byte-) | Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die x‑Höhe der Schriftart angibt. |
### EmfPanose() {#EmfPanose--}
```
public EmfPanose()
```


### getFamilyType() {#getFamilyType--}
```
public byte getFamilyType()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Familientyp angibt. Der Wert MUSS in der FamilyType‑Aufzählungstabelle (Abschnitt 2.1.12) enthalten sein.

**Returns:**
byte
### setFamilyType(byte value) {#setFamilyType-byte-}
```
public void setFamilyType(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Familientyp angibt. Der Wert MUSS in der FamilyType‑Aufzählungstabelle (Abschnitt 2.1.12) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getSerifStyle() {#getSerifStyle--}
```
public byte getSerifStyle()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Serifstil angibt. Der Wert MUSS in der SerifType‑Aufzählungstabelle (Abschnitt 2.1.30) enthalten sein.

**Returns:**
byte
### setSerifStyle(byte value) {#setSerifStyle-byte-}
```
public void setSerifStyle(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Serifstil angibt. Der Wert MUSS in der SerifType‑Aufzählungstabelle (Abschnitt 2.1.30) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getWeight() {#getWeight--}
```
public byte getWeight()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Gewichtung der Schriftart angibt. Der Wert MUSS in der Weight‑Aufzählungstabelle (Abschnitt 2.1.34) enthalten sein.

**Returns:**
byte
### setWeight(byte value) {#setWeight-byte-}
```
public void setWeight(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Gewichtung der Schriftart angibt. Der Wert MUSS in der Weight‑Aufzählungstabelle (Abschnitt 2.1.34) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getProportion() {#getProportion--}
```
public byte getProportion()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Proportion der Schriftart angibt. Der Wert MUSS in der Proportion‑Aufzählungstabelle (Abschnitt 2.1.28) enthalten sein.

**Returns:**
byte
### setProportion(byte value) {#setProportion-byte-}
```
public void setProportion(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Proportion der Schriftart angibt. Der Wert MUSS in der Proportion‑Aufzählungstabelle (Abschnitt 2.1.28) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getContrast() {#getContrast--}
```
public byte getContrast()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Kontrast der Schriftart angibt. Der Wert MUSS in der Contrast‑Aufzählungstabelle (Abschnitt 2.1.8) enthalten sein.

**Returns:**
byte
### setContrast(byte value) {#setContrast-byte-}
```
public void setContrast(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Kontrast der Schriftart angibt. Der Wert MUSS in der Contrast‑Aufzählungstabelle (Abschnitt 2.1.8) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getStrokeVariation() {#getStrokeVariation--}
```
public byte getStrokeVariation()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Strichvariation für die Schriftart angibt. Der Wert MUSS in der StrokeVariation‑Aufzählungstabelle (Abschnitt 2.1.33) enthalten sein.

**Returns:**
byte
### setStrokeVariation(byte value) {#setStrokeVariation-byte-}
```
public void setStrokeVariation(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Strichvariation für die Schriftart angibt. Der Wert MUSS in der StrokeVariation‑Aufzählungstabelle (Abschnitt 2.1.33) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getArmStyle() {#getArmStyle--}
```
public byte getArmStyle()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Armstil der Schriftart angibt. Der Wert MUSS in der ArmStyle‑Aufzählungstabelle (Abschnitt 2.1.3) enthalten sein.

**Returns:**
byte
### setArmStyle(byte value) {#setArmStyle-byte-}
```
public void setArmStyle(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Armstil der Schriftart angibt. Der Wert MUSS in der ArmStyle‑Aufzählungstabelle (Abschnitt 2.1.3) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getLetterform() {#getLetterform--}
```
public byte getLetterform()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Buchstabenform der Schriftart angibt. Der Wert MUSS in der Letterform‑Aufzählungstabelle (Abschnitt 2.1.20) enthalten sein

**Returns:**
byte
### setLetterform(byte value) {#setLetterform-byte-}
```
public void setLetterform(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Buchstabenform der Schriftart angibt. Der Wert MUSS in der Letterform‑Aufzählungstabelle (Abschnitt 2.1.20) enthalten sein

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getMidline() {#getMidline--}
```
public byte getMidline()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Mittelachse der Schriftart angibt. Der Wert MUSS in der MidLine‑Aufzählungstabelle (Abschnitt 2.1.23) enthalten sein.

**Returns:**
byte
### setMidline(byte value) {#setMidline-byte-}
```
public void setMidline(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Mittelachse der Schriftart angibt. Der Wert MUSS in der MidLine‑Aufzählungstabelle (Abschnitt 2.1.23) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getXHeight() {#getXHeight--}
```
public byte getXHeight()
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die x‑Höhe der Schriftart angibt. Der Wert MUSS in der XHeight‑Aufzählungstabelle (Abschnitt 2.1.35) enthalten sein.

**Returns:**
byte
### setXHeight(byte value) {#setXHeight-byte-}
```
public void setXHeight(byte value)
```


Ruft einen 8‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die x‑Höhe der Schriftart angibt. Der Wert MUSS in der XHeight‑Aufzählungstabelle (Abschnitt 2.1.35) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

