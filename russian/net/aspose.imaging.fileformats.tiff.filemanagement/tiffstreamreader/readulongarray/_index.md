---
title: ReadULongArray
second_title: Справочник по Aspose.Imaging for .NET API
description: Считывает массив беззнаковых целых значений из потока.
type: docs
weight: 200
url: /ru/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
## TiffStreamReader.ReadULongArray method

Считывает массив беззнаковых целых значений из потока.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| position | Int64 | Позиция для чтения. |
| count | Int64 | Количество элементов. |

### Возвращаемое значение

Массив целых чисел без знака.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | count;Общее количество байтов отрицательное. + count + x4= + totalBytes |

### Смотрите также

* class [TiffStreamReader](../../tiffstreamreader)
* пространство имен [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->