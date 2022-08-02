---
title: SplitStreamContainer
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет контейнер разделенного потока который содержит поток и предоставляет подпрограммы обработки потока.
type: docs
weight: 11120
url: /ru/net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Представляет контейнер разделенного потока, который содержит поток и предоставляет подпрограммы обработки потока.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Инициализирует новый экземпляр[`SplitStreamContainer`](../splitstreamcontainer) класс. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Инициализирует новый экземпляр[`SplitStreamContainer`](../splitstreamcontainer) класс. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Инициализирует новый экземпляр[`SplitStreamContainer`](../splitstreamcontainer) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | Получает значение, указывающее, поддерживает ли поток чтение. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | Получает значение, указывающее, поддерживает ли поток поиск. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | Получает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Получает значение, указывающее, удаляется ли этот поток при закрытии. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | Получает или задает длину потока в байтах. Это значение меньше, чемLength по начальной позиции потока, переданной в конструкторе StreamContainer. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | Получает или задает текущую позицию в потоке. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизируемому ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | Очищает все буферы для этого потока и вызывает запись всех буферизованных данных на базовое устройство. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | Вставляет контейнер потока в указанную позицию. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | Считывает байты, чтобы заполнить указанный буфер байтов. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | Считывает байт из потока и сдвигает позицию в потоке на один байт или возвращает -1, если в конце потока. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) и поток[`Length`](../streamcontainer/length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) и поток[`Length`](../streamcontainer/length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует поток[`Length`](../streamcontainer/length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует поток[`Length`](../streamcontainer/length) значение. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | Устанавливает позицию потока в начало потока. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | Преобразует потоковые данные вByte массив. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Преобразует потоковые данные вByte массив. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | Записывает все указанные байты в поток. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | Записывает последовательность байтов в текущий поток и продвигает текущую позицию в этом потоке на количество записанных байтов. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |

### Смотрите также

* class [StreamContainer](../streamcontainer)
* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
