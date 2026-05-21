---
title: "EmfLogFont"
second_title: "Aspose.Imaging för Java API-referens"
description: "LogFont-objektet specificerar de grundläggande attributen för ett logiskt teckensnitt."
type: docs
weight: 22
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

LogFont-objektet specificerar de grundläggande attributen för ett logiskt teckensnitt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeight()](#getHeight--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden, i logiska enheter, för teckensnittets teckencell eller tecken. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden, i logiska enheter, för teckensnittets teckencell eller tecken. |
| [getWidth()](#getWidth--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den genomsnittliga bredden, i logiska enheter, för tecken i teckensnittet. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den genomsnittliga bredden, i logiska enheter, för tecken i teckensnittet. |
| [getEscapement()](#getEscapement--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, mellan escapement‑vektorn och enhetens x‑axel. |
| [setEscapement(int value)](#setEscapement-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, mellan escapement‑vektorn och enhetens x‑axel. |
| [getOrientation()](#getOrientation--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, mellan varje teckens baslinje och enhetens x‑axel. |
| [setOrientation(int value)](#setOrientation-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, mellan varje teckens baslinje och enhetens x‑axel. |
| [getWeight()](#getWeight--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar teckensnittets vikt i intervallet 0 till 1000. |
| [setWeight(int value)](#setWeight-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar teckensnittets vikt i intervallet 0 till 1000. |
| [getItalic()](#getItalic--) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett kursivt teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00. |
| [setItalic(byte value)](#setItalic-byte-) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett kursivt teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00. |
| [getUnderline()](#getUnderline--) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett understruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00. |
| [setUnderline(byte value)](#setUnderline-byte-) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett understruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00. |
| [getStrikeout()](#getStrikeout--) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett genomstruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett genomstruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00. |
| [getCharSet()](#getCharSet--) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar uppsättningen av teckenglyfer. |
| [setCharSet(byte value)](#setCharSet-byte-) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar uppsättningen av teckenglyfer. |
| [getOutPrecision()](#getOutPrecision--) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar utskriftsprecisionen. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar utskriftsprecisionen. |
| [getClipPrecision()](#getClipPrecision--) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar beskärningsprecisionen. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar beskärningsprecisionen. |
| [getQuality()](#getQuality--) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar utskriftskvaliteten. |
| [setQuality(byte value)](#setQuality-byte-) | Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar utskriftskvaliteten. |
| [getPitchAndFamily()](#getPitchAndFamily--) | Hämtar eller anger ett WMF PitchAndFamily‑objekt ([MS-WMF] sektion 2.2.2.14) som specificerar teckensnittets pitch och familj. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | Hämtar eller anger ett WMF PitchAndFamily‑objekt ([MS-WMF] sektion 2.2.2.14) som specificerar teckensnittets pitch och familj. |
| [getFacename()](#getFacename--) | Hämtar eller anger ett Facename (64 byte): En sträng på högst 32 Unicode‑tecken som specificerar teckensnittets typsnittsnamn. |
| [setFacename(String value)](#setFacename-java.lang.String-) | Hämtar eller anger ett Facename (64 byte): En sträng på högst 32 Unicode‑tecken som specificerar teckensnittets typsnittsnamn. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden, i logiska enheter, för teckensnittets teckencell eller tecken. Teckenhöjdsvärdet, även känt som em‑storlek, är teckencellens höjdvärde minus det interna ledningsvärdet. Font‑mapparen SHOULD tolka värdet som anges i Height‑fältet på följande sätt.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden, i logiska enheter, för teckensnittets teckencell eller tecken. Teckenhöjdsvärdet, även känt som em‑storlek, är teckencellens höjdvärde minus det interna ledningsvärdet. Font‑mapparen SHOULD tolka värdet som anges i Height‑fältet på följande sätt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den genomsnittliga bredden, i logiska enheter, för tecken i teckensnittet. Om Width‑fältets värde är noll SHOULD ett lämpligt värde beräknas från andra LogFont‑värden för att hitta ett teckensnitt som har typografens avsedda bildförhållande.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den genomsnittliga bredden, i logiska enheter, för tecken i teckensnittet. Om Width‑fältets värde är noll SHOULD ett lämpligt värde beräknas från andra LogFont‑värden för att hitta ett teckensnitt som har typografens avsedda bildförhållande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar vinkeln, i tiondelar av grader, mellan escapement‑vektorn och enhetens x‑axel. Escapement‑vektorn är parallell med baslinjen för en textrad.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar vinkeln, i tiondelar av grader, mellan escapement‑vektorn och enhetens x‑axel. Escapement‑vektorn är parallell med baslinjen för en textrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, mellan varje teckens baslinje och enhetens x‑axel.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar vinkeln, i tiondelar av grader, mellan varje teckens baslinje och enhetens x‑axel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar teckensnittets vikt i intervallet noll till 1000. Till exempel är 400 normalt och 700 fetstil. Om detta värde är noll kan en standardvikt användas.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar teckensnittets vikt i intervallet noll till 1000. Till exempel är 400 normalt och 700 fetstil. Om detta värde är noll kan en standardvikt användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett kursivt teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett kursivt teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett understruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett understruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett genomstruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


Hämtar eller anger ett 8‑bitars osignerat heltal som specificerar ett genomstruket teckensnitt om det är satt till 0x01; annars MUST det vara satt till 0x00.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar uppsättningen av teckenglyfer. Det MÅSTE vara ett värde i WMF CharacterSet‑enumerationen ([MS-WMF] avsnitt 2.1.1.5). Om teckenuppsättningen är okänd bör metafilshanteringen INTE försöka översätta eller tolka strängar som renderas med det teckensnittet.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar uppsättningen av teckenglyfer. Det MÅSTE vara ett värde i WMF CharacterSet‑enumerationen ([MS-WMF] avsnitt 2.1.1.5). Om teckenuppsättningen är okänd bör metafilshanteringen INTE försöka översätta eller tolka strängar som renderas med det teckensnittet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar utskriftsprecisionen. Utskriftsprecisionen definierar hur nära teckensnittet måste matcha den begärda höjden, bredden, teckenorienteringen, escapement, pitch och teckensnittstypen. Det MÅSTE vara ett värde från WMF OutPrecision‑enumerationen.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar utskriftsprecisionen. Utskriftsprecisionen definierar hur nära teckensnittet måste matcha den begärda höjden, bredden, teckenorienteringen, escapement, pitch och teckensnittstypen. Det MÅSTE vara ett värde från WMF OutPrecision‑enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar klippningsprecisionen. Klippningsprecisionen definierar hur tecken som delvis ligger utanför klippningsområdet ska klippas. Det kan vara en eller flera av WMF ClipPrecision‑flaggorna.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar klippningsprecisionen. Klippningsprecisionen definierar hur tecken som delvis ligger utanför klippningsområdet ska klippas. Det kan vara en eller flera av WMF ClipPrecision‑flaggorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar utskriftskvaliteten. Utskriftskvaliteten definierar hur nära man ska försöka matcha de logiska teckensnittsattributen med ett faktiskt fysiskt teckensnitt. Det MÅSTE vara ett av värdena i WMF FontQuality‑enumerationen ([MS-WMF] avsnitt 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar utskriftskvaliteten. Utskriftskvaliteten definierar hur nära man ska försöka matcha de logiska teckensnittsattributen med ett faktiskt fysiskt teckensnitt. Det MÅSTE vara ett av värdena i WMF FontQuality‑enumerationen ([MS-WMF] avsnitt 2.1.1.10).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


Hämtar eller anger ett WMF PitchAndFamily‑objekt ([MS-WMF] avsnitt 2.2.2.14) som specificerar teckensnittets pitch och familj. Teckensnittsfamiljer beskriver ett teckensnitts utseende på ett generellt sätt. De är avsedda för att ange ett teckensnitt när den specificerade teckensnittstypen inte är tillgänglig.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


Hämtar eller anger ett WMF PitchAndFamily‑objekt ([MS-WMF] avsnitt 2.2.2.14) som specificerar teckensnittets pitch och familj. Teckensnittsfamiljer beskriver ett teckensnitts utseende på ett generellt sätt. De är avsedda för att ange ett teckensnitt när den specificerade teckensnittstypen inte är tillgänglig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


Hämtar eller anger ett Facename (64 byte): En sträng på högst 32 Unicode‑tecken som specificerar teckensnittets namn. Om längden på denna sträng är kortare än 32 tecken måste en avslutande NULL finnas, varefter resten av fältet MÅSTE ignoreras.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


Hämtar eller anger ett Facename (64 byte): En sträng på högst 32 Unicode‑tecken som specificerar teckensnittets namn. Om längden på denna sträng är kortare än 32 tecken måste en avslutande NULL finnas, varefter resten av fältet MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

