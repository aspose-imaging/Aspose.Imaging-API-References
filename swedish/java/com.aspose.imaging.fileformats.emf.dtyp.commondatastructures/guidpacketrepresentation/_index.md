---
title: "GuidPacketRepresentation"
second_title: "Aspose.Imaging för Java API-referens"
description: "Paketsversionen används inom blockprotokoll."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

Paketversionen används inom blockprotokoll. Följande diagram visar en GUID som en opak sekvens av byte. En GUID, även känd som en UUID, är en 16‑byte struktur avsedd att fungera som en unik identifierare för ett objekt. Det finns tre representationer av en GUID, som beskrivs i följande avsnitt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | Initierar en ny instans av strukturen `GuidPacketRepresentation`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getData1()](#getData1--) | Hämtar eller anger värdet för Data1‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [setData1(int value)](#setData1-int-) | Hämtar eller anger värdet för Data1‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [getData2()](#getData2--) | Hämtar eller anger värdet för Data2‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [setData2(short value)](#setData2-short-) | Hämtar eller anger värdet för Data2‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [getData3()](#getData3--) | Hämtar eller anger värdet för Data3‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [setData3(short value)](#setData3-short-) | Hämtar eller anger värdet för Data3‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [getData4()](#getData4--) | Hämtar eller anger värdet för Data4‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [setData4(long value)](#setData4-long-) | Hämtar eller anger värdet för Data4‑medlemmen (avsnitt 2.3.4) i little-endian byteordning. |
| [toString()](#toString--) | Returnerar en `System.String` som representerar denna instans. |
| [CloneTo(GuidPacketRepresentation that)](#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)](#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
### GuidPacketRepresentation() {#GuidPacketRepresentation--}
```
public GuidPacketRepresentation()
```


### GuidPacketRepresentation(int data1, short data2, short data3, long data4) {#GuidPacketRepresentation-int-short-short-long-}
```
public GuidPacketRepresentation(int data1, short data2, short data3, long data4)
```


Initierar en ny instans av strukturen `GuidPacketRepresentation`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data1 | int | Data1‑värdet. |
| data2 | short | Data2‑värdet. |
| data3 | short | Data3‑värdet. |
| data4 | long | Data4‑värdet. |

### getData1() {#getData1--}
```
public int getData1()
```


Hämtar eller anger värdet för Data1‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Data1‑värdet.

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


Hämtar eller anger värdet för Data1‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Data1‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


Hämtar eller anger värdet för Data2‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Den data2.

**Returns:**
short
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


Hämtar eller anger värdet för Data2‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Den data2.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getData3() {#getData3--}
```
public short getData3()
```


Hämtar eller anger värdet för Data3‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Den data3.

**Returns:**
short
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


Hämtar eller anger värdet för Data3‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Den data3.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getData4() {#getData4--}
```
public long getData4()
```


Hämtar eller anger värdet för Data4‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Den data4.

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


Hämtar eller anger värdet för Data4‑medlemmen (avsnitt 2.3.4) i little-endian byteordning.

Värde: Den data4.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en `System.String` som representerar denna instans.

**Returns:**
java.lang.String - En `System.String` som representerar denna instans.
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### Clone() {#Clone--}
```
public GuidPacketRepresentation Clone()
```




**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
