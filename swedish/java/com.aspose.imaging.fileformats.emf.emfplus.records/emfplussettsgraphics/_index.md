---
title: "EmfPlusSetTsGraphics"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusSetTSGraphics-posten specificerar tillståndet för en grafikens enhetskontext för en terminalserver."
type: docs
weight: 67
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

Den EmfPlusSetTSGraphics-posten specificerar tillståndet för en grafikens enhetskontext för en terminalserver.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSetTsGraphics`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | Hämtar ett värde som indikerar om [basic vga colors]. |
| [getHavePalette()](#getHavePalette--) | Hämtar ett värde som indikerar om [have palette]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på linjerendering, inklusive typen av linjeantialiasing. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på linjerendering, inklusive typen av linjeantialiasing. |
| [getTextRenderHint()](#getTextRenderHint--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på textrendering, inklusive typen av textantialiasing. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på textrendering, inklusive typen av textantialiasing. |
| [getCompositingMode()](#getCompositingMode--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur källfärger kombineras med bakgrundsfärger. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur källfärger kombineras med bakgrundsfärger. |
| [getCompositingQuality()](#getCompositingQuality--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar graden av utjämning som ska tillämpas på linjer, kurvor och kanterna på fyllda områden för att få dem att framstå mer kontinuerliga eller skarpt definierade. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar graden av utjämning som ska tillämpas på linjer, kurvor och kanterna på fyllda områden för att få dem att framstå mer kontinuerliga eller skarpt definierade. |
| [getRenderOriginX()](#getRenderOriginX--) | Hämtar eller anger ett 16-bitars signerat heltal, vilket är den horisontella koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Hämtar eller anger ett 16-bitars signerat heltal, vilket är den horisontella koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser. |
| [getRenderOriginY()](#getRenderOriginY--) | Hämtar eller anger ett 16-bitars signerat heltal, vilket är den vertikala koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Hämtar eller anger ett 16-bitars signerat heltal, vilket är den vertikala koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser. |
| [getTextContrast()](#getTextContrast--) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma-korrigeringsvärdet som används för rendering av antialiasad och ClearType-text. |
| [setTextContrast(short value)](#setTextContrast-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma-korrigeringsvärdet som används för rendering av antialiasad och ClearType-text. |
| [getFilterType()](#getFilterType--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur skalning, inklusive sträckning och krympning, utförs. |
| [setFilterType(byte value)](#setFilterType-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur skalning, inklusive sträckning och krympning, utförs. |
| [getPixelOffset()](#getPixelOffset--) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar den övergripande kvaliteten på bild- och textrenderingsprocessen. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Hämtar eller anger ett 8-bitars osignerat heltal som specificerar den övergripande kvaliteten på bild- och textrenderingsprocessen. |
| [getWorldToDevice()](#getWorldToDevice--) | Hämtar eller anger ett 192-bitars EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar transformationer från världsrummet till enhetsrummet. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Hämtar eller anger ett 192-bitars EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar transformationer från världsrummet till enhetsrummet. |
| [getPalette()](#getPalette--) | Hämtar eller anger ett valfritt EmfPlusPalette-objekt. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Hämtar eller anger ett valfritt EmfPlusPalette-objekt. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSetTsGraphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Hämtar ett värde som indikerar om [basic vga colors]. Om satt innehåller paletten endast de grundläggande VGA-färgerna.

Värde: `true` om [basic vga colors]; annars `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Hämtar ett värde som indikerar om [have palette]. Om satt innehåller denna post ett EmfPlusPalette-objekt (avsnitt 2.2.2.28) i Palette-fältet efter grafikstatusdata.

