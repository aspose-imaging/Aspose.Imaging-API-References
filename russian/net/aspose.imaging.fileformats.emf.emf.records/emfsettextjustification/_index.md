---
title: EmfSetTextJustification
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_SETTEXTJUSTIFICATION указывает количество дополнительного пробела добавляемого к символам разрыва для выравнивания текста.
type: docs
weight: 4510
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
## EmfSetTextJustification class

Запись EMR_SETTEXTJUSTIFICATION указывает количество дополнительного пробела, добавляемого к символам разрыва для выравнивания текста.

```csharp
public sealed class EmfSetTextJustification : EmfStateRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfSetTextJustification](emfsettextjustification)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfSetTextJustification`](../emfsettextjustification). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [NBreakCount](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakcount) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее количество символов разрыва. |
| [NBreakExtra](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakextra) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее общий объем дополнительного пространства в логических единицах для добавления. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Примечания

Вместо использования записи EMR_SETTEXTJUSTIFICATION реализация ДОЛЖНА использовать EMR_EXTTEXTOUTW запись (раздел 2.3.5.8) для выполнения этой функции.

### Смотрите также

* class [EmfStateRecordType](../emfstaterecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->