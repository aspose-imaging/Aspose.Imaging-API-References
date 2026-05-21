---
title: "TiffStreamReader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El flujo tiff para manejar el formato de archivo tiff little endian."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

El flujo tiff para manejar el formato de archivo tiff little endian.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Inicializa una nueva instancia de la clase `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Inicializa una nueva instancia de la clase `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Inicializa una nueva instancia de la clase `TiffStreamReader`. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Inicializa una nueva instancia de la clase `TiffStreamReader`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLength()](#getLength--) | Obtiene la longitud del lector. |
| [getThrowExceptions()](#getThrowExceptions--) | Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Lee una matriz de valores byte del flujo. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Lee una matriz de valores byte sin signo del flujo. |
| [readDouble(long position)](#readDouble-long-) | Lee un único valor double del flujo. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Lee una matriz de valores double del flujo. |
| [readFloat(long position)](#readFloat-long-) | Lee un único valor float del flujo. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Lee una matriz de valores float del flujo. |
| [readRational(long position)](#readRational-long-) | Lee un único valor de número racional del flujo. |
| [readSRational(long position)](#readSRational-long-) | Lee un único valor de número racional con signo del flujo. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Lee una matriz de valores racionales del flujo. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Lee una matriz de valores racionales con signo del flujo. |
| [readSByte(long position)](#readSByte-long-) | Lee datos de byte con signo del flujo. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Lee una matriz de valores byte con signo del flujo. |
| [readSInt(long position)](#readSInt-long-) | Lee un valor entero con signo del flujo. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Lee una matriz de valores enteros con signo del flujo. |
| [readSShort(long position)](#readSShort-long-) | Lee un valor short con signo del flujo. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Lee una matriz de valores short con signo del flujo. |
| [readUInt(long position)](#readUInt-long-) | Lee un valor entero sin signo del flujo. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Lee una matriz de valores enteros sin signo del flujo. |
| [readUShort(long position)](#readUShort-long-) | Lee un valor short sin signo del flujo. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Lee una matriz de valores enteros sin signo del flujo. |
| [readLong(long position)](#readLong-long-) | Lee un valor long sin signo del flujo. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Lee una matriz de valores long del flujo. |
| [readULong(long position)](#readULong-long-) | Lee un valor long sin signo del flujo. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Lee una matriz de valores ulong del flujo. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Convierte los datos subyacentes al contenedor de flujo. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Inicializa una nueva instancia de la clase `TiffStreamReader`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos del arreglo de bytes. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Inicializa una nueva instancia de la clase `TiffStreamReader`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos del arreglo de bytes. |
| startIndex | int | El índice de inicio en `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Inicializa una nueva instancia de la clase `TiffStreamReader`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos del arreglo de bytes. |
| startIndex | int | El índice de inicio en `data`. |
| dataLength | int | Longitud de los datos. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Inicializa una nueva instancia de la clase `TiffStreamReader`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |

### getLength() {#getLength--}
```
public long getLength()
```


Obtiene la longitud del lector.

Valor: La longitud del lector.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo).

Valor: `true` si se lanzan excepciones al procesar datos incorrectos; de lo contrario, las condiciones de error se ignoran silenciosamente.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo).

Valor: `true` si se lanzan excepciones al procesar datos incorrectos; de lo contrario, las condiciones de error se ignoran silenciosamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Lee una matriz de valores byte del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | byte[] | La matriz a rellenar. |
| arrayIndex | int | El índice de la matriz donde comenzar a colocar valores. |
| posición | long | La posición del flujo desde la cual leer. |
| count | long | El recuento de elementos a leer. |

**Returns:**
long - La matriz de valores de byte.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Lee una matriz de valores byte sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
byte[] - La matriz de valores de byte sin signo.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Lee un único valor double del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
double - El valor doble único.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Lee una matriz de valores double del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
double[] - La matriz de valores dobles.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Lee un único valor float del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
float - El valor flotante único.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Lee una matriz de valores float del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
float[] - La matriz de valores flotantes.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Lee un único valor de número racional del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Lee un único valor de número racional con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Lee una matriz de valores racionales del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - La matriz de valores racionales.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Lee una matriz de valores racionales con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - La matriz de valores racionales con signo.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Lee datos de byte con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
byte - El valor de byte con signo.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Lee una matriz de valores byte con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
byte[] - La matriz de valores de byte con signo.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Lee un valor entero con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
int - Un valor entero con signo.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Lee una matriz de valores enteros con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
int[] - La matriz de valores enteros con signo.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Lee un valor short con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
short - Un valor corto con signo.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Lee una matriz de valores short con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
short[] - La matriz de valores cortos con signo.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Lee un valor entero sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
long - Un valor entero sin signo.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
long[] - La matriz de valores enteros sin signo.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Lee un valor short sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
int - Un valor entero sin signo.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
int[] - La matriz de valores enteros sin signo.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Lee un valor long sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
long - Un valor entero sin signo.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Lee una matriz de valores long del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
long[] - La matriz ulong.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Lee un valor long sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |

**Returns:**
long - Un valor entero sin signo.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Lee una matriz de valores ulong del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
long[] - La matriz ulong.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Convierte los datos subyacentes al contenedor de flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startPosition | long | La posición inicial desde la cual iniciar la conversión. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
