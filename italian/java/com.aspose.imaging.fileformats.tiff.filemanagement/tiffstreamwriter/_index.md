---
title: "TiffStreamWriter"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Lo scrittore di flusso Tiff."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

Lo scrittore di flusso Tiff.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | Inizializza una nuova istanza della classe `TiffStreamWriter`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
| [getPosition()](#getPosition--) | Ottiene o imposta la posizione del flusso. |
| [setPosition(long value)](#setPosition-long-) | Ottiene o imposta la posizione del flusso. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Scrive i dati specificati. |
| [write(byte[] data)](#write-byte---) | Scrive i dati specificati. |
| [writeDouble(double data)](#writeDouble-double-) | Scrive un singolo valore double nel flusso. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Scrive un array di valori double nel flusso. |
| [writeFloat(float data)](#writeFloat-float-) | Scrive un singolo valore float nel flusso. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Scrive un array di valori float nel flusso. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | Scrive un singolo valore di numero razionale nello stream. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Scrive un singolo valore di numero razionale con segno nello stream. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | Scrive un array di valori razionali senza segno nello stream. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Scrive un array di valori razionali con segno nello stream. |
| [writeSByte(byte data)](#writeSByte-byte-) | Scrive un singolo valore di byte con segno nello stream. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Scrive un array di valori di byte con segno nello stream. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | Scrive un array di valori interi nello stream. |
| [writeSShort(short data)](#writeSShort-short-) | Scrive un singolo valore short nello stream. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Scrive un array di valori short nello stream. |
| [writeSInt(int data)](#writeSInt-int-) | Scrive un singolo valore intero nello stream. |
| [writeUByte(byte data)](#writeUByte-byte-) | Scrive un singolo valore byte nello stream. |
| [writeUInt(long data)](#writeUInt-long-) | Scrive un singolo valore intero senza segno nello stream. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | Scrive un array di valori interi senza segno nello stream. |
| [writeUShort(int data)](#writeUShort-int-) | Scrive un singolo valore short senza segno nello stream. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Scrive un array di valori short senza segno nello stream. |
| [writeSLong(long data)](#writeSLong-long-) | Scrive un array di valori long con segno nello stream. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | Scrive un array di valori long con segno nello stream. |
| [writeULong(long data)](#writeULong-long-) | Scrive un array di valori long senza segno nello stream. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Scrive un array di valori long senza segno nello stream. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Inizializza una nuova istanza della classe `TiffStreamWriter`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il writer dello stream. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

Valore: L'oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Ottiene o imposta la posizione del flusso.

Valore: La posizione dello stream.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Ottiene o imposta la posizione del flusso.

Valore: La posizione dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Scrive i dati specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati da scrivere. |
| offset | int | L'offset dei dati. |
| dataLength | int | Lunghezza dei dati da scrivere. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Scrive i dati specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati da scrivere. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Scrive un singolo valore double nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | double | Il valore da scrivere. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Scrive un array di valori double nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | double[] | L'array da scrivere. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Scrive un singolo valore float nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | float | Il valore da scrivere. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Scrive un array di valori float nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | float[] | L'array da scrivere. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Scrive un singolo valore di numero razionale nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Il valore da scrivere. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Scrive un singolo valore di numero razionale con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Il valore da scrivere. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Scrive un array di valori razionali senza segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | L'array da scrivere. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Scrive un array di valori razionali con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | L'array da scrivere. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Scrive un singolo valore di byte con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte | Il valore da scrivere. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Scrive un array di valori di byte con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | L'array da scrivere. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


Scrive un array di valori interi nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int[] | L'array da scrivere. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Scrive un singolo valore short nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | short | Il valore da scrivere. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Scrive un array di valori short nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | short[] | L'array da scrivere. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


Scrive un singolo valore intero nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int | Il valore da scrivere. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Scrive un singolo valore byte nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte | Il valore da scrivere. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


Scrive un singolo valore intero senza segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long | Il valore da scrivere. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


Scrive un array di valori interi senza segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long[] | L'array da scrivere. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Scrive un singolo valore short senza segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int | Il valore da scrivere. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Scrive un array di valori short senza segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int[] | L'array da scrivere. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


Scrive un array di valori long con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long | L'array da scrivere. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


Scrive un array di valori long con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long[] | L'array da scrivere. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


Scrive un array di valori long senza segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long | L'array da scrivere. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


Scrive un array di valori long senza segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long[] | L'array da scrivere. |