Värde: `true` om [have palette]; annars `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på linjerendering, inklusive typen av linjeantialiasing. Det MÅSTE definieras i SmoothingMode‑enumerationen (avsnitt 2.1.1.28).

Värde: Antialias‑läget.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på linjerendering, inklusive typen av linjeantialiasing. Det MÅSTE definieras i SmoothingMode‑enumerationen (avsnitt 2.1.1.28).

Värde: Antialias‑läget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på textrendering, inklusive typen av textantialiasing. Det MÅSTE definieras i TextRenderingHint‑enumerationen (avsnitt 2.1.1.32).

Värde: Textrenderingstips.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar kvaliteten på textrendering, inklusive typen av textantialiasing. Det MÅSTE definieras i TextRenderingHint‑enumerationen (avsnitt 2.1.1.32).

Värde: Textrenderingstips.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur källfärger kombineras med bakgrundsfärger. Det MÅSTE vara ett värde i CompositingMode‑enumerationen (avsnitt 2.1.1.5).

Värde: Sammanfogningsläget.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur källfärger kombineras med bakgrundsfärger. Det MÅSTE vara ett värde i CompositingMode‑enumerationen (avsnitt 2.1.1.5).

Värde: Sammanfogningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar graden av utjämning som ska tillämpas på linjer, kurvor och kanterna på fyllda områden för att få dem att framstå mer kontinuerliga eller skarpt definierade. Det MÅSTE vara ett värde i CompositingQuality‑enumerationen (avsnitt 2.1.1.6).

Värde: sammansättningskvaliteten.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar graden av utjämning som ska tillämpas på linjer, kurvor och kanterna på fyllda områden för att få dem att framstå mer kontinuerliga eller skarpt definierade. Det MÅSTE vara ett värde i CompositingQuality‑enumerationen (avsnitt 2.1.1.6).

Värde: sammansättningskvaliteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Hämtar eller anger ett 16-bitars signerat heltal, vilket är den horisontella koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser.

Värde: Renderingsursprunget x.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Hämtar eller anger ett 16-bitars signerat heltal, vilket är den horisontella koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser.

Värde: Renderingsursprunget x.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Hämtar eller anger ett 16-bitars signerat heltal, vilket är den vertikala koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser.

Värde: Renderingsursprunget y.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Hämtar eller anger ett 16-bitars signerat heltal, vilket är den vertikala koordinaten för ursprunget vid rendering av halvtoning- och dithermatriser.

Värde: Renderingsursprunget y.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionsvärdet som används för rendering av antialiasad och ClearType‑text. Detta värde MÅSTE ligga i intervallet 0 till 12, inklusive.

Värde: Textkontrast.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionsvärdet som används för rendering av antialiasad och ClearType‑text. Detta värde MÅSTE ligga i intervallet 0 till 12, inklusive.

Värde: Textkontrast.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur skalning, inklusive sträckning och krympning, utförs. Det MÅSTE vara ett värde i FilterType‑enumerationen (avsnitt 2.1.1.11).

Värde: Filtreringstypen.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar hur skalning, inklusive sträckning och krympning, utförs. Det MÅSTE vara ett värde i FilterType‑enumerationen (avsnitt 2.1.1.11).

Värde: Filtreringstypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar den övergripande kvaliteten på bild- och textrenderingsprocessen. Det MÅSTE vara ett värde i PixelOffsetMode‑enumerationen (avsnitt 2.1.1.26).

Värde: Pixeloffset.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Hämtar eller anger ett 8-bitars osignerat heltal som specificerar den övergripande kvaliteten på bild- och textrenderingsprocessen. Det MÅSTE vara ett värde i PixelOffsetMode‑enumerationen (avsnitt 2.1.1.26).

Värde: Pixeloffset.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Hämtar eller anger ett 192-bitars EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar transformationer från världsrummet till enhetsrummet.

Värde: Värld till enhet.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Hämtar eller anger ett 192-bitars EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar transformationer från världsrummet till enhetsrummet.

Värde: Värld till enhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


Hämtar eller anger ett valfritt EmfPlusPalette-objekt.

Värde: Paletten.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


Hämtar eller anger ett valfritt EmfPlusPalette-objekt.

Värde: Paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

