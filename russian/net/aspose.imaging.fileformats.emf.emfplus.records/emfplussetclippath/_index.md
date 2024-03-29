---
title: EmfPlusSetClipPath
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusSetClipPath объединяет текущую область отсечения с графическим контуром. Новая текущая область отсечения устанавливается в результате операции CombineMode.
type: docs
weight: 6290
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
## EmfPlusSetClipPath class

Запись EmfPlusSetClipPath объединяет текущую область отсечения с графическим контуром. Новая текущая область отсечения устанавливается в результате операции CombineMode.

```csharp
public sealed class EmfPlusSetClipPath : EmfPlusClippingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusSetClipPath](emfplussetclippath)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusSetClipPath`](../emfplussetclippath) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/cm) { get; set; } | Получает или устанавливает CM (4 бита): определяет логическую операцию для объединения двух областей. См. перечисление CombineMode (раздел 2.1.1.4) для значений значений. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/objectid) { get; set; } | Получает или задает индекс объекта EmfPlusPath (раздел 2.2.1.6) в таблице объектов EMF+ . Значение ДОЛЖНО быть от нуля до 63 включительно. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
