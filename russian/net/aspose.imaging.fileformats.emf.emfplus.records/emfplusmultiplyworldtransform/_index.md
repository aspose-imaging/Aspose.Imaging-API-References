---
title: EmfPlusMultiplyWorldTransform
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusMultiplyWorldTransform умножает текущее преобразование мирового пространства на указанную матрицу преобразования .
type: docs
weight: 6150
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
## EmfPlusMultiplyWorldTransform class

Запись EmfPlusMultiplyWorldTransform умножает текущее преобразование мирового пространства на указанную матрицу преобразования .

```csharp
public sealed class EmfPlusMultiplyWorldTransform : EmfPlusTerminalServerRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusMultiplyWorldTransform](emfplusmultiplyworldtransform)(EmfPlusRecord) | Инициализирует новый экземпляр класса[`EmfPlusMultiplyWorldTransform`](../emfplusmultiplyworldtransform). |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное число байтов данных в поле RecordData, которое следует. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция , и о структуре запись. |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/matrixdata) { get; set; } | Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий матрицу умножения. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/postmultipliedmatrix) { get; } | Получает значение, указывающее, была ли [матрица умножения постов]. Если установлено, матрица преобразования должна быть постумножена. Если ясно, это должно быть предварительно умножено. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее число байтов, выровненных по 32-разрядному выравниванию во всей записи, включая 12 -байтовый заголовок записи и данные, относящиеся к записи. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->