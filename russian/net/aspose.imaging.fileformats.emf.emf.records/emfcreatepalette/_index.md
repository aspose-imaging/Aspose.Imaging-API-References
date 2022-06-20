---
title: EmfCreatePalette
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_CREATEPALETTE определяет логическую палитру для графических операций.
type: docs
weight: 3510
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
## EmfCreatePalette class

Запись EMR_CREATEPALETTE определяет логическую палитру для графических операций.

```csharp
public sealed class EmfCreatePalette : EmfObjectCreationRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfCreatePalette](emfcreatepalette)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfCreatePalette`](../emfcreatepalette). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/ihpal) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее индекс объекта логической палитры в таблице объектов EMF (раздел 3.1.1.1 ). Этот индекс ДОЛЖЕН быть сохранен, чтобы этот объект можно было повторно использовать или модифицировать. |
| [LogPalette](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/logpalette) { get; set; } | Получает или задает объект LogPalette (раздел 2.2.17). Поле версии этого объекта ДОЛЖНО быть установлено на 0x0300. Если значение NumberOfEntries в этом объекте равно нулю, обработка этой записи ДОЛЖНА завершиться ошибкой. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Смотрите также

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->