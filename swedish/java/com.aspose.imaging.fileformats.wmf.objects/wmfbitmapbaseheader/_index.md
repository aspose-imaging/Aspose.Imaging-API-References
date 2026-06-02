---
title: "WmfBitmapBaseHeader"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den grundläggande bitmap-headerklassen."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

Den grundläggande bitmap-headerklassen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Hämtar eller anger ett 32‑bit osignerat heltal som definierar storleken på detta objekt, i byte. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Hämtar eller anger ett 32‑bit osignerat heltal som definierar storleken på detta objekt, i byte. |
| [getPlanes()](#getPlanes--) | Hämtar eller anger ett 16‑bit osignerat heltal som definierar antalet `planes` för mål‑enheten. |
| [setPlanes(short value)](#setPlanes-short-) | Hämtar eller anger ett 16‑bit osignerat heltal som definierar antalet `planes` för mål‑enheten. |
| [getBitCount()](#getBitCount--) | Hämtar eller anger ett 16‑bit osignerat heltal som definierar formatet för varje pixel och det maximala antalet färger i DIB. |
| [setBitCount(short value)](#setBitCount-short-) | Hämtar eller anger ett 16‑bit osignerat heltal som definierar formatet för varje pixel och det maximala antalet färger i DIB. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Hämtar eller anger ett 32‑bit osignerat heltal som definierar storleken på detta objekt, i byte.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Hämtar eller anger ett 32‑bit osignerat heltal som definierar storleken på detta objekt, i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | ett 16‑bit osignerat heltal som definierar antalet `planes` för mål‑enheten. Detta värde MÅSTE vara 0x0001. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Hämtar eller anger ett 16‑bitars osignerat heltal som definierar antalet `planes` för mål‑enheten. Detta värde MÅSTE vara 0x0001.

**Returns:**
short – ett 16‑bitars osignerat heltal som definierar antalet `planes` för mål‑enheten.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Hämtar eller anger ett 16‑bitars osignerat heltal som definierar antalet `planes` för mål‑enheten. Detta värde MÅSTE vara 0x0001.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | ett 16‑bitars osignerat heltal som definierar antalet `planes` för mål‑enheten. Detta värde MÅSTE vara \* 0x0001. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Hämtar eller anger ett 16‑bitars osignerat heltal som definierar formatet för varje pixel och det maximala antalet färger i DIB. Detta värde MÅSTE finnas i `BitCount`‑enumerationen (avsnitt 2.1.1.3).

**Returns:**
short – ett 16‑bitars osignerat heltal som definierar formatet för varje pixel och det maximala antalet färger i DIB.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Hämtar eller anger ett 16‑bitars osignerat heltal som definierar formatet för varje pixel och det maximala antalet färger i DIB. Detta värde MÅSTE finnas i `BitCount`‑enumerationen (avsnitt 2.1.1.3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | ett 16‑bitars osignerat heltal som definierar formatet för varje pixel och det maximala antalet färger i DIB. |

