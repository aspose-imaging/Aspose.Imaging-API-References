---
title: SplitStreamContainer
second_title: Aspose.Imaging für .NET-API-Referenz
description: Repräsentiert Split-Stream-Container der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.
type: docs
weight: 11120
url: /de/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Repräsentiert Split-Stream-Container, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Initialisiert eine neue Instanz von[`SplitStreamContainer`](../splitstreamcontainer) Klasse. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Initialisiert eine neue Instanz von[`SplitStreamContainer`](../splitstreamcontainer) Klasse. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Initialisiert eine neue Instanz von[`SplitStreamContainer`](../splitstreamcontainer) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Lesen unterstützt. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | Ruft einen Wert ab, der angibt, ob der Stream die Suche unterstützt. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Ruft einen Wert ab, der angibt, ob dieser Stream beim Schließen verworfen wird. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | Holt oder setzt die Streamlänge in Byte. Dieser Wert ist kleiner als dieLength durch die Start-Stream-Position, die im StreamContainer-Konstruktor übergeben wird. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | Holt oder setzt die aktuelle Position innerhalb des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | Ruft den Datenstrom ab. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | Ruft ein Objekt ab, das zum Synchronisieren des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | Löscht alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | Fügt den Stream-Container an der angegebenen Position ein. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | Liest Bytes, um den angegebenen Bytepuffer zu füllen. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | Liest ein Byte aus dem Stream und erhöht die Position innerhalb des Streams um ein Byte oder gibt -1 zurück, wenn am Ende des Streams. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) und streamen[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) und streamen[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length) wert. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | Legt die Position innerhalb des aktuellen Streams fest. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | Konvertiert die Stream-Daten in dieByte array. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Konvertiert die Stream-Daten in dieByte array. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | Schreibt eine Folge von Bytes in den aktuellen Stream und erhöht die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position innerhalb des Streams um ein Byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |

### Siehe auch

* class [StreamContainer](../streamcontainer)
* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
