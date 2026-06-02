---
title: "StreamSource"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una sorgente stream."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Rappresenta una sorgente stream.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Inizializza una nuova istanza della classe `StreamSource`. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Inizializza una nuova istanza della classe `StreamSource`. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Inizializza una nuova istanza della classe `StreamSource`. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Inizializza una nuova istanza della classe `StreamSource`. |
| [StreamSource()](#StreamSource--) | Inizializza una nuova istanza della classe `StreamSource` con flusso Null. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Inizializza una nuova istanza della classe `StreamSource`. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Inizializza una nuova istanza della classe `StreamSource`. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Inizializza una nuova istanza della classe `StreamSource`. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Inizializza una nuova istanza della classe `StreamSource`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStream()](#getStream--) | Ottiene lo stream. |
| [getDisposeStream()](#getDisposeStream--) | Ottiene un valore che indica se lo stream deve essere eliminato ogni volta che il contenitore viene eliminato. |
| [getStreamContainer()](#getStreamContainer--) | Ottiene il contenitore di flusso. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//Crea un'istanza di JpegOptions e imposta le sue varie proprietà
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//Crea un'istanza di System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// Definisci la proprietà source per l'istanza di JpegOptions
// Il secondo parametro booleano determina se lo Stream viene eliminato una volta uscito dallo scope
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Crea un'istanza di Image e chiama il metodo Create con JpegOptions come parametro per inizializzare l'oggetto Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Esegui qualche elaborazione dell'immagine
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream | Lo stream da aprire. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da aprire. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | Array di byte che memorizza l'immagine |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | Buffer ByteBuffer per memorizzare l'immagine |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Inizializza una nuova istanza della classe `StreamSource` con flusso Null. Questo costruttore consente di creare nuove immagini senza stream di input, immagini memorizzate solo in memoria.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il file da aprire. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il file da aprire. |
| disposeStream | boolean | se impostato su `true` lo stream verrà eliminato. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream | Lo stream |
| disposeStream | boolean | se impostato su `true` lo stream verrà eliminato. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Inizializza una nuova istanza della classe `StreamSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da aprire. |
| disposeStream | boolean | se impostato su `true` lo stream verrà eliminato. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Ottiene lo stream.

**Returns:**
com.aspose.ms.System.IO.Stream - Lo stream.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Ottiene un valore che indica se lo stream deve essere eliminato ogni volta che il contenitore viene eliminato.

**Returns:**
boolean - `true` se lo stream deve essere eliminato; altrimenti, `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Ottiene il contenitore di flusso.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Usare con cautela. Sarà necessario eliminare il contenitore di flusso dopo il recupero.
