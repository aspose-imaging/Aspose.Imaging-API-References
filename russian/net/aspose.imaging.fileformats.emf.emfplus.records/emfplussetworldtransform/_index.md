---
title: EmfPlusSetWorldTransform
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusSetWorldTransform устанавливает мировое преобразование в соответствии со значениями в указанной матрице преобразования.
type: docs
weight: 6420
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
## EmfPlusSetWorldTransform class

Запись EmfPlusSetWorldTransform устанавливает мировое преобразование в соответствии со значениями в указанной матрице преобразования.

```csharp
public sealed class EmfPlusSetWorldTransform : EmfPlusTerminalServerRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusSetWorldTransform](emfplussetworldtransform)(EmfPlusRecord) | Инициализирует новый экземпляр класса[`EmfPlusSetWorldTransform`](../emfplussetworldtransform). |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное число байтов данных в поле RecordData, которое следует. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция , и о структуре запись. |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/matrixdata) { get; set; } | Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий новое текущее преобразование мира. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее число байтов, выровненных по 32-разрядному выравниванию во всей записи, включая 12 -байтовый заголовок записи и данные, относящиеся к записи. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->