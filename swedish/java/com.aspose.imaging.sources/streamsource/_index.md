---
title: "StreamSource"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en strömkälla."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Representerar en strömkälla.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Initierar en ny instans av klassen `StreamSource`. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Initierar en ny instans av klassen `StreamSource`. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Initierar en ny instans av klassen `StreamSource`. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Initierar en ny instans av klassen `StreamSource`. |
| [StreamSource()](#StreamSource--) | Initierar en ny instans av klassen `StreamSource` med Null-ström. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Initierar en ny instans av klassen `StreamSource`. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Initierar en ny instans av klassen `StreamSource`. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Initierar en ny instans av klassen `StreamSource`. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Initierar en ny instans av klassen `StreamSource`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStream()](#getStream--) | Hämtar strömmen. |
| [getDisposeStream()](#getDisposeStream--) | Hämtar ett värde som indikerar om strömmen ska tas bort när containern tas bort. |
| [getStreamContainer()](#getStreamContainer--) | Hämtar strömbehållaren. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//Skapar en instans av JpegOptions och sätter dess olika egenskaper
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//Skapa en instans av System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// Definiera källpropertyn för instansen av JpegOptions
// Den andra booleska parametern bestämmer om strömmen tas bort när den lämnar scopet
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Skapar en instans av Image och anropar Create-metoden med JpegOptions som parameter för att initiera Image-objektet
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Utför någon bildbehandling.
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream | Strömmen att öppna. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att öppna. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | byte-array som lagrar bilden |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | ByteBuffer-buffer för lagring av bilden |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Initierar en ny instans av klassen `StreamSource` med Null-ström. Denna konstruktor möjliggör att skapa nya bilder utan inmatningsström, bilder lagras endast i minnet.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att öppna. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att öppna. |
| disposeStream | boolean | om den sätts till `true` kommer strömmen att tas bort. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream | Strömmen |
| disposeStream | boolean | om den sätts till `true` kommer strömmen att tas bort. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Initierar en ny instans av klassen `StreamSource`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att öppna. |
| disposeStream | boolean | om den sätts till `true` kommer strömmen att tas bort. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Hämtar strömmen.

**Returns:**
com.aspose.ms.System.IO.Stream - Strömmen.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Hämtar ett värde som indikerar om strömmen ska tas bort när containern tas bort.

**Returns:**
boolesk - `true` om strömmen ska tas bort; annars `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Hämtar strömbehållaren.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Använd med försiktighet. Du måste avyttra strömbehållaren efter hämtning.
