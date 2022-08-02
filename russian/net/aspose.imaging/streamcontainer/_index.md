---
title: StreamContainer
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет контейнер потока который содержит поток и предоставляет подпрограммы обработки потока.
type: docs
weight: 11130
url: /ru/net/aspose.imaging/streamcontainer/
---
## StreamContainer class

Представляет контейнер потока, который содержит поток и предоставляет подпрограммы обработки потока.

```csharp
public class StreamContainer : DisposableObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Инициализирует новый экземпляр[`StreamContainer`](../streamcontainer) класс. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Инициализирует новый экземпляр[`StreamContainer`](../streamcontainer) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Получает значение, указывающее, поддерживает ли поток чтение. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Получает значение, указывающее, поддерживает ли поток поиск. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Получает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Получает значение, указывающее, удаляется ли этот поток при закрытии. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Получает или задает длину потока в байтах. Это значение меньше, чемLength по начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Получает или задает текущую позицию в потоке. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизируемому ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Очищает все буферы для этого потока и вызывает запись всех буферизованных данных на базовое устройство. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read)(byte[]) | Считывает байты, чтобы заполнить указанный буфер байтов. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read_1)(byte[], int, int) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Считывает байт из потока и сдвигает позицию в потоке на один байт или возвращает -1, если в конце потока. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](./readwritebytescount) и поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_3)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](./readwritebytescount) и поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_1)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_4)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_2)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_5)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Устанавливает позицию потока в начало потока. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes)() | Преобразует потоковые данные вByte массив. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes_1)(long, long) | Преобразует потоковые данные вByte массив. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write)(byte[]) | Записывает все указанные байты в поток. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write_1)(byte[], int, int) | Записывает последовательность байтов в текущий поток и продвигает текущую позицию в этом потоке на количество записанных байтов. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto)(StreamContainer) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto_1)(StreamContainer, long) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit) | Выполняет явное преобразование из[`StreamContainer`](../streamcontainer) кStream . |

## Поля

| Имя | Описание |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount) | Указывает количество байтов для чтения и записи при последовательном чтении. |

### Смотрите также

* class [DisposableObject](../disposableobject)
* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
