---
title: "TiffStreamReader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der tiff-Stream zur Verarbeitung des Little-Endian-tiff-Dateiformats."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

Der tiff-Stream zur Verarbeitung des Little-Endian-tiff-Dateiformats.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLength()](#getLength--) | Ermittelt die Länge des Lesers. |
| [getThrowExceptions()](#getThrowExceptions--) | Liest oder setzt einen Wert, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Liest oder setzt einen Wert, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden. |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Liest ein Array von Byte-Werten aus dem Stream. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream. |
| [readDouble(long position)](#readDouble-long-) | Liest einen einzelnen Double-Wert aus dem Stream. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Liest ein Array von Double-Werten aus dem Stream. |
| [readFloat(long position)](#readFloat-long-) | Liest einen einzelnen Float-Wert aus dem Stream. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Liest ein Array von Float-Werten aus dem Stream. |
| [readRational(long position)](#readRational-long-) | Liest einen einzelnen rationalen Zahlenwert aus dem Stream. |
| [readSRational(long position)](#readSRational-long-) | Liest einen einzelnen vorzeichenbehafteten rationalen Zahlenwert aus dem Stream. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Liest ein Array von rationalen Werten aus dem Stream. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Liest ein Array von vorzeichenbehafteten rationalen Werten aus dem Stream. |
| [readSByte(long position)](#readSByte-long-) | Liest vorzeichenbehaftete Byte-Daten aus dem Stream. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Liest ein Array von vorzeichenbehafteten Byte-Werten aus dem Stream. |
| [readSInt(long position)](#readSInt-long-) | Liest einen vorzeichenbehafteten Ganzzahlwert aus dem Stream. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Liest ein Array von vorzeichenbehafteten Ganzzahlwerten aus dem Stream. |
| [readSShort(long position)](#readSShort-long-) | Liest einen vorzeichenbehafteten Short-Wert aus dem Stream. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Liest ein Array von vorzeichenbehafteten Short-Werten aus dem Stream. |
| [readUInt(long position)](#readUInt-long-) | Liest einen vorzeichenlosen Ganzzahlwert aus dem Stream. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream. |
| [readUShort(long position)](#readUShort-long-) | Liest einen vorzeichenlosen Short-Wert aus dem Stream. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream. |
| [readLong(long position)](#readLong-long-) | Liest einen vorzeichenlosen Long-Wert aus dem Stream. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Liest ein Array von Long-Werten aus dem Stream. |
| [readULong(long position)](#readULong-long-) | Liest einen vorzeichenlosen Long-Wert aus dem Stream. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Liest ein Array von ulong-Werten aus dem Stream. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Konvertiert die zugrunde liegenden Daten in den Stream-Container. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |
| startIndex | int | Der Startindex in `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |
| startIndex | int | Der Startindex in `data`. |
| dataLength | int | Länge der Daten. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initialisiert eine neue Instanz der `TiffStreamReader`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |

### getLength() {#getLength--}
```
public long getLength()
```


Ermittelt die Länge des Lesers.

Wert: Die Leselänge.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Liest oder setzt einen Wert, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden.

Wert: `true` wenn Ausnahmen bei falscher Datenverarbeitung ausgelöst werden; andernfalls werden die Fehlbedingungen stillschweigend ignoriert.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden.

Wert: `true` wenn Ausnahmen bei falscher Datenverarbeitung ausgelöst werden; andernfalls werden die Fehlbedingungen stillschweigend ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Liest ein Array von Byte-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Array | byte[] | Das Array zum Befüllen. |
| `arrayIndex` | int | Der Array-Index, ab dem Werte eingefügt werden sollen. |
| Position | long | Die Stream-Position, von der gelesen wird. |
| count | long | Die Anzahl der zu lesenden Elemente. |

**Returns:**
long - Das Array von Byte-Werten.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
byte[] - Das Array von vorzeichenlosen Byte-Werten.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Liest einen einzelnen Double-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
double - Der einzelne double-Wert.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Liest ein Array von Double-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
double[] - Das Array von double-Werten.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Liest einen einzelnen Float-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
float - Der einzelne float-Wert.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Liest ein Array von Float-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
float[] - Das Array von float-Werten.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Liest einen einzelnen rationalen Zahlenwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Liest einen einzelnen vorzeichenbehafteten rationalen Zahlenwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Liest ein Array von rationalen Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Das Array von rationalen Werten.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Liest ein Array von vorzeichenbehafteten rationalen Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - Das Array von vorzeichenbehafteten rationalen Werten.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Liest vorzeichenbehaftete Byte-Daten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
byte - Der vorzeichenbehaftete Byte-Wert.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Liest ein Array von vorzeichenbehafteten Byte-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
byte[] - Das Array von vorzeichenbehafteten Byte-Werten.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Liest einen vorzeichenbehafteten Ganzzahlwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
int - Ein vorzeichenbehafteter Ganzzahlwert.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Liest ein Array von vorzeichenbehafteten Ganzzahlwerten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
int[] - Das Array von vorzeichenbehafteten Ganzzahlwerten.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Liest einen vorzeichenbehafteten Short-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
short - Ein vorzeichenbehafteter Short-Wert.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Liest ein Array von vorzeichenbehafteten Short-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
short[] - Das Array von vorzeichenbehafteten Short-Werten.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Liest einen vorzeichenlosen Ganzzahlwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
long - Ein vorzeichenloser Ganzzahlwert.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
long[] - Das Array von vorzeichenlosen Ganzzahlwerten.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Liest einen vorzeichenlosen Short-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
int - Ein unsigned short-Wert.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
int[] - Das Array von unsigned integer-Werten.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Liest einen vorzeichenlosen Long-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
long - Ein unsigned short-Wert.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Liest ein Array von Long-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
long[] - Das ulong-Array.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Liest einen vorzeichenlosen Long-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |

**Returns:**
long - Ein unsigned short-Wert.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Liest ein Array von ulong-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
long[] - Das ulong-Array.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Konvertiert die zugrunde liegenden Daten in den Stream-Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startPosition | long | Die Startposition, von der die Konvertierung beginnt. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
