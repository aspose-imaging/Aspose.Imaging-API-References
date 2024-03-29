---
title: TiffUnknownType
second_title: Справочник по Aspose.Imaging for .NET API
description: Неизвестный тип TIFF. В случае если тег tiff не может быть распознан создается экземпляр этого типа.
type: docs
weight: 8050
url: /ru/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
## TiffUnknownType class

Неизвестный тип TIFF. В случае, если тег tiff не может быть распознан, создается экземпляр этого типа.

```csharp
public sealed class TiffUnknownType : TiffDataType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffUnknownType](tiffunknowntype)(TiffStreamReader, ushort, ushort, uint, uint) | Инициализирует новый экземпляр[`TiffUnknownType`](../tiffunknowntype) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Получает размер дополнительных данных в байтах (в случае, если 12 байтов недостаточно для размещения данных тега). |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/count) { get; } | Получает количество элементов. |
| override [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/datasize) { get; } | Получает размер дополнительных данных в байтах (в случае, если 12 байтов недостаточно для размещения данных тега). |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Получает целочисленное представление идентификатора тега. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Получает значение, указывающее, допустимы ли данные тега. Действительный тег содержит данные, которые можно сохранить. Недопустимый тег не может быть сохранен. |
| [OffsetOrValue](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/offsetorvalue) { get; } | Получает значение смещения для дополнительных данных или самого значения, если count равен 1. |
| [Stream](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/stream) { get; } | Получает поток для чтения дополнительных данных из. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Получает идентификатор тега. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tagtype) { get; } | Получает тип тега. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/value) { get; set; } | Получает или задает значение, которое содержит этот тип данных. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Выполняет глубокое клонирование этого экземпляра. |
| override [ToString](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tostring)() | ВозвращаетString который представляет этот экземпляр. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/writeadditionaldata)(TiffStreamWriter) | Записывает дополнительные данные тега. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Записывает данные тега. |

### Примечания

Обратите внимание[`TiffUnknownType`](../tiffunknowntype) не сериализуется обратно в поток.

### Смотрите также

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype)
* пространство имен [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
