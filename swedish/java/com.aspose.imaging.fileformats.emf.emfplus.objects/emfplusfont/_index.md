---
title: "EmfPlusFont"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusFont‑objektet specificerar egenskaper som bestämmer textens utseende inklusive teckensnittsstorlek och stil."
type: docs
weight: 42
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

EmfPlusFont-objektet specificerar egenskaper som bestämmer textens utseende, inklusive teckensnitt, storlek och stil.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Hämtar eller anger en sträng med Length Unicode‑tecken som innehåller namnet på teckensnittsfamiljen. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Hämtar eller anger en sträng med Length Unicode‑tecken som innehåller namnet på teckensnittsfamiljen. |
| [getFontStyleFlags()](#getFontStyleFlags--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar attribut för teckenglyfer som påverkar teckensnittets utseende, såsom fetstil och kursiv. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar attribut för teckenglyfer som påverkar teckensnittets utseende, såsom fetstil och kursiv. |
| [getSizeUnit()](#getSizeUnit--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar enheterna som används för EmSize‑fältet. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar enheterna som används för EmSize‑fältet. |
| [getEmSize()](#getEmSize--) | Hämtar eller anger ett 32-bitars flyttalsvärde som specificerar teckensnittets em‑storlek i de enheter som anges av SizeUnit‑fältet. |
| [setEmSize(float value)](#setEmSize-float-) | Hämtar eller anger ett 32-bitars flyttalsvärde som specificerar teckensnittets em‑storlek i de enheter som anges av SizeUnit‑fältet. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Hämtar eller anger en sträng med Length Unicode‑tecken som innehåller namnet på teckensnittsfamiljen.

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Hämtar eller anger en sträng med Length Unicode‑tecken som innehåller namnet på teckensnittsfamiljen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar attribut för teckenglyfer som påverkar teckensnittets utseende, såsom fetstil och kursiv. Detta värde MÅSTE bestå av FontStyle‑flaggor (avsnitt 2.1.2.4).

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar attribut för teckenglyfer som påverkar teckensnittets utseende, såsom fetstil och kursiv. Detta värde MÅSTE bestå av FontStyle‑flaggor (avsnitt 2.1.2.4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar enheterna som används för EmSize‑fältet. Dessa är vanligtvis de enheter som användes när teckensnittet designades. Värdet MÅSTE vara i UnitType‑uppräkningen (avsnitt 2.1.1.33).

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar enheterna som används för EmSize‑fältet. Dessa är vanligtvis de enheter som användes när teckensnittet designades. Värdet MÅSTE vara i UnitType‑uppräkningen (avsnitt 2.1.1.33).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


Hämtar eller anger ett 32-bitars flyttalsvärde som specificerar teckensnittets em‑storlek i de enheter som anges av SizeUnit‑fältet.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


Hämtar eller anger ett 32-bitars flyttalsvärde som specificerar teckensnittets em‑storlek i de enheter som anges av SizeUnit‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

