---
title: "TiffStreamReader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il flusso tiff per gestire il formato di file tiff little endian."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

Il flusso tiff per gestire il formato di file tiff little endian.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Inizializza una nuova istanza della classe `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Inizializza una nuova istanza della classe `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Inizializza una nuova istanza della classe `TiffStreamReader`. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Inizializza una nuova istanza della classe `TiffStreamReader`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLength()](#getLength--) | Ottiene la lunghezza del lettore. |
| [getThrowExceptions()](#getThrowExceptions--) | Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Legge un array di valori byte dallo stream. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Legge un array di valori byte senza segno dallo stream. |
| [readDouble(long position)](#readDouble-long-) | Legge un singolo valore double dallo stream. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Legge un array di valori double dallo stream. |
| [readFloat(long position)](#readFloat-long-) | Legge un singolo valore float dallo stream. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Legge un array di valori float dallo stream. |
| [readRational(long position)](#readRational-long-) | Legge un singolo valore di numero razionale dallo stream. |
| [readSRational(long position)](#readSRational-long-) | Legge un singolo valore di numero razionale con segno dallo stream. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Legge un array di valori razionali dallo stream. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Legge un array di valori razionali con segno dallo stream. |
| [readSByte(long position)](#readSByte-long-) | Legge dati byte con segno dallo stream. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Legge un array di valori byte con segno dallo stream. |
| [readSInt(long position)](#readSInt-long-) | Legge un valore intero con segno dallo stream. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Legge un array di valori interi con segno dallo stream. |
| [readSShort(long position)](#readSShort-long-) | Legge un valore short con segno dallo stream. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Legge un array di valori short con segno dallo stream. |
| [readUInt(long position)](#readUInt-long-) | Legge un valore intero senza segno dallo stream. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Legge un array di valori interi senza segno dallo stream. |
| [readUShort(long position)](#readUShort-long-) | Legge un valore short senza segno dallo stream. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Legge un array di valori interi senza segno dallo stream. |
| [readLong(long position)](#readLong-long-) | Legge un valore long senza segno dallo stream. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Legge un array di valori long dallo stream. |
| [readULong(long position)](#readULong-long-) | Legge un valore long senza segno dallo stream. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Legge un array di valori ulong dallo stream. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Converte i dati sottostanti nel contenitore dello stream. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Inizializza una nuova istanza della classe `TiffStreamReader`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati dell'array di byte. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Inizializza una nuova istanza della classe `TiffStreamReader`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati dell'array di byte. |
| startIndex | int | L'indice iniziale in `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Inizializza una nuova istanza della classe `TiffStreamReader`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati dell'array di byte. |
| startIndex | int | L'indice iniziale in `data`. |
| dataLength | int | Lunghezza dei dati. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Inizializza una nuova istanza della classe `TiffStreamReader`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore dello stream. |

### getLength() {#getLength--}
```
public long getLength()
```


Ottiene la lunghezza del lettore.

Valore: la lunghezza del lettore.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream).

Valore: `true` se le eccezioni vengono generate durante l'elaborazione di dati errati; altrimenti, le condizioni di errore vengono ignorate silenziosamente.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream).

Valore: `true` se le eccezioni vengono generate durante l'elaborazione di dati errati; altrimenti, le condizioni di errore vengono ignorate silenziosamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Legge un array di valori byte dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | byte[] | L'array da riempire. |
| arrayIndex | int | L'indice dell'array da cui iniziare a inserire i valori. |
| position | long | La posizione dello stream da cui leggere. |
| count | long | Il conteggio degli elementi da leggere. |

**Returns:**
long - L'array di valori byte.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Legge un array di valori byte senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
byte[] - L'array di valori byte senza segno.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Legge un singolo valore double dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
double - Il singolo valore double.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Legge un array di valori double dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
double[] - L'array di valori double.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Legge un singolo valore float dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
float - Il singolo valore float.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Legge un array di valori float dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
float[] - L'array di valori float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Legge un singolo valore di numero razionale dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Legge un singolo valore di numero razionale con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Legge un array di valori razionali dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - L'array di valori razionali.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Legge un array di valori razionali con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - L'array di valori razionali con segno.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Legge dati byte con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
byte - Il valore byte con segno.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Legge un array di valori byte con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
byte[] - L'array di valori byte con segno.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Legge un valore intero con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
int - Un valore intero con segno.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Legge un array di valori interi con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
int[] - L'array di valori interi con segno.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Legge un valore short con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
short - Un valore short con segno.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Legge un array di valori short con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
short[] - L'array di valori short con segno.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Legge un valore intero senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
long - Un valore intero senza segno.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Legge un array di valori interi senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
long[] - L'array di valori interi senza segno.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Legge un valore short senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
int - Un valore short senza segno.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Legge un array di valori interi senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
int[] - L'array di valori interi senza segno.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Legge un valore long senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
long - Un valore short senza segno.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Legge un array di valori long dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
long[] - L'array ulong.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Legge un valore long senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
long - Un valore short senza segno.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Legge un array di valori ulong dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
long[] - L'array ulong.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Converte i dati sottostanti nel contenitore dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startPosition | long | La posizione di inizio da cui avviare la conversione. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
