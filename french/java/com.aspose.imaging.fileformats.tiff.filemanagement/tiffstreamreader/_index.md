---
title: "TiffStreamReader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le flux tiff pour gérer le format de fichier tiff little endian."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

Le flux tiff pour gérer le format de fichier tiff little endian.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initialise une nouvelle instance de la classe `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initialise une nouvelle instance de la classe `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initialise une nouvelle instance de la classe `TiffStreamReader`. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Initialise une nouvelle instance de la classe `TiffStreamReader`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLength()](#getLength--) | Obtient la longueur du lecteur. |
| [getThrowExceptions()](#getThrowExceptions--) | Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement de données incorrect (lecture ou écriture du flux). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement de données incorrect (lecture ou écriture du flux). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Lit un tableau de valeurs d'octet depuis le flux. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Lit un tableau de valeurs d'octet non signé depuis le flux. |
| [readDouble(long position)](#readDouble-long-) | Lit une seule valeur double depuis le flux. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Lit un tableau de valeurs double depuis le flux. |
| [readFloat(long position)](#readFloat-long-) | Lit une seule valeur flottante depuis le flux. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Lit un tableau de valeurs flottantes depuis le flux. |
| [readRational(long position)](#readRational-long-) | Lit une seule valeur de nombre rationnel depuis le flux. |
| [readSRational(long position)](#readSRational-long-) | Lit une seule valeur de nombre rationnel signé depuis le flux. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Lit un tableau de valeurs rationnelles depuis le flux. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Lit un tableau de valeurs rationnelles signées depuis le flux. |
| [readSByte(long position)](#readSByte-long-) | Lit des données d'octet signé depuis le flux. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Lit un tableau de valeurs d'octet signé depuis le flux. |
| [readSInt(long position)](#readSInt-long-) | Lit une valeur d'entier signé depuis le flux. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Lit un tableau de valeurs d'entier signé depuis le flux. |
| [readSShort(long position)](#readSShort-long-) | Lit une valeur short signée depuis le flux. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Lit un tableau de valeurs short signées depuis le flux. |
| [readUInt(long position)](#readUInt-long-) | Lit une valeur d'entier non signé depuis le flux. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Lit un tableau de valeurs d'entier non signé depuis le flux. |
| [readUShort(long position)](#readUShort-long-) | Lit une valeur short non signée depuis le flux. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Lit un tableau de valeurs d'entier non signé depuis le flux. |
| [readLong(long position)](#readLong-long-) | Lit une valeur long non signée depuis le flux. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Lit un tableau de valeurs long depuis le flux. |
| [readULong(long position)](#readULong-long-) | Lit une valeur long non signée depuis le flux. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Lit un tableau de valeurs ulong depuis le flux. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Convertit les données sous-jacentes en conteneur de flux. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initialise une nouvelle instance de la classe `TiffStreamReader`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initialise une nouvelle instance de la classe `TiffStreamReader`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |
| startIndex | int | L'index de départ dans `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initialise une nouvelle instance de la classe `TiffStreamReader`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |
| startIndex | int | L'index de départ dans `data`. |
| dataLength | int | Longueur des données. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initialise une nouvelle instance de la classe `TiffStreamReader`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |

### getLength() {#getLength--}
```
public long getLength()
```


Obtient la longueur du lecteur.

Valeur : la longueur du lecteur.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement de données incorrect (lecture ou écriture du flux).

Valeur : `true` si des exceptions sont levées lors d'un traitement de données incorrect ; sinon, les conditions d'erreur sont ignorées silencieusement.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement de données incorrect (lecture ou écriture du flux).

Valeur : `true` si des exceptions sont levées lors d'un traitement de données incorrect ; sinon, les conditions d'erreur sont ignorées silencieusement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Lit un tableau de valeurs d'octet depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tableau | byte[] | Le tableau à remplir. |
| arrayIndex | int | L'index du tableau où commencer à placer les valeurs. |
| position | long | La position du flux à lire. |
| count | long | Le nombre d'éléments à lire. |

**Returns:**
long - Le tableau de valeurs d'octets.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Lit un tableau de valeurs d'octet non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
byte[] - Le tableau de valeurs d'octets non signés.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Lit une seule valeur double depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
double - La valeur double unique.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Lit un tableau de valeurs double depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
double[] - Le tableau de valeurs doubles.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Lit une seule valeur flottante depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
float - La valeur float unique.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Lit un tableau de valeurs flottantes depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
float[] - Le tableau de valeurs float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Lit une seule valeur de nombre rationnel depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Lit une seule valeur de nombre rationnel signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Lit un tableau de valeurs rationnelles depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Le tableau de valeurs rationnelles.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Lit un tableau de valeurs rationnelles signées depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - Le tableau de valeurs rationnelles signées.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Lit des données d'octet signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
byte - La valeur d'octet signé.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Lit un tableau de valeurs d'octet signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
byte[] - Le tableau de valeurs d'octet signées.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Lit une valeur d'entier signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
int - Une valeur entière signée.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Lit un tableau de valeurs d'entier signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
int[] - Le tableau de valeurs entières signées.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Lit une valeur short signée depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
short - Une valeur short signée.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Lit un tableau de valeurs short signées depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
short[] - Le tableau de valeurs short signées.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Lit une valeur d'entier non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
long - Une valeur entière non signée.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Lit un tableau de valeurs d'entier non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
long[] - Le tableau de valeurs entières non signées.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Lit une valeur short non signée depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
int - Une valeur short non signée.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Lit un tableau de valeurs d'entier non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
int[] - Le tableau de valeurs d'entiers non signés.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Lit une valeur long non signée depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
long - Une valeur short non signée.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Lit un tableau de valeurs long depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
long[] - Le tableau d'ulong.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Lit une valeur long non signée depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
long - Une valeur short non signée.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Lit un tableau de valeurs ulong depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
long[] - Le tableau d'ulong.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Convertit les données sous-jacentes en conteneur de flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startPosition | long | La position de départ à partir de laquelle commencer la conversion. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
