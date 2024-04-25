---
title: FileStreamContainer
second_title: Справочник по Aspose.Imaging for .NET API
description: Помощник для обработки файлового потока.
type: docs
weight: 9300
url: /ru/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

Помощник для обработки файлового потока.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Получает значение, указывающее, поддерживает ли поток чтение. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Получает значение, указывающее, поддерживает ли поток поиск. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Получает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | Получает путь к файлу. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | Получает значение, указывающее, был ли поток создан явно. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Получает значение, указывающее, удаляется ли этот поток при закрытии. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | Получает или задает значение, указывающее, является ли поток временным. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Получает или задает длину потока в байтах. Это значение меньше, чемLength по начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Получает или задает текущую позицию в потоке. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизируемому ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | Создает новый файловый поток. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | Открывает существующий файловый поток. Если файловый поток не существует, выдается соответствующее исключение. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Очищает все буферы для этого потока и вызывает запись всех буферизованных данных на базовое устройство. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | Считывает байты, чтобы заполнить указанный буфер байтов. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Считывает байт из потока и сдвигает позицию в потоке на один байт или возвращает -1, если в конце потока. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) и поток[`Length`](../streamcontainer/length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) и поток[`Length`](../streamcontainer/length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует поток[`Length`](../streamcontainer/length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует поток[`Length`](../streamcontainer/length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Устанавливает позицию потока в начало потока. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | Преобразует потоковые данные вByte массив. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | Преобразует потоковые данные вByte массив. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | Записывает все указанные байты в поток. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | Записывает последовательность байтов в текущий поток и продвигает текущую позицию в этом потоке на количество записанных байтов. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | Выполняет явное преобразование из[`FileStreamContainer`](../filestreamcontainer) кStream . (2 operators) |

### Смотрите также

* class [StreamContainer](../streamcontainer)
* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
