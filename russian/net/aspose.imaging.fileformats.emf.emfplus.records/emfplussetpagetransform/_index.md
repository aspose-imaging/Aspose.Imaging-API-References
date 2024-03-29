---
title: EmfPlusSetPageTransform
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusSetPageTransform указывает коэффициенты и единицы масштабирования для преобразования координат пространства страницы в координаты пространства устройства.
type: docs
weight: 6350
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
## EmfPlusSetPageTransform class

Запись EmfPlusSetPageTransform указывает коэффициенты и единицы масштабирования для преобразования координат пространства страницы в координаты пространства устройства.

```csharp
public sealed class EmfPlusSetPageTransform : EmfPlusTerminalServerRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusSetPageTransform](emfplussetpagetransform)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusSetPageTransform`](../emfplussetpagetransform) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| [PageScale](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pagescale) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее коэффициент масштабирования для преобразования координат пространства страницы в координаты пространства устройства. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pageunit) { get; } | Получает единицу измерения координат пространства страницы из перечисления UnitType (раздел 2.1.1.33). Это значение НЕ ДОЛЖНО быть UnitTypeDisplay или UnitTypeWorld. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
