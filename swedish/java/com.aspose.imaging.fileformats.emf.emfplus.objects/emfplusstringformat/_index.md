---
title: "EmfPlusStringFormat"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusStringFormat‑objektet specificerar manipulationer av textlayoutens visning och språkidentifiering"
type: docs
weight: 74
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

EmfPlusStringFormat-objektet specificerar textlayout, visningsmanipulationer och språkidentifiering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt som specificerar språket som ska användas för numeriska siffror i strängen. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt som specificerar språket som ska användas för numeriska siffror i strängen. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur numeriska siffror i strängen ska ersättas enligt en lokal eller ett språk. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur numeriska siffror i strängen ska ersättas enligt en lokal eller ett språk. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Hämtar eller anger ett 32‑bitars flyttal som specificerar antalet mellanslag mellan början av en textrad och den första tabbstoppet |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Hämtar eller anger ett 32‑bitars flyttal som specificerar antalet mellanslag mellan början av en textrad och den första tabbstoppet |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vilken typ av bearbetning som utförs på en sträng när ett tangentbordsgenvägsprefix (det vill säga ett och‑tecken) påträffas. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vilken typ av bearbetning som utförs på en sträng när ett tangentbordsgenvägsprefix (det vill säga ett och‑tecken) påträffas. |
| [getLanguage()](#getLanguage--) | Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt (avsnitt 2.2.2.23) som specificerar språket som ska användas för strängen |
| [setLanguage(short value)](#setLanguage-short-) | Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt (avsnitt 2.2.2.23) som specificerar språket som ska användas för strängen |
| [getLeadingMargin()](#getLeadingMargin--) | Hämtar eller anger ett 32‑bitars flyttal som specificerar längden på det utrymme som ska läggas till startpositionen för en sträng. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Hämtar eller anger ett 32‑bitars flyttal som specificerar längden på det utrymme som ska läggas till startpositionen för en sträng. |
| [getLineAlign()](#getLineAlign--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur strängen ska justeras vertikalt i layoutrektangeln. |
| [setLineAlign(int value)](#setLineAlign-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur strängen ska justeras vertikalt i layoutrektangeln. |
| [getRangeCount()](#getRangeCount--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet EmfPlusCharacterRange‑objekt (avsnitt 2.2.2.8) som definieras i StringFormatData‑fältet. |
| [setRangeCount(int value)](#setRangeCount-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet EmfPlusCharacterRange‑objekt (avsnitt 2.2.2.8) som definieras i StringFormatData‑fältet. |
| [getStringAlignment()](#getStringAlignment--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur strängen ska justeras horisontellt i layoutrektangeln. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur strängen ska justeras horisontellt i layoutrektangeln. |
| [getStringFormatData()](#getStringFormatData--) | Hämtar eller anger ett EmfPlusStringFormatData‑objekt (avsnitt 2.2.2.44) som specificerar valfria textlayoutdata. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | Hämtar eller anger ett EmfPlusStringFormatData‑objekt (avsnitt 2.2.2.44) som specificerar valfria textlayoutdata. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar alternativ för textlayout vid formatering, beskärning och teckensnittshantering. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar alternativ för textlayout vid formatering, beskärning och teckensnittshantering. |
| [getTabstopCount()](#getTabstopCount--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet tabbstopp som definieras i StringFormatData‑fältet. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet tabbstopp som definieras i StringFormatData‑fältet. |
| [getTracking()](#getTracking--) | Hämtar eller anger ett 32‑bitars flyttal som specificerar förhållandet mellan det horisontella utrymme som tilldelas varje tecken i en angiven sträng och teckensnittets definierade teckenbredd. |
| [setTracking(float value)](#setTracking-float-) | Hämtar eller anger ett 32‑bitars flyttal som specificerar förhållandet mellan det horisontella utrymme som tilldelas varje tecken i en angiven sträng och teckensnittets definierade teckenbredd. |
| [getTrailingMargin()](#getTrailingMargin--) | Hämtar eller anger ett 32‑bitars flyttal som specificerar längden på det utrymme som ska lämnas efter en sträng. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Hämtar eller anger ett 32‑bitars flyttal som specificerar längden på det utrymme som ska lämnas efter en sträng. |
| [getTrimming()](#getTrimming--) | Hämtar eller anger hur man trimmar tecken från en sträng som är för stor för att få plats i en layoutrektangel. |
| [setTrimming(int value)](#setTrimming-int-) | Hämtar eller anger hur man trimmar tecken från en sträng som är för stor för att få plats i en layoutrektangel. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt som specificerar språket som ska användas för numeriska siffror i strängen. Till exempel, om denna sträng innehåller arabiska siffror, MÅSTE detta fält innehålla en språkidentifierare som specificerar ett arabiskt språk.

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt som specificerar språket som ska användas för numeriska siffror i strängen. Till exempel, om denna sträng innehåller arabiska siffror, MÅSTE detta fält innehålla en språkidentifierare som specificerar ett arabiskt språk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur numeriska siffror i strängen ska ersättas enligt en lokal eller ett språk. Detta värde MÅSTE vara definierat i StringDigitSubstitution‑uppräkningen (avsnitt 2.1.1.30).

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur numeriska siffror i strängen ska ersättas enligt en lokal eller ett språk. Detta värde MÅSTE vara definierat i StringDigitSubstitution‑uppräkningen (avsnitt 2.1.1.30).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar antalet mellanslag mellan början av en textrad och den första tabbstoppet

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar antalet mellanslag mellan början av en textrad och den första tabbstoppet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vilken typ av bearbetning som utförs på en sträng när ett tangentbordsgenvägsprefix (det vill säga ett och‑tecken) påträffas. I grund och botten specificerar detta fält om tangentbordsgenvägsprefix som relaterar till text ska visas. Värdet MÅSTE vara definierat i HotkeyPrefix‑uppräkningen (avsnitt 2.1.1.14).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vilken typ av bearbetning som utförs på en sträng när ett tangentbordsgenvägsprefix (det vill säga ett och‑tecken) påträffas. I grund och botten specificerar detta fält om tangentbordsgenvägsprefix som relaterar till text ska visas. Värdet MÅSTE vara definierat i HotkeyPrefix‑uppräkningen (avsnitt 2.1.1.14).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt (avsnitt 2.2.2.23) som specificerar språket som ska användas för strängen

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Hämtar eller anger ett EmfPlusLanguageIdentifier‑objekt (avsnitt 2.2.2.23) som specificerar språket som ska användas för strängen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar längden på det utrymme som ska läggas till startpositionen för en sträng. Standardvärdet är 1/6 tum; för typografiska teckensnitt är standardvärdet 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar längden på det utrymme som ska läggas till startpositionen för en sträng. Standardvärdet är 1/6 tum; för typografiska teckensnitt är standardvärdet 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur strängen ska justeras vertikalt i layoutrektangeln. Detta värde MÅSTE vara definierat i StringAlignment‑uppräkningen.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur strängen ska justeras vertikalt i layoutrektangeln. Detta värde MÅSTE vara definierat i StringAlignment‑uppräkningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet EmfPlusCharacterRange‑objekt (avsnitt 2.2.2.8) som definieras i StringFormatData‑fältet.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet EmfPlusCharacterRange‑objekt (avsnitt 2.2.2.8) som definieras i StringFormatData‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur strängen ska justeras horisontellt i layoutrektangeln. Detta värde MÅSTE vara definierat i StringAlignment‑enumerationen (avsnitt 2.1.1.29).

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur strängen ska justeras horisontellt i layoutrektangeln. Detta värde MÅSTE vara definierat i StringAlignment‑enumerationen (avsnitt 2.1.1.29).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


Hämtar eller anger ett EmfPlusStringFormatData‑objekt (avsnitt 2.2.2.44) som specificerar valfria textlayoutdata.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


Hämtar eller anger ett EmfPlusStringFormatData‑objekt (avsnitt 2.2.2.44) som specificerar valfria textlayoutdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar alternativ för textlayout för formatering, beskärning och teckensnittshantering. Detta värde MÅSTE bestå av StringFormat‑flaggor (avsnitt 2.1.2.8).

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar alternativ för textlayout för formatering, beskärning och teckensnittshantering. Detta värde MÅSTE bestå av StringFormat‑flaggor (avsnitt 2.1.2.8).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet tabbstopp som definieras i StringFormatData‑fältet.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet tabbstopp som definieras i StringFormatData‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar förhållandet mellan det horisontella utrymme som tilldelas varje tecken i en angiven sträng och tecknets teckensnittsspecificerade bredd. Stora värden för denna egenskap anger gott om utrymme mellan tecken; värden mindre än 1 kan orsaka teckenöverlappning. Standardvärdet är 1.03; för typografiska teckensnitt är standardvärdet 1.00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar förhållandet mellan det horisontella utrymme som tilldelas varje tecken i en angiven sträng och tecknets teckensnittsspecificerade bredd. Stora värden för denna egenskap anger gott om utrymme mellan tecken; värden mindre än 1 kan orsaka teckenöverlappning. Standardvärdet är 1.03; för typografiska teckensnitt är standardvärdet 1.00.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar längden på det utrymme som ska lämnas efter en sträng. Standardvärdet är 1/6 tum; för typografiska teckensnitt är standardvärdet 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar längden på det utrymme som ska lämnas efter en sträng. Standardvärdet är 1/6 tum; för typografiska teckensnitt är standardvärdet 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Hämtar eller anger hur tecken ska trunkeras från en sträng som är för stor för att få plats i en layoutrektangel. Detta värde MÅSTE vara definierat i StringTrimming‑enumerationen (avsnitt 2.1.1.31).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Hämtar eller anger hur tecken ska trunkeras från en sträng som är för stor för att få plats i en layoutrektangel. Detta värde MÅSTE vara definierat i StringTrimming‑enumerationen (avsnitt 2.1.1.31).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

