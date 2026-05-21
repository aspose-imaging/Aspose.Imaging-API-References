---
title: "EmfFormat"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmrFormat-objektet innehåller information som identifierar formatet för bilddata i en EMR_COMMENT_MULTIFORMATS recordsection 2.3.3.4.3."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

EmrFormat-objektet innehåller information som identifierar formatet för bilddata i en EMR\_COMMENT\_MULTIFORMATS‑post (avsnitt 2.3.3.4.3).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSignature()](#getSignature--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatet för bilddata. |
| [setSignature(int value)](#setSignature-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatet för bilddata. |
| [getVersion()](#getVersion--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatets versionsnummer. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatets versionsnummer. |
| [getSizeData()](#getSizeData--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar storleken på data i byte. |
| [setSizeData(int value)](#setSizeData-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar storleken på data i byte. |
| [getOffData()](#getOffData--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar förskjutningen till data från början av identifierarfältet i en EMR\_COMMENT\_PUBLIC‑post (sektion 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar förskjutningen till data från början av identifierarfältet i en EMR\_COMMENT\_PUBLIC‑post (sektion 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatet för bilddata. Detta värde MÅSTE finnas i FormatSignature‑enumerationen (sektion 2.1.14).

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatet för bilddata. Detta värde MÅSTE finnas i FormatSignature‑enumerationen (sektion 2.1.14).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatets versionsnummer. Om Signature‑fältet specificerar inkapslad PostScript (EPS) måste detta värde vara 0x00000001; annars måste detta värde ignoreras.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar formatets versionsnummer. Om Signature‑fältet specificerar inkapslad PostScript (EPS) måste detta värde vara 0x00000001; annars måste detta värde ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar storleken på data i byte.

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar storleken på data i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar förskjutningen till data från början av identifierarfältet i en EMR\_COMMENT\_PUBLIC‑post (sektion 2.3.3.4). Förskjutningen MÅSTE vara 32-bit justerad.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar förskjutningen till data från början av identifierarfältet i en EMR\_COMMENT\_PUBLIC‑post (sektion 2.3.3.4). Förskjutningen MÅSTE vara 32-bit justerad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

