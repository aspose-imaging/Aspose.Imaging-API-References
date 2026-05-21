---
title: "StreamContainer"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt einen Stream-Container dar, der den Stream enthält und Routinen zur Stream-Verarbeitung bereitstellt."
type: docs
weight: 109
url: /de/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Stellt einen Stream-Container dar, der den Stream enthält und Routinen zur Stream-Verarbeitung bereitstellt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Initialisiert eine neue Instanz der Klasse `StreamContainer`. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Initialisiert eine neue Instanz der Klasse `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Initialisiert eine neue Instanz der Klasse `StreamContainer`. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Gibt die Anzahl der Lese- und Schreibbytes beim sequentiellen Lesen an. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | Führt eine explizite Konvertierung von `com.aspose.imaging.StreamContainer` zu `System.IO.Stream` durch. |
| [getSyncRoot()](#getSyncRoot--) | Liefert ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
| [getPosition()](#getPosition--) | Liest oder setzt die aktuelle Position im Stream. |
| [setPosition(long value)](#setPosition-long-) | Liest oder setzt die aktuelle Position im Stream. |
| [getStream()](#getStream--) | Liest den Daten-Stream. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Liest einen Wert, der angibt, ob dieser Stream beim Schließen freigegeben wird. |
| [getLength()](#getLength--) | Liest oder setzt die Stream-Länge in Bytes. |
| [setLength(long value)](#setLength-long-) | Liest oder setzt die Stream-Länge in Bytes. |
| [canRead()](#canRead--) | Liefert einen Wert, der angibt, ob der Stream das Lesen unterstützt. |
| [canSeek()](#canSeek--) | Liefert einen Wert, der angibt, ob der Stream das Suchen unterstützt. |
| [canWrite()](#canWrite--) | Liefert einen Wert, der angibt, ob der Stream das Schreiben unterstützt. |
| [flush()](#flush--) | Leert alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| [write(byte[] bytes)](#write-byte---) | Schreibt alle angegebenen Bytes in den Stream. |
| [writeByte(byte value)](#writeByte-byte-) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position im Stream um ein Byte. |
| [read(byte[] bytes)](#read-byte---) | Liest Bytes, um den angegebenen Byte-Puffer zu füllen. |
| [toBytes()](#toBytes--) | Konvertiert die Stream-Daten in das `byte`-Array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Konvertiert die Stream-Daten in das `byte`-Array. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die Anzahl der gelesenen Bytes. |
| [readByte()](#readByte--) | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| [seek(long offset, int origin)](#seek-long-int-) | Setzt die Position im aktuellen Stream. |
| [seekBegin()](#seekBegin--) | Setzt die Stream-Position auf den Anfang des Streams. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position in diesem Stream um die Anzahl der geschriebenen Bytes. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(String filePath)](#save-java.lang.String-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | Kopiert die enthaltenen Daten in einen anderen `StreamContainer`. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | Kopiert die enthaltenen Daten in einen anderen `StreamContainer`. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Initialisiert eine neue Instanz der Klasse `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Initialisiert eine neue Instanz der Klasse `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | com.aspose.ms.System.IO.Stream | Der Stream. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Initialisiert eine neue Instanz der Klasse `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Datenstream. |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Initialisiert eine neue Instanz der Klasse `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | com.aspose.ms.System.IO.Stream | Der Datenstream. |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Gibt die Anzahl der Lese- und Schreibbytes beim sequentiellen Lesen an.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Führt eine explizite Konvertierung von `com.aspose.imaging.StreamContainer` zu `System.IO.Stream` durch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |

**Returns:**
com.aspose.ms.System.IO.Stream - Das Ergebnis der Konvertierung.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Liefert ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

Wert: Das Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Versatz von der beim Konstruktor von StreamContainer übergebenen Startposition des Streams dar.

Wert: Die aktuelle Stream-Position.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Versatz von der beim Konstruktor von StreamContainer übergebenen Startposition des Streams dar.

Wert: Die aktuelle Stream-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Liest den Daten-Stream.

Wert: Der Daten-Stream.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Liest einen Wert, der angibt, ob dieser Stream beim Schließen freigegeben wird.

Wert: `true`, wenn der Stream beim Schließen freigegeben wird; andernfalls `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Liest oder setzt die Stream-Länge in Bytes. Dieser Wert ist um die beim Konstruktor von StreamContainer übergebene Startposition des Streams kleiner als Stream\#getLength().getLength().

Wert: Die Stream-Länge.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Liest oder setzt die Stream-Länge in Bytes. Dieser Wert ist um die beim Konstruktor von StreamContainer übergebene Startposition des Streams kleiner als Stream\#getLength().getLength().

Wert: Die Stream-Länge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Liefert einen Wert, der angibt, ob der Stream das Lesen unterstützt.

