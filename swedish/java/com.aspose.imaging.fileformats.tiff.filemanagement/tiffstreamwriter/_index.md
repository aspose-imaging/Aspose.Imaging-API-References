---
title: "TiffStreamWriter"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tiff‑strömskrivaren."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

Tiff‑strömskrivaren.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | Initierar en ny instans av klassen `TiffStreamWriter`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
| [getPosition()](#getPosition--) | Hämtar eller sätter strömmens position. |
| [setPosition(long value)](#setPosition-long-) | Hämtar eller sätter strömmens position. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Skriver den angivna datan. |
| [write(byte[] data)](#write-byte---) | Skriver den angivna datan. |
| [writeDouble(double data)](#writeDouble-double-) | Skriver ett enda dubbelvärde till strömmen. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Skriver en array av dubbelvärden till strömmen. |
| [writeFloat(float data)](#writeFloat-float-) | Skriver ett enda flyttal till strömmen. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Skriver en array av flyttal till strömmen. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | Skriver ett enda rationellt talvärde till strömmen. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Skriver ett enda signerat rationellt talvärde till strömmen. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | Skriver en array av osignerade rationella värden till strömmen. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Skriver en array av signerade rationella värden till strömmen. |
| [writeSByte(byte data)](#writeSByte-byte-) | Skriver ett enda signerat bytevärde till strömmen. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Skriver en array av signerade bytevärden till strömmen. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | Skriver en array av heltalsvärden till strömmen. |
| [writeSShort(short data)](#writeSShort-short-) | Skriver ett enda short‑värde till strömmen. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Skriver en array av short‑värden till strömmen. |
| [writeSInt(int data)](#writeSInt-int-) | Skriver ett enda heltalsvärde till strömmen. |
| [writeUByte(byte data)](#writeUByte-byte-) | Skriver ett enda bytevärde till strömmen. |
| [writeUInt(long data)](#writeUInt-long-) | Skriver ett enda osignerat heltalsvärde till strömmen. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | Skriver en array av osignerade heltalsvärden till strömmen. |
| [writeUShort(int data)](#writeUShort-int-) | Skriver ett enda osignerat short‑värde till strömmen. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Skriver en array av osignerade short‑värden till strömmen. |
| [writeSLong(long data)](#writeSLong-long-) | Skriver en array av signerade long‑värden till strömmen. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | Skriver en array av signerade long‑värden till strömmen. |
| [writeULong(long data)](#writeULong-long-) | Skriver en array av osignerade long‑värden till strömmen. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Skriver en array av osignerade long‑värden till strömmen. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Initierar en ny instans av klassen `TiffStreamWriter`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömmen skrivare. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen.

Värde: Objektet som kan användas för att synkronisera åtkomst till den synkroniserade resursen.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Hämtar eller sätter strömmens position.

Värde: Strömmens position.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Hämtar eller sätter strömmens position.

Värde: Strömmens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Skriver den angivna datan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Datan att skriva. |
| offset | int | Dataoffseten. |
| dataLength | int | Längd på data att skriva. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Skriver den angivna datan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Datan att skriva. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Skriver ett enda dubbelvärde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | double | Värdet att skriva. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Skriver en array av dubbelvärden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | double[] | Arrayen att skriva. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Skriver ett enda flyttal till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | float | Värdet att skriva. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Skriver en array av flyttal till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | float[] | Arrayen att skriva. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Skriver ett enda rationellt talvärde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Värdet att skriva. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Skriver ett enda signerat rationellt talvärde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Värdet att skriva. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Skriver en array av osignerade rationella värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Arrayen att skriva. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Skriver en array av signerade rationella värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Arrayen att skriva. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Skriver ett enda signerat bytevärde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte | Värdet att skriva. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Skriver en array av signerade bytevärden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Arrayen att skriva. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


Skriver en array av heltalsvärden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | int[] | Arrayen att skriva. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Skriver ett enda short‑värde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | short | Värdet att skriva. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Skriver en array av short‑värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | short[] | Arrayen att skriva. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


Skriver ett enda heltalsvärde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | int | Värdet att skriva. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Skriver ett enda bytevärde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte | Värdet att skriva. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


Skriver ett enda osignerat heltalsvärde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | long | Värdet att skriva. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


Skriver en array av osignerade heltalsvärden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | long[] | Arrayen att skriva. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Skriver ett enda osignerat short‑värde till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | int | Värdet att skriva. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Skriver en array av osignerade short‑värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | int[] | Arrayen att skriva. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


Skriver en array av signerade long‑värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | long | Arrayen att skriva. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


Skriver en array av signerade long‑värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | long[] | Arrayen att skriva. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


Skriver en array av osignerade long‑värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | long | Arrayen att skriva. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


Skriver en array av osignerade long‑värden till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | long[] | Arrayen att skriva. |

