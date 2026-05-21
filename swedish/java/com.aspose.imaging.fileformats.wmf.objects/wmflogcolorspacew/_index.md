---
title: "WmfLogColorSpaceW"
second_title: "Aspose.Imaging för Java API-referens"
description: "LogColorSpaceW-objektet specificerar ett logiskt färgrymd som kan definieras av en färgprofilfil med ett namn bestående av Unicode 16-bitars tecken."
type: docs
weight: 45
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

LogColorSpaceW-objektet specificerar ett logiskt färgrymd, vilket kan definieras av en färgprofilfil med ett namn bestående av Unicode 16-bitars tecken.

Se `WmfLogColorSpace`-objektet (avsnitt 2.2.2.11) för ytterligare detaljer om tolkningen av fältvärden för detta objekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSignature()](#getSignature--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar `signature` för färgrymdsobjekt; det MÅSTE sättas till värdet 0x50534F43, vilket är ASCII‑kodningen av strängen "PSOC". |
| [setSignature(int value)](#setSignature-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar `signature` för färgrymdsobjekt; det MÅSTE sättas till värdet 0x50534F43, vilket är ASCII‑kodningen av strängen "PSOC". |
| [getVersion()](#getVersion--) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar ett `version`‑nummer; det MÅSTE vara 0x00000400. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar ett `version`‑nummer; det MÅSTE vara 0x00000400. |
| [getSize()](#getSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar `size` för detta objekt, i byte. |
| [setSize(int value)](#setSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar `size` för detta objekt, i byte. |
| [getColorSpaceType()](#getColorSpaceType--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar färgrymdstypen. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar färgrymdstypen. |
| [getIntent()](#getIntent--) | Hämtar eller anger ett 32-bitars signerat heltal som definierar avsikten för gamut‑mappning. |
| [setIntent(int value)](#setIntent-int-) | Hämtar eller anger ett 32-bitars signerat heltal som definierar avsikten för gamut‑mappning. |
| [getEndpoints()](#getEndpoints--) | Hämtar eller anger ett CIEXYZTriple‑objekt (avsnitt 2.2.2.7) som definierar CIE‑kromaticitetskoordinaterna x, y och z för de tre färger som motsvarar RGB-`endpoints` för den logiska färgrymden som är associerad med bitmapen. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Hämtar eller anger ett CIEXYZTriple‑objekt (avsnitt 2.2.2.7) som definierar CIE‑kromaticitetskoordinaterna x, y och z för de tre färger som motsvarar RGB-`endpoints` för den logiska färgrymden som är associerad med bitmapen. |
| [getGammaRed()](#getGammaRed--) | Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för röd. |
| [setGammaRed(int value)](#setGammaRed-int-) | Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för röd. |
| [getGammaGreen()](#getGammaGreen--) | Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för grön. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för grön. |
| [getGammaBlue()](#getGammaBlue--) | Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för blå. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för blå. |
| [getFilename()](#getFilename--) | Hämtar eller anger en valfri, null‑terminerad Unicode UTF16‑LE‑teckensnittssträng som specificerar namnet på en fil som innehåller en färgprofil. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Hämtar eller anger en valfri, null‑terminerad Unicode UTF16‑LE‑teckensnittssträng som specificerar namnet på en fil som innehåller en färgprofil. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar `signature` för färgrymdsobjekt; det MÅSTE sättas till värdet 0x50534F43, vilket är ASCII‑kodningen av strängen "PSOC".

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar `signature` för färgrymdsobjekt; det MÅSTE sättas till värdet 0x50534F43, vilket är ASCII‑kodningen av strängen "PSOC".

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar ett `version`‑nummer; det MÅSTE vara 0x00000400.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar ett `version`‑nummer; det MÅSTE vara 0x00000400.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar `size` för detta objekt, i byte.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar `size` för detta objekt, i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar färgrymdstypen. Det MÅSTE definieras i LogicalColorSpace‑enumerationen (avsnitt 2.1.1.14). Om detta värde är LCS\_sRGB eller LCS\_WINDOWS\_COLOR\_SPACE, måste sRGB‑färgrymden ANVÄNDAS.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar färgrymdstypen. Det MÅSTE definieras i LogicalColorSpace‑enumerationen (avsnitt 2.1.1.14). Om detta värde är LCS\_sRGB eller LCS\_WINDOWS\_COLOR\_SPACE, måste sRGB‑färgrymden ANVÄNDAS.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar avsikten för gamut‑mappning. Det MÅSTE definieras i GamutMappingIntent‑enumerationen (avsnitt 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar avsikten för gamut‑mappning. Det MÅSTE definieras i GamutMappingIntent‑enumerationen (avsnitt 2.1.1.11).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Hämtar eller anger ett CIEXYZTriple‑objekt (avsnitt 2.2.2.7) som definierar CIE‑kromaticitetskoordinaterna x, y och z för de tre färger som motsvarar RGB-`endpoints` för den logiska färgrymden som är associerad med bitmapen. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Hämtar eller anger ett CIEXYZTriple‑objekt (avsnitt 2.2.2.7) som definierar CIE‑kromaticitetskoordinaterna x, y och z för de tre färger som motsvarar RGB-`endpoints` för den logiska färgrymden som är associerad med bitmapen. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för röd. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för röd. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för grön. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för grön. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för blå. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Hämtar eller anger ett 32-bitars fast‑punkt‑värde som definierar den tonade responskurvan för blå. Om fältet `ColorSpaceType` inte specificerar LCS\_CALIBRATED\_RGB, MÅSTE detta fält ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Hämtar eller anger en valfri, null‑terminerad Unicode UTF16‑LE‑teckensnittssträng som specificerar namnet på en fil som innehåller en färgprofil. Om ett filnamn anges och fältet `ColorSpaceType` är satt till LCS\_CALIBRATED\_RGB, bör de övriga fälten i denna struktur ignoreras.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Hämtar eller anger en valfri, null‑terminerad Unicode UTF16‑LE‑teckensnittssträng som specificerar namnet på en fil som innehåller en färgprofil. Om ett filnamn anges och fältet `ColorSpaceType` är satt till LCS\_CALIBRATED\_RGB, bör de övriga fälten i denna struktur ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

