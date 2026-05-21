---
title: "EmfEpsData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EpsData-objektet är en behållare för EPS‑data."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

EpsData-objektet är en behållare för EPS‑data.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSizeData()](#getSizeData--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den totala storleken på detta objekt, i byte |
| [setSizeData(int value)](#setSizeData-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den totala storleken på detta objekt, i byte |
| [getVersion()](#getVersion--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PostScript-språknivån. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PostScript-språknivån. |
| [getPoints()](#getPoints--) | Hämtar eller anger en array med tre Point28\_4-objekt (avsnitt 2.2.23) som definierar koordinaterna för utdata-parallellogrammet med 28.4-bitars FIX-notation |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | Hämtar eller anger en array med tre Point28\_4-objekt (avsnitt 2.2.23) som definierar koordinaterna för utdata-parallellogrammet med 28.4-bitars FIX-notation |
| [getPostScriptData()](#getPostScriptData--) | Hämtar eller anger en array med byte av PostScript-data. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | Hämtar eller anger en array med byte av PostScript-data. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den totala storleken på detta objekt, i byte

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den totala storleken på detta objekt, i byte

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PostScript-språknivån. Detta värde MÅSTE vara 0x00000001

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PostScript-språknivån. Detta värde MÅSTE vara 0x00000001

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


Hämtar eller anger en array med tre Point28\_4-objekt (avsnitt 2.2.23) som definierar koordinaterna för utdata-parallellogrammet med 28.4-bitars FIX-notation

Det övre vänstra hörnet av parallellogrammet är den första punkten i denna array, det övre högra hörnet är den andra punkten och det nedre vänstra hörnet är den tredje punkten. Det nedre högra hörnet av parallellogrammet beräknas från de tre första punkterna (A, B och C) genom att behandla dem som vektorer.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


Hämtar eller anger en array med tre Point28\_4-objekt (avsnitt 2.2.23) som definierar koordinaterna för utdata-parallellogrammet med 28.4-bitars FIX-notation

Det övre vänstra hörnet av parallellogrammet är den första punkten i denna array, det övre högra hörnet är den andra punkten och det nedre vänstra hörnet är den tredje punkten. Det nedre högra hörnet av parallellogrammet beräknas från de tre första punkterna (A, B och C) genom att behandla dem som vektorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


Hämtar eller anger en array med byte av PostScript-data. Längden på denna array kan beräknas från SizeData-fältet. Dessa data KAN användas för att rendera en bild.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


Hämtar eller anger en array med byte av PostScript-data. Längden på denna array kan beräknas från SizeData-fältet. Dessa data KAN användas för att rendera en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

