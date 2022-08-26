---
title: FileStreamContainer
second_title: Aspose.Imaging für .NET-API-Referenz
description: Helfer für die Dateistreamverarbeitung.
type: docs
weight: 9300
url: /de/net/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

Helfer für die Dateistreamverarbeitung.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Lesen unterstützt. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Ruft einen Wert ab, der angibt, ob der Stream die Suche unterstützt. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | Ruft den Dateipfad ab. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | Ruft einen Wert ab, der angibt, ob der Stream explizit erstellt wurde. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Ruft einen Wert ab, der angibt, ob dieser Stream beim Schließen verworfen wird. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Stream zeitlich ist. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Holt oder setzt die Streamlänge in Byte. Dieser Wert ist kleiner als dieLength durch die Start-Stream-Position, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Holt oder setzt die aktuelle Position innerhalb des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Ruft den Datenstrom ab. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Ruft ein Objekt ab, das zum Synchronisieren des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | Erstellt einen neuen Dateistream. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | Öffnet einen bestehenden Dateistream. Wenn der Dateistream nicht existiert, wird die entsprechende Ausnahme ausgelöst. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Löscht alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | Liest Bytes, um den angegebenen Bytepuffer zu füllen. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Liest ein Byte aus dem Stream und erhöht die Position innerhalb des Streams um ein Byte oder gibt -1 zurück, wenn am Ende des Streams. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) und streamen[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) und streamen[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Legt die Position innerhalb des aktuellen Streams fest. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | Konvertiert die Stream-Daten in dieByte array. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | Konvertiert die Stream-Daten in dieByte array. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | Schreibt eine Folge von Bytes in den aktuellen Stream und erhöht die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position innerhalb des Streams um ein Byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | Führt eine explizite Konvertierung von aus[`FileStreamContainer`](../filestreamcontainer) zuStream . (2 operators) |

### Siehe auch

* class [StreamContainer](../streamcontainer)
* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
