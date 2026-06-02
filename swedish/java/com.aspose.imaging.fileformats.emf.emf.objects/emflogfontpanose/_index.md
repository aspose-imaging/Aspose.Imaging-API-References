---
title: "EmfLogFontPanose"
second_title: "Aspose.Imaging för Java API-referens"
description: "LogFontPanose-objektet specificerar PANOSE‑karaktäristiken för ett logiskt teckensnitt."
type: docs
weight: 25
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

LogFontPanose-objektet specificerar PANOSE‑karaktäristiken för ett logiskt teckensnitt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Initierar en ny instans av klassen `EmfLogFontPanose`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFullName()](#getFullName--) | Hämtar eller anger en sträng med 64 Unicode-tecken som definierar teckensnittets fullständiga namn. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Hämtar eller anger en sträng med 64 Unicode-tecken som definierar teckensnittets fullständiga namn. |
| [getStyle()](#getStyle--) | Hämtar eller anger en sträng med 32 Unicode-tecken som definierar teckensnittets stil. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Hämtar eller anger en sträng med 32 Unicode-tecken som definierar teckensnittets stil. |
| [getVersion()](#getVersion--) | Hämtar eller anger Detta fält MÅSTE ignoreras. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger Detta fält MÅSTE ignoreras. |
| [getStyleSize()](#getStyleSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar punktstorleken där teckensnittshintning utförs. |
| [setStyleSize(int value)](#setStyleSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar punktstorleken där teckensnittshintning utförs. |
| [getMatch()](#getMatch--) | Hämtar eller anger Detta fält MÅSTE ignoreras. |
| [setMatch(int value)](#setMatch-int-) | Hämtar eller anger Detta fält MÅSTE ignoreras. |
| [getVendorId()](#getVendorId--) | Hämtar eller anger Detta fält MÅSTE ignoreras. |
| [setVendorId(int value)](#setVendorId-int-) | Hämtar eller anger Detta fält MÅSTE ignoreras. |
| [getCulture()](#getCulture--) | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE sättas till noll och MÅSTE ignoreras. |
| [setCulture(int value)](#setCulture-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE sättas till noll och MÅSTE ignoreras. |
| [getPanose()](#getPanose--) | Hämtar eller anger ett Panose-objekt (avsnitt 2.2.21) som specificerar PANOSE-egenskaperna för det logiska teckensnittet. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Hämtar eller anger ett Panose-objekt (avsnitt 2.2.21) som specificerar PANOSE-egenskaperna för det logiska teckensnittet. |
| [getPadding()](#getPadding--) | Hämtar eller anger ett fält som endast finns för att säkerställa 32-bitars justering av denna struktur. |
| [setPadding(short value)](#setPadding-short-) | Hämtar eller anger ett fält som endast finns för att säkerställa 32-bitars justering av denna struktur. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


Initierar en ny instans av klassen `EmfLogFontPanose`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | Den grundläggande log font. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Hämtar eller anger en sträng med 64 Unicode-tecken som definierar teckensnittets fullständiga namn. Om längden på denna sträng är mindre än 64 tecken, måste en avslutande NULL vara närvarande, varefter resten av detta fält MÅSTE ignoreras.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Hämtar eller anger en sträng med 64 Unicode-tecken som definierar teckensnittets fullständiga namn. Om längden på denna sträng är mindre än 64 tecken, måste en avslutande NULL vara närvarande, varefter resten av detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Hämtar eller anger en sträng med 32 Unicode-tecken som definierar teckensnittets stil. Om längden på denna sträng är mindre än 32 tecken MÅSTE en avslutande NULL vara närvarande, varpå resten av detta fält MÅSTE ignoreras.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Hämtar eller anger en sträng med 32 Unicode-tecken som definierar teckensnittets stil. Om längden på denna sträng är mindre än 32 tecken MÅSTE en avslutande NULL vara närvarande, varpå resten av detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger Detta fält MÅSTE ignoreras.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger Detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar punktstorleken där teckensnittshintning utförs. Om det sätts till noll, utförs hintning vid den punktstorlek som motsvarar Height-fältet i LogFont-objektet i LogFont-fältet.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar punktstorleken där teckensnittshintning utförs. Om det sätts till noll, utförs hintning vid den punktstorlek som motsvarar Height-fältet i LogFont-objektet i LogFont-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Hämtar eller anger Detta fält MÅSTE ignoreras.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Hämtar eller anger Detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Hämtar eller anger Detta fält MÅSTE ignoreras.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Hämtar eller anger Detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE sättas till noll och MÅSTE ignoreras.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE sättas till noll och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Hämtar eller anger ett Panose-objekt (avsnitt 2.2.21) som specificerar PANOSE-egenskaperna för det logiska teckensnittet. Om alla fält i detta objekt är noll, MÅSTE det ignoreras.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Hämtar eller anger ett Panose-objekt (avsnitt 2.2.21) som specificerar PANOSE-egenskaperna för det logiska teckensnittet. Om alla fält i detta objekt är noll, MÅSTE det ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Hämtar eller anger ett fält som endast finns för att säkerställa 32-bitars justering av denna struktur. Det MÅSTE ignoreras

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Hämtar eller anger ett fält som endast finns för att säkerställa 32-bitars justering av denna struktur. Det MÅSTE ignoreras

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

