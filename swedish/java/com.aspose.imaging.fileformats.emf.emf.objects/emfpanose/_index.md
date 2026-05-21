---
title: "EmfPanose"
second_title: "Aspose.Imaging för Java API-referens"
description: "Panose-objektet beskriver PANOSE‑teckensnittsklassificeringsvärdena för ett TrueType‑teckensnitt."
type: docs
weight: 30
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPanose extends EmfObject
```

Panose-objektet beskriver PANOSE-teckensnittsklassificeringsvärdena för ett TrueType-teckensnitt. Dessa egenskaper används för att associera teckensnittet med andra teckensnitt med liknande utseende men olika namn.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPanose()](#EmfPanose--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyType()](#getFamilyType--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar familjetypen. |
| [setFamilyType(byte value)](#setFamilyType-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar familjetypen. |
| [getSerifStyle()](#getSerifStyle--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar serifstilen. |
| [setSerifStyle(byte value)](#setSerifStyle-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar serifstilen. |
| [getWeight()](#getWeight--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar teckensnittets vikt. |
| [setWeight(byte value)](#setWeight-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar teckensnittets vikt. |
| [getProportion()](#getProportion--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar teckensnittets proportion. |
| [setProportion(byte value)](#setProportion-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar teckensnittets proportion. |
| [getContrast()](#getContrast--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar teckensnittets kontrast. |
| [setContrast(byte value)](#setContrast-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar teckensnittets kontrast. |
| [getStrokeVariation()](#getStrokeVariation--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar stroke-variationen för teckensnittet. |
| [setStrokeVariation(byte value)](#setStrokeVariation-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar stroke-variationen för teckensnittet. |
| [getArmStyle()](#getArmStyle--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar armstilen för teckensnittet. |
| [setArmStyle(byte value)](#setArmStyle-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar armstilen för teckensnittet. |
| [getLetterform()](#getLetterform--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar bokstavsformen för teckensnittet. |
| [setLetterform(byte value)](#setLetterform-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar bokstavsformen för teckensnittet. |
| [getMidline()](#getMidline--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar mittlinjen för teckensnittet. |
| [setMidline(byte value)](#setMidline-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar mittlinjen för teckensnittet. |
| [getXHeight()](#getXHeight--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar x-höjden för teckensnittet. |
| [setXHeight(byte value)](#setXHeight-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar x-höjden för teckensnittet. |
### EmfPanose() {#EmfPanose--}
```
public EmfPanose()
```


### getFamilyType() {#getFamilyType--}
```
public byte getFamilyType()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar familjetypen. Värdet MÅSTE finnas i FamilyType (avsnitt 2.1.12) enumerationstabell.

**Returns:**
byte
### setFamilyType(byte value) {#setFamilyType-byte-}
```
public void setFamilyType(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar familjetypen. Värdet MÅSTE finnas i FamilyType (avsnitt 2.1.12) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getSerifStyle() {#getSerifStyle--}
```
public byte getSerifStyle()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar seriffstilen. Värdet MÅSTE finnas i SerifType (avsnitt 2.1.30) enumerationstabell.

**Returns:**
byte
### setSerifStyle(byte value) {#setSerifStyle-byte-}
```
public void setSerifStyle(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar seriffstilen. Värdet MÅSTE finnas i SerifType (avsnitt 2.1.30) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getWeight() {#getWeight--}
```
public byte getWeight()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar vikten för teckensnittet. Värdet MÅSTE finnas i Weight (avsnitt 2.1.34) enumerationstabell.

**Returns:**
byte
### setWeight(byte value) {#setWeight-byte-}
```
public void setWeight(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar vikten för teckensnittet. Värdet MÅSTE finnas i Weight (avsnitt 2.1.34) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getProportion() {#getProportion--}
```
public byte getProportion()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar proportionen för teckensnittet. Värdet MÅSTE finnas i Proportion (avsnitt 2.1.28) enumerationstabell.

**Returns:**
byte
### setProportion(byte value) {#setProportion-byte-}
```
public void setProportion(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar proportionen för teckensnittet. Värdet MÅSTE finnas i Proportion (avsnitt 2.1.28) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getContrast() {#getContrast--}
```
public byte getContrast()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kontrasten för teckensnittet. Värdet MÅSTE finnas i Contrast (avsnitt 2.1.8) enumerationstabell.

**Returns:**
byte
### setContrast(byte value) {#setContrast-byte-}
```
public void setContrast(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kontrasten för teckensnittet. Värdet MÅSTE finnas i Contrast (avsnitt 2.1.8) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getStrokeVariation() {#getStrokeVariation--}
```
public byte getStrokeVariation()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar stroke-variationen för teckensnittet. Värdet MÅSTE finnas i StrokeVariation (avsnitt 2.1.33) enumerationstabell.

**Returns:**
byte
### setStrokeVariation(byte value) {#setStrokeVariation-byte-}
```
public void setStrokeVariation(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar stroke-variationen för teckensnittet. Värdet MÅSTE finnas i StrokeVariation (avsnitt 2.1.33) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getArmStyle() {#getArmStyle--}
```
public byte getArmStyle()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar armstilen för teckensnittet. Värdet MÅSTE finnas i ArmStyle (avsnitt 2.1.3) enumerationstabell.

**Returns:**
byte
### setArmStyle(byte value) {#setArmStyle-byte-}
```
public void setArmStyle(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar armstilen för teckensnittet. Värdet MÅSTE finnas i ArmStyle (avsnitt 2.1.3) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getLetterform() {#getLetterform--}
```
public byte getLetterform()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar bokstavsformen för teckensnittet. Värdet MÅSTE finnas i Letterform (avsnitt 2.1.20) enumerationstabell

**Returns:**
byte
### setLetterform(byte value) {#setLetterform-byte-}
```
public void setLetterform(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar bokstavsformen för teckensnittet. Värdet MÅSTE finnas i Letterform (avsnitt 2.1.20) enumerationstabell

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getMidline() {#getMidline--}
```
public byte getMidline()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar mittlinjen för teckensnittet. Värdet MÅSTE finnas i MidLine (avsnitt 2.1.23) enumerationstabell.

**Returns:**
byte
### setMidline(byte value) {#setMidline-byte-}
```
public void setMidline(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar mittlinjen för teckensnittet. Värdet MÅSTE finnas i MidLine (avsnitt 2.1.23) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getXHeight() {#getXHeight--}
```
public byte getXHeight()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar x-höjden för teckensnittet. Värdet MÅSTE finnas i XHeight (avsnitt 2.1.35) enumerationstabell.

**Returns:**
byte
### setXHeight(byte value) {#setXHeight-byte-}
```
public void setXHeight(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar x-höjden för teckensnittet. Värdet MÅSTE finnas i XHeight (avsnitt 2.1.35) enumerationstabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

