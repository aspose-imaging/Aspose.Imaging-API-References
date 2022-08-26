---
title: StreamContainer
second_title: Aspose.Imaging für .NET-API-Referenz
description: Stellt den Stream-Container dar der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.
type: docs
weight: 11130
url: /de/net/aspose.imaging/streamcontainer/
---
## StreamContainer class

Stellt den Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.

```csharp
public class StreamContainer : DisposableObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Initialisiert eine neue Instanz von[`StreamContainer`](../streamcontainer) Klasse. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz von[`StreamContainer`](../streamcontainer) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Lesen unterstützt. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Ruft einen Wert ab, der angibt, ob der Stream die Suche unterstützt. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Ruft einen Wert ab, der angibt, ob dieser Stream beim Schließen verworfen wird. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Holt oder setzt die Streamlänge in Byte. Dieser Wert ist kleiner als dieLength durch die Start-Stream-Position, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Holt oder setzt die aktuelle Position innerhalb des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Ruft den Datenstrom ab. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Ruft ein Objekt ab, das zum Synchronisieren des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Löscht alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read)(byte[]) | Liest Bytes, um den angegebenen Bytepuffer zu füllen. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read_1)(byte[], int, int) | Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Liest ein Byte aus dem Stream und erhöht die Position innerhalb des Streams um ein Byte oder gibt -1 zurück, wenn am Ende des Streams. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](./readwritebytescount) und streamen[`Length`](./length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_3)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](./readwritebytescount) und streamen[`Length`](./length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_1)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](./length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_4)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](./length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_2)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_5)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Legt die Position innerhalb des aktuellen Streams fest. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes)() | Konvertiert die Stream-Daten in dieByte array. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes_1)(long, long) | Konvertiert die Stream-Daten in dieByte array. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write_1)(byte[], int, int) | Schreibt eine Folge von Bytes in den aktuellen Stream und erhöht die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position innerhalb des Streams um ein Byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto_1)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit) | Führt eine explizite Konvertierung von aus[`StreamContainer`](../streamcontainer) zuStream . |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount) | Gibt die Anzahl der Lese- und Schreibbytes beim sequenziellen Lesen an. |

### Siehe auch

* class [DisposableObject](../disposableobject)
* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
