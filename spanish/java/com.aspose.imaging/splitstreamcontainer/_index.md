---
title: "SplitStreamContainer"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo."
type: docs
weight: 108
url: /es/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Inicializa una nueva instancia de la clase `SplitStreamContainer`. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Inicializa una nueva instancia de la clase `SplitStreamContainer`. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Inicializa una nueva instancia de la clase `SplitStreamContainer`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
| [getPosition()](#getPosition--) | Obtiene la posición actual dentro del flujo. |
| [setPosition(long value)](#setPosition-long-) | Establece la posición actual dentro del flujo. |
| [getLength()](#getLength--) | Obtiene la longitud del flujo en bytes. |
| [setLength(long value)](#setLength-long-) | Establece la longitud del flujo en bytes. |
| [canRead()](#canRead--) | Obtiene un valor que indica si el flujo admite lectura. |
| [canSeek()](#canSeek--) | Obtiene un valor que indica si el flujo admite búsqueda. |
| [canWrite()](#canWrite--) | Obtiene un valor que indica si el flujo admite escritura. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Inserta el contenedor de flujo en la posición especificada. |
| [flush()](#flush--) | Limpia todos los búferes de este flujo y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente. |
| [write(byte[] bytes)](#write-byte---) | Escribe todos los bytes especificados en el flujo. |
| [writeByte(byte value)](#writeByte-byte-) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| [read(byte[] bytes)](#read-byte---) | Lee bytes para llenar el búfer de bytes especificado. |
| [toBytes()](#toBytes--) | Convierte los datos del flujo al arreglo `byte`. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Convierte los datos del flujo al arreglo `byte`. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos. |
| [readByte()](#readByte--) | Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo. |
| [seek(long offset, int origin)](#seek-long-int-) | Establece la posición dentro del flujo actual. |
| [seekBegin()](#seekBegin--) | Establece la posición del flujo al comienzo del flujo. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Inicializa una nueva instancia de la clase `SplitStreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase `SplitStreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos. |
| disposeStream | boolean | si se establece en `true` el flujo será eliminado cuando el contenedor sea eliminado. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase `SplitStreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |
| disposeStream | boolean | si se establece en `true` elimina el flujo. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado.

**Returns:**
java.lang.Object - El objeto que puede usarse para sincronizar el acceso al recurso sincronizado.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtiene la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

**Returns:**
long - La posición actual del flujo.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | La posición actual del flujo. |

### getLength() {#getLength--}
```
public long getLength()
```


Obtiene la longitud del flujo en bytes. Este valor es menor que `System.IO.Stream.Length` por la posición inicial del flujo pasada en el constructor de StreamContainer.

**Returns:**
long - La longitud del flujo.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Establece la longitud del flujo en bytes. Este valor es menor que `System.IO.Stream.Length` por la posición inicial del flujo pasada en el constructor de StreamContainer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | La longitud del flujo. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Obtiene un valor que indica si el flujo admite lectura.

**Returns:**
boolean - `true` si el flujo soporta lectura; de lo contrario, `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Obtiene un valor que indica si el flujo admite búsqueda.

**Returns:**
boolean - `true` si el flujo soporta búsqueda; de lo contrario, `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Obtiene un valor que indica si el flujo admite escritura.

**Returns:**
boolean - `true` si el flujo soporta escritura; de lo contrario, `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Inserta el contenedor de flujo en la posición especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | int | La posición donde insertar. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor de flujo a insertar. |
| disposeStream | boolean | si se establece en `true` elimina el flujo. |

### flush() {#flush--}
```
public void flush()
```


Limpia todos los búferes de este flujo y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Escribe todos los bytes especificados en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes a escribir. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | El byte a escribir en el flujo. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Lee bytes para llenar el búfer de bytes especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes a rellenar. |

**Returns:**
int - El número de bytes leídos. Este valor puede ser menor que el número de bytes en el búfer si no hay suficientes bytes en el flujo.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Convierte los datos del flujo al arreglo `byte`.

**Returns:**
byte[] - Los datos del flujo convertidos al arreglo `byte`.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Convierte los datos del flujo al arreglo `byte`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición | long | La posición desde la cual comenzar a leer bytes. |
| bytesCount | long | El recuento de bytes a leer. |

**Returns:**
byte[] - Los datos del flujo convertidos al arreglo `byte`.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | byte[] | Una matriz de bytes. Cuando este método devuelve, el buffer contiene la matriz de bytes especificada con los valores entre `offset` y (`offset` + `count` - 1) reemplazados por los bytes leídos de la fuente actual. |
| offset | int | El desplazamiento de byte basado en cero en `buffer` en el que comenzar a almacenar los datos leídos del flujo actual. |
| count | int | El número máximo de bytes que se leerán del flujo actual. |

**Returns:**
int - El número total de bytes leídos en el buffer. Esto puede ser menor que el número de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se ha alcanzado el final del flujo.
### readByte() {#readByte--}
```
public int readByte()
```


Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo.

**Returns:**
int - El byte sin signo convertido a Int32, o -1 si está al final del flujo.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Establece la posición dentro del flujo actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset | long | Un desplazamiento de byte relativo al parámetro `origin`. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| origin | int | Un valor del tipo `System.IO.SeekOrigin` que indica el punto de referencia utilizado para obtener la nueva posición. |

**Returns:**
long - La nueva posición dentro del flujo actual.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Establece la posición del flujo al comienzo del mismo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | byte[] | Una matriz de bytes. Este método copia `count` bytes de `buffer` al flujo actual. |
| offset | int | El desplazamiento de byte basado en cero en `buffer` en el que comenzar a copiar bytes al flujo actual. |
| count | int | El número de bytes que se escribirán en el flujo actual. |