Wert: `true`, wenn der Stream das Lesen unterstützt; andernfalls `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Liefert einen Wert, der angibt, ob der Stream das Suchen unterstützt.

Wert: `true`, wenn der Stream das Suchen unterstützt; andernfalls `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Liefert einen Wert, der angibt, ob der Stream das Schreiben unterstützt.

Wert: `true` wenn der Stream das Schreiben unterstützt; andernfalls `false`.

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Leert alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Schreibt alle angegebenen Bytes in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die zu schreibenden Bytes. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position im Stream um ein Byte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Das Byte, das in den Stream geschrieben werden soll. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Liest Bytes, um den angegebenen Byte-Puffer zu füllen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die Bytes zum Füllen. |

**Returns:**
int - Die Anzahl der gelesenen Bytes. Dieser Wert kann kleiner sein als die Anzahl der Bytes im Puffer, wenn im Stream nicht genügend Bytes vorhanden sind.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Konvertiert die Stream-Daten in das `byte`-Array.

**Returns:**
byte[] - Die Stream-Daten, konvertiert in das `byte`-Array.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Konvertiert die Stream-Daten in das `byte`-Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | long | Die Position, von der aus Bytes gelesen werden sollen. |
| bytesCount | long | Die zu lesende Byte-Anzahl. |

**Returns:**
byte[] - Die Stream-Daten, konvertiert in das `byte`-Array.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die Anzahl der gelesenen Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | byte[] | Ein Array von Bytes. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array, wobei die Werte zwischen `offset` und (`offset` + `count` - 1) durch die aus der aktuellen Quelle gelesenen Bytes ersetzt wurden. |
| offset | int | Der nullbasierte Byte-Offset in `buffer`, an dem das Lesen der Daten aus dem aktuellen Stream gespeichert werden soll. |
| count | int | Die maximale Anzahl von Bytes, die aus dem aktuellen Stream gelesen werden sollen. |

**Returns:**
int - Die Gesamtzahl der in den Puffer gelesenen Bytes. Diese kann kleiner sein als die angeforderte Anzahl von Bytes, wenn nicht genügend Bytes verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde.
### readByte() {#readByte--}
```
public int readByte()
```


Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist.

**Returns:**
int - Das unsigned Byte, in ein Int32 umgewandelt, oder -1, wenn das Ende des Streams erreicht ist.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Setzt die Position im aktuellen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offset | long | Ein Byte-Offset relativ zum Parameter `origin`. Dieser Wert stellt den Offset von der beim StreamContainer-Konstruktor übergebenen Startposition des Streams dar. |
| origin | int | Ein Wert vom Typ `System.IO.SeekOrigin`, der den Referenzpunkt angibt, der zur Ermittlung der neuen Position verwendet wird. |

**Returns:**
long - Die neue Position innerhalb des aktuellen Streams.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Offset von der beim StreamContainer-Konstruktor übergebenen Startposition des Streams dar.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position in diesem Stream um die Anzahl der geschriebenen Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | byte[] | Ein Array von Bytes. Diese Methode kopiert `count` Bytes von `buffer` in den aktuellen Stream. |
| offset | int | Der nullbasierte Byte-Offset in `buffer`, an dem das Kopieren von Bytes in den aktuellen Stream beginnen soll. |
| count | int | Die Anzahl der Bytes, die in den aktuellen Stream geschrieben werden sollen. |

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße `ReadWriteBytesCount` und den Stream‑Wert `Length`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Der Stream, in dem die Daten gespeichert werden sollen. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Stream‑Wert `Length`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Der Stream, in dem die Daten gespeichert werden sollen. |
| bufferSize | int | Der Puffer. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Der Stream, in dem die Daten gespeichert werden sollen. |
| bufferSize | int | Die Puffergröße. Standardmäßig wird der Wert `ReadWriteBytesCount` verwendet. |
| length | long | Die zu kopierende Datenlänge des Streams. Standardmäßig wird die Länge auf den Wert `Length` gesetzt. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße `ReadWriteBytesCount` und den Stream‑Wert `Length`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Stream‑Daten gespeichert werden sollen. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Stream‑Wert `Length`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Stream‑Daten gespeichert werden sollen. |
| bufferSize | int | Die Puffergröße. Standardmäßig wird der Wert `ReadWriteBytesCount` verwendet. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Stream‑Daten gespeichert werden sollen. |
| bufferSize | int | Die Puffergröße. Standardmäßig wird der Wert `ReadWriteBytesCount` verwendet. |
| length | long | Die zu kopierende Datenlänge des Streams. Standardmäßig wird die Länge auf den Wert `Length` gesetzt. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Kopiert die enthaltenen Daten in einen anderen `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container, in den kopiert werden soll. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Kopiert die enthaltenen Daten in einen anderen `StreamContainer`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container, in den kopiert werden soll. |
| length | long | Die zu schreibende Byte‑Anzahl. |

