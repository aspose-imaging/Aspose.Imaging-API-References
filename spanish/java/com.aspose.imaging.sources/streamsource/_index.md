---
title: "StreamSource"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una fuente de flujo."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Representa una fuente de flujo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Inicializa una nueva instancia de la clase `StreamSource`. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Inicializa una nueva instancia de la clase `StreamSource`. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Inicializa una nueva instancia de la clase `StreamSource`. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Inicializa una nueva instancia de la clase `StreamSource`. |
| [StreamSource()](#StreamSource--) | Inicializa una nueva instancia de la clase `StreamSource` con flujo Null. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Inicializa una nueva instancia de la clase `StreamSource`. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Inicializa una nueva instancia de la clase `StreamSource`. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Inicializa una nueva instancia de la clase `StreamSource`. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Inicializa una nueva instancia de la clase `StreamSource`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStream()](#getStream--) | Obtiene el flujo. |
| [getDisposeStream()](#getDisposeStream--) | Obtiene un valor que indica si el flujo debe ser eliminado cuando el contenedor se elimina. |
| [getStreamContainer()](#getStreamContainer--) | Obtiene el contenedor de flujo. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//Crea una instancia de JpegOptions y establece sus diversas propiedades
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//Crea una instancia de System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// Define la propiedad source para la instancia de JpegOptions
// El segundo parámetro booleano determina si el Stream se elimina una vez que sale del alcance
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Crea una instancia de Image y llama al método Create con JpegOptions como parámetro para inicializar el objeto Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Realiza algún procesamiento de imagen
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | com.aspose.ms.System.IO.Stream | El flujo a abrir. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo a abrir. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | matriz de bytes que almacena la imagen |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | Buffer ByteBuffer para almacenar la imagen |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Inicializa una nueva instancia de la clase `StreamSource` con flujo Null. Este constructor permite crear nuevas imágenes sin flujo de entrada, imágenes almacenadas solo en memoria.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El archivo a abrir. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El archivo a abrir. |
| disposeStream | boolean | si se establece en `true` el flujo será eliminado. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | com.aspose.ms.System.IO.Stream | El flujo |
| disposeStream | boolean | si se establece en `true` el flujo será eliminado. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase `StreamSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo a abrir. |
| disposeStream | boolean | si se establece en `true` el flujo será eliminado. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Obtiene el flujo.

**Returns:**
com.aspose.ms.System.IO.Stream - El flujo.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Obtiene un valor que indica si el flujo debe ser eliminado cuando el contenedor se elimina.

**Returns:**
booleano - `true` si el flujo debe ser eliminado; de lo contrario, `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Obtiene el contenedor de flujo.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Usar con precaución. Necesitará disponer del contenedor de flujo después de la recuperación.
