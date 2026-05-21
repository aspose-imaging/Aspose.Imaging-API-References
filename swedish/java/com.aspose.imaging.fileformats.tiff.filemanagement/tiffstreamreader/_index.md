---
title: "TiffStreamReader"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tiff‑strömmen för att hantera little endian tiff‑filformatet."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

Tiff‑strömmen för att hantera little endian tiff‑filformatet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initierar en ny instans av klassen `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initierar en ny instans av klassen `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initierar en ny instans av klassen `TiffStreamReader`. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Initierar en ny instans av klassen `TiffStreamReader`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLength()](#getLength--) | Hämtar läsarens längd. |
| [getThrowExceptions()](#getThrowExceptions--) | Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till ström). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till ström). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Läser en array av bytevärden från strömmen. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Läser en array av osignerade bytevärden från strömmen. |
| [readDouble(long position)](#readDouble-long-) | Läs ett enskilt double‑värde från strömmen. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Läser en array av double‑värden från strömmen. |
| [readFloat(long position)](#readFloat-long-) | Läs ett enskilt float‑värde från strömmen. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Läser en array av float‑värden från strömmen. |
| [readRational(long position)](#readRational-long-) | Läs ett enskilt rationellt talvärde från strömmen. |
| [readSRational(long position)](#readSRational-long-) | Läs ett enskilt signerat rationellt talvärde från strömmen. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Läser en array av rationella värden från strömmen. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Läser en array av signerade rationella värden från strömmen. |
| [readSByte(long position)](#readSByte-long-) | Läser signerad byte‑data från strömmen. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Läser en array av signerade bytevärden från strömmen. |
| [readSInt(long position)](#readSInt-long-) | Läs ett signerat heltalsvärde från strömmen. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Läser en array av signerade heltalsvärden från strömmen. |
| [readSShort(long position)](#readSShort-long-) | Läs ett signerat short‑värde från strömmen. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Läser en array av signerade short‑värden från strömmen. |
| [readUInt(long position)](#readUInt-long-) | Läs ett osignerat heltalsvärde från strömmen. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Läser en array av osignerade heltalsvärden från strömmen. |
| [readUShort(long position)](#readUShort-long-) | Läs ett osignerat short‑värde från strömmen. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Läser en array av osignerade heltalsvärden från strömmen. |
| [readLong(long position)](#readLong-long-) | Läs ett osignerat long‑värde från strömmen. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Läser en array av long‑värden från strömmen. |
| [readULong(long position)](#readULong-long-) | Läs ett osignerat long‑värde från strömmen. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Läser en array av ulong‑värden från strömmen. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Konverterar den underliggande datan till strömkontainern. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initierar en ny instans av klassen `TiffStreamReader`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Bytearrayens data. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initierar en ny instans av klassen `TiffStreamReader`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Bytearrayens data. |
| startIndex | int | Startindexet i `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initierar en ny instans av klassen `TiffStreamReader`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Bytearrayens data. |
| startIndex | int | Startindexet i `data`. |
| dataLength | int | Dataens längd. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initierar en ny instans av klassen `TiffStreamReader`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |

### getLength() {#getLength--}
```
public long getLength()
```


Hämtar läsarens längd.

Värde: Läsarens längd.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till ström).

Värde: `true` om undantag kastas vid felaktig databehandling; annars ignoreras felvillkoren tyst.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till ström).

Värde: `true` om undantag kastas vid felaktig databehandling; annars ignoreras felvillkoren tyst.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Läser en array av bytevärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matris | byte[] | Matrisen att fylla. |
| arrayIndex | int | Matrisindexet att börja sätta värden i. |
| position | long | Strömpositionen att läsa från. |
| antal | long | Antalet element att läsa. |

**Returns:**
long - array av bytevärden.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Läser en array av osignerade bytevärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
byte[] - array av osignerade bytevärden.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Läs ett enskilt double‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
double - det enkla double‑värdet.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Läser en array av double‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
double[] - array av double‑värden.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Läs ett enskilt float‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
float - det enkla float‑värdet.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Läser en array av float‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
float[] - array av float‑värden.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Läs ett enskilt rationellt talvärde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Läs ett enskilt signerat rationellt talvärde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Läser en array av rationella värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - array av rationella värden.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Läser en array av signerade rationella värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - array av signerade rationella värden.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Läser signerad byte‑data från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
byte - det signerade byte‑värdet.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Läser en array av signerade bytevärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
byte[] - array av signerade byte‑värden.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Läs ett signerat heltalsvärde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
int - ett signerat heltalsvärde.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Läser en array av signerade heltalsvärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
int[] - array av signerade heltalsvärden.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Läs ett signerat short‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
short - ett signerat short‑värde.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Läser en array av signerade short‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
short[] - array av signerade short‑värden.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Läs ett osignerat heltalsvärde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
long - ett osignerat heltalsvärde.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Läser en array av osignerade heltalsvärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
long[] - array av osignerade heltalsvärden.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Läs ett osignerat short‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
int - Ett osignerat shortvärde.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Läser en array av osignerade heltalsvärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
int[] - Arrayen av osignerade heltalsvärden.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Läs ett osignerat long‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
long - Ett osignerat shortvärde.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Läser en array av long‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
long[] - ulong‑arrayen.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Läs ett osignerat long‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
long - Ett osignerat shortvärde.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Läser en array av ulong‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| antal | long | Antalet element. |

**Returns:**
long[] - ulong‑arrayen.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Konverterar den underliggande datan till strömkontainern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startPosition | long | Startpositionen att börja konverteringen från. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
