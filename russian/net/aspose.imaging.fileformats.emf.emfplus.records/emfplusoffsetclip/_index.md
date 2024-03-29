---
title: EmfPlusOffsetClip
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusOffsetClip применяет преобразование перевода к текущей области отсечения для мирового пространства. Новая текущая область отсечения устанавливается на результат преобразования преобразования.
type: docs
weight: 6180
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---
## EmfPlusOffsetClip class

Запись EmfPlusOffsetClip применяет преобразование перевода к текущей области отсечения для мирового пространства. Новая текущая область отсечения устанавливается на результат преобразования преобразования.

```csharp
public sealed class EmfPlusOffsetClip : EmfPlusClippingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusOffsetClip](emfplusoffsetclip)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusOffsetClip`](../emfplusoffsetclip) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| [Dx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dx) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее горизонтальное смещение для преобразования. |
| [Dy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dy) { get; set; } | Получает или задает 32-битное значение с плавающей запятой, указывающее вертикальное смещение для перевода. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
