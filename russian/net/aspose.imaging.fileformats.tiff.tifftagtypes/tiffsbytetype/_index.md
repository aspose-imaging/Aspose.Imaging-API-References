---
title: TiffSByteType
second_title: Справочник по Aspose.Imaging for .NET API
description: Тип байта со знаком tiff.
type: docs
weight: 7990
url: /ru/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/
---
## TiffSByteType class

Тип байта со знаком tiff.

```csharp
public sealed class TiffSByteType : TiffCommonArrayType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffSByteType](tiffsbytetype#constructor)(TiffTags) | Инициализирует новый экземпляр класса[`TiffSByteType`](../tiffsbytetype). |
| [TiffSByteType](tiffsbytetype#constructor_1)(ushort) | Инициализирует новый экземпляр класса[`TiffSByteType`](../tiffsbytetype). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Получает размер дополнительных данных в байтах (в случае, если 12 байтов недостаточно для размещения данных тега). |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count) { get; } | Получает количество элементов. |
| [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/datasize) { get; } | Получает размер дополнительных данных в байтах (в случае, если 12 байтов недостаточно для размещения данных тега). |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/elementsize) { get; } | Получает размер элемента в байтах. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Получает целочисленное представление идентификатора тега. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Получает значение, указывающее, допустимы ли данные тега. Действительный тег содержит данные, которые можно сохранить. Недопустимый тег не может быть сохранен. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Получает идентификатор тега. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/tagtype) { get; } | Получает тип тега. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/value) { get; set; } | Получает или задает значение, которое содержит этот тип данных. |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/values) { get; set; } | Получает или задает значения. |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/valuescontainer) { get; } | Получает контейнер значений. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует ли за ним или находится в той же позиции в порядке сортировки как другой объект. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Выполняет глубокое клонирование этого экземпляра. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | ВозвращаетString, представляющий этот экземпляр. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/writeadditionaldata)(TiffStreamWriter) | Записывает дополнительные данные тега. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Записывает данные тега. |

### Смотрите также

* class [TiffCommonArrayType](../tiffcommonarraytype)
* пространство имен [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->