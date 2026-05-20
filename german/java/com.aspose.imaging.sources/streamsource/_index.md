---
title: "StreamSource"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Stream-Quelle dar."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Stellt eine Stream-Quelle dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource()](#StreamSource--) | Initialisiert eine neue Instanz der `StreamSource`-Klasse mit Null-Stream. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStream()](#getStream--) | Liest den Stream. |
| [getDisposeStream()](#getDisposeStream--) | Liest einen Wert, der angibt, ob der Stream freigegeben werden soll, sobald der Container freigegeben wird. |
| [getStreamContainer()](#getStreamContainer--) | Ruft den Stream‑Container ab. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//Erstellt eine Instanz von JpegOptions und setzt deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//Erstelle eine Instanz von System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// Definiere die Quell‑Eigenschaft für die Instanz von JpegOptions
// Der zweite boolesche Parameter bestimmt, ob der Stream freigegeben wird, sobald er aus dem Gültigkeitsbereich heraustritt
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Erstellt eine Instanz von Image und ruft die Create‑Methode mit JpegOptions als Parameter auf, um das Image‑Objekt zu initialisieren
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Führen Sie einige Bildverarbeitungen durch
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | com.aspose.ms.System.IO.Stream | Der zu öffnende Stream. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der zu öffnende Stream. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Byte‑Array, das das Bild speichert |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | ByteBuffer-Puffer zum Speichern des Bildes |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Initialisiert eine neue Instanz der `StreamSource`‑Klasse mit Null‑Stream. Dieser Konstruktor ermöglicht das Erstellen neuer Bilder ohne Eingabestream, Bilder werden nur im Speicher gespeichert.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die zu öffnende Datei. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die zu öffnende Datei. |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | com.aspose.ms.System.IO.Stream | Der Stream |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Initialisiert eine neue Instanz der `StreamSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der zu öffnende Stream. |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Liest den Stream.

**Returns:**
com.aspose.ms.System.IO.Stream - Der Stream.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Liest einen Wert, der angibt, ob der Stream freigegeben werden soll, sobald der Container freigegeben wird.

**Returns:**
boolesch - `true`, wenn der Stream freigegeben werden soll; andernfalls `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Ruft den Stream‑Container ab.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Vorsichtig verwenden. Der Stream‑Container muss nach dem Abrufen freigegeben werden.
