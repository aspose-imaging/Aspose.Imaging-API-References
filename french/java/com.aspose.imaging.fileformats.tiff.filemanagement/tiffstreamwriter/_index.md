---
title: "TiffStreamWriter"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'écrivain de flux Tiff."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

L'écrivain de flux Tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | Initialise une nouvelle instance de la classe `TiffStreamWriter`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |
| [getPosition()](#getPosition--) | Obtient ou définit la position du flux. |
| [setPosition(long value)](#setPosition-long-) | Obtient ou définit la position du flux. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Écrit les données spécifiées. |
| [write(byte[] data)](#write-byte---) | Écrit les données spécifiées. |
| [writeDouble(double data)](#writeDouble-double-) | Écrit une valeur double unique dans le flux. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Écrit un tableau de valeurs double dans le flux. |
| [writeFloat(float data)](#writeFloat-float-) | Écrit une valeur float unique dans le flux. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Écrit un tableau de valeurs float dans le flux. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | Écrit une valeur de nombre rationnel unique dans le flux. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Écrit une valeur de nombre rationnel signé unique dans le flux. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | Écrit un tableau de valeurs de nombres rationnels non signés dans le flux. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Écrit un tableau de valeurs de nombres rationnels signés dans le flux. |
| [writeSByte(byte data)](#writeSByte-byte-) | Écrit une valeur d'octet signé unique dans le flux. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Écrit un tableau de valeurs d'octets signés dans le flux. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | Écrit un tableau de valeurs entières dans le flux. |
| [writeSShort(short data)](#writeSShort-short-) | Écrit une valeur short unique dans le flux. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Écrit un tableau de valeurs short dans le flux. |
| [writeSInt(int data)](#writeSInt-int-) | Écrit une valeur integer unique dans le flux. |
| [writeUByte(byte data)](#writeUByte-byte-) | Écrit une valeur byte unique dans le flux. |
| [writeUInt(long data)](#writeUInt-long-) | Écrit une valeur unsigned integer unique dans le flux. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | Écrit un tableau de valeurs unsigned integer dans le flux. |
| [writeUShort(int data)](#writeUShort-int-) | Écrit une valeur unsigned short unique dans le flux. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Écrit un tableau de valeurs unsigned short dans le flux. |
| [writeSLong(long data)](#writeSLong-long-) | Écrit un tableau de valeurs signed long dans le flux. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | Écrit un tableau de valeurs signed long dans le flux. |
| [writeULong(long data)](#writeULong-long-) | Écrit un tableau de valeurs unsigned long dans le flux. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Écrit un tableau de valeurs unsigned long dans le flux. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Initialise une nouvelle instance de la classe `TiffStreamWriter`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le rédacteur de flux. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.

Valeur : L'objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtient ou définit la position du flux.

Valeur: la position du flux.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Obtient ou définit la position du flux.

Valeur: la position du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Écrit les données spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données à écrire. |
| offset | int | Le décalage des données. |
| dataLength | int | Longueur des données à écrire. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Écrit les données spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données à écrire. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Écrit une valeur double unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | double | La valeur à écrire. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Écrit un tableau de valeurs double dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | double[] | Le tableau à écrire. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Écrit une valeur float unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | float | La valeur à écrire. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Écrit un tableau de valeurs float dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | float[] | Le tableau à écrire. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Écrit une valeur de nombre rationnel unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La valeur à écrire. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Écrit une valeur de nombre rationnel signé unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | La valeur à écrire. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Écrit un tableau de valeurs de nombres rationnels non signés dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Le tableau à écrire. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Écrit un tableau de valeurs de nombres rationnels signés dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Le tableau à écrire. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Écrit une valeur d'octet signé unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte | La valeur à écrire. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Écrit un tableau de valeurs d'octets signés dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Le tableau à écrire. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


Écrit un tableau de valeurs entières dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | int[] | Le tableau à écrire. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Écrit une valeur short unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | short | La valeur à écrire. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Écrit un tableau de valeurs short dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | short[] | Le tableau à écrire. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


Écrit une valeur integer unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | int | La valeur à écrire. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Écrit une valeur byte unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte | La valeur à écrire. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


Écrit une valeur unsigned integer unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | long | La valeur à écrire. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


Écrit un tableau de valeurs unsigned integer dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | long[] | Le tableau à écrire. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Écrit une valeur unsigned short unique dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | int | La valeur à écrire. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Écrit un tableau de valeurs unsigned short dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | int[] | Le tableau à écrire. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


Écrit un tableau de valeurs signed long dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | long | Le tableau à écrire. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


Écrit un tableau de valeurs signed long dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | long[] | Le tableau à écrire. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


Écrit un tableau de valeurs unsigned long dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | long | Le tableau à écrire. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


Écrit un tableau de valeurs unsigned long dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | long[] | Le tableau à écrire. |

