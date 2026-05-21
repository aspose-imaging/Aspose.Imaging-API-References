---
title: "TiffStreamWriter"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El escritor de flujo Tiff."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

El escritor de flujo Tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | Inicializa una nueva instancia de la clase `TiffStreamWriter`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
| [getPosition()](#getPosition--) | Obtiene o establece la posición del flujo. |
| [setPosition(long value)](#setPosition-long-) | Obtiene o establece la posición del flujo. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Escribe los datos especificados. |
| [write(byte[] data)](#write-byte---) | Escribe los datos especificados. |
| [writeDouble(double data)](#writeDouble-double-) | Escribe un solo valor double al flujo. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Escribe una matriz de valores double al flujo. |
| [writeFloat(float data)](#writeFloat-float-) | Escribe un solo valor float al flujo. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Escribe una matriz de valores float al flujo. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | Escribe un único valor de número racional al flujo. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Escribe un único valor de número racional con signo al flujo. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | Escribe una matriz de valores racionales sin signo al flujo. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Escribe una matriz de valores racionales con signo al flujo. |
| [writeSByte(byte data)](#writeSByte-byte-) | Escribe un único valor de byte con signo al flujo. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Escribe una matriz de valores de byte con signo al flujo. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | Escribe una matriz de valores enteros al flujo. |
| [writeSShort(short data)](#writeSShort-short-) | Escribe un único valor short al flujo. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Escribe una matriz de valores short al flujo. |
| [writeSInt(int data)](#writeSInt-int-) | Escribe un único valor entero al flujo. |
| [writeUByte(byte data)](#writeUByte-byte-) | Escribe un único valor de byte al flujo. |
| [writeUInt(long data)](#writeUInt-long-) | Escribe un único valor entero sin signo al flujo. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | Escribe una matriz de valores enteros sin signo al flujo. |
| [writeUShort(int data)](#writeUShort-int-) | Escribe un único valor short sin signo al flujo. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Escribe una matriz de valores short sin signo al flujo. |
| [writeSLong(long data)](#writeSLong-long-) | Escribe una matriz de valores long con signo al flujo. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | Escribe una matriz de valores long con signo al flujo. |
| [writeULong(long data)](#writeULong-long-) | Escribe una matriz de valores long sin signo al flujo. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Escribe una matriz de valores long sin signo al flujo. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Inicializa una nueva instancia de la clase `TiffStreamWriter`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El escritor del flujo. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado.

Valor: El objeto que puede usarse para sincronizar el acceso al recurso sincronizado.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtiene o establece la posición del flujo.

Valor: La posición del flujo.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Obtiene o establece la posición del flujo.

Valor: La posición del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Escribe los datos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos a escribir. |
| offset | int | El desplazamiento de los datos. |
| dataLength | int | Longitud de los datos a escribir. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Escribe los datos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos a escribir. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Escribe un solo valor double al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | double | El valor a escribir. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Escribe una matriz de valores double al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | double[] | La matriz a escribir. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Escribe un solo valor float al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | float | El valor a escribir. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Escribe una matriz de valores float al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | float[] | La matriz a escribir. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Escribe un único valor de número racional al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | El valor a escribir. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Escribe un único valor de número racional con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | El valor a escribir. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Escribe una matriz de valores racionales sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La matriz a escribir. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Escribe una matriz de valores racionales con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | La matriz a escribir. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Escribe un único valor de byte con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte | El valor a escribir. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Escribe una matriz de valores de byte con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | La matriz a escribir. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


Escribe una matriz de valores enteros al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | int[] | La matriz a escribir. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Escribe un único valor short al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | short | El valor a escribir. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Escribe una matriz de valores short al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | short[] | La matriz a escribir. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


Escribe un único valor entero al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | int | El valor a escribir. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Escribe un único valor de byte al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte | El valor a escribir. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


Escribe un único valor entero sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | long | El valor a escribir. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


Escribe una matriz de valores enteros sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | long[] | La matriz a escribir. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Escribe un único valor short sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | int | El valor a escribir. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Escribe una matriz de valores short sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | int[] | La matriz a escribir. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


Escribe una matriz de valores long con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | long | La matriz a escribir. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


Escribe una matriz de valores long con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | long[] | La matriz a escribir. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


Escribe una matriz de valores long sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | long | La matriz a escribir. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


Escribe una matriz de valores long sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | long[] | La matriz a escribir. |

