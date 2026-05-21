---
title: "TiffStreamWriter"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Tiff-Stream-Schreiber."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

Der Tiff-Stream-Schreiber.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | Initialisiert eine neue Instanz der `TiffStreamWriter` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Liefert ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
| [getPosition()](#getPosition--) | Liest oder setzt die Stream-Position. |
| [setPosition(long value)](#setPosition-long-) | Liest oder setzt die Stream-Position. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Schreibt die angegebenen Daten. |
| [write(byte[] data)](#write-byte---) | Schreibt die angegebenen Daten. |
| [writeDouble(double data)](#writeDouble-double-) | Schreibt einen einzelnen double-Wert in den Stream. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Schreibt ein Array von double-Werten in den Stream. |
| [writeFloat(float data)](#writeFloat-float-) | Schreibt einen einzelnen float-Wert in den Stream. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Schreibt ein Array von float-Werten in den Stream. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | Schreibt einen einzelnen rationalen Zahlenwert in den Stream. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Schreibt einen einzelnen signierten rationalen Zahlenwert in den Stream. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | Schreibt ein Array von vorzeichenlosen rationalen Werten in den Stream. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Schreibt ein Array von signierten rationalen Werten in den Stream. |
| [writeSByte(byte data)](#writeSByte-byte-) | Schreibt einen einzelnen signierten Byte-Wert in den Stream. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Schreibt ein Array von signierten Byte-Werten in den Stream. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | Schreibt ein Array von Ganzzahlwerten in den Stream. |
| [writeSShort(short data)](#writeSShort-short-) | Schreibt einen einzelnen Short-Wert in den Stream. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Schreibt ein Array von Short-Werten in den Stream. |
| [writeSInt(int data)](#writeSInt-int-) | Schreibt einen einzelnen Ganzzahlwert in den Stream. |
| [writeUByte(byte data)](#writeUByte-byte-) | Schreibt einen einzelnen Byte-Wert in den Stream. |
| [writeUInt(long data)](#writeUInt-long-) | Schreibt einen einzelnen vorzeichenlosen Ganzzahlwert in den Stream. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | Schreibt ein Array von vorzeichenlosen Ganzzahlwerten in den Stream. |
| [writeUShort(int data)](#writeUShort-int-) | Schreibt einen einzelnen vorzeichenlosen Short-Wert in den Stream. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Schreibt ein Array von vorzeichenlosen Short-Werten in den Stream. |
| [writeSLong(long data)](#writeSLong-long-) | Schreibt ein Array von signierten Long-Werten in den Stream. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | Schreibt ein Array von signierten Long-Werten in den Stream. |
| [writeULong(long data)](#writeULong-long-) | Schreibt ein Array von vorzeichenlosen Long-Werten in den Stream. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Schreibt ein Array von vorzeichenlosen Long-Werten in den Stream. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Initialisiert eine neue Instanz der `TiffStreamWriter` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Writer. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Liefert ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

Wert: Das Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Liest oder setzt die Stream-Position.

Wert: Die Stream-Position.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Liest oder setzt die Stream-Position.

Wert: Die Stream-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Schreibt die angegebenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die zu schreibenden Daten. |
| offset | int | Der Datenoffset. |
| dataLength | int | Länge der zu schreibenden Daten. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Schreibt die angegebenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die zu schreibenden Daten. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Schreibt einen einzelnen double-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | double | Der zu schreibende Wert. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Schreibt ein Array von double-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | double[] | Das zu schreibende Array. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Schreibt einen einzelnen float-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | float | Der zu schreibende Wert. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Schreibt ein Array von float-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | float[] | Das zu schreibende Array. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Schreibt einen einzelnen rationalen Zahlenwert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Der zu schreibende Wert. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Schreibt einen einzelnen signierten rationalen Zahlenwert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Der zu schreibende Wert. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Schreibt ein Array von vorzeichenlosen rationalen Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Das zu schreibende Array. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Schreibt ein Array von signierten rationalen Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Das zu schreibende Array. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Schreibt einen einzelnen signierten Byte-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte | Der zu schreibende Wert. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Schreibt ein Array von signierten Byte-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Das zu schreibende Array. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


Schreibt ein Array von Ganzzahlwerten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int[] | Das zu schreibende Array. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Schreibt einen einzelnen Short-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | short | Der zu schreibende Wert. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Schreibt ein Array von Short-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | short[] | Das zu schreibende Array. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


Schreibt einen einzelnen Ganzzahlwert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int | Der zu schreibende Wert. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Schreibt einen einzelnen Byte-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte | Der zu schreibende Wert. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


Schreibt einen einzelnen vorzeichenlosen Ganzzahlwert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long | Der zu schreibende Wert. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


Schreibt ein Array von vorzeichenlosen Ganzzahlwerten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long[] | Das zu schreibende Array. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Schreibt einen einzelnen vorzeichenlosen Short-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int | Der zu schreibende Wert. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Schreibt ein Array von vorzeichenlosen Short-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int[] | Das zu schreibende Array. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


Schreibt ein Array von signierten Long-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long | Das zu schreibende Array. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


Schreibt ein Array von signierten Long-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long[] | Das zu schreibende Array. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


Schreibt ein Array von vorzeichenlosen Long-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long | Das zu schreibende Array. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


Schreibt ein Array von vorzeichenlosen Long-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long[] | Das zu schreibende Array. |

