---
title: "StreamContainer"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa un contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo."
type: docs
weight: 109
url: /es/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Representa un contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Inicializa una nueva instancia de la clase `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Inicializa una nueva instancia de la clase `StreamContainer`. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Inicializa una nueva instancia de la clase `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Inicializa una nueva instancia de la clase `StreamContainer`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Especifica la cantidad de bytes de lectura y escritura al leer secuencialmente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | Realiza una conversión explícita de `com.aspose.imaging.StreamContainer` a `System.IO.Stream`. |
| [getSyncRoot()](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
| [getPosition()](#getPosition--) | Obtiene o establece la posición actual dentro del flujo. |
| [setPosition(long value)](#setPosition-long-) | Obtiene o establece la posición actual dentro del flujo. |
| [getStream()](#getStream--) | Obtiene el flujo de datos. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Obtiene un valor que indica si este flujo se elimina al cerrarse. |
| [getLength()](#getLength--) | Obtiene o establece la longitud del flujo en bytes. |
| [setLength(long value)](#setLength-long-) | Obtiene o establece la longitud del flujo en bytes. |
| [canRead()](#canRead--) | Obtiene un valor que indica si el flujo admite lectura. |
| [canSeek()](#canSeek--) | Obtiene un valor que indica si el flujo admite búsqueda. |
| [canWrite()](#canWrite--) | Obtiene un valor que indica si el flujo admite escritura. |
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
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Guarda (copia) los datos del flujo al flujo especificado. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Guarda (copia) todos los datos del flujo al flujo especificado. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Guarda (copia) los datos del flujo al flujo especificado. |
| [save(String filePath)](#save-java.lang.String-) | Guarda (copia) los datos del flujo al flujo especificado. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Guarda (copia) los datos del flujo al flujo especificado. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Guarda (copia) los datos del flujo al flujo especificado. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | Copia los datos contenidos a otro `StreamContainer`. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | Copia los datos contenidos a otro `StreamContainer`. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Inicializa una nueva instancia de la clase `StreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Inicializa una nueva instancia de la clase `StreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | com.aspose.ms.System.IO.Stream | El flujo. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase `StreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos. |
| disposeStream | boolean | si se establece en `true` el flujo será eliminado cuando el contenedor sea eliminado. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase `StreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | com.aspose.ms.System.IO.Stream | El flujo de datos. |
| disposeStream | boolean | si se establece en `true` el flujo será eliminado cuando el contenedor sea eliminado. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Especifica la cantidad de bytes de lectura y escritura al leer secuencialmente.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Realiza una conversión explícita de `com.aspose.imaging.StreamContainer` a `System.IO.Stream`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |

**Returns:**
com.aspose.ms.System.IO.Stream - El resultado de la conversión.
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


Obtiene o establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La posición actual del flujo.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Obtiene o establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La posición actual del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Obtiene el flujo de datos.

Valor: El flujo de datos.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Obtiene un valor que indica si este flujo se elimina al cerrarse.

Valor: `true` si el flujo se elimina al cerrarse; de lo contrario, `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Obtiene o establece la longitud del flujo en bytes. Este valor es menor que el Stream\#getLength().getLength() por la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La longitud del flujo.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Obtiene o establece la longitud del flujo en bytes. Este valor es menor que el Stream\#getLength().getLength() por la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La longitud del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Obtiene un valor que indica si el flujo admite lectura.

Valor: `true` si el flujo admite lectura; de lo contrario, `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Obtiene un valor que indica si el flujo admite búsqueda.

Valor: `true` si el flujo admite búsqueda; de lo contrario, `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Obtiene un valor que indica si el flujo admite escritura.

Valor: `true` si la secuencia admite escritura; de lo contrario, `false`.

**Returns:**
boolean
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

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado `ReadWriteBytesCount` y el valor de `Length` del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | El flujo donde guardar los datos. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Guarda (copia) todos los datos del flujo al flujo especificado. Utiliza el valor de `Length` del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | El flujo donde guardar los datos. |
| bufferSize | int | El búfer. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Guarda (copia) los datos del flujo al flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | El flujo donde guardar los datos. |
| bufferSize | int | El tamaño del búfer. Por defecto se utiliza el valor `ReadWriteBytesCount`. |
| length | long | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece en el valor `Length`. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado `ReadWriteBytesCount` y el valor de `Length` del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del flujo. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Guarda (copia) los datos del flujo al flujo especificado. Utiliza el valor de `Length` del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del flujo. |
| bufferSize | int | El tamaño del búfer. Por defecto se utiliza el valor `ReadWriteBytesCount`. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Guarda (copia) los datos del flujo al flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del flujo. |
| bufferSize | int | El tamaño del búfer. Por defecto se utiliza el valor `ReadWriteBytesCount`. |
| length | long | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece en el valor `Length`. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copia los datos contenidos a otro `StreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo al que copiar. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copia los datos contenidos a otro `StreamContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo al que copiar. |
| length | long | El recuento de bytes a escribir. |

