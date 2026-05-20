---
title: "SplitStreamContainer"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt einen geteilten Stream-Container dar, der den Stream enthält und Routinen zur Stream-Verarbeitung bereitstellt."
type: docs
weight: 108
url: /de/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Stellt einen geteilten Stream-Container dar, der den Stream enthält und Routinen zur Stream-Verarbeitung bereitstellt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Initialisiert eine neue Instanz der `SplitStreamContainer`-Klasse. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Initialisiert eine neue Instanz der `SplitStreamContainer`-Klasse. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Initialisiert eine neue Instanz der `SplitStreamContainer`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Liefert ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
| [getPosition()](#getPosition--) | Liefert die aktuelle Position im Stream. |
| [setPosition(long value)](#setPosition-long-) | Setzt die aktuelle Position im Stream. |
| [getLength()](#getLength--) | Liefert die Stream-Länge in Bytes. |
| [setLength(long value)](#setLength-long-) | Setzt die Stream-Länge in Bytes. |
| [canRead()](#canRead--) | Liefert einen Wert, der angibt, ob der Stream das Lesen unterstützt. |
| [canSeek()](#canSeek--) | Liefert einen Wert, der angibt, ob der Stream das Suchen unterstützt. |
| [canWrite()](#canWrite--) | Liefert einen Wert, der angibt, ob der Stream das Schreiben unterstützt. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Fügt den Stream-Container an der angegebenen Position ein. |
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
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Initialisiert eine neue Instanz der `SplitStreamContainer`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Initialisiert eine neue Instanz der `SplitStreamContainer`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Datenstream. |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Initialisiert eine neue Instanz der `SplitStreamContainer`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Liefert ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

**Returns:**
java.lang.Object - Das Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Ermittelt die aktuelle Position im Stream. Dieser Wert stellt den Offset von der beim StreamContainer‑Konstruktor übergebenen Startposition des Streams dar.

**Returns:**
long - Die aktuelle Stream-Position.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Setzt die aktuelle Position im Stream. Dieser Wert stellt den Offset von der beim StreamContainer‑Konstruktor übergebenen Startposition des Streams dar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die aktuelle Stream-Position. |

### getLength() {#getLength--}
```
public long getLength()
```


Ermittelt die Stream-Länge in Bytes. Dieser Wert ist kleiner als `System.IO.Stream.Length` um die beim StreamContainer‑Konstruktor übergebene Startposition des Streams.

**Returns:**
long - Die Stream-Länge.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Setzt die Stream-Länge in Bytes. Dieser Wert ist kleiner als `System.IO.Stream.Length` um die beim StreamContainer‑Konstruktor übergebene Startposition des Streams.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Stream-Länge. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Liefert einen Wert, der angibt, ob der Stream das Lesen unterstützt.

**Returns:**
boolean - `true`, wenn der Stream das Lesen unterstützt; andernfalls `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Liefert einen Wert, der angibt, ob der Stream das Suchen unterstützt.

**Returns:**
boolean - `true`, wenn der Stream das Suchen unterstützt; andernfalls `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Liefert einen Wert, der angibt, ob der Stream das Schreiben unterstützt.

**Returns:**
boolean - `true`, wenn der Stream das Schreiben unterstützt; andernfalls `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Fügt den Stream-Container an der angegebenen Position ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position | int | Die Position, an die eingefügt werden soll. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream-Container, in den eingefügt werden soll. |
| disposeStream | boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben. |

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

