---
title: "EmfUniversalFontId"
second_title: "Aspose.Imaging för Java API-referens"
description: "UniversalFontId-objektet definierar en mekanism för att identifiera typsnitt i EMF-metafiler."
type: docs
weight: 37
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

UniversalFontId-objektet definierar en mekanism för att identifiera typsnitt i EMF-metafiler.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChecksum()](#getChecksum--) | Hämtar eller anger ett 32-bitars osignerat heltal som är kontrollsumman för teckensnittet. |
| [setChecksum(int value)](#setChecksum-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som är kontrollsumman för teckensnittet. |
| [getIndex()](#getIndex--) | Hämtar eller anger ett 32-bitars osignerat heltal som är ett index kopplat till teckensnittobjektet. |
| [setIndex(int value)](#setIndex-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som är ett index kopplat till teckensnittobjektet. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Hämtar eller anger ett 32-bitars osignerat heltal som är kontrollsumman för teckensnittet. Kontrollsummavärdet har följande betydelser. 0x00000000 Objektet är ett enhetsteckensnitt. 0x00000001 Objektet är ett Type 1-teckensnitt som har installerats på klientmaskinen och som enumereras av PostScript-skrivardrivrutinen som ett enhetsteckensnitt. 0x00000002 Objektet är inte ett teckensnitt utan ett Type 1-rasteriseringsprogram. 3 \\u2264 value Objektet är en bitmap, vektor eller TrueType-teckensnitt, eller ett Type 1-rasteriserat teckensnitt som skapats av ett Type 1-rasteriseringsprogram.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som är kontrollsumman för teckensnittet. Kontrollsummavärdet har följande betydelser. 0x00000000 Objektet är ett enhetsteckensnitt. 0x00000001 Objektet är ett Type 1-teckensnitt som har installerats på klientmaskinen och som enumereras av PostScript-skrivardrivrutinen som ett enhetsteckensnitt. 0x00000002 Objektet är inte ett teckensnitt utan ett Type 1-rasteriseringsprogram. 3 \\u2264 value Objektet är en bitmap, vektor eller TrueType-teckensnitt, eller ett Type 1-rasteriserat teckensnitt som skapats av ett Type 1-rasteriseringsprogram.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Hämtar eller anger ett 32-bitars osignerat heltal som är ett index kopplat till teckensnittobjektet. Betydelsen av detta fält bestäms av teckensnittstypen.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som är ett index kopplat till teckensnittobjektet. Betydelsen av detta fält bestäms av teckensnittstypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

